base-requires
=============

This package separates the requirements of XOOPS/XoopsCore from other requirements that may be added to the main composer.json, such as modules.

To update just the packages in base-requires use:

    composer update xoops/base-requires --with-dependencies

To check for, but not install updates:

    composer update xoops/base-requires --dry-run --with-dependencies
