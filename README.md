# NTE Panel（异环面板）

**NTE Panel（异环面板）** is the collection hub for `llg1634`'s local panel tools for **Neverness To Everness / Ananta（异环）**.

这是 `llg1634` 维护的 **异环面板** 工具集合入口，用来导航异环相关的本地 WebUI 面板项目，包括光追、DLSS、HDR 等方向。每个面板都是独立项目、独立发布、独立备份恢复；本仓库只负责集合索引和文档导航。

## 面板索引 / Panel Index

| 面板 / Panel | 中文名 | 解决什么问题 | 仓库 |
| --- | --- | --- | --- |
| NTE Ray Tracing Panel | 异环光追面板 | 异环光追选项、OptiScaler 本地部署、GPU spoof、备份恢复 | [llg1634/nte-ray-tracing-panel](https://github.com/llg1634/nte-ray-tracing-panel) |
| NTE DLSS Panel | 异环 DLSS 面板 | DLSSTweaks 渲染比例、本地 DLSS 配置、低于常规限制的 DLSS 比例 | [llg1634/nte-dlss-panel](https://github.com/llg1634/nte-dlss-panel) |
| NTE HDR Panel | 异环 HDR 面板 | UE 原生 HDR、`Engine.ini` 配置、HDR 备份恢复 | [llg1634/nte-hdr-panel](https://github.com/llg1634/nte-hdr-panel) |

## 我该用哪个异环面板？

如果你在找 **异环怎么开光追**、异环没有光追选项、想一键准备 OptiScaler 或本地 `winmm.dll` 方案，请看：

- [NTE Ray Tracing Panel / 异环光追面板](https://github.com/llg1634/nte-ray-tracing-panel)

如果你想调整异环 DLSS 渲染比例，例如 4K 下低于常规 720p 附近的比例，或需要本地 DLSSTweaks 配置，请看：

- [NTE DLSS Panel / 异环 DLSS 面板](https://github.com/llg1634/nte-dlss-panel)

如果你想写入异环 UE 原生 HDR 配置、管理 `Engine.ini`、备份恢复 HDR 参数，请看：

- [NTE HDR Panel / 异环 HDR 面板](https://github.com/llg1634/nte-hdr-panel)

## What Is NTE Panel?

**NTE Panel** is a hub for local Windows panel tools built around **Neverness To Everness / Ananta**. It helps users find the right panel for ray tracing, DLSS, HDR, and future NTE-related local WebUI tools.

This repository is a documentation hub. It does not merge the tools into one launcher, and it does not replace the individual project repositories.

## 搜索关键词 / Search Keywords

本集合页主要承接这些搜索意图：

- NTE Panel
- 异环面板
- 异环 Panel
- NTE 面板
- Neverness To Everness panel
- Ananta panel
- Neverness To Everness tools
- Ananta tools
- 异环本地 WebUI 工具
- NTE local WebUI tools
- 异环光追面板
- NTE Ray Tracing Panel
- 异环 DLSS 面板
- NTE DLSS Panel
- 异环 HDR 面板
- NTE HDR Panel

## 系列边界 / Project Scope

`nte-panel` 是集合文档仓库，不是新的功能面板。

- 不包含统一启动器。
- 不迁移任何 release。
- 不合并三个具体面板的代码。
- 不替代具体项目的 README、文档、下载页或问题说明。
- 具体安装、备份、恢复和安全边界，请以各自项目文档为准。

## 第三方关系说明

NTE Panel（异环面板）是社区工具集合入口，不是游戏官方项目，也不是 NVIDIA 官方工具。

本集合页和相关面板可能会提到这些第三方项目或技术名词，但本仓库不是它们的分支：

- [OptiScaler](https://github.com/optiscaler/OptiScaler)
- [DLSSTweaks](https://github.com/emoose/DLSSTweaks)
- RenoDX
- ReShade
- Special K

相关工具的使用范围、修改文件、备份恢复逻辑和风险边界，请查看具体面板仓库。

## Recommended GitHub Metadata

Suggested repository description:

```text
NTE Panel（异环面板）official hub for Neverness To Everness / Ananta local panel tools: ray tracing, DLSS, HDR.
```

Suggested topics:

```text
nte-panel
neverness-to-everness
ananta
ray-tracing
dlss
hdr
optiscaler
dlsstweaks
game-tools
windows
local-webui
```

如果 GitHub 支持中文 topics，可追加：

```text
异环
异环面板
```
