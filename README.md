
# About
This is a MultiPlatform GUI Interface For Team Molecule / Yifanlu's PSVIMGTools 
Which is a tool that can be used to decrypt & extract PSVita Backup Files (.psvimg) Providing you know the AID (AccountID)
of the account that created said backup

# Requirements
1. A PC 32 or 64 Bit PC Running Windows, Mac or Linux. 
2. A PSVita on ANY Firmware (even 3.67)
3. QCMA by Codestation (Normal SONY CMA will work, but not recommended.)
4. If your on linux you require *libcurl4-gnutls-dev libboost-all-dev zlib1g-dev* and *libgcrypt-dev* 

# Building/Running from source
This software is written in Python 2.7.14,          
you will need to install that for whatever operating system you are using,             
 
Requires the following python libaries:          

bplistlib (only really needed if you are using a mac) - https://github.com/tungol/bplistlib              
requests - http://python-requests.org (or $ pip install requests)                     

if you want to build the application you are going to need [Pyinstaller](https://www.pyinstaller.org/)          
if you just want to run it from source. do $ python run.py           

for mac/linux: $ pyinstaller -F run.py     
for windows C:\> pyinstaller -i icon.ico run.py       

after thats done copy the easyinstallers folder from the source folder into dist/run           
download [psvimgtools from yifanlu](https://github.com/yifanlu/psvimgtools/releases) and copy it into the dist/run directory
(optional: download psvpfstools and put it into the dist/run if you dont, pfs decryption will not work.)                 

# Credits
Thanks to Tungol for bplistlib, Reading binary property lists in python.              
Thanks to Yifanlu for the original PSVIMGTOOLS command line                 
Thanks to Don Rozenberg for PAGE Which i used to create GUI's                  
Thanks to Codestation for QCMA                  
Thanks to Chris Kreager a.k.a LanThief for his Python .SFO Parser             
Thanks to DaveeFTW for cracking CMA keys. (cma.henkaku.xyz)               
Thanks to Sony for the PSVITA.               
Thanks to Motoharu for psvpfstools             
Thanks to all NoPayStation Contributers for decryption zRIFs        

# Features
Intergration with CMA. (Particually QCMA) PSVIMGTOOLS-FRONTEND will read some data from CMA Config files.          
EasyInstallers, to easily install common hacks, such as ARK-2, VHBL, Whitelist Hack and more.              
Account Mannager - Supports multiple PSN Accounts                   
Quick Resign - Quickly change the owner of a backup from one account to another.            
CMBACKUP - A way to share backup files with anyone easily                  
Automatic updates - Will automatically scan for new updates and ask if u want to install           
PFS Decryption - Decrypt the PFS Layer of applications and patch files, (thanks motoharu-gosuto)
# EasyInstallers
**HiddenApps** - Install ★Hidden Applications -- Enables [Account Switching](https://pastebin.com/raw/CiTUyjr4) [3.60 & 3.65]  
**Skype** - Install the Skype App -- The one from PSN [3.63 Or Lower]                                                
**ARK** - Patch a PSP Game with ARK-2 -- PSP/PSX ISO Loader [3.63 Or Lower]                                    
**PSMRuntime** - Install the Playstation(R)Mobule Runtime v2.01 [All FW]                                       
**URICaller** - Patch a SYSTEM Backup to enable all support_uri's and install a uricaller app [All FW]                      
**VHBL** - Patch a PSP Game with VHBL -- Vita Half Byte Loader [All FW]                             
**RemoveFeatured** - Patch a SYSTEM Backup to remove the "Topics" app on a PSTV [All FW]                                
**CmBackup** - Install a .cmbackup file -- [Download .cmbackup's](https://stack.gigafyde.nl/s/3BOIO2m7vCnTh81) [All FW]                                       
**Whitelister** - Patch a SYSTEM Backup with Whitelister v2 -- Play ALL games on your PSTV! [All FW]                      
**EmuBubble** - Patch a PSP Game with an emulator bubble [All FW]         
**VitaShell** - Install a vitashell bubble, only usefull if you have 3.65 henkaku. [ALL FW]



Want to donate to me? really? ok: https://goo.gl/dvHkEh
