# openwrt
openwrt 操作手册

newifi mini 参考：https://github.com/bettermanbao/openwrt-shadowsocksR-libev-full/releases

## 方法一

https://github.com/bettermanbao/openwrt-shadowsocksR-libev-full/tree/master

lede-17.01.1-ramips-mt7620-shadowsocksr-libev.zip

```shell
opkg install --force-overwrite shadowsocksr-libev-gfwlist_v20170613-1pre_mipsel_24kc.ipk
```

## 方法二：

https://github.com/ywb94/openwrt-ssr

软件包包含 shadowsocksr-libev 的可执行文件,以及luci控制界面

```shell
opkg install luci-app-shadowsocksR-GFW_1.2.1_all.ipk
```
