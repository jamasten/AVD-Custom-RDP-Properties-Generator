# AVD Custom RDP Properties Generator

## Description

The AVD Custom RDP Properties Generator is a web tool that simplifies the generation and output of Custom RDP properties for an AVD Host Pool.

The tool was created to fill the following gaps:

- In the Azure Portal on a Host Pool's RDP Properties blade: 
  - Most of the RDP properties exist there but not all of them.
  - The settings do not state which property works with which client.
- The [Supported RDP Properties webpage](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/clients/rdp-files?context=%2Fazure%2Fvirtual-desktop%2Fcontext%2Fcontext) in the AVD Docs lists most of the supported properties but not all of them.
- The [Supported Redirections webpage](https://docs.microsoft.com/en-us/windows-server/remote/remote-desktop-services/clients/remote-desktop-app-compare#other-redirection-devices-etc) states that drive redirection does not work with the web client.  However, that is not true.
- Anyone that deploys AVD with code, either has to deploy a dummy host pool to create the Custom RDP Properties or try to string everything together using the documentation.

## Directions
1. Download the "solution.html" file.
2. Open the "solution.html" file in your web browser.
3. Choose your desired AVD RDP property settings.  Each selection will update the string in the output section at the bottom of the page and is automatically added to your clipboard.
4. Update the "customRdpProperty" on your AVD host pool using your choice of tooling.
