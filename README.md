[中文]:https://github.com/LomotHo/Hackintosh-600g1-DM-4670t/blob/master/README-zh.md
[English]:https://github.com/LomotHo/Hackintosh-600g1-DM-4670t/blob/master/README.md

[English] | [中文]

# Hackintosh-600g1-DM-4670t

 - CLOVER: 5120 | MacOS: 10.15.6

## Hardware list

 - CPU: i5 4670t
 - GPU: HD Graphics 4600
 - Wireless card: bcm943224pciebt2
 - Disk: WD sn720

## BIOS configuration

 - CFG lock -> unlock
 - DVMT -> 96M
Infact you cant find any configuration about CGF lock or DVMT, you need to use same efi tools such as modified grub with setup_var command.

## How to insert the Nvme module into the BIOS

you can view this article from my blog, sorry for no English version.
[魔改600g1 DM的bios以支持nvme硬盘](https://zhuanlan.zhihu.com/p/163219746)

## Attention
 - 800g1-DM or 400g1-DM user can also try this EFI

## Unsolved problem

 - VGA not work
 - Can't sleep, just enable the option "Prevent computer from sleeping automatically when the display is off" can solve it.

If you can solve any problem above, please open an issue or pull requests, or email me to lomot@qq.com.
