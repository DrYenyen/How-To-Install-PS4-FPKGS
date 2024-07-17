# What are FPKGS       
1. Ripped games from a disc, digital game, game update or DLC that are converted to fake package for easy installation     
2. Homebrew apps like Appolo Save tool and Itemzflow        
3. Repackaged PS1, PS2 or PSP games made to work through emulation        
ETC      
       
        
# How-To-Install-PS4-FPKGs
How To Install PS4 FPKG on Goldhen (Note Instalation from the internal HDD is not supported by PS4hen VTX)          

# USB Method     
You can use any kind of USB drive or External USB HDD enclosure as long as it can power on from the usb port and is formwatted in EXFAT   
1. Format your USB drive to EXFAT    
2. Place your fpkgs on the usb drive    
3. Follow one of my guides to jailbreak your console or use your own proccess     
[How to use a GUI tool to run PPPwn on Windows](https://github.com/DrYenyen/PPPwnGo-Guide)           
[How to set up Raspberry-Pi on Windows for PPPwn](https://github.com/DrYenyen/PPPwn-Setup-Guide-For-Raspberry-Pi)         
4. Go into Goldhen at the top left of the home screen    
5. Go into Debug Settings       
6. Under *Package Installer* make sure *Package Source* is usb[ usb:/ ]     
if it is Hdd [ hdd:/data/pkg/ ]  change it to usb[ usb:/ ]          
6. Go into Package Installer         
From there you can choose to install any 1 pkg you want or alternatively you will be automatically asked if you want to install all the available pkgs         

# FTP Method PC to PS4 (fastest transfer speed)    
1. Follow one of my guides to jailbreak your console or use your own proccess        
[How to use a GUI tool to run PPPwn on Windows](https://github.com/DrYenyen/PPPwnGo-Guide)               
[How to set up Raspberry-Pi on Windows for PPPwn](https://github.com/DrYenyen/PPPwn-Setup-Guide-For-Raspberry-Pi)          
2. After Jailbreaking connect your PS4 to your home network over WiFi or Ethernet (WiFi and Ethernet Transfers with this method are significantly slower than direct PC to PS4 method above     
3. Create a folder called *pkg* and put your pkgs inside of it             
4. Connect your PS4 to your PC with a LAN cable      
5. On your PC go into Start>Settings>Network & Internet>Ethernet and then at the top right choose *Change Adapter Options*     
![-](imgs/settings.JPG)    
6. Find the ethernet Adapter you are using and right click on it then choose *properties*            
7. Double left click on *Internet Protocol Version 4 (TCP/IPv4)*              
![-](imgs/ipv4.JPG)          
8. Press on the empty circle next to *Use the following IP address:* to unlock the fields below it       
![-](imgs/ipv42.JPG)       
9. Fill them in to match as shown in the image below        
![-](imgs/ipv43.JPG)      
10. Go to your PS4 and go into Settings>Network>Set Up Internet Connection   
11. Choose **Use a LAN Cable** then choose **Custom** then choose **Manual** 
12. Set *IP Address* to **10.1.1.2**  
13. Set *Subnet Mask* to **255.255.255.0**   
14. Set *Default Gateway* to **10.1.1.0**
15. Set *Primary DNS* to **10.1.1.1**  
16. Set *Secondary DNS* to **10.1.1.100**  
17. Set *MTU Settings* to **Automatic** Set *Proxy Server* to **Do Not Use**      
18. Test Internet Connection and once you get an IP Adresss go back to the home screen      
19. Go into Goldhen at the top left of the home screen     
20. Go into *Server Settings*    
21. Enable the FTP server by making sure the box to the right of *Enabel FTP Server* is ticked      
22. Find your Console IP address by going into Settings>System>System Information (if the steps above were followed it will be **10.1.1.2**)    
23. Download and Install [Filezilla](https://filezilla-project.org/download.php?type=client)    
24. In Filezilla at *Host:* type your PS4 IP address and in *Port:* type 2121 then press on *Quickconnect* then press *OK* on the popup window    
25. On the left window of Filezilla go to where you made the folder *pkg* and drag and drop it to the right side window into the folder called *data*     
![-](imgs/ftp.JPG)   
(In the future you can go into the *data* folder and drag directly into the *pkg* folder)
26. Go into Goldhen at the top left of the home screen        
27. Go into Debug Settings        
28. Under *Package Installer* change *Package Source* from usb[ usb:/ ] To Hdd [ hdd:/data/pkg/ ]   
29. Go into Package Installer             
From there you can choose to install any 1 pkg you want or alternatively you will be automatically asked if you want to install all the available pkgs     

     
# FTP Method over network to internal PS4 Storage    
1. Follow one of my guides to jailbreak your console or use your own proccess        
[How to use a GUI tool to run PPPwn on Windows](https://github.com/DrYenyen/PPPwnGo-Guide)               
[How to set up Raspberry-Pi on Windows for PPPwn](https://github.com/DrYenyen/PPPwn-Setup-Guide-For-Raspberry-Pi)       
2. After Jailbreaking connect your PS4 to your home network over WiFi or Ethernet (WiFi and Ethernet Transfers with this method are significantly slower than direct PC to PS4 method above 
3. Create a folder called *pkg* and put your pkgs inside of it        
4. Go into Goldhen at the top left of the home screen     
5. Go into *Server Settings*    
6. Enable the FTP server by making sure the box to the right of *Enabel FTP Server* is ticked      
7. Find your Console IP address by going into Settings>System>System Information  
8. Download and Install [Filezilla](https://filezilla-project.org/download.php?type=client)    
9. In Filezilla at *Host:* type your PS4 IP address and in *Port:* type 2121 then press on *Quickconnect* then press *OK* on the popup window    
10. On the left window of Filezilla go to where you made the folder *pkg* and drag and drop it to the right side window into the folder called *data*     
![-](imgs/ftp.JPG)   
(In the future you can go into the *data* folder and drag directly into the *pkg* folder)
11. Go into Goldhen at the top left of the home screen        
12. Go into Debug Settings        
13. Under *Package Installer* change *Package Source* from usb[ usb:/ ] To Hdd [ hdd:/data/pkg/ ]   
14. Go into Package Installer             
From there you can choose to install any 1 pkg you want or alternatively you will be automatically asked if you want to install all the available pkgs       

# Direct Package Installer and Remote Package Sender soon    


# Other guides  
# 1. [Guides Thread](https://github.com/DrYenyen/Guide-Links-For-PS4)             
# 1. [How to use a GUI tool to run PPPwn on Windows](https://github.com/DrYenyen/PPPwnGo-Guide)             
# 2. [How to manually update PS4 firmware](https://github.com/DrYenyen/PS4-Firware-Update-Guide)                            
# 3. [How to set up Raspberry-Pi on Windows for PPPwn](https://github.com/DrYenyen/PPPwn-Setup-Guide-For-Raspberry-Pi)                          
# 4. [How to set up PPPwn on a OpenWRT compatible router(by FalsePhilosopher)](https://github.com/FalsePhilosopher/PPPwnWRT)              




