# ShadowsocksD-X for Android

```
因 @TheCGDF 繁忙，现计划转让本repo，要求：
1、有Android开发能力（能够跟随上游更新）
2、不咕
注：转让后不限制接手者是否移除“全家桶检测”
转让条件：
向本repo提一条PR，将SSD-Android跟随上游更新至最新稳定版本，无重大BUG即可获得转让资格
如有困难可以TG联系 @TheCGDF 获取一定的技术支持
Tips:
本repo中所有和上游有差异的代码都使用“region SSD”注释标记并包裹了起来，总计不超过50处
因此git clone上游之后项目，可以使用Android Studio的Find in Path功能，搜索本repo中的“region SSD”并转移至上游项目即可
```

## Basic Project - 基础项目

[SSD-Andoird](https://github.com/TheCGDF/SSD-Android)

本项目与上游项目SSD-Andoird保持同步。**仅去除系统及APP限制。**

## Shared Wiki - 共享Wiki

[ShadowsocksD项目共享Wiki](https://github.com/TheCGDF/SSD-Windows/wiki)

## Environment - 环境

Android 5.0+

**去除了无法在特定系统及含有特定APP的手机上运行SSD的限制。**

## Development - 开发

\[Windows/Linux/MacOS\]

需使用`git clone --recurse-submodules <repo>`或 `git submodule update --init --recursive`进行初始化

## Open Source References - 开源引用
```
shadowsocks-android (GPLv3) https://github.com/shadowsocks/shadowsocks-android
redsocks (APL 2.0)          https://github.com/shadowsocks/redsocks
mbed TLS (APL 2.0)          https://github.com/ARMmbed/mbedtls
libevent (BSD)              https://github.com/shadowsocks/libevent
tun2socks (BSD)             https://github.com/shadowsocks/badvpn
pcre (BSD)                  https://android.googlesource.com/platform/external/pcre/+/master/dist2
libancillary (BSD)          https://github.com/shadowsocks/libancillary
shadowsocks-libev (GPLv3)   https://github.com/shadowsocks/shadowsocks-libev
libev (GPLv2)               https://github.com/shadowsocks/libev
libsodium (ISC)             https://github.com/jedisct1/libsodium
```
