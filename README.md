<p align="center">
    <img src="docs/image/light-icon.png#gh-light-mode-only" width=50%/ alt="">
    <img src="docs/image/dark-icon.png#gh-dark-mode-only" width=50%/ alt="">
</p>
<p align="center">
    <img title="docker build version" src="https://img.shields.io/docker/v/estrellaxd/auto_bangumi" alt="">
    <img title="release date" src="https://img.shields.io/github/release-date/estrellaxd/auto_bangumi" alt="">
    <img title="docker pull" src="https://img.shields.io/docker/pulls/estrellaxd/auto_bangumi" alt="">
    <img title="python version" src="https://img.shields.io/badge/python-3.11-blue" alt="">
</p>

# 项目说明

<p align="center">
    <img title="AutoBangumi" src="docs/image/window.png" alt="" width=75%>
</p>

本项目是基于 [Mikan Project](https://mikanani.me)、[qBittorrent](https://qbittorrent.org) 的全自动追番整理下载工具。只需要在 [Mikan Project](https://mikanani.me) 上订阅番剧，就可以全自动追番。并且整理完成的名称和目录可以直接被 [Plex]()、[Jellyfin]() 等媒体库软件识别，无需二次刮削。

## AutoBangumi 功能说明

- 简易单次配置就能持续使用
- 无需介入的 `RSS` 解析器，解析番组信息并且自动生成下载规则。
- 番剧文件整理:

    ```
    Bangumi
    ├── bangumi_A_title
    │   ├── Season 1
    │   │   ├── A S01E01.mp4
    │   │   ├── A S01E02.mp4
    │   │   ├── A S01E03.mp4
    │   │   └── A S01E04.mp4
    │   └── Season 2
    │       ├── A S02E01.mp4
    │       ├── A S02E02.mp4
    │       ├── A S02E03.mp4
    │       └── A S02E04.mp4
    ├── bangumi_B_title
    │   └─── Season 1
    ```

- 全自动重命名，重命名后 99% 以上的番剧可以直接被媒体库软件直接刮削

    ```
  [Lilith-Raws] Kakkou no Iinazuke - 07 [Baha][WEB-DL][1080p][AVC AAC][CHT][MP4].mp4 
  >>
   Kakkou no Iinazuke S01E07.mp4
  ```

- 自定义重命名，可以根据上级文件夹对所有子文件重命名。
- 季中追番可以补全当季遗漏的所有剧集
- 高度可自定义的功能选项，可以针对不同媒体库软件微调
- 无需维护完全无感使用
- 内置 TDMB 解析器，可以直接生成完整的 TMDB 格式的文件以及番剧信息。
- 对于 Mikan RSS 的反代支持。

## [快速开始](https://www.autobangumi.org/deploy/quick-start.html)

- **[项目官网](https://autobangumi.org)**
- **[3.0 更新说明](https://www.autobangumi.org/changelog/3.0.html)**

## 相关群组

- 更新推送：[Telegram Channel](https://t.me/autobangumi_update)
- Bug 反馈群：[Telegram](https://t.me/+yNisOnDGaX5jMTM9)

## Roadmap

***开发中的功能：***

- 内置 RSS 推送更新器。
- 搜索功能

***计划开发的功能：***

- 对其他站点种子的解析归类。
- 本地化番剧订阅方式。
- Transmission 的支持。

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=EstrellaXD/Auto_Bangumi&type=Date)](https://star-history.com/#EstrellaXD/Auto_Bangumi)

## 贡献

欢迎提供 ISSUE 或者 PR, 贡献代码前建议阅读 [CONTRIBUTING.md](CONTRIBUTING.md)。

贡献者名单请见：

<a href="https://github.com/EstrellaXD/Auto_Bangumi/graphs/contributors"><img src="https://contrib.rocks/image?repo=EstrellaXD/Auto_Bangumi"></a>


## Licence

[MIT licence](https://github.com/EstrellaXD/Auto_Bangumi/blob/main/LICENSE)
