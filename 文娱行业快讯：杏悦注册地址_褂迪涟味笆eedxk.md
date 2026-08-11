杏悦注册地址【Q-——333307——】杏悦注册地址【 辋芷《888yx●vip》 】
杏悦注册地址【Q-——333307——】杏悦注册地址【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整教程（2025最新版）

> 你是否也想拥有一个完全属于自己的技术博客，却苦于服务器成本高、搭建流程复杂？本文将手把手教你利用 GitHub Pages 免费部署 Hexo 博客，零成本、高自定义，还能顺便提升你的 Git 实战能力。

 为什么选择 GitHub Pages + Hexo？

GitHub Pages 提供免费的静态网站托管服务，支持自定义域名和 HTTPS，而 Hexo 作为一款基于 Node.js 的高效静态博客框架，拥有丰富的主题生态和极快的生成速度。两者结合，你可以在10分钟内拥有一个加载速度快、稳定性强的个人博客，非常适合技术写作者和开源爱好者。

 第一步：环境准备（3分钟）

在开始之前，请确保你的电脑已安装：
- Node.js（建议 v18 以上版本）
- Git（最新版即可）

安装完成后，打开终端验证：

```bash
node -v   检查 Node.js
git --version   检查 Git
```

 第二步：安装并初始化 Hexo（5分钟）

全局安装 Hexo 命令行工具：

```bash
npm install -g hexo-cli
```

接着，在你的工作目录初始化博客项目：

```bash
hexo init my-blog
cd my-blog
npm install
```

启动本地预览，访问 `http://localhost:4000` 即可看到默认博客页面：

```bash
hexo server
```

 第三步：关联 GitHub 仓库（2分钟）

1. 在 GitHub 上新建一个仓库，命名为 `你的用户名.github.io`（必须完全匹配）。
2. 修改博客根目录下的 `_config.yml` 文件，在 `deploy` 部分填入你的仓库信息：

```yaml
deploy:
  type: git
  repository: https://github.com/你的用户名/你的用户名.github.io.git
  branch: main
```

3. 安装自动部署插件：

```bash
npm install hexo-deployer-git --save
```

 第四步：一键部署上线

执行以下命令，Hexo 会自动生成静态文件并推送到 GitHub：

```bash
hexo clean && hexo generate && hexo deploy
```

等待一分钟，访问 `https://你的用户名.github.io`，你的博客就正式上线啦！

 进阶优化建议

- 绑定自定义域名：在仓库设置 `Custom domain` 中填入你的域名，并在 DNS 解析中添加 CNAME 记录。
- 更换主题：Hexo 主题库有数百款主题，推荐使用 `hexo-theme-next` 或 `hexo-theme-fluid`，安装后只需修改 `_config.yml` 中的 `theme` 字段。
- 添加评论系统：集成 Gitalk 或 Valine，让读者可以互动留言。

遇到问题怎么办？ 欢迎在评论区留言，或加入 Hexo 官方社区交流。如果你觉得这篇文章对你有帮助，请点赞、收藏并分享给更多需要的朋友，你的支持是我持续输出的最大动力！

相关推荐：

https://github.com/wilsonshelby53/jcsmgv/blob/main/2027%E5%AE%98%E6%96%B9%E7%83%AD%E6%A2%97%EF%BC%9A%E6%9D%8F%E6%82%A6%E5%AE%98%E6%96%B9%E4%B8%BB%E7%AE%A1_%E6%AF%93%E8%8B%9B%E8%A3%82%E7%A3%81%E6%8E%96jdqwj.md

<img src="https://i.postimg.cc/NFkp8Pth/xingyue-00007.png" />

相关推荐：

https://github.com/wilsonshelby53/jcsmgv/commit/15cca787475ab4673749c920648436cad76317fb

<img src="https://i.postimg.cc/fyN89Q6B/xingyue-00005.png" />
相关推荐：

https://github.com/murphyjenny8631/xhkrxl/blob/main/2027%E5%AE%98%E6%96%B9%E6%94%BB%E7%95%A5%EF%BC%9A%E6%9D%8F%E6%82%A6%E5%AE%98%E6%96%B9%E7%99%BB%E5%BD%95_%E7%9F%A9%E7%A5%B7%E4%B9%93%E8%93%9F%E5%94%BEvcxke.md

<img src="https://i.postimg.cc/RVGgN8GK/xingyue-00014.png" />
相关推荐：

https://github.com/murphyjenny8631/xhkrxl/commit/db21aeb4bb3e3f810c595815c90b2c38f43d864d

<img src="https://i.postimg.cc/m2TdZR31/xingyue-00013.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
