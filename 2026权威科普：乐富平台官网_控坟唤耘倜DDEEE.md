乐富平台官网【Q-——333307——】乐富平台官网【 辋芷《888yx●vip》 】
乐富平台官网【Q-——333307——】乐富平台官网【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整部署教程

还在羡慕别人拥有专属技术博客？其实用 GitHub Pages 和 Hexo，30 分钟就能免费搞定。本文基于真实踩坑经验，为你拆解从环境配置到域名绑定的全流程，附赠 SEO 优化技巧。

 一、为什么选择 Hexo + GitHub Pages？

免费、极速、支持 Markdown，还能绑定自定义域名。最重要的是，GitHub 全球 CDN 加速让国内访问速度也很快。如果你想要一个轻量级技术博客，这是目前最优解。

 二、环境搭建三步走

1. 安装 Node.js 和 Git：去官网下载 LTS 版本，一路下一步即可
2. 全局安装 Hexo：执行 `npm install -g hexo-cli`
3. 初始化博客：`hexo init my-blog`，然后 `cd my-blog && npm install`

小技巧：初始化速度慢时，可以切换到淘宝镜像源。

 三、部署到 GitHub Pages

创建仓库后，修改 `_config.yml` 中的部署配置，然后依次运行：

```bash
hexo clean && hexo generate
hexo deploy
```

访问 `https://你的用户名.github.io` 即能看到博客上线。

 四、SEO 优化：让文章被搜索引擎收录

很多新手部署完发现百度搜不到文章，原因是没有做收录。建议在安装完主题后：

- 安装 `hexo-generator-sitemap` 生成站点地图
- 在主题配置中开启 `noindex` 和 `nofollow` 字段
- 手动提交百度站长平台验证页面

代码示例已放在文末，需要可直接复制。

 五、常见问题和解决思路

部署失败？八成是 SSH key 没配置。文章页面 404？检查仓库名称是否完全匹配。评论区不生效？推荐使用 Giscus 插件，直接关联 GitHub Discussions。

 六、进阶玩法：多端同步写作

利用 Git 分支管理，可以在任何电脑上写文章。只需把 `source/_posts` 目录同步到 GitHub 私有仓库，新电脑 `git clone` 后继续写就行。

---

动手试试吧！如果你配置过程中卡在哪一步，欢迎在评论区留言，我会逐一回复。也欢迎在 GitHub 上 Star 我的项目仓库，后续会更新更多主题定制技巧。如果你觉得这篇教程有用，可以分享给正在搭建博客的朋友，一起用写作沉淀技术。

相关推荐：

https://github.com/rhodesandrea462/zjvmux/blob/main/2026%E5%AE%98%E6%96%B9%E7%88%86%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%A8%B1%E4%B9%90%E7%BD%91%E5%9D%80_%E7%9A%87%E5%BB%96%E8%A3%99%E6%B1%B2%E8%AF%9CBIUCQ.md

<img src="https://i.postimg.cc/XNH0VrMC/lefu-00016.png" />

相关推荐：

https://github.com/rhodesandrea462/zjvmux/commit/eb93aab2b8019ed9bcd9df1b44d45f7630e40fc5

<img src="https://i.postimg.cc/9McjfTF9/lefu-00009.png" />
相关推荐：

https://github.com/martinezkelly827/fwhecg/blob/main/2026%E5%AE%98%E7%BD%91%E8%AE%B2%E8%A7%A3%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%A8%B1%E4%B9%90%E5%BC%80%E6%88%B7_%E5%AD%95%E6%95%99%E8%B4%AB%E6%A1%88%E8%B0%92TOCJD.md

<img src="https://i.postimg.cc/YSKHJZ5P/lefu-00006.png" />
相关推荐：

https://github.com/martinezkelly827/fwhecg/commit/b23614420e3f704c88bf52621d7671170c5b3c31

<img src="https://i.postimg.cc/c4vG6dZ5/lefu-00018.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
