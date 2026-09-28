[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025, 2026  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be)
[comment]: <> (useful, but WITHOUT ANY WARRANTY; without even the)
[comment]: <> (implied warranty of MERCHANTABILITY or FITNESS FOR)
[comment]: <> (A PARTICULAR PURPOSE. See the)
[comment]: <> (See the GNU Affero General Public License for)
[comment]: <> (more details.)

[comment]: <> (You should have received a copy of the GNU Affero)
[comment]: <> (General Public License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# Android Window Manager (`android-wm`)

Google does not distribute the `android-wm`
program together with Android.

This repository provides the `android-wm`
command, together with many other basic
Android window management programs such
as `alt-tab` and `windows-list`.

The Android Window Manager is a core part of
[DogeOS](
  https://github.com/themartiancompany/dogeos)
Android platform base.

## Manual

Manuals can be consulted with the

```bash
man \
  <program-name>
```

command. For a list of installed manuals consult the
[manual submodule repository](
  https://github.com/themartiancompany/android-wm-man).

## Installation

The programs in this source repo
can be installed from source using GNU Make.

```bash
make \
  install
```

The collection has been officially published
on the the uncensorable
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store as
`android-wm`.
The source code is published on the
[Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
so it can't possibly be taken down.

To install it from there just type

```bash
ur \
  android-wm
```

A censorable HTTP Github mirror of the recipe published there,
containing a full list of the software dependencies needed to run the
tools is hosted on
[android-wm-ur](
  https://github.com/themartiancompany/android-wm-ur).

Be aware the mirror could go offline any time as Github and more
in general all HTTP resources are inherently unstable and censorable.

## License

This program is released by Pellegrino Prevete under the terms
of the GNU Affero General Public License version 3.
