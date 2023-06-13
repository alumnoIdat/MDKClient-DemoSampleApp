# MDKClient-DemoSampleApp

Prerequisites
MDK 6.X and follow the tutorials below
https://developers.sap.com/tutorials/cp-mobile-dev-kit-build-client.html

Instructions to load application on mobile

1. Execute op PowerShell
    C:\MDKClient_SDK\create-client.cmd -m ./DemoSampleApp.mdkproject
2. Write .mdkproject direction
3. go into new created directory
cd DemoSampleApp
4. Run tns
- tns run android --emulator
or
- tns device android
- tns run android --device ABCDEFGH