<!-- =========================================================
     ChaosJulien / GitHub Profile
     ========================================================= -->

<div align="center">

<a href="https://github.com/ChaosJulien">
  <img
    width="100%"
    src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=220&section=header&text=ChaosJulien&fontSize=70&fontAlignY=35&fontColor=ffffff&desc=Software%20Builder%20%C2%B7%20Full-stack%20%C2%B7%20Desktop%20%C2%B7%20AI-native&descSize=18&descAlignY=58&animation=fadeIn"
  />
</a>

### Build things that actually run.

从一个想法开始，把它做成**能运行、能部署、能维护的东西**。

Full-stack systems · Desktop applications · Automation · AI-assisted engineering

<br>

<img src="https://komarev.com/ghpvc/?username=ChaosJulien&label=Profile%20views&color=58A6FF&style=flat" alt="Profile views" />
<img src="https://img.shields.io/github/followers/ChaosJulien?label=Followers&style=flat&color=58A6FF" alt="Followers" />
<img src="https://img.shields.io/github/stars/ChaosJulien?affiliations=OWNER&style=flat&color=58A6FF&label=Stars" alt="Stars" />
<img src="https://img.shields.io/badge/Open%20to-Collaboration-58A6FF?style=flat" alt="Open to Collaboration" />

</div>

---

## 👋 About Me

I'm **ChaosJulien**, a student developer and software builder from China.

我更喜欢从真实问题出发，而不是为了技术而技术。

最近主要在探索：

- 🖥️ **Desktop & Graphics** — .NET / Avalonia / SkiaSharp / Windows
- 🌐 **Full-stack Systems** — Java / Spring Boot / Vue / TypeScript
- 🤖 **AI-native Applications** — Agent integration / automation / AI-assisted workflows
- 🐧 **Infrastructure** — Linux / Docker / Nginx / Redis / MySQL
- 📡 **Networking & Edge** — OpenWrt / LuCI / campus network automation
- 🛠️ **Developer Tools** — CI/CD / GitHub Actions / automation tooling

> I enjoy turning messy real-world problems into software that can actually ship.

---

## 🚧 Currently Building

```text
Desktop / Graphics
├─ Avalonia desktop applications
├─ GPU-backed UI experiments
└─ Windows native deployment

Full-stack / AI
├─ Spring Boot backend systems
├─ Vue / TypeScript frontends
├─ AI Agent & provider integration
├─ MySQL / Redis persistence
└─ Docker-based deployment

Infrastructure
├─ Linux services
├─ OpenWrt / LuCI
├─ GitHub Actions
└─ Production-oriented engineering
```

最近尤其关注：

**AI 应用如何真正进入现有业务系统，以及一个项目如何从 Prototype 一路走到 Production。**

---

# ✨ Featured Projects

## 🫧 LiquidGlassLab

**GPU-backed Liquid Glass rendering laboratory for Avalonia 11**

