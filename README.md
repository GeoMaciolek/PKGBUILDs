# PKGBUILDs
Various `PKGBUILD` filess for Arch Linux's AUR (Arch User Repository).  They will be listed as *(Fix)* for ones that update existing `PKGBUILD` files, and as *(New)* for newly created ones.

## Projects

### f3-git (Fix)

[F3](https://github.com/AltraMayor/f3) is a tool to detect counterfeit flash media.  The [f3-git](https://aur.archlinux.org/packages/f3-git) `PKGBUILD` contains a recent version of this. This `PKGBUILD` fixes some issues with the version on AUR (as of 2016-10-20).

#### Changelog

* 2016-10-20 - Updated `PKGBUILD` to get `make` to install the `extra` target via `install-extra`. (It's already built by the `PKGBUILD`). Also, f3 GIT version bump
