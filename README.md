# IX-Ray

<div align="center">
  <p>
    <a href="https://github.com/ixray-team">
      <img src="https://github.com/ixray-team/ixray-docs/blob/default/logo.png" alt="IX-Ray Team" width="150" height="150" />
    </a>
  </p>

  <p>
    <a href="https://github.com/ixray-team/ixray-1.5-stcs/releases/tag/r0.4">
      <img src="https://img.shields.io/github/v/release/ixray-team/ixray-1.5-stcs?include_prereleases&label=Release" alt="Latest release" />
    </a>
    <a  href="https://github.com/ixray-team/ixray-1.5-stcs/actions/workflows/build-engine.yml">
      <img src="https://github.com/ixray-team/ixray-1.5-stcs/actions/workflows/build-engine.yml/badge.svg" alt="Build engine" />
    </a>
  </p>
</div>

Stable repository of the modernized _X-Ray_ 1.5 game engine

## Requirements

- Visual Studio 2022 Community Edition
  - MFC
  - C++/CLI
  - Windows SDK 10.0.19041.0

## Building

Download the repository:

```console
git clone https://github.com/ixray-team/ixray-1.5-stcs.git
```

### Engine

- Run `download-dependencies.ps1`
- Build `XRay.Engine.sln` on `Win32` without projects from `utils`

## Changelog

All significant changes to this repository are documented in [this](CHANGELOG.md) file

## License

See [this](LICENSE.md) file for details
