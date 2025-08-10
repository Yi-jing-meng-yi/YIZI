2# YIZI 安全防护系统

[![License](https://img.shields.io/badge/license-GPLv3-blue.svg)](LICENSE)
[![Min SDK](https://img.shields.io/badge/min%20SDK-24%2B(Android%207.0)-green.svg)](#)
[![Kotlin](https://img.shields.io/badge/language-Kotlin%2BJava-purple.svg)](#)

**为每个人的隐私防护方案** 

## English Version

[English Version](README_EN.md)

## 核心特性

### 空白通行证
- 动态生成虚拟设备信息（IMEI/Android ID等）
- 提供虚假位置数据（支持GPS/基站/WiFi模拟）
- 伪造通讯录和通话记录
- 应用级权限隔离控制

### 黑皇后防护
- 主动占用逆向分析端口（8080/8888等）
- 实时网络流量监控
- 检测Frida/Xposed等调试工具
- 反VPN流量嗅探

### 智能权限代理
- 三模权限获取（Root/Shizuku/ADB）
- 自动化ADB无线调试配置
- 一键式权限授予管理
- 后台服务保活机制

## 技术架构

```
graph TD
    A[YIZI Core] --> B[Virtual Passport]
    A --> C[BlackQueen]
    A --> D[Permission Proxy]
    B --> B1[Data Generator]
    B --> B2[Permission Hook]
    C --> C1[Port Occupier]
    C --> C2[Traffic Analyzer]
    D --> D1[Root Manager]
    D --> D2[Shizuku Bridge]
```

## 快速开始

### 编译要求
- Android Studio Giraffe+ 
- JDK 17
- Android SDK 24

### 运行模式
| 模式 | 所需权限 | 功能完整性 |
|------|---------|-----------|
| Root模式 | Root权限 | 100% |
| Shizuku模式 | Shizuku授权 | 85% |
| ADB模式 | 无线调试 | 70% |

##  开源许可
```text
GNU General Public License v3.0

允许：
- 私人使用
- 商业授权（需申请）
禁止：
- 恶意代码植入
- 闭源商业分发
```

##  参与贡献

**暂无**
---

>  联系我们: xyhqqpyp@outlook.com


### 目前YIZI的状态
正在开发中

### 我想使用?不知道怎么使用。
[YIZI使用方法](YIZI使用方法.md)

## 我们为什么那么做?

- 病毒窃取资料
- 非法应用窃取手机资料
- 不经意的一点"允许"，你的隐私在不法商贩那里就像裸奔。

## 我们应用未来准备做哪些方面的隐私防护?

- 网站防护
- 电脑YIZI反向病毒防范
- 黑皇后改进
- 防止合法应用误检查

## 我想要加入，可以吗
>  技术交流群(QQ):1043544284 
---
**我们是YIZI，欢迎您的加入和构想提供**
