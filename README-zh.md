[中文]:https://github.com/LomotHo/Hackintosh-600g1-DM-4670t/blob/master/README-zh.md
[English]:https://github.com/LomotHo/Hackintosh-600g1-DM-4670t/blob/master/README.md

[English] | [中文]

# Hackintosh-600g1-DM-4670t

 - CLOVER版本：5120 | MacOS版本: 10.15.6

## 配置

 - CPU: i5 4670t
 - GPU: HD Graphics 4600
 - 无线网卡: bcm943224pciebt2
 - 硬盘: WD sn720

## BIOS设置

 - CFG lock -> unlock
 - DVMT -> 96M
这两个设置在bios设置界面是没有的需要用setup_var工具，此处暂时先不介绍

## 如何给BIOS插入NVME模块

请参考我的一篇博客：[魔改600g1 DM的bios以支持nvme硬盘](https://zhuanlan.zhihu.com/p/163219746)

## 注意事项
 - 理论上也支持 800g1-DM 与 400g1-DM
 - 如果使用4代魔改的笔记本CPU如i7 4980HQ，除了需要自行在BIOS中添加微码外，本配置中关于显卡的设置也需要修改

## 目前已知的问题

 - VGA不能显示
 - 不能休眠，需要自行关闭休眠

如果你有上面问题的解决方案，欢迎给我提issue或者pull request，或者直接通过邮箱lomot@qq.com联系我
