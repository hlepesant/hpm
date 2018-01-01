# Hashicorp Products Manager

Claim to do the job as [chtf](https://github.com/Yleisradio/homebrew-terraforms) do for MacOS X with homebrew,  
but want to support many products from [Hashicorp](https://www.hashicorp.com/).

## Install

```shell
cd ~
git clone https://github.com/hlepesant/hpm.git
mkdir ~/bin
mv hpm/hpm.linux ~/bin/hpm
chmod u+x ~/bin/hpm
```

## Usage

### Install specific terraform release
```shell
hpm terraform 0.11.1
```

### List installed releases of terraform
```shell
hpm terraform
   0.8.8
 * 0.11.1

To get avaliable releases check this link :
 - https://releases.hashicorp.com/terraform/

```

## Supported Products

* [terraform](https://www.terraform.io/)
* [vault](https://www.vaultproject.io/)
* [consul](https://www.consul.io/)
* [packer](https://www.packer.io/)
* [nomad](https://www.nomadproject.io/)
* [serf](https://www.serf.io/)
* [sentinel](https://www.hashicorp.com/sentinel)


## Supported Operating Systems

* GNU/Linux : tested on [Debian](https://www.debian.org/) ans [Ubuntu](https://www.ubuntu.com/)
* FreeBSD   : tested on [FreeBSD](https://www.freebsd.org/)
* Solaris   : tested on [OmniOS](https://omnios.omniti.com/)

