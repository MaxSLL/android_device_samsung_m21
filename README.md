## Recovery Device Tree for the Samsung Galaxy M31s (Exynos)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_m31s-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_m31s
