# 使用 Github Actions 在线编译 NanoPi-R4S 固件

## 说明
* 管理 IP: 192.168.2.1
* 默认管理密码: password

## 用法
直接从 Release 下载最新版固件；或 Fork 到自己的账号下，编辑文件 `CHANGELOG.md` 触发编译动作。

## 特色
* 支持 RTL8821CU/RTL8822BU 芯片的 USB WiFi 8112cu 设备，已知支持列表：
    - COMFAST 726B
    - COMFAST CF-759BF
* 集成 [vernesong/OpenClash](https://github.com/vernesong/OpenClash) 及其 core/tun/game binaries
* 集成 [jerrykuku/luci-app-vssr](https://github.com/jerrykuku/luci-app-vssr)
* 集成 [rufengsuixing/luci-app-adguardhome](https://github.com/rufengsuixing/luci-app-adguardhome)
* 集成 [coolsnowwolf/packages](https://github.com/coolsnowwolf/packages), [coolsnowwolf/luci](https://github.com/coolsnowwolf/luci) 与 [coolsnowwolf/lede/package/lean](https://github.com/coolsnowwolf/lede/tree/master/package/lean)
* 更新 [jerrykuku/luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)
* 集成 [pymumu/smartdns](https://github.com/pymumu/smartdns) 与 luci-app-smartdns
* 集成 [luci-app-jd-dailybonus](https://github.com/jerrykuku/luci-app-jd-dailybonus)

## 注意
产品发布初期，官方代码每天都在变，遇到无法编译时，请过来查看 `.yml` 与 `config` 最新异动。

## 原作者
soffchen: https://github.com/soffchen/NanoPi-R2S

## 参考
* [使用Github的Actions功能在线编译NanoPi-R1S固件（包含H5和H3）](https://totoro.site/index.php/archives/70/)
* [skytotwo/NanoPi-R1S-Build-By-Actions](https://github.com/skytotwo/NanoPi-R1S-Build-By-Actions)
* [klever1988/nanopi-openwrt](https://github.com/klever1988/nanopi-openwrt)
* [yangliu/NanoPi-R2S](https://github.com/yangliu/NanoPi-R2S)
* [maxming2333/NanoPi-R2S](https://github.com/maxming2333/NanoPi-R2S)
* [songchenwen/nanopi-r2s](https://github.com/songchenwen/nanopi-r2s)
* [fanck0605/nanopi_r2s](https://github.com/fanck0605/nanopi_r2s)
