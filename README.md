[![license](https://img.shields.io/github/license/micro-os-plus/devices-rp2xxx-cmsis-xpack)](https://github.com/micro-os-plus/devices-rp2xxx-cmsis-xpack/blob/xpack/LICENSE)

# A source xPack with <your-description-here>

This xxx project provides ....

The project is hosted on GitHub as
[micro-os-plus/devices-rp2xxx-cmsis-xpack](https://github.com/micro-os-plus/devices-rp2xxx-cmsis-xpack).

## Maintainer info

This page is addressed to developers who plan to include this package
into their own projects.

For maintainer infos, please see the
[README-MAINTAINER](README-MAINTAINER.md) file.

## Install

As a source xPacks, the easiest way to add it to a project is via **xpm**,
but it can also be used as any Git project, for example as a submodule.

### Prerequisites

A recent [xpm](https://xpack.github.io/xpm/),
which is a portable [Node.js](https://nodejs.org/) command line application.

For details please follow the instructions in the
[install](https://xpack.github.io/install/) page.

### xpm

Note: the package will be available from npmjs.com at a later date.

For now, it can be installed from GitHub:

```console
$ cd <project>
$ xpm init # Unless a package.json is already present

$ xpm install github:micro-os-plus/devices-rp2xxx-cmsis-xpack
```

When ready, this package will be available as
[`@micro-os-plus/devices-rp2xxx-cmsis`](https://www.npmjs.com/package/@micro-os-plus/devices-rp2xxx-cmsis)
from the `npmjs.com` registry:

```console
$ cd <project>
$ xpm init # Unless a package.json is already present

$ xpm install @micro-os-plus/devices-rp2xxx-cmsis@latest
```

### Git submodule

If, for any reason, **xpm** is not available, the next recommended
solution is to link it as a Git submodule below an `xpacks` folder.

```console
$ cd <project>
$ git init # Unless already a Git project
$ mkdir -p xpacks

$ git submodule add https://github.com/micro-os-plus/devices-rp2xxx-cmsis-xpack.git \
  xpacks/micro-os-plus-devices-rp2xxx-cmsis
```

## Branches

Apart from the unused `master` branch, there are two active branches:

- `xpack`, with the latest stable version
- `xpack-develop`, with the current development version

All development is done in the `xpack-develop` branch, and contributions via
Pull Requests should be directed to this branch.

When new releases are published, the `xpack-develop` branch is merged
into `xpack`.

## User info

TBD

### Status

The ... are fully functional.

### Limitations

TBD

### Build & integration info

To include this package in a project, consider the following details.

#### Source folders

- `src`

#### Include folders

- `include`

The header file to be included in user project is:

```c++
#include <micro-os-plus/xxx.h>
```

TODO: list all header files.

#### Preprocessor definitions

TBD

#### Compiler options

- `-std=c++17` or higher for C++ sources
- `-std=c11` for C sources

#### Namespaces

TBD

#### Classes

TBD

### Examples

TBD

### Known problems

- none

### Tests

TBD

## License

The original content is released under the
[MIT License](https://opensource.org/licenses/MIT),
with all rights reserved to
[Liviu Ionescu](https://github.com/ilg-ul).
