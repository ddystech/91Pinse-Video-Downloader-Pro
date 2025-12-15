# 91Pinse-Video-Downloader-Pro

![License](https://img.shields.io/badge/license-MIT-green) ![Python](https://img.shields.io/badge/python-3.9-blue) ![Build](https://img.shields.io/badge/build-passing-brightgreen)

**91Pinse-Video-Downloader-Pro** 是一款基于 Python 开发的高级桌面视频下载工具。
它集成了 `yt-dlp` 核心解析算法，支持从 91pinse 及相关镜像站自动提取并高速下载视频资源。

## ❤️ 赞助商与数据支持 (Sponsors)

本项目的网络线路优化与测试节点资源由以下平台提供支持：

> ### 🌸 [寻芳](https://xunfang.io)
> **全网最全的同城楼凤信息与兼职外围索引平台。**
> 拒绝照骗和仙人跳，收录海量真实老师资源，老司机修车必备的靠谱导航。
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
