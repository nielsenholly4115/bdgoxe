蓝图主管地址【Q-——333307——】蓝图主管地址【 辋芷《888yx●vip》 】
蓝图主管地址【Q-——333307——】蓝图主管地址【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

> 想拥有一个完全免费、可自定义、无广告的个人博客？本篇教程手把手带你用 GitHub Pages 和 Hexo 搭建属于自己的技术博客站点，零基础也能轻松上手。

---

 一、为什么选择 GitHub Pages 搭建博客？

对于开发者而言，GitHub Pages 是最稳定的静态博客托管方案。相比购买云服务器，它有三大核心优势：

- 完全免费：绑定自定义域名也不收取任何费用
- 全球加速：依托 GitHub CDN 节点，国内访问速度也在持续优化
- 版本管理：所有文章天然纳入 Git 版本控制，历史记录永不丢失

搭配 Hexo 框架，无需掌握复杂的后端语言，仅需几个命令即可生成高颜值、SEO友好的静态页面。这组方案目前已成为个人技术博客的首选。

---

 二、搭建前的准备工作

在开始前，请确保你已完成以下基础配置：

1. 注册 [GitHub](https://github.com) 账号并创建空仓库，仓库名格式必须为 `你的用户名.github.io`
2. 本地安装 Git 和 Node.js（建议 LTS 版本，v16+ 均可）
3. 准备一个趁手的代码编辑器（推荐 VSCode）

> 小提示：国内用户建议同时配置 npm 淘宝镜像源，避免依赖下载超时：
> `npm config set registry https://registry.npmmirror.com`

---

 三、Hexo 博客搭建五部曲

 第一步：全局安装 Hexo 脚手架

打开终端，执行以下命令：

```bash
npm install -g hexo-cli
```

 第二步：初始化博客项目

```bash
hexo init my-blog
cd my-blog
npm install
```

 第三步：本地预览效果

```bash
hexo server
```

浏览器访问 `http://localhost:4000`，此时你已拥有可运行的本地博客。

 第四步：部署到 GitHub Pages

修改根目录下的 `_config.yml` 配置文件，在 `deploy` 节点添加：

```yaml
deploy:
  type: git
  repo: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

然后依次执行部署命令：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate && hexo deploy
```

恭喜！ 访问 `https://你的用户名.github.io` 即可看到你的线上博客。

 第五步：发布文章与主题美化

在 `source/_posts` 目录下新建 Markdown 文件，开头写入 YAML front-matter：

```yaml
---
title: 我的第一篇博客
date: 2025-01-01 10:00:00
tags: [Hexo, 教程]
categories: 技术分享
---
```

若想更换博客外观，在 [Hexo 主题商店](https://hexo.io/themes/) 挑选一款热门主题，克隆到 `themes` 目录，并将 `_config.yml` 中的 `theme` 字段替换为主题名称。

---

 四、常见问题排查（FAQ）

Q1：`hexo deploy` 报错认证失败？
A：GitHub 已取消密码推送，需改用 [Personal Access Token](https://github.com/settings/tokens)。生成时勾选 `repo` 权限，并以 token 作为密码填写。

Q2：文章更新后网页不变化？
A：多数为缓存问题。先执行 `hexo clean` 再重新生成部署。

Q3：想绑定自己的域名？
A：在仓库设置 `Custom domain` 处填写域名，并在 DNS 服务商添加一条 CNAME 记录指向 `你的用户名.github.io`。

---

 五、进阶优化提升收录

为提高内容在百度、Google 的收录率，务必配置 SEO：

1. 安装插件：`npm install hexo-generator-sitemap --save`
2. 提交站点地图：在百度站长平台提交 `你的域名/sitemap.xml`
3. 使用 [百度自动推送脚本](https://ziyuan.baidu.com/college/courseinfo?id=1622&page=2)，在主题模板 `head.ejs` 中插入 JS 代码

---

 写在最后

搭建个人博客只是第一步，持续输出高质量技术文章才是核心。建议你在博客首页展示 GitHub 热门开源项目链接，并在每篇文章底部加上参与讨论的 GitHub Issues 链接，增强读者互动。

如果你在搭建过程中遇到报错或疑惑，欢迎在下方评论区留言，我看到后会第一时间回复。也可以关注本博客右侧的公众号，获取每期教程的 PDF 版本。

---

本文首发于 [你的博客名]（你的博客链接），转载请注明出处，感谢支持！

相关推荐：

https://github.com/martinezkelly827/fwhecg/blob/main/2026%E6%9D%83%E5%A8%81%E7%88%86%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E6%B3%A8%E5%86%8C%E4%BB%A3%E7%90%86_%E7%9F%AB%E4%BC%BC%E7%A9%B6%E5%B8%9C%E6%A3%95PJXLG.md

<img src="https://i.postimg.cc/sfKP2ZJh/lantu-00007.png" />

相关推荐：

https://github.com/martinezjessica6229/eyvqwl/blob/main/2026%E5%AE%98%E7%BD%91%E7%A7%91%E6%99%AE%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E6%96%B9%E5%AE%98%E6%96%B9_%E6%B2%B8%E5%83%AD%E5%8E%A6%E9%9F%B5%E5%B9%B3EFAHC.md

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/blob/main/2026%E6%9D%83%E5%A8%81%E8%AE%B2%E8%A7%A3%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%AE%98%E6%96%B9%E5%A8%B1%E4%B9%90_%E5%BB%B6%E8%A1%97%E6%B0%90%E5%97%BD%E8%B7%8BSTGNB.md

<img src="https://i.postimg.cc/T2Zb1qDM/lantu-00015.png" />
相关推荐：

https://github.com/jarvisdanielle312/mphvpi/commit/a333546f2f9b55649d20145cb55a5a2d6d6a9f5a

<img src="https://i.postimg.cc/sfKP2ZJh/lantu-00007.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
