# TicWatch CN Google-ify (msm8909-pie)
TicWatch CN Google-ify (msm8909-pie)

This module could make TicWatch Wear OS China version into Global version. You can pair the watch with Wear OS App from play store and purchase Apps from watch from Play Store

此模块将使 TicWatch Wear OS 中国版 变为国际版，并使用 Play 商店的 Wear OS 应用进行配对，通过 Play 商店购买应用和表盘。

As Magisk could modify system with magic mount, this module wouldn't affect OTA if you have the backup of **boot.img**.

由于 Magisk 的特性，如果您有备份 **boot.img**，此模块就将不会影响 OTA 的更新。

This module is compatible with TicWatch Pro & TicWatch C2.

## Feature

- Replace current **Play Service Updater** to **Play Store**

   将 **Play 服务更新程序** 替换为 **Play 商店**

## Additional

**Please make sure Google app is installed.**

**请确保您已经安装 Google 应用**

To disable mobvoi ticwear assistant and make use of Google Assistant, run commands followed:

为了禁用出门问问语音助手以正常使用 Google Assistant，请在adb中执行以下命令：
```
pm uninstall --user 0 com.mobvoi.ticwear.sidewearvoicesearch
```
If you want to install it back:

如果需要恢复：
```
cmd package install-existing com.mobvoi.ticwear.sidewearvoicesearch
```

## Credit & Support

* Copyright (C) 2018-2019 Mobvoi & Google
* Copyleft (ↄ) 2019 simonsmh <simonsmh@gmail.com>
* Any issue or pull request is welcomed.
* Star this module at [GitHub](https://github.com/Magisk-Modules-Repo/ticwatch-googleify).
