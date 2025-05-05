# Build PiCommOS from Source

## Requirements
- Debian/Ubuntu Linux host or VM
- git, debootstrap, qemu-user-static, gpg

## Instructions

1. Clone the repo:

    git clone https://github.com/ReclaimingTheImage/PiCommOS.git  
    cd PiCommOS

2. Run the build script:

    sudo ./build_image.sh

3. Flash the resulting `.img` file using Balena Etcher.
