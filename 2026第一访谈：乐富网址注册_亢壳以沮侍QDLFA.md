乐富网址注册【Q-——333307——】乐富网址注册【 辋芷《888yx●vip》 】
乐富网址注册【Q-——333307——】乐富网址注册【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整指南

还在羡慕别人炫酷的个人博客？其实，你完全可以在 GitHub 上免费搭建一个属于自己的技术博客。无需购买服务器，无需备案，只需三步，你的专属博客就能上线。

 为什么要选择 GitHub Pages？

- 完全免费：静态托管和自定义域名都不花钱
- SEO 友好：GitHub Pages 的加载速度快，天生受搜索引擎青睐
- 版本管理：所有文章都在 Git 仓库中，修改历史一目了然

 第一步：环境准备（5分钟）

首先，确保你的电脑上已安装 Node.js 和 Git。在命令行中输入 `node -v` 和 `git --version` 验证是否成功。如果没有，去官网下载安装包，一路“下一步”即可。

 第二步：搭建 Hexo 博客框架

Hexo 是目前最流行的静态博客框架之一。打开终端，执行以下命令：

```bash
npm install -g hexo-cli
hexo init my-blog
cd my-blog
npm install
hexo server
```

此时，浏览器访问 `http://localhost:4000`，你就能看到默认的 Hexo 博客了。

 第三步：部署到 GitHub Pages

1. 新建仓库：在 GitHub 上创建一个名为 `你的用户名.github.io` 的公共仓库（务必与用户名一致）。
2. 修改配置：打开博客根目录的 `_config.yml` 文件，将 `deploy` 部分修改为：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

3. 一键部署：安装部署插件后，运行：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo deploy
```

 文章创作与 SEO 优化技巧

写文章时，在 `source/_posts` 目录下新建 `.md` 文件，使用 `hexo new "文章标题"` 创建。为了获得更好的收录效果，务必在文章头部填写 `title`、`tags` 和 `categories` 等 Front-matter 信息。

同时，安装 SEO 优化插件（如 `hexo-generator-sitemap`），并将站点地图提交给 Google Search Console 和百度搜索资源平台。

 遇到问题怎么办？

- 部署失败：检查 GitHub 邮箱是否公开，或确认仓库名是否完全匹配用户名。
- 样式错乱：运行 `hexo clean` 清除缓存后重新生成。

---

评论区聊聊：你的博客搭好了吗？踩过什么坑？ 如果这篇文章对你有帮助，点赞 + 收藏，下次搭建直接抄作业。更多《GitHub 从入门到进阶》系列教程正在路上，关注我，第一时间获取更新。

相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/2026%E6%9D%83%E5%A8%81%E7%83%AD%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E7%BD%91%E5%AE%98%E7%BD%91_%E8%AF%BD%E5%BE%98%E7%84%95%E6%8B%B1%E7%93%A4SYLFS.md

<img src="https://i.postimg.cc/XNH0VrMC/lefu-00016.png" />

相关推荐：

https://github.com/leebradley6/ubrqlg/commit/974b3eb6c4bff5eeb313a3a77dc4779bbe6d32c7

<img src="https://i.postimg.cc/c4vG6dZ5/lefu-00018.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/blob/main/%E8%B6%85%E5%85%A8%E5%AE%9E%E6%93%8D%E6%8C%87%E5%8D%97%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E7%BD%91%E5%BC%80%E6%88%B7_%E5%AD%9C%E4%BA%A4%E6%AA%80%E9%B9%BF%E4%B8%94SMRFZ.md

<img src="https://i.postimg.cc/50pWQ0XN/lefu-00012.png" />
相关推荐：

https://github.com/larsenpaul061/lcndhr/commit/cba92dfc9306120dac3bc0bde7f96cbe6aec41a9

<img src="https://i.postimg.cc/sf6RVMFw/lefu-00017.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
