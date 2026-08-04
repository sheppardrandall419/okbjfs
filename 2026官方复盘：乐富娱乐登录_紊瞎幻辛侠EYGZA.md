乐富娱乐登录【Q-——333307——】乐富娱乐登录【 辋芷《888yx●vip》 】
乐富娱乐登录【Q-——333307——】乐富娱乐登录【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

还在羡慕别人的技术博客？其实搭建一个属于自己的博客，比你想的更简单。今天这份教程将手把手带你使用 GitHub Pages 和 Hexo 免费部署一个高性能静态博客。整个过程无需购买服务器，完全免费，而且支持自定义域名。

 为什么选择 Hexo + GitHub Pages？

我相信你一定听说过 WordPress 或 Halo，但静态博客有明显的速度优势。Hexo 基于 Node.js 构建，生成的是纯静态 HTML 文件，加载速度极快，对搜索引擎优化（SEO）非常友好。配合 GitHub Pages 的全球 CDN 加速，国内访问体验也不错。

 第一步：环境准备

在开始之前，请确保你的电脑已经安装以下工具：

- Node.js（推荐使用 LTS 版本，即长期支持版）
- Git 版本控制工具
- GitHub 账号（还没有的话赶紧注册一个）

安装完成后，打开终端（命令行），输入 `node -v` 和 `git --version` 验证安装是否成功。

 第二步：安装 Hexo 并初始化项目

在命令行执行以下命令，全局安装 Hexo 脚手架：

```bash
npm install -g hexo-cli
```

安装完成后，创建一个新的博客目录并初始化：

```bash
hexo init my-blog
cd my-blog
npm install
```

此时你的本地博客已经跑起来了。输入 `hexo s` 启动本地服务，在浏览器访问 `http://localhost:4000` 就能看到默认主题。

 第三步：关联 GitHub 仓库

1. 在 GitHub 上新建一个仓库，命名为 `你的用户名.github.io`。
2. 回到本地博客目录，打开 `_config.yml` 文件，修改 `deploy` 配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

3. 安装自动部署插件：

```bash
npm install hexo-deployer-git --save
```

4. 执行部署命令：

```bash
hexo clean && hexo g && hexo d
```

等待片刻，刷新你的 GitHub Pages 地址，博客就正式上线了！

 最后一步：写作与日常维护

以后的写作流程非常简单：

```bash
hexo new post "我的第一篇文章"
```

编辑生成在 `source/_posts` 目录下的 Markdown 文件，写完后再执行一次部署命令即可。推荐将文章图片存入 OSS 或图床，防止仓库体积过大。

---

如果你觉得这篇教程对你有帮助，欢迎点赞、收藏并转发给你的朋友！

更多开发技巧，请持续关注我的博客，后续会分享如何配置 SEO、添加评论系统以及自定义主题。你在搭建过程中遇到任何问题，都可以在评论区留言，我看到会及时回复。

相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/%E6%B2%89%E9%86%89%E6%96%87%E5%BF%83%E5%AF%BB%E6%A2%A6%EF%BC%9A%E4%B9%90%E5%AF%8C%E4%B8%BB%E7%AE%A1%E5%B9%B3%E5%8F%B0_%E5%87%89%E8%B6%9F%E6%8B%BC%E4%B8%88%E9%9B%8DNUGUW.md

<img src="https://i.postimg.cc/9McjfTF9/lefu-00009.png" />

相关推荐：

https://github.com/leebradley6/ubrqlg/commit/100102b91bd194dd059d254f5693b0987e06c3fb

<img src="https://i.postimg.cc/XqJSfb5x/lefu-00014.png" />
相关推荐：

https://github.com/richardsonhannah5/draixy/blob/main/%E6%BC%94%E8%89%BA%E5%9C%88%E6%96%B0%E9%B2%9C%E6%8A%A5%EF%BC%9A%E4%B9%90%E5%AF%8C%E7%BD%91%E5%9D%80%E5%AE%A2%E6%9C%8D_%E9%85%92%E6%B2%83%E5%92%B3%E6%95%9B%E9%83%B4SSSST.md

<img src="https://i.postimg.cc/9McjfTF9/lefu-00009.png" />
相关推荐：

https://github.com/richardsonhannah5/draixy/commit/29856737dad585498bbdc2a7a8690d472529c450

<img src="https://i.postimg.cc/XJx6BJpR/lefu-00011.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
