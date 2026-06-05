# CodexKey

CodexKey 是面向 Codex 高频使用场景的本地桌面增强工具，支持卡密授权、多卡管理、自动换号、无限续杯和 OpenAI 兼容模型接入。软件会自动写入 Codex 本地配置，并在额度耗尽时通过手动续杯或自动切换可用卡账号继续对话，减少重复配置和手动换号。

> 本仓库仅用于产品说明、截图展示、版本发布和安装包分发。客户端源码不在此仓库公开。

英文版说明：[README.en.md](README.en.md)

## 核心能力

- **无限续杯流程**：当前额度用完后，可通过一键续杯或自动切换卡账号继续对话。
- **多卡管理**：一台设备可保存多张授权卡，支持卡片切换和当前卡状态展示。
- **自动换号**：从远程直连号池调度可用账号，减少额度耗尽后的手动处理。
- **本地配置写入**：自动写入 Codex 所需配置，并拉起 Codex 桌面端。
- **模型兼容**：支持 GPT-5.5、Image2 等 OpenAI 兼容模型。
- **自动更新**：通过 GitHub Releases 分发安装包，新版客户端支持启动后自动下载安装器。

## 下载

- 最新版本：`v4.4.27`
- 更新页面：https://github.com/Markovmodcn/CodexKey/releases/latest
- Windows 安装包：`Codexkey_4.4.27_x64-setup.exe`

## 软件截图

![CodexKey 软件截图](assets/software-screenshot.svg)

## 使用流程

1. 安装并打开 CodexKey。
2. 输入有效卡密并登录。
3. 点击一键续杯，写入 Codex 本地配置并拉起 Codex。
4. 额度用完后，选择手动续杯或自动切换其他可用卡账号继续对话。
5. 如服务端要求升级，新版客户端会自动下载安装器并启动更新。

## 支持与交流

欢迎 Star 收藏项目。版本更新、使用支持和活动通知会同步到交流群。

<p align="center">
  <a href="https://qm.qq.com/q/9DRP6SMeeA">
    <img src="assets/qq-group.jpg" width="220" alt="CodexKey QQ 群二维码" />
  </a>
</p>

<p align="center">
  <a href="https://qm.qq.com/q/9DRP6SMeeA"><strong>加入 QQ 群</strong></a>
</p>

## 说明

请合理使用账号与模型能力，遵守 OpenAI、Codex 及相关上游服务的使用条款。
