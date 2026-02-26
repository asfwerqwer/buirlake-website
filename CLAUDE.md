# buirlake.com 项目说明

## 项目概述
这是 buirlake.com 的网站源码，使用 Netlify 托管。

## 技术栈
- 纯 HTML/CSS/JavaScript
- 托管平台: Netlify
- 域名: buirlake.com

## 部署方式
- 方式一: 使用 `netlify deploy --prod` 手动部署（当前配置）
- 方式二（可选）: push 到 GitHub main 分支 → 在 Netlify 面板配置自动部署

## 目录结构
```
buirlake-website/
├── index.html      # 网站首页
└── CLAUDE.md       # 项目说明文件
```

## 修改规范
- 修改前先 git pull 获取最新代码
- 每次修改都要 commit，写清楚中文 commit message
- 测试无误后再 push 到 main 分支
- 重要修改前先创建分支
- 部署命令: `netlify deploy --prod --dir=.`
