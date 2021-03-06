---
title: Arch Linux 源使用帮助
---

地址
====

<https://mirror.nyist.edu.cn/archlinux/>

说明
====

Arch Linux 软件源

收录架构
========

i686, x86\_64

使用说明
========

编辑 `/etc/pacman.d/mirrorlist`，在文件的最顶端添加

    Server = https://mirror.nyist.edu.cn/archlinux/$repo/os/$arch

更新软件包缓存

    sudo pacman -Syy

国内用户，推荐另外使用 Arch Linux CN 的源，请参考
`archlinuxcn`

相关链接
========

官方主页

:   <https://www.archlinux.org/>

邮件列表

:   <https://www.archlinux.org/mailman/listinfo/>

论坛

:   <https://bbs.archlinux.org/>

Wiki

:   <https://wiki.archlinux.org/>