[![Repo](https://img.shields.io/badge/GitHub-LiquidGlassLab-181717?style=for-the-badge&logo=github)](https://github.com/ChaosJulien/LiquidGlassLab)
[![.NET](https://img.shields.io/badge/.NET-9.0-512BD4?style=for-the-badge&logo=dotnet)](https://github.com/ChaosJulien/LiquidGlassLab)
[![Avalonia](https://img.shields.io/badge/Avalonia-11-8B44AC?style=for-the-badge)](https://github.com/ChaosJulien/LiquidGlassLab)

一个面向 Avalonia / SkiaSharp 的实时 Liquid Glass 渲染实验项目。

探索：

- GPU-backed backdrop rendering
- Real-time refraction
- Progressive blur
- Chromatic dispersion
- Rounded-rectangle SDF
- Spring-driven interaction
- Persistent GPU surfaces
- CPU fallback
- NativeAOT
- Rendering diagnostics & tests

重点不是复刻某个 UI，而是探索 **桌面 UI 材质背后的实时渲染实现**。

➡️ **[Explore LiquidGlassLab](https://github.com/ChaosJulien/LiquidGlassLab)**

---

## 🧮 XiaoYuanKouSuan_Auto

**Computer vision + desktop automation experiment**

[![Stars](https://img.shields.io/github/stars/ChaosJulien/XiaoYuanKouSuan_Auto?style=for-the-badge&logo=github)](https://github.com/ChaosJulien/XiaoYuanKouSuan_Auto/stargazers)
[![Forks](https://img.shields.io/github/forks/ChaosJulien/XiaoYuanKouSuan_Auto?style=for-the-badge&logo=github)](https://github.com/ChaosJulien/XiaoYuanKouSuan_Auto/network/members)
[![Python](https://img.shields.io/badge/Python-OCR%20%2B%20Automation-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/ChaosJulien/XiaoYuanKouSuan_Auto)

基于 Python 的 OCR 视觉识别与自动化交互工具。

通过：

`Screen Capture → OCR → Result Parsing → Automated Interaction`

完成视觉驱动的自动化流程。

项目主要使用：

**Python · Tesseract OCR · OpenCV · PyAutoGUI**

➡️ **[Explore XiaoYuanKouSuan_Auto](https://github.com/ChaosJulien/XiaoYuanKouSuan_Auto)**

---

## 🌐 luci-app-drcom-auth

**OpenWrt / iStoreOS campus network authentication service**

[![Build](https://github.com/ChaosJulien/luci-app-drcom-auth/actions/workflows/build-ipk.yml/badge.svg)](https://github.com/ChaosJulien/luci-app-drcom-auth/actions)
[![Release](https://img.shields.io/github/v/release/ChaosJulien/luci-app-drcom-auth)](https://github.com/ChaosJulien/luci-app-drcom-auth/releases)
[![OpenWrt](https://img.shields.io/badge/OpenWrt-LuCI-00B5E2?style=flat&logo=openwrt&logoColor=white)](https://github.com/ChaosJulien/luci-app-drcom-auth)

为 OpenWrt / iStoreOS 编写的校园网 Drcom 自动认证插件。

包含：

- 网络状态自动检测
- 掉线自动恢复
- Session 异常处理
- 自动解绑与重新认证
- UCI 配置管理
- LuCI 图形化界面
- 运行状态与日志查看
- GitHub Actions 自动构建 IPK / Release

它来自一个很简单的问题：

> **“为什么路由器不能自己把校园网维护好？”**

于是把它做成了一个可以长期运行的服务。

➡️ **[Explore luci-app-drcom-auth](https://github.com/ChaosJulien/luci-app-drcom-auth)**

---

## 🛡️ RDPGuard

**Windows RDP defense, forensics and automated firewall response**

[![Repo](https://img.shields.io/badge/GitHub-RDPGuard-181717?style=for-the-badge&logo=github)](https://github.com/ChaosJulien/RDPGuard)
[![Python](https://img.shields.io/badge/Python-Security%20Automation-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://github.com/ChaosJulien/RDPGuard)

用于 Windows 公网服务器的 RDP 防御和攻击取证工具。

主要流程：

```text
Security Logs
      ↓
Attack Event Extraction
      ↓
Persistent Statistics
      ↓
Threshold Detection
      ↓
Windows Firewall Blocking
      ↓
Forensics / Reports / IP Attribution
```

支持：

- RDP 暴力破解事件提取
- SQLite 持久化
- 时间窗口攻击统计
- 自动 Windows Firewall 封禁
- 临时 / 永久封禁策略
- HTML 报告
- 云厂商 / IDC IP 归属分析
- 攻击取证数据导出

➡️ **[Explore RDPGuard](https://github.com/ChaosJulien/RDPGuard)**

---

# 🧰 Tech Stack

<div align="center">

### Core

<img src="https://skillicons.dev/icons?i=java,spring,vue,ts,js,py,cs,dotnet&perline=8" />

### Data & Infrastructure

<img src="https://skillicons.dev/icons?i=mysql,redis,docker,linux,nginx,cloudflare&perline=6" />

### Engineering

<img src="https://skillicons.dev/icons?i=git,githubactions,bash,powershell,vscode,idea,visualstudio&perline=7" />

<br>

<img src="https://img.shields.io/badge/Avalonia-Desktop_UI-8B44AC?style=for-the-badge" />
<img src="https://img.shields.io/badge/SkiaSharp-GPU_Rendering-4285F4?style=for-the-badge" />
<img src="https://img.shields.io/badge/OpenWrt-Networking-00B5E2?style=for-the-badge&logo=openwrt&logoColor=white" />
<img src="https://img.shields.io/badge/AI--Native-Engineering-7C3AED?style=for-the-badge" />

</div>

---

# 🧠 How I Build

我越来越倾向于把软件开发看成一个完整流程，而不仅是“写完代码”。

```text
Problem
  ↓
Research
  ↓
Architecture
  ↓
Prototype
  ↓
Implementation
  ↓
Tests
  ↓
Security
  ↓
Deployment
  ↓
Observability
  ↓
Iteration
```

AI 是这个流程中的 **engineering multiplier**，而不是最终目的。

我喜欢让 AI 参与：

- Research
- Architecture exploration
- Implementation
- Code review
- Refactoring
- Testing
- Documentation
- Debugging
- Automation

但最后仍然要回答一个问题：

> **Does it actually work?**

---

# 📊 GitHub

<div align="center">

<img
  height="170"
  src="https://github-readme-stats.vercel.app/api?username=ChaosJulien&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58A6FF&icon_color=58A6FF&count_private=true"
/>

<img
  height="170"
  src="https://github-readme-stats.vercel.app/api/top-langs/?username=ChaosJulien&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58A6FF&langs_count=8"
/>

</div>

---

## 🐍 Contributions

<div align="center">

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/ChaosJulien/ChaosJulien/output/github-contribution-grid-snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/ChaosJulien/ChaosJulien/output/github-contribution-grid-snake.svg"
  />
  <img
    alt="GitHub contribution snake"
    src="https://raw.githubusercontent.com/ChaosJulien/ChaosJulien/output/github-contribution-grid-snake.svg"
  />
</picture>

</div>

---

# 📫 Contact

<div align="center">

If you're building something interesting, feel free to reach out.

<br><br>

<a href="mailto:ChaosJulien@qq.com">
  <img src="https://img.shields.io/badge/Email-ChaosJulien%40qq.com-EB1923?style=for-the-badge&logo=tencentqq&logoColor=white" />
</a>

<a href="https://github.com/ChaosJulien">
  <img src="https://img.shields.io/badge/GitHub-ChaosJulien-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

<br><br>

**Build. Ship. Learn. Iterate.**

</div>

<img
  width="100%"
  src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=130&section=footer"
/>
