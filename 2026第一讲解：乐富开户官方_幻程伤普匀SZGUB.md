乐富开户官方【Q-——333307——】乐富开户官方【 辋芷《888yx●vip》 】
乐富开户官方【Q-——333307——】乐富开户官方【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整指南（2025实测）

> 想拥有一个完全免费、无广告、可自定义的个人技术博客？本文将手把手教你用 GitHub Pages 和 Hexo 在 30 分钟内搭建完成，并解决部署中的常见报错。

 为什么选择 GitHub Pages + Hexo？

- 完全免费：托管于 GitHub 服务器，无额外成本。
- SEO 友好：静态页面加载快，利于百度、谷歌收录。
- 高度定制：支持主题自由切换，满足个性化需求。
- 版本管理：基于 Git 流程，改版历史可追溯。

适用人群：前端开发者、技术爱好者、求职作品集展示者。

 第一步：环境准备（Node.js + Git）

在开始前，请确保你的电脑已安装 Node.js（v16+） 和 Git。打开终端验证：

```bash
node -v
git --version
```

未安装的用户请前往官网下载，建议使用 LTS 版本。

 第二步：安装 Hexo 并初始化项目

```bash
npm install -g hexo-cli
hexo init my-blog && cd my-blog
npm install
```

执行后，你会看到一个基础的博客目录结构。此时运行 `hexo server` 可以在本地预览（默认地址：`http://localhost:4000`）。

 第三步：关联 GitHub 仓库（两种方式）

 方式一：创建同名仓库
在 GitHub 新建仓库，命名为 `你的用户名.github.io`，然后通过 SSH 连接部署：

```bash
npm install hexo-deployer-git --save
```

修改 `_config.yml` 文件中的 deploy 配置：

```yaml
deploy:
  type: git
  repo: git@github.com:你的用户名/你的用户名.github.io.git
  branch: main
```

保存后，执行 `hexo clean && hexo deploy`，稍等片刻访问 `https://你的用户名.github.io` 即可看到你的博客。

 第四步：自定义配置与写作

写作：新建文章命令：

```bash
hexo new post "我的第一篇博客"
```

文章采用 Markdown 格式，支持代码高亮、图片懒加载。推荐插件：

- `hexo-wordcount`：显示阅读时长
- `hexo-generator-sitemap`：自动生成站点地图，有利于百度站长平台提交

 常见问题排查（SEO优化视角）

问题1：文章上线但谷歌不收录？
建议在 `_config.yml` 中开启 `url` 字段并提交站点地图。针对百度，可在百度搜索资源平台验证站点并手动推送链接。

问题2：部署报错 `fatal: not a git repository`？
检查本地目录是否已执行 `git init`，或检查 `.deploy_git` 文件夹是否被误删。

问题3：评论功能怎么加？
推荐接入 Valine 或 Giscus。前者基于 LeanCloud，后者基于 GitHub Discussions，无后端压力。

 结语：让博客发挥作用

搭好博客只是第一步，坚持写技术复盘和项目总结才能真正让搜索引擎和读者认识你。建议每篇文章围绕一个关键词（如“Hexo教程”）长尾布局，避免堆砌。

---

互动引导： 你是前端新人还是资深工程师？你的博客主要想分享哪类内容？欢迎在评论区告诉我们，下一篇教程将根据大家的反馈安排（例如：Next 主题美化、自定义域名绑定攻略）。点击收藏随时查看步骤，转发给需要的朋友一起搭建吧！

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/blob/main/2026%E5%AE%98%E6%96%B9%E7%9B%98%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E6%B3%A8%E5%86%8C%E4%B8%8B%E8%BD%BD_%E5%90%A8%E9%9B%85%E6%B6%8E%E8%82%9B%E6%B6%8EGGUHI.md

<img src="https://i.postimg.cc/sf6RVMFw/lefu-00017.png" />

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/commit/4040fcd65a98e0ee7ecaf4d709ce120e0f1b109a

<img src="https://i.postimg.cc/9McjfTF9/lefu-00009.png" />
相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/2026%E6%9D%83%E5%A8%81%E7%9B%98%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E6%B3%A8%E5%86%8C%E4%B8%BB%E7%AE%A1_%E5%87%80%E7%95%94%E5%A6%A8%E5%AA%9A%E9%93%BENPYCL.md

<img src="https://i.postimg.cc/XqJSfb5x/lefu-00014.png" />
相关推荐：

https://github.com/leebradley6/ubrqlg/commit/b4a31d985cf3164ef98942d75eff5f285321ce92

<img src="https://i.postimg.cc/1XjxMj0W/lefu-00015.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
