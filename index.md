## List of published repositories

* * *

### AUR packages repository

These are the packages that I maintain on AUR plus their dependencies
not present in official Arch Linux repositories. All are built with
GitHub Actions. The history is not preserved. To use the repository,
add this to pacman.conf:

```
[AUR]
SigLevel = Never TrustAll
Server = https://tmn505.github.io/$repo/$arch
```

[Browse repository](./AUR)

[Browse source](https://github.com/tmn505/AUR)

* * *

### VDR4Arch packages repository

These are the packages built from my fork of [VDR4Arch](https://github.com/VDR4Arch) project.
All are built with GitHub Actions. The history is not preserved.
To use the repository, add this to pacman.conf:

```
[vdr4arch]
SigLevel = Never TrustAll
Server = https://tmn505.github.io/$repo/$arch
```

[Browse repository](./vdr4arch)

[Browse source](https://github.com/tmn505/vdr4arch)

* * *

### Modified U-boot for ZoomGo Media Stick (ZX10)

Binaries ready for writing to ZoomGo ZX10.
These are built with GitHub Actions. The history is preserved.

[Browse files](./u-boot)

[Browse source](https://github.com/tmn505/u-boot/tree/zx10)
