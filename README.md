# PKGBUILDs
Various `PKGBUILD` filess for Arch Linux's AUR (Arch User Repository).  They will be listed as *(Fix)* for ones that update existing `PKGBUILD` files, and as *(New)* for newly created ones.

## Projects

### multibootusb-git (New)

[multibootusb](http://multibootusb.org) is a tool to write multiple "LiveCD" images to the same USB key.  The [multiboot](https://aur.archlinux.org/packages/multiboot) `PKGBUILD` contains the most recent stable release (as of this writing), and this PKGBUILD will let people add a more current version

#### Changelog

* 2016-10-22 - Created a `PKGBUILD` using the existing `multibootusb` AUR entry's `PKGBUILD`, updated to use GIT and to "build" it.

### f3-git (Fix)

[F3](https://github.com/AltraMayor/f3) is a tool to detect counterfeit flash media.  The [f3-git](https://aur.archlinux.org/packages/f3-git) `PKGBUILD` contains a recent version of this. This `PKGBUILD` fixes some issues with the version on AUR (as of 2016-10-20).

#### Changelog

* 2016-10-20 - Updated `PKGBUILD` to get `make` to install the `extra` target via `install-extra`. (It's already built by the `PKGBUILD`). Also, f3 GIT version bump
