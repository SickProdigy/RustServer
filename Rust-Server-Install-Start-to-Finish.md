# Complete Rust Install Method

Use putty, login to server (SSH shell)
Login to user, shouldn't be root, but doesn't matter if testing.

35.209.133.227 
Rustication SickProdigy@gmail.com
 
if you ctrl z by accident
type "fg" next line to pull back up that process!

    sudo apt update
    sudo apt upgrade
    sudo dpkg --add-architecture i386; sudo apt update; sudo apt install curl wget file tar bzip2 gzip unzip bsdmainutils python util-linux ca-certificates binutils bc jq tmux netcat lib32gcc1 lib32stdc++6 steamcmd lib32z1
    sudo adduser ruster
    su - ruster
    MySecretPassword
    mkdir ruster

wget -O linuxgsm.sh https://linuxgsm.sh && chmod +x linuxgsm.sh && bash linuxgsm.sh rustserver        // Install LinuxGSM the files that makes using rust easy.


    ./rustserver install		// didn't add every dpkg from earlier command had to exit exit sudo (whatever dependencies where missing)

Reran above command // worked
 
    ./rustserver start
 
connect 35.208.110.204:28015		// had to turn to static, was having issues with firewall. after creating fresh vm and made ip static was able to connect after 15 minutes.

    ./rustserver console
CTRL+b d    // how to exit, DO NOT CTRL-C this will fudge stuff up, type in console type "fg" enter and maybe you can bring it back if it's still up.

    ./rustserver mods-install
    ./rustserver stop
    ./rustserver start

In game run this:

    oxide.version   // This will show oxide is installed or not or working or not basically.
