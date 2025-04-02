[comment]: <> (SPDX-License-Identifier: AGPL-3.0)

[comment]: <> (-------------------------------------------------------------)
[comment]: <> (Copyright © 2024, 2025  Pellegrino Prevete)
[comment]: <> (All rights reserved)
[comment]: <> (-------------------------------------------------------------)

[comment]: <> (This program is free software: you can redistribute)
[comment]: <> (it and/or modify it under the terms of the GNU Affero)
[comment]: <> (General Public License as published by the Free)
[comment]: <> (Software Foundation, either version 3 of the License.)

[comment]: <> (This program is distributed in the hope that it will be useful,)
[comment]: <> (but WITHOUT ANY WARRANTY; without even the implied warranty of)
[comment]: <> (MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the)
[comment]: <> (GNU Affero General Public License for more details.)

[comment]: <> (You should have received a copy of the GNU Affero General Public)
[comment]: <> (License along with this program.)
[comment]: <> (If not, see <https://www.gnu.org/licenses/>.)

# GNU Privacy Guard Signature Info

The GNU Privacy Guard Signature Info
tool returns various information file
cryptographically signed with OpenPGP.

The GNU Privacy Guard Signature Info
tool is written using the
[Crash Bash](
  https://github.com/themartiancompany/crash-bash)
library and of course requires
GNU Privacy Guard.

## Installation

The program in this source repo
can be installed from source using GNU Make.

```bash
make \
  install
```

or even run directly

```bash
bash \
  gpg-signature-info/gpg-signature-info
```

The tool has officially published on the
the uncensorable
[Ur](
  https://github.com/themartiancompany/ur)
user repository and application store as
`lur`.
The source code is published on the
[Ethereum Virtual Machine File System](
  https://github.com/themartiancompany/evmfs)
so it can't possibly be taken down.

To install it from there just type

```bash
ur \
  gpg-signature-info
```

A censorable HTTP Github mirror of the recipe published there,
containing a full list of the software dependencies needed to run the
tools is hosted on
[gpg-signature-info-ur](
  https://github.com/themartiancompany/gpg-signature-info-ur).

A censorable binary package has been published on the
[Fallback User Repository](
  https://github.com/themartiancompany/fur)
and it can be installed with

```bash
fur \
  gpg-signature-info
```

Be aware the mirrors could go offline any time as Github and more
in general all HTTP resources are inherently unstable and censorable.

## License

This program is released by Pellegrino Prevete under the terms
of the GNU Affero General Public License version 3.
