PS5 UMTX2 Jailbreak Raspberry PI Offline Host Server
----------------------------------------------------

OS is Raspian Lite x64 and the UMTX2 Jailbreak from idlesauce.

Source: https://github.com/idlesauce/umtx2 

Crontabs are set up for automated start of the host and fakedns, ip address of the Raspberry Pi is set to DHCP.

Details:
--------
- OS: Raspian Lite with SSH
- Hostname: umtx2.local
- Keyboard Layout: de

Credentials:
------------
Login: umtx2 
Password: umtx2 (user & root)

HowTo:
------
1. Download & Extract the umtx2rpi Image from .zip File
2. Download & Run Win32DiskImager and restore the Image to your microSD Card (Minimun Card Size 4GB)
3. Connect your Raspberry Pi via LAN to your Network with the inserted microSD Card an let it boot
4. Lookup on your Network which IP your Raspberry Pi recieved from your DHCP
5. Point DNS Server on your PS5 to the Raspberry Pi IP
6. Run the Jailbreak over the Userguide or via IP Adress on the Browser from the PS5

Advantages:
-----------
- Offline Jailbreak directly via LAN 
- Access to directories (payloads) via SSH / SFTP

Win32 DiskImager Download Link:
-------------------------------
https://win32diskimager.b-cdn.net/win32diskimager-1.0.0-install.exe

Image Download Link:
--------------------
https://www.mediafire.com/file/8okrj5olvgsq9l4/umtx2rpi.zip/file
