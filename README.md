# 场景仓库

AI 对话驱动开发 — 场景节点拆解与商业化优化指南。

## 概述

记录和整理 AI 对话驱动开发中的典型场景，将每个场景拆解为可执行的节点，并为每个节点提供优化建议和商业化方向。

## 场景列表

| # | 场景 | 节点数 | 建议数 |
|---|------|--------|--------|
| 1 | 视频媒体下载与处理 | 4 | 12 |
| 2 | 网页数据抓取与分析 | 4 | 12 |
| 3 | 网站建设与自动部署 | 4 | 12 |
| 4 | AI 技能工具链管理 | 4 | 12 |
| 5 | 内网穿透与公网暴露 | 3 | 9 |
| 6 | AI 对话驱动开发 | 4 | 12 |
| 7 | 连锁门店收益统计与抽成 | 4 | 12 |
| 8 | 上海科技馆参观流程 | 9 | 27 |

共 **8** 个场景、**38** 个节点、**108** 条优化建议。

## 部署方式

### GitHub Pages（当前方案）

纯静态页面，所有数据内嵌在 HTML 中。

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
