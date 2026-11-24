# 3D 64-Channel EEG & Cortical Atlas · 3D 64导联脑电与皮层定位交互图谱

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-06b6d4?style=flat-square&logo=github)](https://hollis-cao.github.io/eeg-64ch-atlas/)
[![License: MIT](https://img.shields.io/badge/License-MIT-a855f7?style=flat-square)](LICENSE)

一个基于 **Three.js** 构建的纯静态交互式 **3D 64 导联（国际 10-10 / 10-20 系统）脑电与大脑皮层定位图谱**，帮助神经科学、脑机接口（BCI）与认知心理学研究者直观查看电极空间位置、皮层解剖投射、经典 ERP 成分及脑电节律。

👉 **在线体验 (Live Demo)**：https://hollis-cao.github.io/eeg-64ch-atlas/

---

## ✨ 主要特性 (Features)

- **完整 64 导联国际 10-10 系统**：自动标注 10-20 核心导联与 10-10 扩展导联，支持点击任意 3D 电极或 2D 投影标签查看详情。
- **程序化 3D 大脑皮层模型**：包含脑回/脑沟、外侧裂、中央沟、顶枕沟、小脑与脑干结构，支持一键切换「脑叶分区着色」与「解剖组织着色」，以及头皮透明度滑块。
- **双侧同源对称与皮层投射可视化**：选中电极后实时绘制头皮至皮层的垂直投射光束与对侧同源电极（如 `P3 ↔ P4`、`C3 ↔ C4`）虚线对称弧。
- **五大功能网络一键筛选**：运动想象与执行（MI/ME）、空间定向与注意、执行控制与 P300、视觉与 SSVEP、语言与听觉。
- **全文即时检索**：支持按导联名、脑区、ERP 成分（如 `P300`、`N170`、`ERN`、`MMN`、`SSVEP`）或 BCI 范式检索，选中后相机自动环绕聚焦。
- **高清图谱 PNG 导出**：一键导出带电极标注与左右方位标（`L / R`）的高分辨率透明背景/深色背景示意图，适合论文与 PPT 配图。

## ⌨️ 快捷键 (Keyboard Shortcuts)

| 按键 | 功能 |
| :--- | :--- |
| `/` | 聚焦搜索框 |
| `1` – `5` | 切换视角（俯视 / 左侧 / 右侧 / 前额 / 后枕） |
| `Space` | 开启 / 暂停自动旋转 |
| `Esc` | 关闭搜索下拉框 / 移动端详情抽屉 |

## 🚀 本地运行 (Local Usage)

本项目为单文件纯静态网页，无需构建步骤，直接用浏览器打开 `index.html` 即可运行。

## 📄 License

MIT License © [Hollis-Cao](https://github.com/Hollis-Cao)
