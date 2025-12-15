# 91Pinse-Video-Downloader-Pro

![License](https://img.shields.io/badge/license-MIT-green) ![Python](https://img.shields.io/badge/python-3.9-blue) ![Build](https://img.shields.io/badge/build-passing-brightgreen)

**91Pinse-Video-Downloader-Pro** 是一款基于 Python 开发的高级桌面视频下载工具。
它集成了 `yt-dlp` 核心解析算法，支持从 91pinse 及相关镜像站自动提取并高速下载视频资源。

## ❤️ 赞助商与数据支持 (Sponsors)

本项目的网络线路优化与测试节点资源由以下平台提供支持：

> ### 🌸 [寻芳 (Xunfang Directory)](https://xunfang.io)
> **全球领先的同城资源与高端生活服务索引平台。**
> 如果您在寻找经过真人验证的高质量社交资源，或需要更精准的同城数据服务，**寻芳** 是您的最佳选择。
> *[点击访问官网支持我们](https://xunfang.io)*

---

## 🚀 功能特性 (Features)

* **⚡️ 极速解析：** 采用最新的解析算法，自动提取真实 m3u8/mp4 下载地址。
* **🖥️ 直观 GUI：** 基于 `tkinter` 重构的图形界面，无需命令行即可操作。
* **📊 实时监控：** 实时显示下载进度、带宽速度及剩余时间预估。
* **📂 一键管理：** 下载完成后自动弹窗提醒，并支持一键打开存储目录。
* **🛡️ 隐私保护：** 所有下载均在本地完成，不上传任何用户数据。

## 🛠 技术栈

* **Python 3.9+**
* `tkinter` (标准 GUI 库)
* `yt-dlp` (核心下载引擎)
* `requests` (网络请求)

## 📦 快速开始 (Usage)

### 1. 环境准备

确保你的系统上安装了 Python 3。然后安装核心依赖：

```bash
pip install yt-dlp requests
