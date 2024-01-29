# Digital Obsidian Garden
This is the template to be used together with the [Digital Garden Obsidian Plugin](https://github.com/oleeskild/Obsidian-Digital-Garden). 
See the README in the plugin repo for information on how to set it up.

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/oleeskild/digitalgarden)

---
## Docs
Docs are available at [dg-docs.ole.dev](https://dg-docs.ole.dev/)
---
以下为本人所记
本人在构建obsidian站时主要参考了[Obsidian 简明发布方式](forum-zh.obsidian.md/t/topic/19256). 以及[利用obsidian构建个人博客](https://zytomorrow.top/%E6%8A%80%E6%9C%AF%E6%8A%98%E8%85%BE/%E5%88%A9%E7%94%A8obsidian%E6%9E%84%E5%BB%BA%E4%B8%AA%E4%BA%BA%E5%8D%9A%E5%AE%A2/)
其中在构建前期以第一篇为主，在运行完所有教程后出现问题，在查阅完第二篇笔记后解决，问题在于没有通过插件，在右侧点击树苗图标上传笔记
网站由Netlify构建，没有替换域名，在此基础上照抄了一些代码改进，文件存储地址分别在于
1./src/site/_includes/components/user/common/head/font.njk
2./src/site/styles/user/font.scss
3./site/_includes/components/user/common/footer/comment.njk
前两者用于字体美化，字体为霞骛文楷，第三个为添加评论系统
