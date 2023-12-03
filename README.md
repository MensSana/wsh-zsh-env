# wsh-zsh-env
Scripts for preparing wsh zsh environment

On first WSL login :

    whoami >/tmp/user.tmp
    cd /usr/local/bin
    explorer.exe .

Copy **wsl-setup** and **wsl-setup-2** into opened folder
On WSL prompt:

    chmod 750 /usr/local/bin/wsl*
    chown 1000:1000 /usr/local/bin/wsl*
    sudo -i
    /usr/local/bin/wsl-setup
    exit
Exits from shell completely
Relaunch shell and on prompt:
    
    /usr/local/bin/wsl-setup-2
    
