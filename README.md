# Pelion-GR-LYCHEE-camera

Web app to view photos took by GR-LYCHEE via Pelion Device Management.

## Prerequisites
* [GR-LYCHEE](https://os.mbed.com/platforms/Renesas-GR-LYCHEE/) with camera and [this firmware](https://os.mbed.com/users/coisme/code/Pelion-GR-LYCHEE-camera-firmware/)
* Pelion Device Management API Key ([Generating an API key](https://cloud.mbed.com/docs/v2.1/integrate-web-app/api-keys.html))

## How to use

1. Open https://coisme.github.io/Pelion-GR-LYCHEE-camera/.
1. Input your API key and click the **CONNECT** button. Then you'll see the online devices associated with your account.
1. Select your GR-LYCHEE from the connected devices list and click the **SELECT DEVICE** button.
1. Click the **CAPTURE** button, then you'll get a photo from your GR-LYCHEE!

**Note: you can open only 1 channel per 1 API key. Don't open more than 2 pages by 1 API key.**

This web UI is tested on
* Safari on Mac
* Safari on iPhone
* Chrome on Mac

If you'd like to run the page at your local machine, use Chrome with `--args -allow-file-access-from-files` option. For example on Mac,
```
$ open -a Google\ Chrome --args -allow-file-access-from-files
```
