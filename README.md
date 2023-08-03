# My System Config Shell script 

# PS

将这段代码添加到~/.ssh/config里完成对git的配置
```
Host github.com
Hostname ssh.github.com
Port 443
User git
```
请手动添加archlinuxcn源
将此段加入 /etc/pacman.conf
```
[archlinuxcn]
Server = https://mirrors.ustc.edu.cn/archlinuxcn/$arch
```
并
```
sudo pacman -Sy archlinuxcn-keyring
```
