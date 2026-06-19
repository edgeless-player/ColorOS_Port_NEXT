<div align="center">

#  ColorOS/OxygenOS 移植项目

简体中文&nbsp;&nbsp;|&nbsp;&nbsp;[English](/README_en-US.md) 

</div>

## 简介
- ColorOS/OxygenOS 一键自动移植打包

## 支持机型
- OnePlus8T

## 测试机型及版本
BASE:
- OnePlus 8T (ColorOS_14.0.0.602)
PORT:
- OnePlus Ace6T（ColorOS_16.0.5.702）
- OnePlus 15 (ColorOS_16.0.7.206)

## 正常工作
- 人脸
- 挖孔
- 指纹
- 相机
- NFC
- 自动亮度
- 小布语音唤醒
- 关机充电
- etc

## BUG
- AOD亮度太低
- 模拟音频输出不可用
- 亮度条异常（C16）

## 如何使用
- 在Ubuntu下
```shell
    sudo apt update && sudo apt upgrade -y
    sudo apt install git -y
    # 克隆项目
    git clone https://github.com/edgeless-player/ColorOS_Port_NEXT.git
    cd ColorOS_Port_NEXT
    # 安装依赖
    sudo ./setup.sh
    # 开始移植
    sudo ./port.sh <底包路径> <移植包路径>
```
- 路径可以是系统包链接，将路径替换为系统包下载链接即可
- 请确保设备的运行内存足够使用，通常需要空闲8G以上，存储空间请预留大约100G

## 感谢
> 本项目使用了以下开源项目的部分或全部内容，感谢这些项目的开发者（排名顺序不分先后）。

- [「BypassSignCheck」by Weverses](https://github.com/Weverses/BypassSignCheck)
- [「contextpatch」 by ColdWindScholar](https://github.com/ColdWindScholar/TIK)
- [「fspatch」by affggh](https://github.com/affggh/fspatch)
- [「gettype」by affggh](https://github.com/affggh/gettype)
- [「lpunpack」by unix3dgforce](https://github.com/unix3dgforce/lpunpack)
- [「miui_port」by ljc-fight](https://github.com/ljc-fight/miui_port)
- etc

## 注
- 严禁以商品形式将该项目的任何内容（包括打包后的移植包）转卖出去，这是极其无耻的，没有道德底线的行为
- 我们在任何平台发现这种情况，将会选择创建一个文档，将这类情况集中收集到文档中
- 欢迎大佬或者有能力的人发送issue为我们项目提供帮助，该项目永久开源
- 在此处向所有曾经为本项目付出努力的人致以最崇高的感谢，同时也向所有移植作者致以最崇高的感谢
