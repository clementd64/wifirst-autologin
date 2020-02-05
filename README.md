# wifirst-autologin
Autologin to wifirst network

## Usage

> Require `wget` with https support. See below for OpenWrt install steps

```sh
sh wifirst-autologin.sh LOGIN PASSWORD
```

Add a cron for auto login

## Install on OpenWrt

You need to update `wget` and install https support

```sh
opkg update && opkg install wget ca-certificates libustream-openssl
```