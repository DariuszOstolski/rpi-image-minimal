# rpi-image-gen-example

Build a default system with auto login to the macmind user.

This has been tested on both ARM64 Mac and AMD64 Mac laptops.

AMD is much slower as expected due to emulation.

```bash
git clone git@github.com:DariuszOstolski/rpi-image-minimal.git
```

Build the rpi img

```bash
./build.sh
```

Locate the output image in the ./deploy directory

Use the Raspberry Pi Imager tool to install the img file on an SD card or USB stick
