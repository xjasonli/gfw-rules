# gfw-rules
GFW rules in multiple formats

## geosite.dat
V2ray geosite file as a drop-in replacement of the official version.
URL: https://raw.githubusercontent.com/xjasonli/gfw-rules/master/geosite.dat

```json
      {
        "type": "field",
        "domain": ["geosite:geolocation-!cn"],
        "outboundTag": "o.proxy"
      },
      {
        "type": "field",
        "domain": ["geosite:category-ads"],
        "outboundTag": "o.block"
      },
      {
        "type": "field",
        "domain": ["geosite:cn"],
        "outboundTag": "o.direct"
      }
      // default o.proxy
```

## shadowrocket.conf
Shadowrocket(iOS App) rule.
URL: https://raw.githubusercontent.com/xjasonli/gfw-rules/master/shadowrocket.conf
