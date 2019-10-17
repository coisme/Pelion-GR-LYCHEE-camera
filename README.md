# Pelion-GR-LYCHEE-camera

Web app to view photos took by GR-LYCHEE or GR-PEACH via Pelion Device Management.

## Prerequisites
* Pelion Device Management account
* Pelion Device Management API Key ([Generating an API key](https://cloud.mbed.com/docs/v2.1/integrate-web-app/api-keys.html))
* [GR-LYCHEE](https://os.mbed.com/platforms/Renesas-GR-LYCHEE/) with camera module(https://os.mbed.com/users/coisme/code/Pelion-GR-LYCHEE-camera-firmware/) or [GR-PEACH](https://os.mbed.com/platforms/Renesas-GR-PEACH/) with [Wireless CAMERA SHIELD](https://www.core.co.jp/product/m2m/gr-peach/audio-camera.html)
* GR-LYCHEE/GR-PEACH firmware: [Pelion GR-LYCHEE camera firmware](https://os.mbed.com/users/coisme/code/Pelion-GR-LYCHEE-camera-firmware/)


## Stable Version

The master branch is always under development and must be used with the latest firmware. If you need a stable version, fork this repository and deploy by yourself with a specific release combination.

| Webapp | [Firmware](https://os.mbed.com/users/coisme/code/Pelion-GR-LYCHEE-camera-firmware/) |
| :--- | :--- |
| master | tip |
|v1.1|v1.3|
|v1.0.0|v1.0.0|


## How to use

1. Open https://coisme.github.io/Pelion-GR-LYCHEE-camera/.
1. Input your API key and click the **CONNECT** button. Then you'll see the online devices associated with your account.
1. Select your GR-LYCHEE/PEACH from the connected devices list and click the **SELECT DEVICE** button.
1. Click the **CAPTURE** button, then you'll get a photo from your GR-LYCHEE/PEACH!

**Note: you can open only 1 channel per 1 API key. Don't open more than 2 pages by 1 API key.**
