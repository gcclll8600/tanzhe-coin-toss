# 投铜钱 · 听福音

一个受潭柘寺线下投掷铜钱体验启发的零依赖网页小游戏。玩家移动准星、控制力度，把铜钱投向五枚由小到大的悬挂铜钱；正中铃铛、击中铜钱本体和落空会触发不同的动画、得分与声音反馈。

![项目封面](docs/cover.png)

[English README](README.en.md) · [贡献指南](CONTRIBUTING.md) · [更新记录](CHANGELOG.md)

## 特性

- 红金福字墙、金色支架、五枚递增铜钱的沉浸式场景
- 鼠标全屏瞄准，按住空格蓄力、松开投掷
- 触屏与纯鼠标的“两次点击”操作方式
- 铃铛、铜钱本体和落空三种命中反馈
- 原创 Web Audio BGM、铃声、铜声和落空音效
- 八枚铜钱、功德分和清铃连中奖励
- 手机、平板和桌面浏览器响应式适配
- 无框架、无依赖、无构建步骤，单个 `index.html` 即可运行

## 立即体验

下载仓库后直接双击 `index.html`，或在项目目录启动任意静态文件服务器。

浏览器出于安全限制，需要在首次点击或按空格后才会开始播放音乐。

## 操作方法

### 电脑

1. 移动鼠标控制准星。
2. 按住空格键蓄力，蓄力期间仍可继续瞄准。
3. 松开空格键投掷，约七成力度最稳定。

### 触屏或纯鼠标

1. 点击游戏区域确定准星位置。
2. 第一次点击底部按钮开始蓄力。
3. 第二次点击按钮投掷。

## 发布到 GitHub Pages

仓库已包含自动发布工作流：

1. 新建一个公开 GitHub 仓库。
2. 将本文件夹内的全部内容推送到仓库的 `main` 分支。
3. 在仓库的 **Settings → Pages** 中将发布来源设为 **GitHub Actions**。
4. 打开 **Actions** 页面，等待 `Deploy static site to Pages` 完成。

此后每次推送到 `main`，GitHub Pages 都会自动更新。

## 项目结构

```text
.
├── index.html                 # 完整游戏：结构、样式、交互与声音
├── docs/
│   ├── cover.png              # README 封面
│   └── architecture.md        # 实现说明
├── .github/
│   ├── workflows/pages.yml    # GitHub Pages 自动发布
│   ├── ISSUE_TEMPLATE/        # Bug 与功能建议模板
│   └── pull_request_template.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
├── SECURITY.md
├── CHANGELOG.md
└── LICENSE
```

## 参与贡献

欢迎提交 Bug、玩法建议、无障碍改进、音效设计或视觉优化。开始前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。

## 文化与版权说明

本项目是基于线下民俗游戏的独立数字化实验，与潭柘寺官方无隶属、合作或授权关系。参考照片未包含在仓库中。项目中的代码、代码生成视觉和原创程序化声音按 [MIT License](LICENSE) 开放。

## License

[MIT](LICENSE) © 2026 Tanzhe Coin Toss contributors
