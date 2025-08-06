# Advantech ETC

Advantech is a global leader in industrial computing and IoT solutions. The BSPs developed by the Advantech Engineering and Technology Center offer distinct advantages for developers working with Yocto, particularly in industrial IoT environments, by providing optimized, reliable, and hardware-specific support for embedded systems.

## Modular BSP

A Modular BSP is a lightweight board support package tailored for Yocto-based IoT applications. It provides a streamlined set of components—including the kernel, bootloader, and a minimal root filesystem—required to boot and run an IoT device. By minimizing build complexity and system overhead, it enables faster development cycles, smaller image sizes, and improved performance. This makes it especially suitable for resource-constrained edge devices and rapid prototyping in industrial environments.

### Supported Hardware

* [ROM-2620](https://www.advantech.com/en-eu/products/8fc6f753-ca1d-49f9-8676-10d53129570f/rom-2620/mod_294031c8-4a21-4b95-adf2-923c412ef761) (`rom2620-ed91` NXP i.MX 8ULP)
* [ROM-2820](https://www.advantech.com/en/products/8fc6f753-ca1d-49f9-8676-10d53129570f/rom-2820/mod_bb82922e-d3a2-49d7-80ff-dc57f400185e?gad_source=1&gad_campaignid=19833722581&gclid=EAIaIQobChMIpeeb5bfzjgMVJZODBx2WIjDNEAAYAiAAEgIJFfD_BwE) (`rom2820-ed93` NXP i.MX 93)
* [ROM-5722](https://www.advantech.com/en-eu/products/77b59009-31a9-4751-bee1-45827a844421/rom-5722/mod_11aa0c77-868e-4014-8151-ac7a7a1c5c1b) (`rom5722-db2510` NXP i.MX 8M Plus)
* [RSB-3720](https://www.advantech.com/en-eu/products/5912096e-f242-4b17-993a-1acdcaada6f6/rsb-3720/mod_d2f1b0bc-650b-449a-8ef7-b65ce4f69949) (`rsb3720` NXP i.MX 8M Plus)

### Repositories

* [imx-manifests](https://github.com/Advantech-EECC/imx-manifest): Helps coordinate multiple layers and components in i.MX Yocto builds.
* [meta-eecc-nxp](https://github.com/Advantech-EECC/meta-eecc-nxp): Yocto meta-layer for NXP-based Advantech platforms. Supports building custom Linux distributions for embedded devices.
* [linux-imx](https://github.com/Advantech-EECC/linux-imx): Fork of the i.MX Linux kernel source. Tailored for Advantech's ARM-based platforms.

## Contributing 

Contributions are welcome! Each request will be reviewed on a per-project basis, so the best place to begin is the repository of the project you’re interested in contributing to.
