# 人类图标注工具

一个**纯前端、单文件、无需构建**的静态网页工具。用户对照自己手上的人类图，把每个闸门的颜色、中心的定义状态、定义通道逐项录入，最终**一键导出**一份标准化的文本报告，方便交给 AI 做交叉分析。

## 功能

- 按人类图九宫格展示 9 个中心、64 个闸门、36 条通道。
- 点击闸门循环切换 5 种颜色状态：无色、浅红、深红、黑色、条纹。
- 中心可切换「已定义 / 未定义」。
- 通道可标记「定义通道 / 未定义」。
- 一键生成并导出结构化报告（复制 / 下载 `.txt`）。
- 完全离线可用，数据仅存内存 + 导出，无后端、无账号。

## 使用

浏览器直接打开 `index.html` 即可使用，双击即开，无需安装。

## 线上地址

- 主站：https://humandesign.createtheunknowns.space
- 备用：https://humandesign-tool.vercel.app

## 部署（Vercel）

详见 [`DEPLOY-VERCEL.md`](./DEPLOY-VERCEL.md)。该项目是纯静态站，Vercel 按「Other」框架直接发布，无需构建命令。

## 目录结构

| 文件 | 说明 |
|---|---|
| `index.html` | 对外入口（空白版） |
| `humandesign-tool.html` | 空白交互版 |
| `humandesign-tool-DEVREADME.md` | 开发需求文档 |
| `DEPLOY-VERCEL.md` | 部署说明 |

> `humandesign-tool-阿比.html` 为个人测试用文件，仅本地，未上传。
