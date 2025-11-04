[![Open Collective backers and sponsors](https://img.shields.io/opencollective/all/komga?label=OpenCollective%20Sponsors&color=success)](https://opencollective.com/komga) [![GitHub Sponsors](https://img.shields.io/github/sponsors/gotson?label=Github%20Sponsors&color=success)](https://github.com/sponsors/gotson)
[![Discord](https://img.shields.io/discord/678794935368941569?label=Discord&color=blue)](https://discord.gg/TdRpkDu)

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/gotson/komga/tests.yml?branch=master)](https://github.com/gotson/komga/actions?query=workflow%3ATests+branch%3Amaster)
[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/gotson/komga?color=blue&label=download&sort=semver)](https://github.com/gotson/komga/releases) [![GitHub all releases](https://img.shields.io/github/downloads/gotson/komga/total?color=blue&label=github%20downloads)](https://github.com/gotson/komga/releases)
[![Docker Pulls](https://img.shields.io/docker/pulls/gotson/komga)](https://hub.docker.com/r/gotson/komga)

[![Translation status](https://hosted.weblate.org/widgets/komga/-/webui/svg-badge.svg)](https://hosted.weblate.org/engage/komga/)

# ![app icon](./.github/readme-images/app-icon.png) Komga

Komga is a media server for your comics, mangas, BDs, magazines and eBooks.

#### Chat on [Discord](https://discord.gg/TdRpkDu)

## Features

- Browse libraries, series and books via a responsive web UI that works on desktop, tablets and phones
- Organize your library with collections and read lists
- Edit metadata for your series and books
- Import embedded metadata automatically
- **Plugin system** for extending metadata providers - [Documentation](./PLUGIN_SYSTEM.md)
- **Multi-language title support** with language priority system - [Documentation](./LANGUAGE_PRIORITY.md)
- Webreader with multiple reading modes
- **Enhanced reader features** (Tachidesk-like, webtoon splitting, EPUB optimization) - [Documentation](./READER_ENHANCEMENTS.md)
- **Anonymous access** with age-based content restrictions - [Documentation](./ANONYMOUS_ACCESS.md)
- Manage multiple users, with per-library access control, age restrictions, and labels restrictions
- **Tag and genre blacklisting** for personalized content filtering
- Offers a REST API, many community tools and scripts can interact with Komga
- **Database backup and export** functionality with admin interface
- **Reverse proxy IP tracking** for accurate client IP resolution
- OPDS v1 and v2 support
- Kobo Sync with your Kobo eReader
- KOReader Sync
- Download book files, whole series, or read lists
- Duplicate files detection
- Duplicate pages detection and removal
- Import books from outside your libraries directly into your series folder
- Import ComicRack `cbl` read lists

## Extended Features

This fork includes several enhanced features:

### 🔌 Plugin System
Extensible plugin architecture for adding custom metadata providers. Load plugins from JAR files, download from GitHub, and manage them through the REST API.
- [Plugin System Documentation](./PLUGIN_SYSTEM.md)

### 🌍 Multi-Language Support
Advanced language priority system for managing titles and summaries in multiple languages. Supports 20+ languages including Japanese romaji, Korean, Chinese, and more.
- [Language Priority Documentation](./LANGUAGE_PRIORITY.md)

### 📖 Reader Enhancements
Enhanced reading experience with Tachidesk-like features:
- Webtoon image splitting for tall images
- EPUB performance optimization with lazy loading
- Customizable reader settings per series
- Multiple reading modes (LTR, RTL, vertical, webtoon, continuous)
- [Reader Enhancements Documentation](./READER_ENHANCEMENTS.md)

### 🔓 Anonymous Access
Optional authentication system with age-based content restrictions:
- Allow unauthenticated users to browse non-adult content
- Configurable age restrictions (ESRB, PEGI, FSK ratings)
- Library-level anonymous access control
- [Anonymous Access Documentation](./ANONYMOUS_ACCESS.md)

### 🛡️ Content Filtering
Personalized content filtering with tag and genre blacklisting:
- User-specific blacklists for tags and genres
- Filter summary and management API
- Seamless integration with existing restrictions

### 💾 Database Management
Administrative tools for database backup and maintenance:
- Create backups with optional image inclusion
- Download, list, and manage backups
- Automatic cleanup of old backups
- REST API for backup operations

### 🌐 Reverse Proxy Support
Enhanced IP tracking for accurate client identification:
- Support for X-Forwarded-For, X-Real-IP headers
- IPv4 and IPv6 support
- Private IP detection
- Debug endpoints for proxy configuration

## Installation

Refer to the [website](https://komga.org/docs/category/installation) for instructions.

## Documentation

Head over to our [website](https://komga.org) for more information.

## Develop in Komga

Check the [development guidelines](./DEVELOPING.md).

## Translation

[![Translation status](https://hosted.weblate.org/widgets/komga/-/webui/horizontal-auto.svg)](https://hosted.weblate.org/engage/komga/)

## Sponsors

[![Jetbrains_logo](./.github/readme-images/jetbrains.svg)](https://www.jetbrains.com/?from=Komga)

Thanks to [JetBrains](https://www.jetbrains.com/?from=Komga) for providing the development environment that helps us develop Komga.

[![Chromatic logo](https://user-images.githubusercontent.com/321738/84662277-e3db4f80-af1b-11ea-88f5-91d67a5e59f6.png)](https://www.chromatic.com)

Thanks to [Chromatic](https://www.chromatic.com/) for providing the visual testing platform that helps us review UI changes and catch visual regressions.

## Credits

The Komga icon is based on an icon made by [Freepik](https://www.freepik.com/home) from www.flaticon.com
