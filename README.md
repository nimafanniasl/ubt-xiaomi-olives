## Xiaomi Redmi 8/8A Series Halium Patched Tree


## How to build

To manually build this project, follow these steps:
```bash
./build.sh -b bd  # bd is the name of the build directory
./build/prepare-fake-ota.sh out/device_olivelite.tar.xz ota
./build/system-image-from-ota.sh ota/ubuntu_command out
```
