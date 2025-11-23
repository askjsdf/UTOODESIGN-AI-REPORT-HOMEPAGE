# UTOO DESIGN

AI驱动的品牌内容系统与战略设计服务平台

## 项目简介

UTOO DESIGN 是一个汇聚全球顶尖设计院校专家的创意团队，致力于通过AI驱动的内容系统与战略设计，为品牌提供兼具美学高度与商业智慧的解决方案。

## 核心功能

- **全球舆情侦测** - 24/7实时监控社交媒体热点与用户情绪
- **AI+专家双重解码** - 结合LLM推理与行业专家洞察
- **跨文化内容资产** - 多语言本地化内容生成
- **全场景数字化分发** - 全渠道内容复用与分发

## 技术栈

- HTML5
- CSS3 (模块化架构)
- JavaScript (jQuery, GSAP, Swiper)
- SVG 动画

## 本地开发

1. 克隆项目
```bash
git clone <your-repo-url>
cd ashley
```

2. 使用本地服务器运行
```bash
# 使用 Python
python -m http.server 8000

# 或使用 Node.js
npx serve
```

3. 在浏览器中访问
```
http://localhost:8000
```

## 部署

项目已配置 Vercel 部署，推送到 GitHub 后可自动部署。

### Vercel 部署步骤：
1. 将项目推送到 GitHub
2. 在 Vercel 中导入 GitHub 仓库
3. Vercel 会自动检测并部署

## 项目结构

```
ashley/
├── index.html          # 主页面
├── 404.html           # 404错误页
├── publication.html   # 案例详情页
├── css/              # 样式文件
│   ├── modules/      # 模块化CSS
│   └── plugins/      # 第三方插件样式
├── js/               # JavaScript文件
│   ├── main.js       # 主要逻辑
│   └── plugins/      # 第三方插件
├── img/              # 图片资源
└── vercel.json       # Vercel配置

## License

© 2025 UTOO DESIGN. All Rights Reserved.
