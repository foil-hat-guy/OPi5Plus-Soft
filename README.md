# Extra software repository for Orange Pi 5 Plus

## Description:

This repository contains some software packages for Orange Pi 5 Plus SBC.
It is ment to be used with Debian OS. Some packages are too old in the Debian
repository, some do not avaliable for arm64 architecture and you have to 
build them from source. Or you can download them and install from this repository.


## Installation:

1. Download a gpg key for the repository:
```sh
wget -qO - https://foil-hat-guy.github.io/OPi5Plus-Soft/PUBLIC.KEY | sudo tee /etc/apt/trusted.gpg.d/OPi5Plus-Soft.asc
```

2. Add the repository tp the repository list.
```sh
printf "\ndeb https://foil-hat-guy.github.io/OPi5Plus-Soft/ bookworm contrib \n" | sudo tee --append /etc/apt/sources.list 
```

## Usage:

To install packages use your standard Debian package manager: apt or synaptic.
