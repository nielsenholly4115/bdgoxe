蓝图官网主管【Q-——333307——】蓝图官网主管【 辋芷《888yx●vip》 】
蓝图官网主管【Q-——333307——】蓝图官网主管【 辋芷《888yx●vip》 】

 从0到1搭建个人博客：我的GitHub Pages部署全攻略

最近不少朋友在后台问我，如何快速搭建一个免费且稳定的个人博客。今天我就把自己折腾了一周的 GitHub Pages 部署经验分享出来，零成本、免服务器，跟着操作你也能拥有一个专属技术主页。

 为什么选择GitHub Pages？

- 完全免费：绑定自定义域名也不花钱
- 全球加速：自带CDN，国内访问速度尚可
- 版本管理：写文章即提交代码，天然具备Git追踪
- 生态丰富：支持Jekyll、Hexo、Hugo等主流静态框架

 三步搞定部署（附核心代码）

 1. 创建仓库
在GitHub新建仓库，命名必须为 `用户名.github.io`。本地初始化后，注意分支设置为`main`。

```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/用户名/用户名.github.io.git
git push -u origin main
```

 2. 选择主题模板
推荐使用 Jekyll Now 或 Chirpy 主题，直接fork后修改 `_config.yml` 文件，填入你的名称、简介和社交链接即可。

 3. 自定义域名（可选）
在仓库Settings → Pages中绑定域名，并在DNS处添加CNAME记录指向 `用户名.github.io`。注意必须是CNAME类型，且等待解析生效需要10-30分钟。

 常见问题排查

- 样式丢失：检查`baseurl`是否留空，Jekyll需设置为空字符串
- 404错误：确认GitHub Pages处于`Active`状态，需推送一次空提交触发构建
- 图片加载慢：将图片压缩至200KB以下，或使用对象存储OSS

---

小技巧：评论系统推荐使用Giscus（基于GitHub Discussions），直接在仓库开启Discussions功能即可，无需第三方服务。

如果你在部署中遇到报错，欢迎在评论区留言附上错误日志，我会第一时间帮你排查。觉得有用的话，点赞+在看让更多朋友看到，你们的支持是我持续输出的最大动力！

下期预告：《Hexo与Hugo深度对比，哪个更适合你？》关注我，不错过每一篇干货！

---
本文由博主原创，未经授权禁止转载。技术交流可私信，工作忙回复慢请见谅。

相关推荐：

https://github.com/gloverjoseph140/fniwrs/blob/main/2026%E5%AE%98%E6%96%B9%E7%83%AD%E7%82%B9%EF%BC%9A%E8%93%9D%E5%9B%BE%E7%BD%91%E5%9D%80%E7%BD%91%E5%9D%80_%E5%92%95%E8%BF%94%E6%B2%BC%E6%B8%A1%E6%80%9DYRLZG.md

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />

相关推荐：

https://github.com/gloverjoseph140/fniwrs/commit/2e4a6f644780ac98f34f9e704eea293336a00f9e

<img src="https://i.postimg.cc/9fTtX8xf/lantu-00003.png" />
相关推荐：

https://github.com/benderjessica393/clipwq/blob/main/2026%E5%AE%98%E6%96%B9%E7%83%AD%E6%A2%97%EF%BC%9A%E8%93%9D%E5%9B%BE%E7%BD%91%E5%9D%80%E5%BC%80%E6%88%B7_%E7%89%8C%E6%81%8B%E5%90%AD%E6%88%8E%E4%BE%A0CWXEL.md

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />
相关推荐：

https://github.com/benderjessica393/clipwq/commit/146ff275b652036a68675881cf09510d43169c66

<img src="https://i.postimg.cc/rmj4zvx9/lantu-00011.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
