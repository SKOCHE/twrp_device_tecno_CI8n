# TWRP device tree for Tecno Camon 19 Pro (CI8n) - A13


PRIVATE_BUILD_DESC="sys_tssi_64_tecno-user 13 TP1A.220624.014 366960 release-keys"

BUILD_FINGERPRINT := TECNO/CI8n-GL/TECNO-CI8n:13/TP1A.220624.014/230629V576:user/release-keys
```

## Status

Specs [here](https://www.gsmarena.com/tecno_camon_19_pro-11618.php)
MT6781 - Helio G96

## What's the history?
The tester [abaza92](https://4pda.to/forum/index.php?showuser=4591571) only install `boot-TECNO_CI8n-A13-noCrypt.img` test file to know if TWRP can start.

This branch A13 not have encrypt/decrypt process and files. So the process to backup Data have vendor.img ***encryptable***.

![Tecno Camon 19 Pro](https://fdn2.gsmarena.com/vv/pics/tecno/tecno-camon-19-pro-2.jpg)


---------------
## Building

```bash
source build/envsetup.sh
lunch twrp_CI8n-eng
mka bootimage
```
-------------

