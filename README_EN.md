# YIZI Security Protection System

[![License](https://img.shields.io/badge/license-GPLv3-blue.svg)](LICENSE)
[![Min SDK](https://img.shields.io/badge/min%20SDK-24%2B(Android%207.0)-green.svg)](#)
[![Kotlin](https://img.shields.io/badge/language-Kotlin%2BJava-purple.svg)](#)

**Next-Generation Android Privacy Protection Solution** 

## 中文版

[中文版](README.md)

## Core Features

### Blank Passport
- Dynamically generate virtual device information (IMEI/Android ID, etc.)
- Provide fake location data (supports GPS/cell tower/WiFi simulation)
- Fabricate contacts and call logs
- App-level permission isolation control

### BlackQueen Protection
- Actively occupy reverse analysis ports (8080/8888, etc.)
- Real-time network traffic monitoring
- Detect debugging tools like Frida/Xposed
- Anti-VPN traffic sniffing

### Smart Permission Proxy
- Triple-mode permission acquisition (Root/Shizuku/ADB)
- Automated ADB wireless debugging configuration
- One-click permission granting management
- Background service keep-alive mechanism

## Technical Architecture

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

## Quick Start

### Compilation Requirements
- Android Studio Giraffe+
- JDK 17
- Android SDK 24

### Operation Modes
| Mode | Required Permissions | Feature Completeness |
|------|----------------------|----------------------|
| Root Mode | Root access | 100% |
| Shizuku Mode | Shizuku authorization | 85% |
| ADB Mode | Wireless debugging | 70% |

## Open Source License
```text
GNU General Public License v3.0

Permitted:
- Private use
- Commercial authorization (requires application)
Prohibited:
- Malicious code implantation
- Closed-source commercial distribution
```

## Contributing
Currently none
---

> Contact us: xyhqqpyp@outlook.com

### Current Status of YIZI
Under development

## Why Are We Doing This?

- Viruses stealing data
- Illegal apps stealing phone information
- An accidental "Allow" click, and your privacy is exposed to malicious vendors.

## What Privacy Protections Are We Planning for the Future?

- Website protection
- Computer YIZI reverse virus prevention
- BlackQueen improvements
- Preventing false positives by legitimate apps

## Can I Join?
> Technical discussion group (QQ): 1043544284

#### We are YIZI. Welcome to join and share your ideas.