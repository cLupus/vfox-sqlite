# `vfox-sqlite`

[SQLite](https://sqlite.org/) plugin for [`vfox`](https://vfox.lhan.me/). Port of [asdf-sqlite](https://github.com/cLupus/asdf-sqlite).


## Usage

1. [Generate](https://github.com/version-fox/vfox-plugin-template/generate) a new repository based on this template.
2. Configure [metadata](https://github.com/version-fox/vfox-plugin-template/blob/main/metadata.lua) information
3. To develop your plugin further, please read [the plugins create section of the docs](https://vfox.lhan.me/plugins/create/howto.html).


## How to publish?

1. Push a new tag to the repository which name is `vX.Y.Z` (X.Y.Z is the version number).
2. The CI will automatically package, then publish [release](https://github.com/version-fox/vfox-plugin-template/releases/tag/v0.0.1) and publish [manifest](https://github.com/version-fox/vfox-plugin-template/releases/tag/manifest).
