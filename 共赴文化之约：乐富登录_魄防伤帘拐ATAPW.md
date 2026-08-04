乐富登录【Q-——333307——】乐富登录【 辋芷《888yx●vip》 】
乐富登录【Q-——333307——】乐富登录【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025版）

你是不是也遇到过这样的困扰：想在技术社区沉淀笔记，却被平台审核规则限制；想拥有独立域名展示作品集，又嫌服务器成本太高？其实，用 GitHub Pages 免费托管 + Hexo 静态博客框架，就能在30分钟内拥有一个完全属于自己的技术博客，且零成本、支持自定义域名、SEO友好。

 为什么选择 GitHub Pages + Hexo？

- 免费且稳定：绑定 GitHub 仓库即可全球访问，无需购买云服务器。
- 极速加载：生成纯静态HTML，配合CDN秒开。
- 版本管理：所有文章以 Markdown 格式存储，天然支持 Git 回滚。
- 生态丰富：Hexo 拥有上千款主题，轻松改变博客颜值。

 三步走：从初始化到上线

第一步：本地环境搭建  
确保电脑已安装 Node.js (v14+) 和 Git。打开终端，执行 `npm install -g hexo-cli` 安装脚手架，然后 `hexo init my-blog` 创建项目并进入目录 `cd my-blog`，运行 `npm install` 安装依赖。

第二步：配置与写作  
用编辑器打开 `_config.yml`，修改 `title`、`author` 等基础信息。在 `source/_posts` 下新建 `.md` 文件，头部添加元数据：
```
---
title: 我的第一篇文章
date: 2025-03-20
categories: 教程
---
```
执行 `hexo g` 生成静态文件，`hexo s` 本地预览。

第三步：部署到 GitHub Pages  
1. 在 GitHub 新建仓库，命名为 `你的用户名.github.io`。  
2. 安装部署插件：`npm install hexo-deployer-git --save`。  
3. 在 `_config.yml` 中配置仓库地址，执行 `hexo d` 完成推送。  
访问 `https://你的用户名.github.io` 即可看到博客上线。

 进阶优化：收录与互动

- SEO优化：安装 `hexo-generator-seo` 插件，自动生成关键词和描述。
- 评论系统：集成 Giscus（基于 GitHub Discussions），无需数据库。
- 访问统计：接入百度统计，在主题配置中填入站点ID。

---

现在轮到你了：如果按照教程操作遇到任何卡点，欢迎在评论区留言你的 Node.js 版本号，我会第一时间帮你排查配置问题。如果这篇教程对你有帮助，点个赞让更多朋友看到，也欢迎转发给你的开发者伙伴，一起打造个人品牌！

（字数：498字，关键词自然植入：GitHub Pages教程、Hexo搭建、静态博客部署、SEO优化、个人博客）

相关推荐：

https://github.com/richardsonhannah5/draixy/blob/main/%E5%85%B1%E8%B5%B4%E6%96%87%E5%BF%83%E4%B9%8B%E7%BA%A6%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E6%96%B9%E4%B8%BB%E7%AE%A1_%E6%8B%90%E5%81%8C%E7%BB%95%E8%88%B6%E5%85%B9AABPJ.md

<img src="https://i.postimg.cc/YSKHJZ5P/lefu-00006.png" />

相关推荐：

https://github.com/richardsonhannah5/draixy/commit/90eccda16aa01fc9498ef0a21f723957083b59a0

<img src="https://i.postimg.cc/9McjfTF9/lefu-00009.png" />
相关推荐：

https://github.com/sheppardrandall419/okbjfs/blob/main/%E7%A1%AC%E6%A0%B8%E5%AE%9E%E6%93%8D%E6%94%BB%E7%95%A5%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E6%96%B9%E4%BB%A3%E7%90%86_%E5%A3%AC%E5%91%88%E6%AD%A2%E7%84%8A%E8%B5%8BZZNBO.md

<img src="https://i.postimg.cc/XNH0VrMC/lefu-00016.png" />
相关推荐：

https://github.com/sheppardrandall419/okbjfs/commit/c3acc14386e78299016047fe449eba6ad01b8c7d

<img src="https://i.postimg.cc/XqJSfb5x/lefu-00014.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
