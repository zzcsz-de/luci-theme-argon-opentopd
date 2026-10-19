# luci-theme-argon-opentopd

A LuCI theme based on **luci-theme-argon**, styled with the color scheme of **luci-theme-opentopd**.

## Origins & Thanks

This theme is a derivative work combining two excellent open-source LuCI themes:

1. **[luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)** by [Jerrykuku](https://github.com/jerrykuku) — the base framework. All layout, components, and functionality come from Argon. Licensed under Apache License 2.0.

2. **[luci-theme-opentopd](https://github.com/sirpdboy/luci-theme-opentopd)** by [sirpdboy](https://github.com/sirpdboy) — the visual design inspiration. The color palette (dark sidebar, orange accents, beige form elements) is adapted from opentopd's style. Licensed under Apache License 2.0.

**Thank you to both original authors** for their outstanding work on the LuCI ecosystem. This theme would not exist without them.

## Why this theme?

The opentopd theme has a distinctive warm color scheme, but its custom dropdown widgets had compatibility issues with newer LuCI versions. This theme keeps opentopd's visual identity while using Argon's rock-solid, well-maintained component foundation.

## License

Apache License 2.0 — same as both upstream projects. See LICENSE file for details.

## Building

This is a standard OpenWrt LuCI theme package. To build:

```bash
# In OpenWrt buildroot
./scripts/feeds update luci
./scripts/feeds install luci-theme-argon-opentopd
make menuconfig  # Select LuCI -> Themes -> luci-theme-argon-opentopd
make package/luci-theme-argon-opentopd/compile
```
