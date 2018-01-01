# Hashicorp Product Manager

Claim to do the job as [chtf](https://github.com/Yleisradio/homebrew-terraforms) do for MacOS X with homebrew,
but want to support many products from [Hashicopr](https://www.hashicorp.com/)

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
```

## Supported Products


* [terraform](https://www.terraform.io/)
* [vault](https://www.vaultproject.io/)
* [consul](https://www.consul.io/)
* [packer](https://www.packer.io/)
* [nomad](https://www.nomadproject.io/)
* [serf](https://www.serf.io/)
* [sentinel](https://www.hashicorp.com/sentinel)


