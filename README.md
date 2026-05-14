# JianJiCode Show

JianJiCode 产品展示页面 —— 单文件 HTML 实现粒子动画开场 + 11 页互动幻灯片。

## 技术栈

- **Three.js** — 3D 粒子云动画（打字机文字 → 形变 → 炸开 → 挥洒 → 收缩）
- **GSAP** — 入场动画、时间轴编排
- **PIXI.js** — 2D 粒子背景层
- **原生 ESM import map** — 零构建、零依赖安装

## 运行

直接用浏览器打开 `index.html` 即可。

或使用任意静态文件服务器：

```bash
python -m http.server 8765
# 打开 http://localhost:8765
```

## 操作

- **键盘 ↑↓ / 滚轮** — 翻页
- **右侧圆点** — 快速跳转

## 幻灯片

| 页 | 内容 |
|----|------|
| 1 | 3D 粒子动画开场 + JianJiCode 标题 |
| 2 | 用嘴剪视频 —— AI 看懂画面，听懂指令 |
| 3 | 交互即编辑 —— 卡片式主页 |
| 4 | 不只是聊天 —— AI 侧边栏 + 编辑器 |
| 5 | 对话即剪辑 —— 横滑对比展示 |
| 6 | 视觉化编辑 —— Before/After |
| 7 | 宫格跟踪 —— 全息界面感知 |
| 8 | 全链路透明执行 —— 意图→命令 |
| 9 | 越剪越顺手 —— AI 记忆工作流 |
| 10 | 38 个剪辑引擎，一句话调度 |
| 11 | 结尾 CTA |

## 文件结构

```
├── index.html          # 主文件（CSS + HTML + JS）
└── images/
    ├── *.png           # 截图/素材
    └── grid.mp4        # 宫格动画视频
```
<img width="736" height="553" alt="image" src="https://github.com/user-attachments/assets/e8322553-a126-4e10-95a0-0e8bf718ed06" />
