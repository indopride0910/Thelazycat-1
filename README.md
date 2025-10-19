# TheLazyCat - Persistent Auto-Injector v4.2

![TheLazyCat Banner](https://img.shields.io/badge/Version-4.2-blue) ![Android Support](https://img.shields.io/badge/Android-5.0--12.0-green) ![Metasploit](https://img.shields.io/badge/Metasploit-Compatible-red)

A powerful Android persistence injection tool that creates persistent backdoor APKs with advanced stealth capabilities. Support for Android 5.0 to 12.0.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Quick Start](#quick-start)
- [Detailed Usage Guide](#detailed-usage-guide)
- [Permission Reference](#permission-reference)
- [Troubleshooting](#troubleshooting)
- [Persistence Mechanisms](#persistence-mechanisms)
- [Legal Disclaimer](#legal-disclaimer)

## 🚀 Overview

TheLazyCat is an advanced Android APK injection tool that automatically injects persistent Meterpreter payloads into legitimate applications. It provides multiple persistence mechanisms and flexible permission selection for comprehensive access.

## ✨ Features

- ✅ **Auto Persistence** - Multiple startup mechanisms
- ✅ **Boot Time Execution** - Auto-starts after device reboot
- ✅ **Background Services** - Runs as foreground service
- ✅ **Permission Injection** - Flexible permission selection
- ✅ **Stealth Operation** - Minimal user detection
- ✅ **Android 5-12 Support** - Broad compatibility
- ✅ **Automated Process** - One-click operation

## ⚙️ Prerequisites

### Essential Tools Installation

**Ubuntu/Debian:**
```bash
# Update system
sudo apt update && sudo apt upgrade -y

# Install required tools
sudo apt install apktool metasploit-framework default-jdk wget -y
