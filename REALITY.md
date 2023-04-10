1. 安装Xray

```
bash -c "$(curl -L https://github.com/XTLS/Xray-install/raw/main/install-release.sh)" @ install --beta
```

2. 下载配置

VLESS-XTLS-uTLS-REALITY

```
curl -Lo /usr/local/etc/xray/h2.json https://raw.githubusercontent.com/123Diego/tools/main/VLESS-H2-uTLS-REALITY/config_server.json
```

```
curl -Lo /usr/local/etc/xray/re.json https://raw.githubusercontent.com/123Diego/tools/main/VLESS-XTLS-uTLS-REALITY/config_server.json
```

3. 启动程序

```
systemctl restart xray && sleep 0.2 && systemctl status xray
```


# 域名推荐
```
gateway.icloud.com
itunes.apple.com
download-installer.cdn.mozilla.net
airbnb【这个不同的区有不同的域名建议自己搜索】
addons.mozilla.org
www.microsoft.com
www.lovelive-anime.jp
```

# CDN
```
Apple:
swdist.apple.com
swcdn.apple.com
updates.cdn-apple.com
mensura.cdn-apple.com
osxapps.itunes.apple.com
aod.itunes.apple.com
```

```
Microsoft:
cdn-dynmedia-1.microsoft.com
update.microsoft
software.download.prss.microsoft.com
```

```
Amazon:
s0.awsstatic.com
d1.awsstatic.com
images-na.ssl-images-amazon.com
m.media-amazon.com
player.live-video.net
```

```
Google:
dl.google.com
```
