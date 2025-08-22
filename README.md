# SukiSU-Ultra

[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](./LICENSE)
[![Kernel](https://img.shields.io/badge/kernel-5.15-green.svg)]()
[![Platform](https://img.shields.io/badge/platform-Android-orange.svg)]()

```text
#
# Copyright (C) 2024 The Android Open Source Project
#
# SPDX-License-Identifier: Apache-2.0
#
````

A kernel-based root solution for Android devices, forked from [`tiann/KernelSU`](https://github.com/tiann/KernelSU), with additional features and patches.

---

## 📦 Build Instructions

1. Download the kernel source from the **Samsung Open-Source** website.
2. Delete all content inside `kernel-5.15/`.
3. `cd` into the `kernel-5.15/`.
4. Clone this repository inside.

Then build with:

```bash
cd ..
bash ./build_kernel.sh
```

The output will be placed in the `out/target/product/a15x/obj/KERNEL_OBJ/kernel-5.15/arch/arm64/boot` directory.

---

## 🙏 Credits

* [topjohnwu](https://github.com/topjohnwu) for **magiskboot**
* **SukiSU-Ultra** developers for patches
* [KernelSU](https://github.com/tiann/KernelSU) developers for patches
* **AOSP developers** for system and kernel
* **Zediss P** for testing inspiration, and asking me to do it
* **Samsung developers** for kernel sources
* **Ravindu** for inspiration and tutorials about preparing environment

---

## 📜 License

This project is licensed under the [Apache-2.0 License](./LICENSE).
