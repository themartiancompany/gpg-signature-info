..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License
   along with this program.  If not, see <https://www.gnu.org/licenses/>.


====================================
gpg-signature-info
====================================

---------------------------------------------
GNU Privacy Guard Signature Info tool
---------------------------------------------
:Version: gpg-signature-info |version|
:Manual section: 1

Synopsis
========

gpg-signature-info *[options]* *target_file*


Description
===========

It returns information about the
target file's signature.

Options
========

-t  output_type         It can be 'fingerprint'.
-H  gnupg_home          GnuPG home (for when the signature type
                        is 'fingeprint').

-h                      Display help.
-c                      Enable color output
-v                      Enable verbose output


Bugs
====

https://github.com/themartiancompany/gpg-signature-info/-/issues

Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* gpg
* gpg-key-info

.. include:: variables.rst
