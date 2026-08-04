蓝图地址主管【Q-——333307——】蓝图地址主管【 辋芷《888yx●vip》 】
蓝图地址主管【Q-——333307——】蓝图地址主管【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

你是否想过拥有一个完全免费、无广告、可自定义的个人技术博客？今天教你用 GitHub Pages + Hexo 十分钟搞定，零基础也能上手。本文已按SEO优化，建议收藏转发。

 为什么选择 GitHub Pages + Hexo？
- 免费托管：GitHub Pages 提供无限流量静态托管，无需服务器费用。
- 极速访问：静态页面加载快，国内可用 CDN 加速。
- 生态丰富：Hexo 有数千款主题和插件，满足个性化需求。
- 版本管理：文章 Markdown 格式，天然适配 Git 工作流。

 第一步：环境准备（3分钟）
1. 安装 Node.js（v18+）：官网下载 LTS 版本，一路默认安装。
2. 注册 GitHub 账号：已有账号可跳过，记得开启 SSH 密钥认证。
3. 安装 Git：Windows 用户建议安装 Git Bash。

 第二步：搭建 Hexo 博客（5分钟）
```bash
npm install -g hexo-cli    全局安装
hexo init my-blog           初始化项目
cd my-blog && npm install   安装依赖
hexo s                      本地预览（http://localhost:4000）
```
看到默认页面即成功！此时可打开 `_config.yml` 修改站点标题、描述、关键词。

 第三步：部署到 GitHub Pages（2分钟）
1. 在 GitHub 新建仓库，命名为 `你的用户名.github.io`。
2. 安装部署插件：
```bash
npm install hexo-deployer-git --save
```
3. 修改 `_config.yml` 中 deploy 配置：
```yaml
deploy:
  type: git
  repo: git@github.com:你的用户名/你的用户名.github.io.git
  branch: main
```
4. 执行 `hexo clean && hexo g && hexo d`，浏览器访问 `https://你的用户名.github.io`，大功告成！

 进阶优化：让博客更专业
- SEO 优化：安装 `hexo-generator-seo-friendly-sitemap` 生成站点地图，提交到 Google Search Console。
- 访问加速：将静态资源迁移到 CDN（如 jsDelivr）。
- 评论系统：集成 Giscus（基于 GitHub Discussions）或 Waline（支持微信通知）。
- 文章规范：每篇文章设置 `tags` 和 `categories`，利于收录。

 常见问题排查
- 部署失败：检查仓库名是否准确，SSH 密钥是否配置。
- 样式丢失：清除浏览器缓存，或执行 `hexo clean` 后重新生成。
- 版本冲突：Node.js 版本过高时，可自行编译源码（详见文档）。

 邀请你互动
动手试过的小伙伴，欢迎在评论区分享你的博客地址，我会从新独立博客中随机抽取 3 位，送出《技术写作指南》PDF！如果遇到任何问题，点赞 + 收藏本文，私信必回。

持续更新：关注我，后续会拆解自定义主题开发、多端适配等进阶技巧。你的支持是我创作的最大动力！

---

本文关键词：GitHub Pages、Hexo教程、静态博客搭建、个人网站搭建、免费博客平台、SEO优化、博客部署教程、Hexo主题配置、GitHub Actions自动化部署、程序员建站

相关推荐：

https://github.com/brownbarbara40/yzuprm/blob/main/2026%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%A8%B1%E4%B9%90%E7%BD%91%E5%9D%80_%E5%92%8F%E5%82%BA%E7%BA%B1%E5%9E%82%E4%BF%A3KRELU.md

<img src="https://i.postimg.cc/6QsnPV9w/lantu-00010.png" />

相关推荐：

https://github.com/brownbarbara40/yzuprm/commit/70afb6d7a496294e60376604533d2ced9476cb16

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />
相关推荐：

https://github.com/nielsenholly4115/bdgoxe/blob/main/2026%E5%AE%98%E6%96%B9%E7%83%AD%E6%A2%97%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%A8%B1%E4%B9%90%E7%99%BB%E5%BD%95_%E5%A6%93%E5%8F%AF%E9%A1%BF%E6%B3%BB%E5%BD%B1EYZTA.md

<img src="https://i.postimg.cc/6QsnPV9w/lantu-00010.png" />
相关推荐：

https://github.com/nielsenholly4115/bdgoxe/commit/a731b907b2803b0d1bf136085e0018cc90c2c256

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
