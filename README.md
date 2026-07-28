# 5586L\_FUR9.2\_OpenSourceSoftware

## Environment
Individual build components may list different versions of Ubuntu for compilation in their respective README or build instruction files.
However, all components were compiled successfully on Ubuntu 22.04 (jammy).

### Preparing your Ubuntu environment
Run the following commands:
```
sudo apt-get update
sudo apt-get install build-essential cmake-data docker.io docker-buildx libglib2.0-dev meson ninja-build pkg-config
```

You may also want to add your user to the docker group (`adduser <username> docker`), and log out
and back in. This will remove the need to run docker commands via sudo.

## Build Instructions 
After downloading the tarball, run the following commands:
```
tar xzf 5586L_FUR9.2.tar.gz 
cd 5586L_FUR9.2
./build.sh all
```

Further instructions for the contents of the tarball can be found in its included README.

Download the tarball here: 
https://d2mi77xcznxniv.cloudfront.net/index.html?file=5586L_FUR9.2.tar.gz

