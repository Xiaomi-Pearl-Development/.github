## Xiaomi-Pearl-Development - Personal extras
<img align="right" width="180" height="180" src="https://github.com/Xiaomi-Pearl-Development/.github/blob/main/profile/RedmiNote12TPro.png">

This organization contains repositories to build AOSP ROMs for Redmi Note 12T Pro (pearl) with personal additions and modifications over [xiaomi-mediatek-devs](https://github.com/xiaomi-mediatek-devs) and [XagaForge](https://github.com/XagaForge) trees.

### Repositories
* [**Device Tree (pearl)**](https://github.com/Xiaomi-Pearl-Development/android_device_xiaomi_pearl.git) (`android_device_xiaomi_pearl`)
* [**Kernel Tree**](https://github.com/Xiaomi-Pearl-Development/android_kernel_xiaomi_mt6895.git) (`android_kernel_xiaomi_mt6895`)
* [**Vendor Tree (pearl)**](https://github.com/Xiaomi-Pearl-Development/android_vendor_xiaomi_pearl.git) (`android_vendor_xiaomi_pearl`,only have the file we Kang)
* [**MIUI Camera (pearl)**](https://gitlab.com/enceka/proprietary_vendor_xiaomi_miuicamera-pearl) (`proprietary_vendor_xiaomi_miuicamera-pearl`,modified version,owing to @[AetherPX](https://github.com/AetherPX))

Repositories such as `android_hardware_mediatek`, `android_hardware_xiaomi` and `android_device_mediatek_sepolicy_vndr` remain unmodified and can be used directly from the  [XagaForge](https://github.com/XagaForge) or [xiaomi-mediatek-devs](https://github.com/xiaomi-mediatek-devs) organization.


### External patches
* [compat: expose android.hardware.sensors@1.0-convert as shared lib](https://review.lineageos.org/c/400894)
* [sensors: Add a sensors 2.0 -> 1.0 subhal wrapper](https://github.com/bengris32/android_hardware_lineage_interfaces/commit/cacfae73e44d18f8bba2bbe327d5c0d5cbafe4f1)
* [vendor: Add fastboot packages build](https://github.com/AresOS-UDC/vendor_lineage/commit/19afe7c7e98c9ff5f57c57d09edfa954142e65b6) (Only required if you choose to build fastboot packages using our method)
