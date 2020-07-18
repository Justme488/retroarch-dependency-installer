# retroarch-dependency-installer

## This will install the needed dependencies for [_build-retroarch_](https://github.com/Justme488/build-retroarch) script
* Tested with Linux Mint 20
* _Should_ work with ubuntu

### Executes the following commands:
* apt-get update
* apt-get build-dep -y retroarch
* apt-get install -y git
* apt-get install -y nasm
* apt-get install -y cmake
* apt-get install -y libboost-all-dev
* apt-get install -y gcc-7
* apt-get install -y g++-7
