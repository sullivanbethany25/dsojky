摩臣5网址主管【Q-——333307——】摩臣5网址主管【 辋芷《888yx●vip》 】
摩臣5网址主管【Q-——333307——】摩臣5网址主管【 辋芷《888yx●vip》 】

 从零搭建个人博客：GitHub Pages + Hexo 完整指南（2025最新版）

> 还在羡慕别人炫酷的技术博客？花30分钟跟着教程走一遍，你也能拥有完全属于自己的独立博客，免费、稳定、还能自定义域名。

你是否遇到过这些痛点：CSDN广告太多？掘金审核严格？语雀无法被搜索引擎收录？使用GitHub Pages搭建博客，完美解决以上所有问题。

 为什么选择GitHub Pages + Hexo？

| 特性 | 传统平台 | GitHub Pages |
|------|---------|--------------|
| 成本 | 会员/广告 | 完全免费 |
| SEO | 平台受限 | 百度/谷歌秒收录 |
| 自由度 | 模板固定 | 高度自定义 |
| 数据 | 平台掌控 | 完全属于你 |

 第一步：环境准备

需要准备：GitHub账号（没有的去注册一个）、Git（版本控制工具）、Node.js（运行环境）。

> 小提示：建议Node.js安装LTS稳定版本，避免后续出现兼容性问题。

 第二步：安装Hexo框架

Hexo是一个快速、简洁且高效的博客框架，支持Markdown语法，让你专注于写作而非抠代码。

```bash
 全局安装hexo
npm install -g hexo-cli

 初始化博客项目
hexo init my-blog
cd my-blog
npm install

 本地预览
hexo s
```

浏览器访问`localhost:4000`，看到默认页面就代表安装成功。

 第三步：部署到GitHub

1. 新建仓库，命名为`用户名.github.io`（必须完全一致）
2. 修改根目录`_config.yml`配置文件：

```yaml
deploy:
  type: git
  repo: https://github.com/用户名/用户名.github.io.git
  branch: main
```

3. 上传代码：

```bash
npm install hexo-deployer-git --save
hexo clean && hexo generate && hexo deploy
```

浏览器访问`用户名.github.io`，你的博客已经全球可访问了。

 第四步：让百度收录你的博客

百度搜索引擎不收录GitHub Pages？那是老黄历了。现在只需三步：

1. 去[百度站长平台](https://ziyuan.baidu.com/)添加站点
2. 验证网站所有权（推荐CNAME方式）
3. 提交sitemap.xml链接

> 已实测有效：新站点通常3-7天内即可被百度收录。

 进阶技巧：自定义域名

想用自己花钱买的域名？在仓库Settings→Pages中绑定域名，然后在域名服务商处添加CNAME解析到`用户名.github.io`即可。记得在source文件夹新建CNAME文件，内容填你的域名，不然重新部署后绑定会失效。

---

评论区留下你的博客链接，互访互关，共同成长。有搭建问题也可以直接留言，看到都会回复。

如果这篇文章帮到你，点赞+收藏，让更多小伙伴看到。关注我，持续分享更多实用技术干货。

相关推荐：

https://github.com/gardnertommy78/iilnjs/blob/main/Th%E1%BB%83%20thao%20%E2%9A%BD%EF%B8%8F%EF%BC%9A%E6%91%A9%E8%87%A35%E5%B9%B3%E5%8F%B0%E5%A8%B1%E4%B9%90_%E6%95%B2%E6%B7%B9%E6%A6%B7%E7%AC%86%E6%82%A6sylls.md

<img src="https://i.postimg.cc/WzXLPvWt/mochen5-00013.png" />

相关推荐：

https://github.com/gardnertommy78/iilnjs/commit/a907fc9d7f894cdf44b7c2ca4c791ddab5f25798

<img src="https://i.postimg.cc/4yBkTgLf/mochen5-00012.png" />
相关推荐：

https://github.com/freemanmaria8/acffij/blob/main/Tr%E1%BB%B1c%20tuy%E1%BA%BFn%20%F0%9F%90%93%EF%BC%9A%E6%91%A9%E8%87%A35%E5%A8%B1%E4%B9%90%E5%BC%80%E5%8F%B7_%E5%A2%83%E7%A7%A4%E8%BF%AA%E8%B0%8C%E6%8A%A0yypiv.md

<img src="https://i.postimg.cc/rm2L1gRs/mochen5-00004.png" />
相关推荐：

https://github.com/freemanmaria8/acffij/commit/54e81bd98d17c5e651d1566ab909a3435cbc3494

<img src="https://i.postimg.cc/4yBkTgLf/mochen5-00012.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
