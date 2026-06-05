# CodexKey

## 中文

CodexKey 是面向 Codex 高频使用场景的本地桌面增强工具，提供卡密授权、多卡管理、自动换号、无限续杯和 OpenAI 兼容模型接入能力。软件会自动写入 Codex 本地配置，并在额度耗尽时通过手动续杯或自动切换可用卡账号继续对话，减少重复配置和手动换号。

> 本仓库仅用于产品说明、截图展示、版本发布和安装包分发。客户端源码不在此仓库公开。

### 核心能力

- **无限续杯流程**：当前额度用完后，可通过一键续杯或自动切换卡账号继续对话。
- **多卡管理**：一台设备可保存多张授权卡，支持卡片切换和当前卡状态展示。
- **自动换号**：从可用账号池中调度直连账号，减少额度耗尽后的手动处理。
- **本地配置写入**：自动写入 Codex 所需配置，并拉起 Codex 桌面端。
- **模型兼容**：支持 GPT-5.5、Image2 等 OpenAI 兼容模型。
- **线上更新**：通过 GitHub Releases 分发安装包和更新文件，公开仓库不包含客户端源码。

### 下载

- 最新版本：`v4.4.26`
- 更新页面：https://github.com/Markovmodcn/CodexKey/releases/latest
- Windows 安装包：`Codexkey_4.4.26_x64-setup.exe`

### 软件截图

![CodexKey 软件截图](assets/software-screenshot.svg)

### 使用流程

1. 安装并打开 CodexKey。
2. 输入有效卡密并登录。
3. 点击一键续杯，写入 Codex 本地配置。
4. 打开或继续使用 Codex 桌面端。
5. 额度用完后，选择手动续杯或自动切换其他可用卡账号继续对话。

### 支持与交流

欢迎 Star 收藏项目。版本更新、使用支持和活动通知会同步到交流群。

<p align="center">
  <a href="https://qm.qq.com/q/9DRP6SMeeA">
    <img src="assets/qq-group.jpg" width="220" alt="CodexKey QQ 群二维码" />
  </a>
</p>

<p align="center">
  <a href="https://qm.qq.com/q/9DRP6SMeeA"><strong>加入 QQ 群</strong></a>
</p>

### 说明

请合理使用账号与模型能力，遵守 OpenAI、Codex 及相关上游服务的使用条款。

## English

CodexKey is a local desktop enhancement tool for high-frequency Codex workflows. It provides card-key authorization, multi-card management, automatic account rotation, unlimited refill workflows, and OpenAI-compatible model access. CodexKey writes the required local Codex configuration and helps continue conversations when quota is exhausted by using one-click refill or automatic switching to another available card/account.

> This repository is used only for product documentation, screenshots, release notes, and installer distribution. Client source code is not published here.

### Highlights

- **Unlimited refill workflow**: continue after quota exhaustion through one-click refill or automatic card/account switching.
- **Multi-card management**: save multiple authorized cards on one device, switch cards, and view current card status.
- **Automatic account rotation**: schedule available direct accounts from the account pool to reduce manual handling.
- **Local Codex configuration**: write the required local Codex configuration and launch the Codex desktop app.
- **Model compatibility**: supports GPT-5.5, Image2, and other OpenAI-compatible models.
- **Release channel**: installers and update files are distributed through GitHub Releases, while client source code remains private.

### Download

- Latest version: `v4.4.26`
- Update page: https://github.com/Markovmodcn/CodexKey/releases/latest
- Windows installer: `Codexkey_4.4.26_x64-setup.exe`

### Screenshot

![CodexKey screenshot](assets/software-screenshot.svg)

### Usage

1. Install and open CodexKey.
2. Log in with a valid card key.
3. Click one-click refill to write the local Codex configuration.
4. Open or continue using the Codex desktop app.
5. When quota is exhausted, use manual refill or automatic switching to continue with another available card/account.

### Support

Star this repository to follow release updates. Usage support and activity notices are shared in the QQ group.

### Notice

Use accounts and model capabilities responsibly. Follow the terms of OpenAI, Codex, and related upstream services.
