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


