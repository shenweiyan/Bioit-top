# WebStack-Hugo 导航站点

本项目是基于 [WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo) 静态响应式网址导航主题，打造的的**个人定制版本**。

### 安装部署

下载更新，更新子模块。

```
$ git clone https://github.com/shenweiyan/Bioit-top.git
$ cd Bioit-top
$ git submodule update --init --recursive
$ cd themes/WebStack-Hugo
$ git pull https://github.com/shenweiyan/WebStack-Hugo.git
```

### 静态资源

本站点的所有静态资源，包括导航站点 logo 图片等均已开源，详情请参考 [shenweiyan/WebStackRES](https://github.com/shenweiyan/WebStackRES)。

### 发布站点

通过 GitHub Actions - [HugoAction.yml](https://github.com/shenweiyan/NavBioIT/blob/main/.github/workflows/HugoAction.yml)，本源码执行自动构建，并发布到以下仓库。

发布至 GitHub 的 **[Bioit-top](https://github.com/shenweiyan/Bioit-top)**（即本仓库）的 [gh-pages](https://github.com/shenweiyan/Bioit-top/tree/gh-pages) 分支：

- [gh-pages](https://github.com/shenweiyan/Bioit-top/tree/gh-pages) 分支部署至 [Netlify](https://app.netlify.com/)，同时绑定 [https://bioit.top](https://bioit.top)，**国内访问相对快一些！**

- [gh-pages](https://github.com/shenweiyan/Bioit-top/tree/gh-pages) 分支部署至 [Cloudflare Pages](https://pages.cloudflare.com/)，同时绑定 [https://nav.bioit.top](https://nav.bioit.top)，**国内访问可能有一定延迟。**

