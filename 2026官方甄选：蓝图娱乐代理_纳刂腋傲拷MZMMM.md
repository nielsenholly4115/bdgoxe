蓝图娱乐代理【Q-——333307——】蓝图娱乐代理【 辋芷《888yx●vip》 】
蓝图娱乐代理【Q-——333307——】蓝图娱乐代理【 辋芷《888yx●vip》 】

 从零搭建个人博客：用Github Pages免费部署的完整指南

对于开发者而言，拥有一块属于自己的技术自留地，不仅能沉淀知识，更是打造个人品牌的关键一步。提到搭建博客，很多人第一反应是买服务器、备案、装WordPress，流程繁琐且成本不低。

其实，借助 Github Pages，你完全可以通过免费且高效的方式，搭建出一个极速访问的静态博客。本文将手把手带你完成从仓库创建到域名访问的全流程，建议收藏！

 第一步：创建GitHub仓库（Repository）

首先，你需要一个GitHub账号。登录后，点击右上角的“+”号，选择“New repository”。

关键点：仓库名的格式必须是 `你的用户名.github.io`。例如你的用户名是 `john`，仓库名就应该是 `john.github.io`。这是GitHub识别个人站点主页的硬性规则，搞错了无法上线。

 第二步：选择站点生成框架（Hugo / Hexo / Jekyll）

Github Pages原生支持 Jekyll，但你往往希望有更多主题和更快的编译速度。目前社区最流行的是 Hugo 或 Hexo。

- Hugo：基于Go语言，编译速度极快，适合文章量大的站点。
- Hexo：基于Node.js，插件丰富，适合喜欢折腾JavaScript的开发者。

无论选择哪个，核心逻辑都是：在本地生成静态HTML文件，然后推送到Github仓库的特定分支（通常是`main`或`gh-pages`）。

 第三步：部署与发布（以Hugo为例）

1. 在本地安装Hugo并创建站点：`hugo new site myblog`
2. 选择一个你喜欢的主题，配置好`config.toml`。
3. 写好文章后，执行 `hugo` 命令生成`public`目录。
4. 将该目录下的所有文件，通过`git push`推送到远端仓库。

小技巧：建议在你的仓库Settings -> Pages选项中，将Source设置为 `Deploy from a branch`，并选择`main`分支的根目录。

 第四步：绑定自定义域名（加分项）

如果你觉得 `xxx.github.io` 不够专业，可以在域名服务商处买一个域名，然后在仓库的Settings -> Pages中填写你的域名，并在DNS解析处添加一条CNAME记录指向 `你的用户名.github.io`。

---

互动引导
你在搭建过程中是否遇到了图片加载慢或评论系统无法显示的问题？欢迎在评论区留言你的具体报错信息，我看到后会第一时间帮你排查。

顺手点个“在看”，让更多朋友学会这项技能，我们下期见！

相关推荐：

https://github.com/singhcourtney93/oormzh/blob/main/2026%E5%AE%98%E7%BD%91%E7%83%AD%E6%A6%9C%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%AE%98%E7%BD%91%E5%AE%A2%E6%9C%8D_%E5%AE%98%E8%8F%B2%E7%9D%AC%E5%BE%8A%E8%AF%B1VVVVI.md

<img src="https://i.postimg.cc/mkZQwbTF/lantu-00005.png" />

相关推荐：

https://github.com/singhcourtney93/oormzh/commit/48645707b8ececb663811a0dfa0d7f54e47aae5f

<img src="https://i.postimg.cc/zXVhX2BP/lantu-00013.png" />
相关推荐：

https://github.com/bakerangela2326/pvryuo/blob/main/%E8%B6%85%E5%85%A8%E5%AE%9E%E6%93%8D%E6%8C%87%E5%8D%97%EF%BC%9A%E8%93%9D%E5%9B%BE%E5%AE%98%E7%BD%91%E7%BD%91%E5%9D%80_%E5%B2%97%E5%92%8F%E8%AF%9A%E7%90%B6%E8%80%99BBPHP.md

<img src="https://i.postimg.cc/6QsnPV9w/lantu-00010.png" />
相关推荐：

https://github.com/bakerangela2326/pvryuo/commit/0a081081e6fafc87e12eae5ae89caa616ab69d8d

<img src="https://i.postimg.cc/rsg9XDf0/lantu-00001.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
