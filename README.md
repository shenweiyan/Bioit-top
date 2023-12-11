# WebStack-Hugo 导航站点

本项目是基于 [WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo) 静态响应式网址导航主题，打造的的**个人定制版本**。

### 安装部署

下载更新，更新子模块。

```
$ git clone https://github.com/shenweiyan/NavBioIT.git
$ cd NavBioIT
$ git submodule update --init --recursive
$ cd themes/WebStack-Hugo
$ git pull https://github.com/shenweiyan/WebStack-Hugo.git
```

### 发布站点

通过 GitHub Actions - [HugoAction.yml](https://github.com/shenweiyan/NavBioIT/blob/main/.github/workflows/HugoAction.yml)，本源码执行自动构建，并发布到以下仓库。


发布至 GitHub 的 **[NavBioIT](https://github.com/shenweiyan/NavBioIT)** 的 [gh-pages](https://github.com/shenweiyan/NavBioIT/tree/gh-pages) 分支 ，该 [gh-pages](https://github.com/shenweiyan/NavBioIT/tree/gh-pages) 分支与 Cloudflare 的 **[bioit.pages.dev](https://bioit.pages.dev)** 进行绑定；同时可通过以下自定义域名访问：

- **[https://www.bioit.top](https://www.bioit.top)**

