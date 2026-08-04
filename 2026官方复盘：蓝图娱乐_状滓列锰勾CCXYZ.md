蓝图娱乐【Q-——333307——】蓝图娱乐【 辋芷《888yx●vip》 】
蓝图娱乐【Q-——333307——】蓝图娱乐【 辋芷《888yx●vip》 】

 用 GitHub Actions 自动部署静态博客，我后悔没早点知道

 关键词布局（适合百度搜索）

GitHub Actions、自动部署、静态博客、Hexo、Hugo、VuePress、CI/CD、GitHub Pages、博客自动化、持续集成、免费部署、GitHub Workflow。

 什么是 GitHub Actions？

很多人把博客搭建在 GitHub Pages 上，但每次写文章都要手动执行 `hexo g` 再 `git push`，重复又容易出错。GitHub Actions 是 GitHub 官方提供的自动化流程工具，能帮你省掉这些步骤。

只要你把代码推送到仓库，它会自动完成构建、部署，整个过程不需要你打开命令行。

 它能帮你做什么？

我举个最简单例子：你写了一篇新文章，`git push` 之后，GitHub Actions 会自动执行这些流程：

1. 拉取最新代码
2. 安装依赖（比如 npm install）
3. 执行构建命令（比如 hexo generate）
4. 把生成的静态文件推送到 gh-pages 分支

全自动，不需要你手动操作。

 最推荐的部署方案

如果你用的是 Hexo，可以直接在你的仓库里新建一个 `.github/workflows/deploy.yml` 文件，内容大概长这样：

```yaml
name: 自动部署博客

on:
  push:
    branches: [ main ]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: actions/setup-node@v3
        with:
          node-version: 18
      - run: npm install
      - run: npm run build
      - uses: peaceiris/actions-gh-pages@v3
        with:
          github_token: ${{ secrets.GITHUB_TOKEN }}
          publish_dir: ./public
```

这套配置适用于大部分静态博客生成器，Hugo 和 VuePress 也只需要改一下构建命令。

 部署失败怎么办？

很多朋友第一次配置会遇到 404 或者页面不更新。这通常是因为你忘记开启 GitHub Pages 的部署来源。

你需要进入仓库的 Settings → Pages，把部署分支选择为 `gh-pages`，保存之后等一两分钟就能访问了。

如果你用的是自己的服务器，也可以用 SSH 方式部署，逻辑一样，只是上传目标从 GitHub Pages 换成了你的 VPS 而已。

 适配度与外链建议

这篇文章适配：
- 想要搭建个人博客的新手
- 正在用静态博客但嫌手动部署麻烦的开发者
- 对 CI/CD 感兴趣但不敢上手的人

建议收藏起来，下次配流程的时候照着抄一遍就能用。

 最后说一句

GitHub Actions 完全免费（公共仓库），还能免去你每月买部署面板的钱。用起来之后，你会发现写博客的欲望都变高了——因为那一步重复劳动，真的太劝退了。

你目前用的是哪款博客框架？Hexo、Hugo 还是 VuePress？如果你有部署上的疑惑，可以直接把报错截图发在评论区，我看到就回复你。

相关推荐：

https://github.com/rhodesandrea462/zjvmux/blob/main/2026%E7%A7%91%E6%8A%80%E6%B1%87%E6%80%BB%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%9C%B0%E5%9D%80%E5%A8%B1%E4%B9%90_%E7%B2%97%E8%87%83%E8%B4%A4%E6%A3%A0%E6%88%91MFZMU.md

<img src="https://i.postimg.cc/ZnqdNVLn/lantu-00012.png" />

相关推荐：

https://github.com/rhodesandrea462/zjvmux/commit/1cb44464ca587a9e3886808f495a252129c3b391

<img src="https://i.postimg.cc/T2Zb1qDM/lantu-00015.png" />
相关推荐：

https://github.com/vazquezdarin376/rowkxj/blob/main/2026%E7%AC%AC%E4%B8%80%E7%83%AD%E7%82%B9%EF%BC%9A%E4%B9%90%E5%AF%8C%E5%BC%80%E6%88%B7app_%E9%BC%BB%E8%B0%86%E5%8D%A6%E5%8A%AB%E5%AF%BAZGBIJ.md

<img src="https://i.postimg.cc/FsWxTJds/lantu-00002.png" />
相关推荐：

https://github.com/vazquezdarin376/rowkxj/commit/e1b62962d043f58aa90dc7d54e59d261af73c33e

<img src="https://i.postimg.cc/ZnqdNVLn/lantu-00012.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
