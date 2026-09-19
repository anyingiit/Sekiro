<!-- Source: Best-README-Template BLANK_README (Unlicense) — https://github.com/othneildrew/Best-README-Template -->
<a id="readme-top"></a>

# Sekiro

A personal backup of a Sekiro: Shadows Die Twice save file and its graphics settings, not a piece of software with anything to build, install, or run.

**English** · [简体中文](README.zh-CN.md)

[![License](https://img.shields.io/github/license/anyingiit/Sekiro)](LICENSE)

[Report a bug](https://github.com/anyingiit/Sekiro/issues/new?template=bug_report.yml) · [Request a feature](https://github.com/anyingiit/Sekiro/issues/new?template=feature_request.yml)

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a></li>
    <li><a href="#getting-started">Getting Started</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>

## About The Project

Sekiro is one of anyingiit's personal repositories, archived on GitHub. Its entire content is two files copied out of a Sekiro: Shadows Die Twice installation: [`save/S0000.sl2`](save/S0000.sl2), a save-game file in the `.sl2` format FromSoftware's PC titles use; and [`GraphicsConfig.xml`](GraphicsConfig.xml), the graphics-settings file the same game writes to its own config folder. There is no manifest, source file, or entry point anywhere in the tree — this is a save-game backup, not software.

See the [open issues](https://github.com/anyingiit/Sekiro/issues) for anything planned.

## Getting Started

### Prerequisites

- A licensed installation of Sekiro: Shadows Die Twice — the `.sl2` save format is specific to that game, so nothing else can open [`save/S0000.sl2`](save/S0000.sl2).
- The Steam account the save belongs to, if you mean to restore it rather than just look at it; otherwise no software of any kind is required to store or move these two files.

### Installation

There is no build step and nothing to install. Cloning the repository gets you a local copy of the two files:

```sh
git clone https://github.com/anyingiit/Sekiro.git
```

To actually restore them, copy `save/S0000.sl2` into Sekiro: Shadows Die Twice's own save folder, renaming the `save` directory to your own Steam account's SteamID64, and copy `GraphicsConfig.xml` into the game's config folder the same way. The game must already be installed before either file means anything to it.

## Usage

Neither file is run. Once `save/S0000.sl2` sits in Sekiro: Shadows Die Twice's save folder and `GraphicsConfig.xml` sits in its config folder, launch the game as usual — it reads the restored save and the saved graphics settings on its own.

## Contributing

Contributions are welcome. Read [CONTRIBUTING.md](CONTRIBUTING.md) for how to open an issue or a pull request, and [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) for the standards expected of everyone taking part.

Please do not report security issues in public issues or pull requests. [SECURITY.md](SECURITY.md) explains how to report them privately.

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for details.

## Contact

Project link: [https://github.com/anyingiit/Sekiro](https://github.com/anyingiit/Sekiro)

<p align="right">(<a href="#readme-top">back to top</a>)</p>
