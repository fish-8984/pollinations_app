# Pollinations AI 创作工坊

基于 [pollinations.ai](https://pollinations.ai) API 的 AI 图片生成与聊天工具。

## 功能

- **图片生成** — 输入文字描述，AI 生成对应图片
- **AI 聊天** — 与 AI 进行对话，支持 Markdown 渲染

## 技术栈

- 纯前端，无后端依赖
- HTML + CSS + JavaScript
- 使用 API：
  - [pollinations.ai Image Generation API](https://image.pollinations.ai)
  - [pollinations.ai Text Generation API](https://text.pollinations.ai)
- Markdown 渲染：[marked.js](https://marked.js.org)

## 在线演示

- [https://fish-8984.github.io/pollinations_app/index.html](https://fish-8984.github.io/pollinations_app/index.html)

## 本地运行

```bash
# 克隆仓库
git clone https://github.com/fish-8984/pollinations_app.git

# 直接打开 index.html 即可，或使用本地服务器
npx serve .
```

## 部署

支持一键部署到：

- GitHub Pages
- Vercel
- Netlify
- Cloudflare Pages

## License
MIT
