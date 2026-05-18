# NTE Panel（异环配置工具集合）

**NTE Panel（异环配置工具集合）** 是 `llg1634` 维护的 **异环配置工具集合文档页**，用于索引 Neverness To Everness / Ananta（异环）相关的本地 WebUI 配置面板。

这个仓库本身不是新的启动器，也不合并各个工具的功能；它主要用来整理 **异环光追配置**、**异环 DLSS 配置**、**异环 HDR 配置** 等配置方向，并把用户导向对应的独立项目。你也可以把它理解为 **异环面板**、**异环配置面板**、**异环本地配置工具** 的导航入口。

## 配置工具索引 / Configuration Tool Index

| 配置方向 | 对应配置工具 | 适合处理的问题 | 仓库 |
| --- | --- | --- | --- |
| 异环光追配置 | NTE Ray Tracing Panel（异环光追面板） | 开启或管理异环光追相关配置、OptiScaler 本地方案、GPU spoof、配置备份恢复 | [llg1634/nte-ray-tracing-panel](https://github.com/llg1634/nte-ray-tracing-panel) |
| 异环 DLSS 配置 | NTE DLSS Panel（异环 DLSS 面板） | 调整异环 DLSS 渲染比例、DLSSTweaks 本地配置、低于常规限制的 DLSS 比例、配置备份恢复 | [llg1634/nte-dlss-panel](https://github.com/llg1634/nte-dlss-panel) |
| 异环 HDR 配置 | NTE HDR Panel（异环 HDR 面板） | 写入或恢复异环 UE 原生 HDR 配置、管理 `Engine.ini` HDR 参数、配置备份恢复 | [llg1634/nte-hdr-panel](https://github.com/llg1634/nte-hdr-panel) |

## 我该用哪个异环配置工具？

如果你在找 **异环怎么开光追**、**异环光追配置**、异环没有光追选项，或想准备 OptiScaler / 本地 `winmm.dll` 方案，请看：

- [NTE Ray Tracing Panel / 异环光追面板](https://github.com/llg1634/nte-ray-tracing-panel)

如果你想调整 **异环 DLSS 配置**，例如修改 DLSS 渲染比例、在 4K 下使用低于常规 720p 附近的比例，或需要本地 DLSSTweaks 配置，请看：

- [NTE DLSS Panel / 异环 DLSS 面板](https://github.com/llg1634/nte-dlss-panel)

如果你想写入 **异环 HDR 配置**、管理异环 `Engine.ini`、备份或恢复 UE 原生 HDR 参数，请看：

- [NTE HDR Panel / 异环 HDR 面板](https://github.com/llg1634/nte-hdr-panel)

## 常见中文搜索场景

这个集合页主要承接中文用户在查找异环配置工具时的导航需求，例如：

- 搜索“异环配置工具”“异环配置面板”“异环面板”，想找到异环相关本地 WebUI 配置工具。
- 搜索“异环光追配置”“异环怎么开光追”“异环没有光追选项”，想找到光追配置面板。
- 搜索“异环 DLSS 配置”“异环 DLSS 比例”“异环 DLSSTweaks”，想找到 DLSS 配置面板。
- 搜索“异环 HDR 配置”“异环 Engine.ini HDR”“异环 UE HDR”，想找到 HDR 配置面板。

## What Is NTE Panel?

**NTE Panel** is a documentation hub for local Windows configuration tools built around **Neverness To Everness / Ananta**. It helps users find the right configuration panel for ray tracing, DLSS, HDR, and future NTE-related local WebUI tools.

This repository only provides collection, indexing, and documentation navigation. It does not merge the tools into one launcher, and it does not replace the individual project repositories.

## 系列边界 / Project Scope

`nte-panel` 是异环配置工具集合文档仓库，不是新的功能面板。

- 不包含统一启动器。
- 不迁移任何 release。
- 不合并三个具体配置面板的代码。
- 不替代具体项目的 README、文档、下载页或问题说明。
- 具体安装、配置写入、备份、恢复和安全边界，请以各自项目文档为准。

## 第三方关系说明

NTE Panel（异环配置工具集合）是社区文档导航入口，不是游戏官方项目，也不是 NVIDIA 官方工具。

本集合页和相关配置面板可能会提到这些第三方项目或技术名词，但本仓库不是它们的分支：

- [OptiScaler](https://github.com/optiscaler/OptiScaler)
- [DLSSTweaks](https://github.com/emoose/DLSSTweaks)
- RenoDX
- ReShade
- Special K

相关工具的使用范围、修改文件、配置写入方式、备份恢复逻辑和风险边界，请查看具体面板仓库。

## Recommended GitHub Metadata

Suggested repository description:

```text
NTE Panel（异环配置工具集合）community hub for Neverness To Everness / Ananta local configuration tools: ray tracing, DLSS, HDR.
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
configuration-tools
```

如果 GitHub 支持中文 topics，可追加：

```text
异环
异环面板
异环配置工具
异环配置面板
```
