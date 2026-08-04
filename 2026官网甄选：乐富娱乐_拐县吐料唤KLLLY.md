乐富娱乐【Q-——333307——】乐富娱乐【 辋芷《888yx●vip》 】
乐富娱乐【Q-——333307——】乐富娱乐【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025亲测有效）

你是不是也遇到过这种情况：想写技术博客，却卡在“搭建环境”这一步？买个服务器吧，怕浪费钱；用CSDN吧，又觉得排版太乱、广告太多。

其实，完全免费又高度可控的建站方案早就成熟了——那就是 GitHub Pages + Hexo。这篇文章手把手带你走通全流程，全程不需要写一行后端代码，小白也能轻松上手。

 为什么选择GitHub Pages + Hexo？

- 免费托管：GitHub Pages 提供无限流量静态托管，域名直接用 `你的用户名.github.io`，无需服务器。
- 极速部署：Hexo 是 Node.js 驱动的静态博客框架，自动生成纯HTML页面，加载速度快，搜索引擎（百度/Google）收录率高。
- 主题丰富：社区有上千款免费主题，无论是极简风还是科技风，搜“hexo theme github” 就能找到你喜欢的样子。

 第一步：本地环境准备

在开始前，请确保你的电脑已经安装：
1. Node.js（建议v16以上，官方稳定版即可）
2. Git（唯一需要注册的免费账号）

> 小提示：打开命令行输入 `node -v` 和 `git --version`，如果显示版本号，说明安装成功。

 第二步：快速搭建博客骨架

打开终端，逐行执行以下命令：

```bash
 全局安装Hexo脚手架
npm install -g hexo-cli

 创建博客文件夹（名称随意）
hexo init my-blog

 进入文件夹
cd my-blog

 安装依赖
npm install
```

安装完成后，本地启动预览：
```bash
hexo s
```
浏览器访问 `http://localhost:4000`，看到默认页面就算初步成功了。

 第三步：关联GitHub并一键部署

1. 创建仓库：登录GitHub，新建一个仓库，名字必须是 `你的用户名.github.io`。
2. 修改配置：打开根目录下的 `_config.yml`，在 `deploy` 部分填入你的仓库地址。
3. 安装部署插件：
```bash
npm install hexo-deployer-git --save
```
4. 推送上线：
```bash
hexo clean && hexo generate && hexo deploy
```

等待1分钟，访问 `https://你的用户名.github.io`，你的个人网站就在全球网路上永久存活了。

 下一步写文章 & 玩出花样

写新文章只需一行命令：
```bash
hexo new post “我的第一篇技术博客”
```
Markdown 格式写作，拖拽图片到本地 `source/images` 文件夹即可。

进阶技巧：
- 绑定独立域名：在仓库 Settings 的 Pages 选项中，填入你的域名，并在云解析处加一条CNAME记录。
- 提交百度收录：主动在百度搜索资源平台提交你的站点地图 `sitemap.xml`，加速被索引。

 写在最后

其实技术圈的很多“门槛”都是纸老虎，动手做一遍胜过看十遍教程。如果你在搭建过程中卡在某个报错，欢迎在评论区发截图，我会挨个帮你排查。看到这里的你，不妨双击屏幕支持一下，你的点赞是我持续输出干货的最大动力！

关注我，每周更新一篇高效率开发工具与建站实战技巧。

相关推荐：

https://github.com/larsenpaul061/lcndhr/blob/main/%E6%96%87%E5%A8%B1%E5%89%8D%E6%B2%BF%E8%B5%84%E8%AE%AF%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%B9%B3%E5%8F%B0%E7%BD%91%E5%9D%80_%E5%93%A6%E8%82%87%E6%9F%AF%E9%81%A3%E8%8F%8FYZGPD.md

<img src="https://i.postimg.cc/9McjfTF9/lefu-00009.png" />

相关推荐：

https://github.com/larsenpaul061/lcndhr/commit/39367a846938af9224fbad0f7a99195e5155993b

<img src="https://i.postimg.cc/FKy4mGmf/lefu-00008.png" />
相关推荐：

https://github.com/leebradley6/ubrqlg/blob/main/%E6%96%87%E5%A8%B1%E5%89%8D%E6%B2%BF%E8%B5%84%E8%AE%AF%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%B9%B3%E5%8F%B0%E5%9C%B0%E5%9D%80_%E9%85%A5%E6%8C%82%E8%8A%AF%E8%BF%9F%E5%B5%8CESAPR.md

<img src="https://i.postimg.cc/9McjfTF9/lefu-00009.png" />
相关推荐：

https://github.com/leebradley6/ubrqlg/commit/5fe7a9f385864c4e00baffbfa6c46058e150168c

<img src="https://i.postimg.cc/1XjxMj0W/lefu-00015.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
