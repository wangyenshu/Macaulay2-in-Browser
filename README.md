Macaulay2 in Browser

Screenshot:
![screenshot](screenshot.png)
How to build:

- clone this project
- delete "images" folder
- run `cd tools/docker/Macaulay2`
- run `./build.sh`
- run `./build-state.js`
- run `cd ../../../`
- run `make run`

Then, you can remove debian-9p-rootfs.tar

You may need tools/docker/Macaulay2/split.sh to split the debian-state-base.bin file.

Credit:
- Macaulay2: https://macaulay2.com/
- v86: https://github.com/copy/v86
- sandbox.bio's debian 12 on v86 configuration: https://github.com/sandbox-bio/v86
