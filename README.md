## Recovery Device Tree for the Samsung Galaxy M21 (Exynos)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_m21-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_m31s
