![系统概览](https://upload-images.jianshu.io/upload_images/1710902-c178e2037660b0d6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![硬盘信息](https://upload-images.jianshu.io/upload_images/1710902-1a3c6c934ed02c04.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![内存信息](https://upload-images.jianshu.io/upload_images/1710902-15c5092ac2831a2f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 先说硬件信息：

```
处理器 Prozessor: AMD Ryzen 9 3900X
主板 Mainboard: GIGABYTE X570 AORUS PRO WIFI (移除自带的AX200 WiFi蓝牙模块，使用BCM94360CD+PCI-E x 1替代)
内存 Memory: Corsair Vengeance (2x, 16GB) DDR4-3600
硬盘 Storage: SAMSUNG 960 EVO 256G、intel 660P 512G
显卡 Video Card: Sapphire RX580 8G
电源 Power Supply: CORSAIR RM650x
机箱 Case: NTXZ H510
```

## 已知问题：
- 麦克风无法使用（H510机箱前面板的耳机麦克风一体插口）
- 睡眠未测试，台式机没必要

## Cinebench R20跑分：
![Cinebench R20](https://upload-images.jianshu.io/upload_images/1710902-f1b89834a818021b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## OpenCore引导结构：
![OpenCore引导结构](https://upload-images.jianshu.io/upload_images/1710902-8436c62cd0f3b473.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 使用步骤：
#### 注意，本文章意在分享，且仅适用于和我配置一致或者X570系列主板，其他主板或配置请勿使用！需要了解黑苹果技术，并具备操作能力，本人不承担任何因为此EFI造成的后果。
- 1.使用[https://github.com/corpnewt/GenSMBIOS](https://github.com/corpnewt/GenSMBIOS)生成三码，填入以下位置：
![GenSMBIOS](https://upload-images.jianshu.io/upload_images/1710902-fdc69c79df1a68ef.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- 2.下载github项目中的EFI文件，替换你的U盘启动引导

## GitHub项目地址：
[https://github.com/SherlockGougou/ryzen-x570-3900x-hackintosh](https://github.com/SherlockGougou/ryzen-x570-3900x-hackintosh)
