![GitHub releases](https://img.shields.io/github/downloads/Xposed-Modules-Repo/com.mihuashi.paybyfinger/total?label=LSPosed%20downloads&labelColor=F48FB1) ![Release Download](https://img.shields.io/github/downloads/ghhccghk/mhspay/total?style=flat-square) [![Release Version](https://img.shields.io/github/v/release/ghhccghk/mhspay?style=flat-square)](https://github.com/ghhccghk/mhspay/releases/latest)  
[![GitHub license](https://img.shields.io/github/license/ghhccghk/mhspay?style=flat-square)](https://github.com/ghhccghk/mhspay/LICENSE.md)  
[![GitHub Star](https://img.shields.io/github/stars/ghhccghk/mhspay?style=flat-square)](https://github.com/ghhccghk/mhspay/stargazers) [![GitHub Star](https://img.shields.io/github/stars/Xposed-Modules-Repo/com.mihuashi.paybyfinger?style=flat-square&label=LSPosed%20Star&labelColor=F48FB1)](https://github.com/Xposed-Modules-Repo/com.mihuashi.paybyfinger/stargazers)
[![GitHub Fork](https://img.shields.io/github/forks/ghhccghk/mhspay?style=flat-square)](https://github.com/ghhccghk/mhspay/network/members)
---
通过Hook米画师的密码输入接口并在指纹识别正确后填入密码来实现指纹识别

## lsp-it 打开清理内联钩子可以正常使用
### ~~不要更新新版本，新版本有反hook，目前支持到 7.21.0~~

## 告示
##### 本应用准备上架Google play 现在征集测试人员，详情可以去下面issue里可以看看

# 完整使用说明/GitHub项目
#### 模块成功Hook后会在设置里显示指纹设置选项，在里面打开总开关并设置好密码即可使用。
https://github.com/ghhccghk/mhspay

## 输入的密码会不会被窃取？
#### 密码使用AES加密，在有tee的设备会在tee加解密来保证安全，所有和密码有关的界面做了防录屏截图处理，防止第三方APP截取密码。本模块不会保留密码，密码只能在开启Debug编译的情况下在系统日志里会出现。

## 关于
### 讨论交流
去[这里](https://github.com/ghhccghk/mhspay)的Issue 交流
### 关于转载
该模块仅在Xposed module repo官方仓库发布
### 使用守则
严禁在公开区域宣传与展示本软件！
## 致谢
#### [Shellwen](https://github.com/ShellWen) 感谢其帮忙脱壳
#### [EzXHelper](https://github.com/KyuubiRan/EzXHelper) 使用了其项目
#### [XKT](https://github.com/xiaowine/XKT) 使用了其项目
#### [Lyric-Getter](https://github.com/xiaowine/Lyric-Getter) 参考了界面写法
#### [HyperCeiler](https://github.com/ReChronoRain/HyperCeiler) 参考了焦点通知实现
#### [MIUINativeNotifyIcon](https://github.com/fankes/MIUINativeNotifyIcon) 参考了小米系统信息获取
[<img src="https://resources.jetbrains.com/storage/products/company/brand/logos/jb_beam.png" width="200"/>](https://www.jetbrains.com)


