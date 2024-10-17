# 自己一一实现并放在自己的博客上
## 导读
**（1）不要自己管理服务器。** 服务器管理是一个非常繁琐的专门工种，如果不是专业的运维工程师，很难做好。退一步说，即使你拥有这方面的专业知识，也不值得把大量时间和精力投入在自己的博客服务器上。网络世界是一个黑暗森林，到处都有人向你打冷枪，防不胜防，解决方法就下一条。

**（2）使用专业的云服务商。** 现在大部分云服务器商，都有静态网站托管服务，把静态网页托管在它们那里，省时省心。如果你需要后端动态生成内容，那就使用云函数（叫做 FaaS），通过服务商提供的边缘计算、而不是你的主机自带的 CPU 算力。

**（3）使用专业的云服务商。** 你应该开始写博客，如果不知道写什么，就写你学到的东西，以及写下你创造或建立的东西。-- [《博客写什么》](https://simonwillison.net/2022/Nov/6/what-to-blog-about/)
[TIL](https://github.com/jbranchaud/til)（今天我学到的）

![](https://cdn.beekka.com/blogimg/asset/202311/bg2023110704.webp)

一个开源笔记库。大家可以学习他做笔记的方式，内容按主题分类，放在 GitHub 上面。


**（4）我喜欢的技术博客，都有一些共同特征。** 

- （1）解决困难，或者帮助读者理解一些令人困惑的话题。

- （2）带有清晰可理解的代码或例子。

- （3）让事情变得更简单。

- （4）定期写作。

- （5）不回避所介绍的技术的代价和缺点。

- （6）不使用网络俚语、咒骂、讽刺和咆哮。

**(5) 2021年只有两种人在写blog.**一种是试图建立受众并从中获利的人，另一种是只想写出想法、而没有任何目标的人。

这两种人的行为都非常好。选择做你喜欢的事，坚持下去，它们最终都可以对他人产生价值。

## TODO list

1. [gridea](https://github.com/getgridea/gridea)：静态博客写作客户端，你可以用它来记录你的生活、心情、知识、笔记、创意。使用了 electron 技术，对于学习 Javascript 桌面端开发是一个很好的项目

2. [halo](https://github.com/halo-dev/halo)：Java 博客系统。在层出不穷的博客系统中，很难看到使用 Java 编写的简洁优雅的博客系统。该项目还具备着轻快且功能强大的特点，这些特性使它从众多 Java 博客系统脱颖而出。安装命令：
```
# 安装 Halo
$ yum install -y wget && wget -O halo-cli.sh https://git.io/fxHqp && bash halo-cli.sh -i
# 更新 Halo
$ bash halo-cli.sh -u
```
搞一台服务器，直接命令行一运行，就行了。改改代码

3. [jekyll](https://github.com/jekyll/jekyll)：强大的静态博客网站生成工具。无需数据库，可以通过 Markdown 和 Config 轻松生成一个静态博客。该项目十分成熟、社区活跃、拥有多种主题可供选择。最后可以通过 [GitHub Page](https://pages.github.com/) 把生成的博客免费部署上线。快速开始：
```
1. 安装 jekll：gem install bundler jekyll
2. 创建项目：jekyll new my-awesome-site
3. 进入新创建的项目：cd my-awesome-site
4. 本地运行：bundle exec jekyll serve
5. 本地访问地址：http://localhost:4000
```

4. [folio-2019](https://github.com/brunosimon/folio-2019)：一个开源的 3D 博客项目。这个博客我点进去后就惊呆了，用户可通过操控一辆小汽车选择要阅读的文章，过程中还有汽车的声音和砖块碰撞的效果等，特别炫酷！快去体验下吧！[点击尝试](https://bruno-simon.com/)

5. [hugo](https://github.com/gohugoio/hugo)：Go 语言的静态网站生成器。静态网站生成器就是在本地把内容文件生成静态网页（HTML+CSS），然后把生成好的页面上传到服务器的工具。这种工具能够帮你轻松且快速地上线网站，而用户仅需选择喜欢的主题，便可以专注于内容创作。Hugo 作为最流行的静态网站生成器之一，拥有丰富的插件和主题，就算没有编程基础也能帮你快速制作出满意的博客或者网站

6. [vanblog](https://github.com/Mereithhh/vanblog)：实用的一站式个人博客系统。一款简洁优雅的博客系统，追求极致响应速度和博客体验。前后台均为响应式，支持 Docker 一键部署。前台为静态页面并支持增量渲染，按需构建更新页面。拒绝花里胡哨的功能，专注于个人博客场景。

7. - [《2023年，这9个项目助你成为前端高手》](https://mp.weixin.qq.com/s/ivZzXb0XpOYGTcN2rU3e-g)，如果你不知道写点啥来练手，可以从这里找找灵感，包括电影搜索 App、聊天 App、天气 App、TODO List App、购物车 App、多语言博客、音频播放器等。

8. - [blog-cells。](https://github.com/rameshvarun/blog-cells) 为任何博客或网页添加交互式代码片段。

9. - [《如何建立写博客的习惯》](https://blog.douchi.space/keep-blogging/)。 作者提出了几个建议：1. 选择适合自己的工具，减小写博客的外界阻力；2. 把想写的点子随手记录下来，建立一个题材库；3. 建立激励机制，包括自身激励和外部激励；4. 培养有效的分发平台，让更多人看到自己的文章；5. 建立自己的博客社交圈，与其他博主交流互动。

10 - [《如何免费用云服务搭建博客评论系统》](https://blog.alswl.com/2023/11/build-blog-comment-system-based-on-free-cloud-service/)。 博主因为对 Disqus 广告过于频繁不满，寻找新的评论系统替代。博主在寻找新评论系统时，有三个主要的选型原则：数据自有、服务部署和存储，以及访问速度。非功能需求方面主要考虑低成本和系统稳定性。在探索过程中考虑了多个方案，如 Utterances、Cusdis、Waline 等，并进行一些特性的横向对比。最终博主选择了使用 Utterances 和 Waline 作为英文博客和中文博客的评论系统，两者部署成本都是 0，满足了博主的需求。
[cusdis](https://github.com/djyde/cusdis)：这是一个界面清爽、注重隐私的轻量级博客评论系统。可以很方便地与 React、Vue 或其他博客系统结合，并且还提供了一个后台来管理所有的评论。除此之外，还支持一键从 Disqus 导入、邮件通知等强大的功能


11. Django 框架的中文入门教程，免费带你学 Django 全栈。https://github.com/HelloGitHub-Team/HelloDjango-blog-tutorial

12. [我的复古网站](https://ash.ms/2019-10-02/retro-website-launch/)（英文）

![](https://cdn.beekka.com/blogimg/asset/202104/bg2021041808.jpg)

作者将他的个人网站，做成 WIndows 95 的样子，把个人博客放在上面，很有意思。本文介绍他是怎么做的。

13. 5、[如何使用 Next.js 搭建博客](https://www.joshwcomeau.com/blog/how-i-built-my-blog/)（英文）

![](https://cdn.beekka.com/blogimg/asset/202207/bg2022071103.webp)

如何使用 Next.js 在 Vercel 免费空间上搭建博客的教程。

14. 6、[Sonic](https://github.com/go-sonic/sonic/blob/master/doc/README_ZH.md)

![](https://cdn.beekka.com/blogimg/asset/202211/bg2022111011.webp)

一个 Go 语言开发的博客平台，支持 Linux/Windows/macOS，系统资源占用小，自带管理后台。

15. 6、[Aurora](https://github.com/linhaojun857/aurora)

![](https://cdn.beekka.com/blogimg/asset/202211/bg2022111724.webp)

一个在校大学生开源的博客系统，后端基于 Java 的 Spring Boot，前端基于 Vue，自带管理后台。（[@linhaojun857](https://github.com/ruanyf/weekly/issues/2737) 投稿）

16. 3、[Astro Air Blog](https://yufengbiji.com/posts/astro-air-blog-guide)

![](https://cdn.beekka.com/blogimg/asset/202303/bg2023030601.webp)

一个基于 Astro 的静态博客生成器，查看 [Demo](astro.yufengbiji.com)。

17. 4、[个人网站集成 GitHub issue 评论功能](https://richard-docs.netlify.app/blogs/b-027)（中文）

![](https://cdn.beekka.com/blogimg/asset/202307/bg2023070405.webp)

作者采用 VitePress 搭建博客，本文介绍他怎么引入 GitHub issue 作为网站的评论功能。（[@Richard-Zhang1019](https://github.com/ruanyf/weekly/issues/3237) 投稿）

18. 8、[Gmeek](https://github.com/Meekdai/Gmeek)

![](https://cdn.beekka.com/blogimg/asset/202311/bg2023113006.webp)

超轻量级个人博客模板，将 GitHub 的 issue 转成博客网站。（[@Meekdai](https://github.com/ruanyf/weekly/issues/3669) 投稿）

19. 5、[Rin](https://github.com/OXeu/Rin)

![](https://cdn.beekka.com/blogimg/asset/202406/bg2024060601.webp)

一个基于 Cloudflare Pages + Workers + D1 + R2 全家桶的博客项目，参见 [demo](https://xeu.life/)。（[@OXeu](https://github.com/ruanyf/weekly/issues/4580) 投稿）

20. 6、[N-blog](https://github.com/nswbmw/N-blog)：面向新手的 Node.js 教程，该教程讲述了 Node.js 基本知识点，同时结合搭建一个多人博客的实战，从零基础到实际开发，由浅到深帮助新手入门 Node.js 这门语言

21. C# 项目 3、[Blog.Core](https://github.com/anjoy8/Blog.Core)：基于 ASP.NET Core 和 Vue 从零开始搭建前后端分离项目教程+实战项目。该项目从 .NET Core 基础讲起，内容完整、系统，对初学者和有一定基础的小伙伴都有借鉴和学习的价值

22. 10、[vueblog](https://github.com/MarkerHub/vueblog)：一款轻量级 Java 博客项目。基于 SpringBoot+Vue 实现并附有详细开发文档和讲解视频，让刚学会 Java 的同学也能搞定。每个体面的技术人员可能都有一个自己说了算的博客吧

23. 19、[vanblog](https://github.com/Mereithhh/vanblog)：实用的一站式个人博客系统。一款简洁优雅的博客系统，追求极致响应速度和博客体验。前后台均为响应式，支持 Docker 一键部署。前台为静态页面并支持增量渲染，按需构建更新页面。拒绝花里胡哨的功能，专注于个人博客场景。

24. [Docusaurus。](https://github.com/facebook/docusaurus) 
![](https://docusaurus.io/assets/images/social-card-7b2ed059f27fc8b64f3f20025ebb382f.png)
是一个静态网站生成器，它可以帮助你在短时间内开发漂亮的文档网站。同时除文档之外，还可用于博客、知识库或 Landing Page。Prettier、Figma Developer、Supabase、StackBliz、Gulp、Tauri、Babel、React Native 等网站都基于 Docusaurus。

25. - [《Self hosting in 2023》](https://grifel.dev/decentralization/)。作者介绍了如何将静态页面托管在树莓派上，以及如何设置自己的 DDNS，从而将域名连接到本地服务器。作者通过购买一个二手的树莓派、安装 [Coolify](https://coolify.io/) 和 DDClient 等简单的步骤，仅花费了大约一个小时的时间便将博客部署在了自己的本地服务器上。这样做不仅节约了成本，而且提供了更好的开发体验。文章还提到了一些可能的运营成本，如一次性成本、电费、域名费用等。

26. - [《如果我明天去世了，我的网络应用程序会持续多久？》](https://casparwre.de/blog/webapp-afterlife/)。一位名为 “Hacker News” 的开发人员在其博客上分享了一个问题：如果他突然去世，他的 Web 应用程序会运行多久？他估计，只要数据库、域和云服务继续运作，该应用程序将无限期在线。但是，他也考虑到了可能导致应用程序离线的几种情况，例如自然灾害、基础设施故障、技术故障、产品故障、安全漏洞或恶意攻击以及付款故障。最后，他认为最有可能导致应用程序离线的是付款故障。

27. 8、[如何将 WordPress 站点发布成 Gitlab 静态页面站点？](https://opensource.com/article/18/8/publish-wordpress-static-gitlab-pages-site)（英文）

WordPress 是常用的博客软件，虽然方便易用，但是容易产生安全问题。作者提供了一个脚本，可以将 WordPress 网站的 HTML 页面，部署到 Gitlab Pages 服务，做成一个静态网站。 

28. 8、[writefreely](https://github.com/writeas/writefreely)

一个 Go 语言写的博客软件，类似 WordPress，特点是非常简洁。

29. 3、[vuepress-theme-reco](https://github.com/recoluan/vuepress-theme-reco)

VuePress 的一个主题，为博客定制。（@[recoluan](https://github.com/ruanyf/weekly/issues/336)  投稿）

30. 6、[如何使用 GitHub issue 作为博客后端？](https://github.com/ruanyf/weekly/issues/585)（中文）

你可以使用 GitHub issue 写博客，然后依靠 API 通过 Circle-CI 构建出网站。

31. 6、[静态博客的技术方案](https://news.ycombinator.com/item?id=20796729)（英文）

这是 Hacker News 的讨论帖，讨论当前自己搭建博客的最佳技术方案。

32. 5、[Cloud Run 托管网站](https://blog.mrtrustor.net/post/making-this-blog-with-cloud-run/)（英文）

Cloud Run 是谷歌云的一个 Serverless 服务，特点是直接抓取 Docker 镜像文件运行，不用自己部署文件。

本文介绍作者如何使用这个服务，部署自己的静态博客网站。此外，网上还有一份 [Cloud Run 介绍](https://github.com/ahmetb/cloud-run-faq/blob/master/README.md)，也可以参考。

33. 下面是目前支持 ActivityPub 协议的开源软件，可以自己架设服务。 
> - 博客（Facebook 的替代品）：[WriteFreely](https://writefreely.org/)，[WordPress + ActivityPub 插件](https://wordpress.org/plugins/activitypub/)，[Plume](https://joinplu.me/)

34. 6、[vdoing](https://github.com/xugaoyi/vuepress-theme-vdoing)

VuePress 的一款主题，可以用于个人博客或知识管理。（[@xugaoyi](https://github.com/ruanyf/weekly/issues/1254) 投稿）

35. 9、[如何使用 GitHub Actions 发布到 GitHub Pages](https://itsopensource.com/publish-github-pages-with-github-actions/)（英文）

一个简单的教程，教你通过 GitHub Actions 构建一个静态博客，自动发布到 GitHub Pages。

36.  博客构建工具推荐

  - [Blogdown](https://github.com/rstudio/blogdown)
  - [Docusaurus](https://docusaurus.io/)
  - [Gatsby](https://gatsbyjs.org/)
  - [Ghost](https://ghost.org/)
  - [Gridea](https://gridea.dev/)
  - [Halo](https://github.com/halo-dev/halo)
  - [Hexo](https://hexo.io/): [hexo](https://github.com/hexojs/hexo)：基于 Node.js 快速、简洁且高效的静态博客生成框架。可以使用 hexo 快速生成静态博客，它拥有丰富的[插件库](https://hexo.io/plugins/)、[主题库](https://hexo.io/themes/)。在使用 hexo 的时候也可以自己创建、定制属于自己的主题

  - [Hugo](https://gohugo.io/) ：Go 语言的静态网站生成器。静态网站生成器就是在本地把内容文件生成静态网页（HTML+CSS），然后把生成好的页面上传到服务器的工具。这种工具能够帮你轻松且快速地上线网站，而用户仅需选择喜欢的主题，便可以专注于内容创作。Hugo 作为最流行的静态网站生成器之一，拥有丰富的插件和主题，就算没有编程基础也能帮你快速制作出满意的博客或者网站

  - [Jekyll](https://jekyllrb.com/) : 3.
  - [Pelican](https://blog.getpelican.com/)
  - [Saber](https://saber.land/)
  - [Typecho](https://typecho.org)
  - [Vuepress](https://vuepress.vuejs.org/)： ：Vue 官方出品的静态网站生成器。大家的个人博客是不是要折腾一番了？[官方中文文档](https://vuepress.vuejs.org
  - [Wordpress](https://wordpress.com/)
  - [Wowchemy](https://wowchemy.com)
  - [Astro](https://astro.build)
  - [Vanblog](https://vanblog.mereith.com/)

博客部署工具推荐

  - [Netlify](https://www.netlify.com/)
  - [Vercel](https://vercel.com/)
  - [Cloudflare Pages](https://pages.cloudflare.com/)

37. 26、[Qexo](https://github.com/Qexo/Qexo)：漂亮的 Hexo 静态博客编辑器。该项目是基于 Django 的 Hexo 静态博客管理后台，支持文章管理、多种图床、自动更新、友情链接、站点统计等功能。

38. 6、[tale](https://github.com/otale/tale)：简洁、漂亮、轻量级、Java 博客，[在线预览](https://tale.biezhi.me/)。特性：
- 设计简洁，界面美观
- Markdown 文章发布
- 自定义文章链接
- 支持多主题
- 支持 Emoji 表情
- 支持网易云音乐播放
- 支持附件和数据库备份
- 部署简单，不依赖 Tomcat

39. 9、[symphony](https://github.com/88250/symphony)：用 Java 实现的现代化社区（论坛／社交网络／博客）平台，功能众多，[访问该社区](https://hacpai.com/tag/Sym)

40. 41、[Publii](https://github.com/GetPublii/Publii)：带 GUI 的静态网站生成工具。一款本地的静态网站 CMS 工具，有了它无需编程基础，即可通过图形化界面，轻松地创建个人博客、企业官网等，还支持一键发布到 GitHub Page、GitLab、Netlify 等网站。

41. 19、[WeHalo](https://github.com/sav7ng/WeHalo)：清爽的微信小程序版博客。该项目是基于 Halo 博客后端的微信小程序，可以轻松地将博客内容搬到微信小程序上，支持个人名片、博文展示、评论、搜索文章、自定义导航栏等功能。来自 [@umail.com](https://hellogithub.com/user/a0L3Omilqk8zNQY) 的分享

42. 37、[realworld](https://github.com/gothinkster/realworld)：该项目汇集了不同技术栈的实战项目。这里有采用不同编程语言框架，实现相同功能内容网站的项目代码。例如用 Vue.js+Django 开发包含注册、登录、发布文章、标签、评论等功能的网站，让你通过简单但完整的实战项目，快速上手新的技术栈，消除刚接触某个技术时的手足无措。[点击查看](https://codebase.show/projects/realworld)

43. - [免费的 Next.js 商业化模版。](https://medusajs.com/nextjs-commerce/)

44. [Next.js Commerce](https://github.com/vercel/commerce) vercel 电商平台开源

45. 21、[running_page](https://hellogithub.com/periodical/statistics/click?target=https://github.com/yihong0618/running_page)：一个展示个人跑步主页的 Python 项目。特性：
- GitHub Actions 管理自动同步跑步进程及自动生成新的页面
- Gatsby 生成的静态网页，速度快
- Mapbox 进行地图展示
- 支持 Nike、Runtastic、佳明、Keep 的数据
- 自动备份 gpx 数据，方便备份及上传到其它软件