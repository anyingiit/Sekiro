[English](README.md) · **简体中文**

> 英文版是规范版本。本页与 [README.md](README.md) 不一致时，以英文版为准。

<!-- translation-of: README.md sha256:92c7e2651635bf44 -->

<!-- Source: Best-README-Template BLANK_README (Unlicense) — https://github.com/othneildrew/Best-README-Template -->
<a id="readme-top"></a>

# Sekiro

《只狼：影逝二度》（Sekiro: Shadows Die Twice）存档文件及其画面设置的个人备份，不是可以构建、安装或运行的软件。

[![License](https://img.shields.io/github/license/anyingiit/Sekiro)](LICENSE)

[报告问题](https://github.com/anyingiit/Sekiro/issues/new?template=bug_report.yml) · [提出需求](https://github.com/anyingiit/Sekiro/issues/new?template=feature_request.yml)

<details>
  <summary>目录</summary>
  <ol>
    <li><a href="#关于本项目">关于本项目</a></li>
    <li><a href="#开始使用">开始使用</a></li>
    <li><a href="#使用方法">使用方法</a></li>
    <li><a href="#贡献">贡献</a></li>
    <li><a href="#许可证">许可证</a></li>
    <li><a href="#联系方式">联系方式</a></li>
  </ol>
</details>

## 关于本项目

Sekiro 是 anyingiit 的个人仓库之一，已在 GitHub 上归档。它的全部内容是从一份《只狼：影逝二度》安装目录中复制出来的两个文件：[`save/S0000.sl2`](save/S0000.sl2)，一个 FromSoftware 旗下 PC 游戏使用的 `.sl2` 格式存档文件；以及 [`GraphicsConfig.xml`](GraphicsConfig.xml)，同一款游戏写入自身配置文件夹的画面设置文件。目录树中没有任何清单文件、源代码或入口点——这是一份存档备份，不是软件。

规划中的内容参见 [open issues](https://github.com/anyingiit/Sekiro/issues)。

## 开始使用

### 前置条件

- 一份正版的《只狼：影逝二度》安装——`.sl2` 存档格式是该游戏专用的，除它之外没有任何程序能打开 [`save/S0000.sl2`](save/S0000.sl2)。
- 如果你打算恢复这份存档而不只是查看它，还需要该存档所属的 Steam 账号；否则，保存或移动这两个文件不需要任何软件。

### 安装

没有需要构建的内容，也没有需要安装的东西。克隆本仓库即可在本地获得这两个文件的副本：

```sh
git clone https://github.com/anyingiit/Sekiro.git
```

要真正恢复它们，请将 `save/S0000.sl2` 复制到《只狼：影逝二度》自己的存档文件夹中（请将 `save` 文件夹重命名为你自己 Steam 账号的 SteamID64），并用同样的方式把 `GraphicsConfig.xml` 复制到游戏的配置文件夹中。必须先安装好游戏，这两个文件才有意义。

## 使用方法

这两个文件都不是用来运行的。当 [`save/S0000.sl2`](save/S0000.sl2) 位于《只狼：影逝二度》的存档文件夹、[`GraphicsConfig.xml`](GraphicsConfig.xml) 位于其配置文件夹后，正常启动游戏即可——它会自动读取恢复的存档和保存的画面设置。

## 贡献

欢迎任何形式的贡献。参与前请阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 了解如何提交 issue 或 pull request，并阅读 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) 了解参与者应遵守的行为准则。

请不要在公开的 issue 或 pull request 中报告安全问题。请参阅 [SECURITY.md](SECURITY.md) 了解如何私下报告。

## 许可证

基于 MIT 许可证发布。详见 [LICENSE](LICENSE)。

## 联系方式

项目地址：[https://github.com/anyingiit/Sekiro](https://github.com/anyingiit/Sekiro)

<p align="right">(<a href="#readme-top">回到顶部</a>)</p>
