# 个人定制版本 WebStack-Hugo 导航站点

本项目是基于 [WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo) 静态响应式网址导航主题，打造的的**个人（Weiyan Shum）定制版本**。

### 安装部署

下载更新，更新子模块。

```
$ git clone https://github.com/shenweiyan/NavBioITee.git
$ cd NavBioITee
$ git submodule update --init --recursive
$ cd themes/WebStack-Hugo
$ git pull https://github.com/shenweiyan/WebStack-Hugo.git
```

### 发布站点

通过 GitHub Actions - [HugoAction.yml](https://github.com/shenweiyan/NavBioITee/blob/main/.github/workflows/HugoAction.yml)，本源码执行自动构建，并发布到以下仓库。

- GitHub - [WebStackBioIT](https://github.com/shenweiyan/WebStackBioIT)（master），与 Cloudflare 的 **[bioit.pages.dev](https://bioit.pages.dev/)** 进行绑定，同时可通过以下自定义域名访问；

  - [https://nav.bioitee.com](https://nav.bioitee.com)

- GitHub - [NavBioIT](https://github.com/shenweiyan/NavBioIT)（gh-pages），与 Cloudflare 的 **[biox.pages.dev](https://biox.pages.dev)** 进行绑定；


### 站点地址

- [https://nav.bioitee.com](https://nav.bioitee.com)
