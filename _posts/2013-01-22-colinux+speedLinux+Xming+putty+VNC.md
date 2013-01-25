---
layout: post
category : unix/linux
tags : [colinux, ubuntu, speedLinux, xming, putty, vnc]
---
This page will introduce how to use colinux to cooperate a win7 host and a ubuntu 12.04 virtual machine.


## Installation
1. install colinux
2. carry on speedLinux
3. enlarge the capbility
4. modify the sources.list
5. update & upgrade
6. install xming into host, modify x0.hosts, add the host ip into it.
7. install gdm, enable xdmcp; vim /etc/profile, and the DISPLAY envrienment variaty. DISPLAY="your host ip":0.0
8. colinux-daemon --install server @ubuntu.cfg "colinux", then set this service the ability that can be startup along with the host system.
9. configure putty allow X11 forwarding
10. sudo apt-get install ubuntu-desktop
11. configure putty to allow login automationly.
12. install and configure samba to allow the sharing dir
13. install vnc server and configure that

## Ref
1. www.colinux.org
2. sourceforge.net/projects/freetzlinux
3. blog.creke.net/696.html/comment-page-1
4. http://colinux.wikia.com/wiki/Main_Page
5. wangchengtai.blog.hexun.com.tw/35370962_d.html
