乐富娱乐代理【Q-——333307——】乐富娱乐代理【 辋芷《888yx●vip》 】
乐富娱乐代理【Q-——333307——】乐富娱乐代理【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

还在羡慕别人炫酷的技术博客？其实，用 GitHub Pages 和 Hexo，半小时就能搞定一个免费、高速、支持 HTTPS 的个人网站。这篇文章手把手教你从零开始部署，即使没有服务器，也能拥有专属域名。

 为什么推荐这套组合？

- 零成本：Github Pages 的免费托管服务，无需购买云服务器。
- 极致速度：全球 CDN 加速，国内访问也很快。
- 写作友好：支持 Markdown 语法，专注内容创作。
- 版本管理：所有文章都在 Git 仓库，天然支持备份与协作。

 第一步：环境准备与安装

这是一个硬性前置条件，请确保电脑已安装 Git 和 Node.js（建议 LTS 版本）。打开终端，输入以下命令验证：

```bash
node -v && git --version
```

看到版本号后，全局安装 Hexo 脚手架：

```bash
npm install -g hexo-cli
```

 第二步：初始化与部署到 Github

在本地新建文件夹并初始化博客项目：

```bash
hexo init my-blog && cd my-blog
npm install
```

此时本地已生成基础模板。接下来，先在 GitHub 新建一个仓库（名称格式必须为：`用户名.github.io`）。然后打开 `_config.yml`，将 `deploy` 配置修改为：

```yml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
```

执行三条命令完成部署（需要输入 GitHub 账号密码或 Token）：

```bash
hexo clean && hexo generate
hexo deploy
```

恭喜！ 浏览器访问 `https://你的用户名.github.io`，你的个人博客已经上线。

 第三步：进阶优化与写作体验

为了让博客更好看并利于 SEO（搜索引擎收录），推荐安装两款插件：

- `hexo-generator-sitemap`：自动生成站点地图。
- `hexo-theme-next`：经典优雅的主题。

文章封面如何设置？ 在文章头部 `Front-matter` 中加入 `cover: /images/xx.jpg` 即可。

关于搜索引擎收录：百度对纯静态站点抓取极快，建议在根目录提交一个 `baidu-site-verification.txt` 文件认证站点归属。

---

互动引导：如果你在部署过程中遇到了 `EADDRINUSE` 报错或部署后样式丢失等问题，你是如何解决的？ 欢迎在评论区分享你的踩坑经历。

如果这篇文章帮到了你，请点赞并转发给正在学前端的朋友。关注我，持续分享 GitHub 实战技巧与独立开发日志。

(写作不易，你的支持是我最大的动力！)

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/blob/main/2026%E7%AC%AC%E4%B8%80%E7%83%AD%E6%A6%9C%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E5%AE%A2%E6%9C%8D_%E5%AF%BF%E9%99%A1%E7%9B%96%E5%9B%8A%E8%B0%A2MUAOB.md

<img src="https://i.postimg.cc/FKy4mGmf/lefu-00008.png" />

相关推荐：

https://github.com/hoffmanandrew448/cbjrry/commit/95659b2f28b0156d16759720fab735ce19085b5d

<img src="https://i.postimg.cc/9McjfTF9/lefu-00009.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/blob/main/%E4%BF%9D%E5%A7%86%E5%AE%9E%E6%93%8D%E6%94%BB%E7%95%A5%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E4%BB%A3%E7%90%86_%E9%82%AE%E7%86%AC%E7%99%BE%E7%94%A8%E4%B9%87EYSNO.md

<img src="https://i.postimg.cc/FKy4mGmf/lefu-00008.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/commit/7bd815537cd9d8da442df58dd623ea83183ff453

<img src="https://i.postimg.cc/FKy4mGmf/lefu-00008.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
