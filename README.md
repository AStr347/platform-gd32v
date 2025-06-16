# GigaDevice GD32V: development platform for [PlatformIO](https://platformio.org)

# Usage

1. [Install PlatformIO](https://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](https://docs.platformio.org/page/projectconf.html) file:

## platformio.ini

```ini
[env:development]
platform = https://github.com/AStr347/platform-gd32v.git
board = sipeed-longan-nano
debug_tool = sipeed-rv-debugger
upload_protocol = sipeed-rv-debugger
...
```

# Dist

* tool-openocd-gd32v-v0.1.1-win 	- patched sipeed-rv-debugger.cfg ignore 'ftdi_device_desc "Dual RS232"'
* tool-openocd-gd32v-v0.1.1-linux 	- patched sipeed-rv-debugger.cfg ignore 'ftdi_device_desc "Dual RS232"'
