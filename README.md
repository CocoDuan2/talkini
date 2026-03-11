# Talkini - 英语课件推荐与水平测试

帮助家长和学生找到最适合的英语课程。通过科学的水平测试快速定级，精准推荐匹配的课件。

## 功能

- **英语水平测试** — 4 个趣味关卡（字母识别 → 词汇量 → 句子理解 → 综合运用），5 分钟快速定级，测完自动推荐课程
- **课件推荐指南** — 40+ 套课件详细介绍，覆盖启蒙、进阶、拔高、成人四个阶段

## 项目结构

```
├── index.html               # 首页入口
├── pages/
│   ├── level-test.html      # 英语水平测试页
│   └── courseware.html       # 课件推荐页
└── docs/
    └── 课件推荐.md           # 课件内容 Markdown 源文件
```

## 部署

本项目为纯静态站点，无需构建步骤，直接通过 GitHub Pages 部署：

1. 推送代码到 GitHub 仓库
2. Settings → Pages → Source 选择 `main` 分支，目录选 `/ (root)`
3. 保存后等待部署完成，访问 `https://<username>.github.io/talkini/`

## 技术栈

- 纯 HTML / CSS / JavaScript，无框架依赖
- [marked.js](https://github.com/markedjs/marked)（CDN）用于 Markdown 渲染
- 移动端优先的响应式设计
