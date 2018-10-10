
环境变量： CONFIG_JSON（配置）、

用notepad++将上述变量中 \r\n 替换为\\n，变成一行，导入容器。
客户端： android Actinium、windows v2ray 可用同一个服务端。

{
  "log": {
    "loglevel": "warning"
  },
  "inbound": {
    "protocol": "vmess",
    "port": 8080,
    "settings": {
      "clients": [
        {
          "id": "2df3f75c-cd41-40e4-9cd6-d9b3a1465e10",
          "alterId": 64,
          "security": "aes-128-gcm"
        }
      ]
    },
    "streamSettings": {
      "network": "ws"
    }
  },
  "inboundDetour": [],
  "outbound": {
    "protocol": "freedom",
   "settings": {}
  }
}


