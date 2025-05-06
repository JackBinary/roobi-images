# ROOBI OS Image Repository for Radxa Rock 5 ITX

This repository provides custom image definitions for use with **ROOBI**, Radxa's OS installer, enabling easy installation of prebuilt Armbian images on the **Radxa Rock 5 ITX** board.

---

## Available Images

- **Minimal** – headless CLI/server setup
- **XFCE** – lightweight graphical desktop
- **Cinnamon** – full-featured modern desktop with backported MESA

All images are official Armbian builds, mirrored here for ROOBI compatibility.

---

##  How to Use with ROOBI

1. **Boot into ROOBI** on your Rock 5 ITX
2. Go to: `Advanced > Custom Image Source`
3. Enter the following URL:
```https://jackbinary.github.io/roobi-images/list.json```
4. Select one of the listed images and proceed with installation.

> **Note:** These definitions follow ROOBI’s JSON schema and use the `auto` install type. No user interaction is required after selection.

---

## Contributing

Pull requests are welcome! Feel free to open an issue if you'd like to request a specific image or help maintain support for other Radxa devices.

---

## Disclaimer

These are community-hosted definitions based on official Armbian builds. No warranties are provided. Use at your own risk.

For security, you are encouraged to verify the SHA or MD5 hashes of the downloaded `.img.xz` files against the official values provided at:

[https://www.armbian.com/radxa-rock-5-itx/](https://www.armbian.com/radxa-rock-5-itx/)

