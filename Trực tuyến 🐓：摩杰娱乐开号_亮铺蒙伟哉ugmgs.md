摩杰娱乐开号【Q-——333307——】摩杰娱乐开号【 辋芷《888yx●vip》 】
摩杰娱乐开号【Q-——333307——】摩杰娱乐开号【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

> 想拥有一个完全属于自己的技术博客？不需要买服务器，不需要备案，GitHub Pages 免费托管，配合 Hexo 静态生成器，30分钟就能上线。本文手把手带你走通全流程。

 为什么选择 GitHub Pages + Hexo？

- 零成本：域名、托管、CDN 全部免费（个人使用）
- 高度自定义：主题自由更换，支持 Markdown 写作
- SEO 友好：纯静态页面，加载速度快，搜索引擎收录快
- 版本管理：文章即代码，Git 天然备份，不怕丢

如果你正在写技术笔记、面试经验或项目复盘，这套方案几乎是首选。

 第一步：准备环境（Windows/Mac 通用）

1. 安装 Node.js（LTS版即可）和 Git
2. 注册 GitHub 账号（已有请跳过）
3. 创建仓库：命名为 `你的用户名.github.io`（必须完全一致）

 第二步：本地搭建 Hexo 项目

```bash
npm install -g hexo-cli
hexo init blog
cd blog
npm install
hexo s   本地预览 http://localhost:4000
```

看到默认页面，说明本地环境就绪。此时你会看到 `source/_posts` 文件夹，里面有一个 `hello-world.md`，这就是你的第一篇文章。

 第三步：部署到 GitHub Pages

1. 在 `_config.yml` 中修改 `url` 和 `deploy` 配置：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

2. 安装部署插件并推送：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo g && hexo d
```

等待1分钟，访问 `https://你的用户名.github.io`，你的博客已经上线。

 第四步：SEO 优化与收录加速

- 安装 sitemap 插件：`npm install hexo-generator-sitemap --save`，让搜索引擎更快发现你的文章
- 提交百度站长平台：在百度搜索资源平台添加站点，并验证所有权（推荐 CNAME 验证）
- 文章内链：每篇文章至少添加2个站内相关链接，提升爬虫抓取深度
- 设置永久链接：`_config.yml` 中设置 `permalink: :year/:month/:title/`，避免动态参数

 互动引导：你的博客，从第一篇开始

现在轮到你了。准备好第一篇技术文章了吗？建议从“踩坑记录”或“项目复盘”开始，这类内容既容易写，也容易获得共鸣。

如果这篇文章对你有帮助：
- 点赞收藏，方便下次直接查看
- 在评论区告诉我你的 GitHub 用户名，我会去你的新博客留言支持
- 有任何报错，直接贴出错误截图，我看到就会回复

---
本文同步发布于个人博客，追求长期 SEO 收录价值。欢迎转载，请保留作者链接。

相关推荐：

https://github.com/hilltimothy3744/xgiwkr/blob/main/Tr%E1%BB%B1c%20tuy%E1%BA%BFn%20%F0%9F%90%93%EF%BC%9A%E6%91%A9%E8%87%A3%E5%9C%B0%E5%9D%80%E5%A8%B1%E4%B9%90_%E7%82%BC%E5%88%91%E8%B2%8C%E5%92%86%E8%B5%90qccvp.md

<img src="https://i.postimg.cc/yxwhxJbK/mojie-00015.png" />

相关推荐：

https://github.com/hilltimothy3744/xgiwkr/commit/fb6ddbc61e4b80047b5ac444ac76577fa80c65ce

<img src="https://i.postimg.cc/W3YwRYmV/mojie-00001.png" />
相关推荐：

https://github.com/crawfordjonathan31/tksmst/blob/main/Tr%E1%BB%B1c%20tuy%E1%BA%BFn%20%F0%9F%90%93%EF%BC%9A%E6%91%A9%E8%87%A3%E5%9C%B0%E5%9D%80%E5%B9%B3%E5%8F%B0_%E5%8F%B3%E6%A3%BA%E6%9E%84%E6%98%A0%E5%95%AApuuha.md

<img src="https://i.postimg.cc/fy3jM75B/mojie-00010.png" />
相关推荐：

https://github.com/crawfordjonathan31/tksmst/commit/e9d5b51fd0f15b031e4c8c17c6cb0c15cdd40b3f

<img src="https://i.postimg.cc/yxJX7hn7/mojie-00004.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
