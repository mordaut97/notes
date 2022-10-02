### Sources
(Blog @ Ben | imbushuo Home Archive)[https://imbushuo.net/blog/archives/1002/]
+ Indepth and easy to follow Tutorial
(Putty CAC)[https://github.com/NoMoreFood/putty-cac]
(WSL-SSH-Pageant)[https://github.com/benpye/wsl-ssh-pageant]


### Autostart Config
+ 1) Open startup folder:
    + press "win-key + r"
    + type "shell:startup"
+ 2) 
    + Place a link to pagent ("C:\Program Files\PuTTY\pageant.exe") into the startup folder
    + Place the bat file also here.

```bat
@echo off
start "" "C:\Program Files\wsl-ssh-pageant-amd64-gui.exe" -systray -winssh openssh-ssh-agent -force
```
