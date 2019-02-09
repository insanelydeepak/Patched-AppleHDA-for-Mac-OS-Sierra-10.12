
![HDA Icon](https://raw.githubusercontent.com/insanelydeepak/cloverHDA/master/cloverHDA.jpg)
# cloverHDA 

Collection of Patched AppleHDA to enables audio/sound on Mac OS Sierra 10.12


if you like this project, please star it.

### Requirements : 
      1 - a good Kext Installer or [EastKextPro](http://www.insanelymac.com/forum/files/file/397-easykext-pro-a-minimal-and-super-fast-kext-installer/)
  
      2 - Property List Editors - Xcode or Property List Editor, PlistEdit Pro, TextEdit, etc.
      3 -  must have CLOVER/config.plist
           i. RtVariables/BooterConfig/0x28
            ii. RtVariables/CsrActiveConfig/0x03 


### Installation :

      1 - Download Patched AppleHDA as per your Audio ID's 
      2 - Install using EastKextPro or any Kext Installer
      3 - Add Layout_ID = 13 , 11 or 12 as described in ReadME.txt 
      4 - Restart 

#### Note : for Layout_ID you can use DSDT (HDEF Patch) or Clover (Clover/Config.plist/Devices/Audio/Inject=Audio_ID) or [HDAEnabler's kexts](https://bitbucket.org/insanelydeepak/hdaenablers-applehda-for-hackintosh/downloads)

### Layout_ID/Audio ID description :

    for Desktop's:
      1 - Layout_ID 11 = 5/6 ports supported (Pink, Green, Blue) (Note : without auto-switch , you have to manually select between output/input device's) 
      3 - Layout_ID 13 =   5/6 ports supported (Grey, Black, Laranja, Pink, Green, Blue)

    for Laptop's :
      1 - Layout_ID 13 =   3/5 ports supported (Black, Pink, Green, Blue)


### Supported Codec/DEVICE_ID :

  You must have one of the following DEVICE_ID/Codec name described below :
 
      1 - Realtek ALC to Desktop's: ALC887, ALC888, ALC891, ALC892
      2 - Realtek ALC to Laptop's: ALC255, ALC269, ALC269VC, ALC269VB, ALC270, ALC271, ALC272, ALC275, ALC282, ALC292, ALC298, ALC662, ALC665, ALC898 , ALC88
      3 - Conexant for laptop's: CX20590,CX20724 ,CX20752
      4 - IDT for Laptop's: IDT92HD71B7X,IDT92HD73C1X5, IDT92HD75B2X5, IDT92HD75B2X5, IDT92HD81B1X5, IDT92HD90BXX, IDT92HD91BXX, IDT92HD93BXX
      5 - VIA Laptop's: VT1802 
      6 - Cirrus Logic Laptop's: CS4213 and CS4210 



### Credits :
  PikeRAlpha, Mirone, EmlyDinesh, The king, Master Chief, RevoGirl, toleda, bcc9, TimeWalker and many others who contributed to AppleHDA patching.

## Donation
If this project help you reduce time to develop, you can give me a cup of coffee :) 

[![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](http://paypal.me/insanelydeepak)
