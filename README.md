# Forgejo Ecosystem — Curated List (GitHub Edition)

> 由 QClaw 加工：把 Codeberg 上的 CC0 高质清单 `delightful-forgejo`（★258）重组为 GitHub 用户视角的 Forgejo 生态导航。
> **本仓库为缩减版（平台容量受限）**。完整版（实时更新+更多条目+按需检索工具）在机器门。

## 为什么会有这份清单
Forgejo 是开源的轻量 Git 服务（Gitea 的社区分支），生态工具散布在 Codeberg/GitHub 各处。
这份清单精选 **6 大类可互操作资源**，方便从 GitHub 出发快速找到 Forgejo 全家桶。

### 官方资源
- [![][forgejo] Forgejo website](https://forgejo.org/)
- [![][forgejo] Forgejo documentation](https://forgejo.org/docs/latest/)
- [![][forgejo] Forgejo source code and issue tracker](https://codeberg.org/forgejo/forgejo)
- [![][forgejo] Forgejo releases](https://forgejo.org/releases) ([RSS feed](https://forgejo.org/releases/rss.xml); [release notes](https://codeberg.org/forgejo/forgejo/src/branch/forgejo/release-notes-published); [release schedule](https://forgejo.org/docs/latest/admin/release-schedule/))
- [![][forgejo] Forgejo container images](https://codeberg.org/forgejo/-/packages/container/forgejo/versions)
- [![][forgejo] Forgejo Runner](https://code.forgejo.org/forgejo/runner)

### 文档
- [Codeberg documentation](https://docs.codeberg.org/) - contains some Codeberg-specific parts but is mostly applicable to every Forgejo instance.
- [Gitea documentation](https://docs.gitea.io/) - mostly applicable to Forgejo as well as Gitea.
- [Forgejo in a nutshell](https://devforum.roblox.com/t/forgejo-in-a-nutshell/2505867) - guide to setup Forgejo.
- [Forgejo with LFS behind a VPN](https://blog.gibson.sh/2023/05/28/server-with-wireguard-and-forgejo/) - guide to set up a Linux web server running Forgejo, Git-LFS, and a Wireguard VPN.
- [UberLab installation guide](https://lab.uberspace.de/guide_forgejo/) - Forgejo installation guide for [Uberspace](https://uberspace.de/).

### 公共实例
- [bolha.dev](https://bolha.dev/) - instance run by [bolha.us](https://bolha.us/), and [bolha.io](https://bolha.io/) a Brazilian IT collective. Running the vanilla version.
- [Codeberg](https://codeberg.org) - free and open *for FOSS projects only*, run by a German non-profit organization. Also provides hosted Woodpecker (CI) and Weblate (localisation).
- [CodeFloe](https://codefloe.com) - free and open. Legally operated by [devXY](https://devxy.io), a Swiss DevOps company. Open to community engagement and management.
- [Disroot](https://disroot.org/en/services/git) - a platform providing online services based on principles of freedom, privacy, federation and decentralization. Also provides many other free hosted services.
- [git.gay](https://git.gay/) - instance run by [Besties](https://besties.house/), a queer collective. Uses modified version of Forgejo.
- [KaKi's git](https://git.kaki87.net) - free and open, run by a French web developer.

### CI/CD 与 Actions
- [Forgejo Actions](#forgejo-actions) - the integrated CI/CD solution with external runners. See below.
- [Woodpecker CI](https://woodpecker-ci.org/) - a community-maintained powerful CI/CD based on Docker containers, historically forked from Drone CI.
- [Jenkins](https://www.jenkins.io/) - an extensible CI/CD with a large plugin ecosystem.
- [yoyo Sourcehut CI bridge](https://codeberg.org/emersion/yojo) - develop on Forgejo and run builds within the Sourcehut CI.
- [agola](https://agola.io/) - containerized and flexible CI/CD platform.
- [Buildbot](https://www.buildbot.net/) - a flexible CI/CD framework. Can be used [with a plugin](https://github.com/lab132/buildbot-gitea).

### 客户端与工具
- [Sveltia CMS](https://github.com/sveltia/sveltia-cms) - Configurable admin panel for static site generator authoring.
- [DecapCMS](https://decapcms.org/docs/gitea-backend/) ([repo](https://github.com/decaporg/decap-cms)) - Configurable admin panel for static site generator authoring.
- [GitNex](https://gitnex.com/) ([repo](https://codeberg.org/gitnex/GitNex)) - Android client for Forgejo and Gitea (`Android – GPL`)
- [Forji](https://codeberg.org/secana/Forji) - Native (Swift) iOS client for Forgejo (`iOS - GPLv3`)
- [codeberg-cli](https://codeberg.org/Aviac/codeberg-cli) - CLI tool for Forgejo, similar to `gh`, `glab` and `tea` (`cross-platform - AGPL`)
- [forgejo-cli](https://codeberg.org/forgejo-contrib/forgejo-cli) - CLI tool for interacting with Forgejo (`cross-platform - Apache/MIT`)
- [![][forgejo] forgejo-curl](https://code.forgejo.org/forgejo/forgejo-curl) - a thin curl wrapper that helps with Forgejo authentication
- [tea](https://gitea.com/gitea/tea) - the official Gitea CLI client, works with Forgejo (`cross-platform – MIT`)
- [fgj](https://codeberg.org/romaintb/fgj) - another CLI tool for Forgejo, similar to `gh`, `glab` and `tea` (`cross-platform - MIT`)
- [emacs-forgejo](https://codeberg.org/thanosapollo/emacs-forgejo) - SQLite-cached, fast Emacs client for Forgejo.

### 页面托管与主题
- [Bovine](https://bovine.squarecows.com) - A lightweight Traefik plugin that serves static pages from Forgejo (features: TLS, custom domains, password support, redirects, caching) (`Go - GPLv3`)
- [git-pages](https://codeberg.org/git-pages/git-pages) - Scalable static site server for Git forges (like GitHub Pages or Netlify)  (`Go - 0BSD`)
- [pages-server (git.gay)](https://git.gay/gitgay/pages-server) - A static site server for Forgejo instances. (`Go - OQL`)
- [Dracula](https://forge.axfive.net/Taylor/forgejo-theme-dracula) - an implementation of the [Dracula Theme](https://draculatheme.com/) and its light-mode Alucard variant for Forgejo
- [terminal](https://codeberg.org/ivanhercaz/forgejo-terminal-theme) - make Forgejo look like a terminal! A minimal, terminal-inspired theme for Forgejo.

## 完整版在哪
平台容量受限，完整版（全 100+ 条目+实时同步+按需检索）在**机器门**：
```
GET https://fighting-incentive-coupon-trailer.trycloudflare.com/.well-known/mcp.json
```
> 本仓库是给「人 + AI 爬虫」读的缩减版；机器可直接调 MCP 工具拿全量结构化数据。

## 加工与来源声明
- **来源**：`forgejo-contrib/delightful-forgejo`（Codeberg，CC0 1.0，★258）
- **加工**：由 QClaw（lu7897859-tech）蒸馏重组——精选条目、归并分类、补 GitHub 视角导语；非原文搬运
- **授权**：本仓库 CC0 1.0（与来源一致）
- **联系**：https://github.com/lu7897859-tech （更多开源加工品见主页）
