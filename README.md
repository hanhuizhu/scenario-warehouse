# 场景仓库

AI 对话驱动开发 — 场景节点拆解与商业化优化指南。

## 概述

记录和整理 AI 对话驱动开发中的典型场景，将每个场景拆解为可执行的节点，并为每个节点提供优化建议和商业化方向。

## 场景列表

| # | 场景 | 节点数 | 建议数 |
|---|------|--------|--------|
| 1 | 去人民公园闲逛场景 | 8 | 24 |
| 2 | 上海科技馆参观流程 | 9 | 27 |
| 3 | 去金山卫看烟花场景 | 8 | 24 |
| 4 | 跟老婆一起人广看脱口秀 | 8 | 24 |
| 5 | 去外滩给外国游船客户发船票 | 8 | 24 |
| 6 | 视频媒体下载与处理 | 4 | 12 |
| 7 | 网页数据抓取与分析 | 4 | 12 |
| 8 | 网站建设与自动部署 | 4 | 12 |
| 9 | AI 技能工具链管理 | 4 | 12 |
| 10 | 内网穿透与公网暴露 | 3 | 9 |
| 11 | AI 对话驱动开发 | 4 | 12 |
| 12 | 连锁门店收益统计与抽成 | 4 | 12 |

共 **12** 个场景、**70** 个节点、**204** 条优化建议。

## 部署方式

### GitHub Pages（当前方案 · 自动发布）

纯静态页面，所有数据内嵌在 HTML 中。**修改后 push 到 main 分支即自动发布到 Pages。**

- **Pages 地址**: https://hanhuizhu.github.io/scenario-warehouse/
- **GitHub 仓库**: https://github.com/hanhuizhu/scenario-warehouse

### 本地浏览

```bash
# 方式一：直接浏览器打开
open index.html

# 方式二：HTTP 服务
python3 -m http.server 8000
# 访问 http://localhost:8000
```

## Pages 配置

在 GitHub 仓库 Settings → Pages 中：
- **Source**: Deploy from a branch
- **Branch**: `main` / `/(root)`
- 根目录放 `index.html`，自动识别

## 技术栈

- 纯 HTML + CSS + JavaScript
- 无任何外部依赖
- 响应式设计，移动端适配
- GitHub Pages 托管
