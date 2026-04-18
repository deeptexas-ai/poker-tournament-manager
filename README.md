# 🏆 德州扑克赛事系统 - Poker Event Server (CPG/TJPT Style)

[![License: AGPL v3](https://img.shields.io/badge/License-AGPLv3-blue.svg)](LICENSE)
[![C++17](https://img.shields.io/badge/C%2B%2B-17-blue)](https://isocpp.org/)
[![TARS](https://img.shields.io/badge/TARS-RPC-blue)](https://tarscloud.org/)
[![Docker](https://img.shields.io/badge/docker-ready-brightgreen)](docker-compose.yml)

**专业德州扑克赛事服务端** — 类似CPG、TJPT的线上线下比赛系统，支持锦标赛、积分榜、盲注结构管理。

## ✨ 核心特性

| 模块 | 支持内容 |
|------|----------|
| 🏅 **赛事管理** | 线上线下锦标赛、卫星赛、资格赛 |
| 📊 **盲注结构** | 自定义盲注级别、涨盲时间、休息时间 |
| 👥 **选手管理** | 注册、签到、座位分配、计分牌 |
| 🏆 **排名系统** | 实时排行榜、积分计算、奖励分配 |
| 🔄 **赛事状态** | 延迟注册、暂停、重新开赛、结束 |
| 📱 **全平台** | 服务端为移动端/PC端提供API |
| ⚡ **高性能** | C++17 + TARS RPC + Redis，支撑千级并发 |


## 📱 💰 获取源码 | Contact


📱 Telegram：@xuzongbin001



## 📸 系统截图

| 赛事大厅 | 盲注结构 | 排行榜 |
|:--------:|:--------:|:------:|
![2024_02_03_21_40_IMG_7034](https://github.com/user-attachments/assets/85861554-0d1b-4658-8c9c-babf035bf0ef)
![2024_02_03_21_39_IMG_7030](https://github.com/user-attachments/assets/6f219415-3af4-4da0-86db-9783c718c81f)
![2024_01_20_13_01_IMG_6700](https://github.com/user-attachments/assets/239be3ab-4baf-48b7-9828-6bec8fb2a808)
![2024_01_20_12_59_IMG_6697](https://github.com/user-attachments/assets/95196594-fe7e-4ad4-bb26-52925a5e2999)
![2024_01_20_12_59_IMG_6696](https://github.com/user-attachments/assets/84d1328c-58f8-441d-bfed-1a4b59ce4fb4)
![2024_01_20_12_59_IMG_6695](https://github.com/user-attachments/assets/9efddd2d-7e12-4d10-8dc4-a2b6e5f68de3)
![2024_01_20_12_59_IMG_6694](https://github.com/user-attachments/assets/802f4dc6-9a01-45ca-9312-5978671bb023)
![2024_01_20_12_59_IMG_6693](https://github.com/user-attachments/assets/8c48cb1e-9ebd-41f4-90fb-68035171ddcb)
![2024_01_20_12_59_IMG_6692](https://github.com/user-attachments/assets/3c33b7c5-21c5-456c-9cb8-ef66102fc147)
![2024_01_20_12_59_IMG_6691](https://github.com/user-attachments/assets/8291aec3-048d-422b-a3d2-b3fc7a54119f)

## 🚀 快速开始

### 方式一：Docker 一键运行（推荐）
```bash
# 1. 克隆仓库
git clone https://github.com/deeptexas-ai/Texas-Hold-em-Poker-Event.git
cd Texas-Hold-em-Poker-Event

# 2. 启动所有服务
docker-compose up -d

# 3. 查看日志
docker logs -f poker-event-server

# 4. 访问TARS管理端
open http://localhost:3000
## 🏗️ 企业级技术栈 / Enterprise Stack / 企業級技術棧
Frontend: React + TypeScript + Tailwind
Backend: Node.js + Express + Socket.io
Database: SQLite/PostgreSQL
Real-time: WebSocket广播
BigScreen: HTML5全屏投影
Mobile: PWA + 响应式
Deploy: Docker + Nginx
Monitor: 选手在线统计

## 📱 多设备完美协作 / Multi-Device / 多設備協作

💻 PC管理赛事
📱 手机选手报名/入座
📺 大屏实时投影
⌚ iPad盲注控制
🔄 全程同步

## 🎯 赛事全流程 / Event Workflow / 賽事流程

创建赛事 → 设置盲注表/报名费

选手扫码报名 → 自动分组

启动时钟 → 大屏投影

淘汰入桌 → 自动更新

决赛FT → 实时排行

自动结算 → 奖金分配

积分统计 → 年度冠军

## 💎 独家赛事功能 / Unique Features / 獨家賽事功能
✅ 扫码快速报名
✅ 自动盲注推进
✅ 实时转桌管理
✅ 奖池智能分配
✅ FT大屏特效
✅ 直播流集成
✅ 选手自助入座
✅ 历史赛事存档
## 📦 跨平台部署 / Cross-Platform / 跨平台部署
💻 Windows/macOS/Linux (Electron)
🌐 浏览器PWA
📱 手机WebApp
📺 大屏投影
🔌 Docker容器

## 🎯 适用场景 / Use Cases / 適用場景
🏠 家庭扑克之夜
👥 俱乐部周赛
🏢 企业团建赛
📺 直播赛事
🎰 赌场锦标赛
🌍 线上卫星赛

## 📄 License
MIT License - 赛事商用顶级友好
Copyright (c) 2026 deeptexas-ai

---

**⭐ 专业赛事，从筹备到冠军一站式！ / Pro tournament management! / 專業賽事，從籌備到冠軍一站式！**

