> **📖 [Read the Build FAQ first →](https://github.com/isygold/Vegas-Private/blob/1.11.1/VEGAS-DXVK-SAREK-BUILD-FAQ.md)**
> Important info about which file to download, VEGAS+VKD3D auto-install, and Unity compatibility.

# vegas-releases

[![Downloads](https://img.shields.io/github/downloads/isygold/vegas-releases/total?color=blue&style=flat-square)](https://github.com/isygold/vegas-releases/releases)
[![Stars](https://img.shields.io/github/stars/isygold/vegas-releases?style=flat-square)](https://github.com/isygold/vegas-releases)
[![Latest Release](https://img.shields.io/github/v/release/isygold/vegas-releases?style=flat-square)](https://github.com/isygold/vegas-releases/releases/latest)
[![Sponsor](https://img.shields.io/badge/Sponsor-%24?logo=github&style=flat-square)](https://github.com/sponsors/isygold/card)

📖 **[Wiki](https://github.com/isygold/vegas-releases/wiki)** — quickstart, installation, configuration reference, FAQ

VEGAS — Community DXVK builds for Adreno Android Emulation 🎰

## About

This repository hosts release artifacts for **VEGAS**, a community-driven fork of GPLAsync 2.7.1 (itself a DXVK fork) purpose-built for Qualcomm Adreno GPUs running under Winlator and Star Emulator on Android (ARM64).

Each release provides:
- **WCP packages** — Import directly into Winlator (type: DXVK) or Star Emulator (type: VEGAS)
- **ZIP archives** — Raw DLLs for manual installation
- **Configuration** — Pre-tuned `dxvk.conf` for Adreno GPUs

## Releases

| Tag | Date | Description |
|-----|------|-------------|
| [v2.4.1-3137660](https://github.com/isygold/vegas-releases/releases/tag/v2.4.1-3137660) | Aug 5, 2026 | **Final Stable Release (release-v2.4.1 line)** — GPLAsync, FSR 1.0, framegen, TBDR governor, telemetry keys |
| [v2.7.3-vegas](https://github.com/isygold/vegas-releases/releases/tag/v2.7.3-vegas) | Jun 6, 2026 | Initial Community Release |
| [v2.7.3-vegas-stable](https://github.com/isygold/vegas-releases/releases/tag/v2.7.3-vegas-stable) | Jun 8, 2026 | Stable Release |
| [v2.7.3-vegas-release-V2](https://github.com/isygold/vegas-releases/releases/tag/v2.7.3-vegas-release-V2) | Jun 12, 2026 | GPU BCn→ASTC Transcoder |

> **Note — can't find a config file for a build?**
> All VEGAS builds and their artifacts (including `vegas-config-*` `dxvk.conf`) are stationed on the development repo **before** they become releases. If what you need isn't attached to a release at **github.com/isygold/vegas-releases**, go to **github.com/isygold/Vegas-Private** — that's where every build and artifact lives until it's promoted to a release (Actions tab → artifact list).

See [CHANGELOG.md](CHANGELOG.md) for full details.

## License

zlib/libpng— added a new copyright in licence.
