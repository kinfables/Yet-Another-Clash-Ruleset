# Yet-Another-Clash-Ruleset
A classical type of ruleset for Clash (based on lhie1's rules).
## How to use

<details>
  <summary>Write the following configuration file to the profile (click to expand)</summary>

```yaml
rule-providers:
  AdBlock:
    type: file
    behavior: classical
    path: ./providers/rules/adblock.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/adblock.yaml
    interval: 86400
  Special:
    type: file
    behavior: classical
    path: ./providers/rules/special.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/special.yaml
    interval: 86400
  AsianTV:
    type: file
    behavior: classical
    path: ./providers/rules/asiantv.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/asiantv.yaml
    interval: 86400
  GlobalTV:
    type: file
    behavior: classical
    path: ./providers/rules/globaltv.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/globaltv.yaml
    interval: 86400
  Netflix:
    type: file
    behavior: classical
    path: ./providers/rules/netflix.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/netflix.yaml
    interval: 86400
  Spotify:
    type: file
    behavior: classical
    path: ./providers/rules/spotify.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/spotify.yaml
    interval: 86400
  Telegram:
    type: file
    behavior: classical
    path: ./providers/rules/telegram.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/telegram.yaml
    interval: 86400
  Steam:
    type: file
    behavior: classical
    path: ./providers/rules/steam.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/steam.yaml
    interval: 86400
  Speedtest:
    type: file
    behavior: classical
    path: ./providers/rules/speedtest.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/speedtest.yaml
    interval: 86400
  PayPal:
    type: file
    behavior: classical
    path: ./providers/rules/paypal.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/paypal.yaml
    interval: 86400
  Microsoft:
    type: file
    behavior: classical
    path: ./providers/rules/microsoft.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/microsoft.yaml
    interval: 86400
  Netease Music:
    type: file
    behavior: classical
    path: ./providers/rules/neteasemusic.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/neteasemusic.yaml
    interval: 86400
  Proxy:
    type: file
    behavior: classical
    path: ./providers/rules/proxy.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/proxy.yaml
    interval: 86400
  Domestic:
    type: file
    behavior: classical
    path: ./providers/rules/domestic.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/domestic.yaml
    interval: 86400
  Apple:
    type: file
    behavior: classical
    path: ./providers/rules/apple.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/apple.yaml
    interval: 86400
  LAN:
    type: file
    behavior: classical
    path: ./providers/rules/lan.yaml
    url: https://raw.githubusercontent.com/kinfables/Yet-Another-Clash-Ruleset/master/ruleset/lan.yaml
    interval: 86400

rules:
  - RULE-SET,AdBlock,AdBlock
  - RULE-SET,Special,DIRECT
  - RULE-SET,AsianTV,AsianTV
  - RULE-SET,GlobalTV,GlobalTV
  - RULE-SET,Netflix,Netflix
  - RULE-SET,Spotify,Spotify
  - RULE-SET,Telegram,Telegram
  - RULE-SET,Steam,Steam
  - RULE-SET,Speedtest,Speedtest
  - RULE-SET,Microsoft,Microsoft
  - RULE-SET,Netease Music,Netease Music
  - RULE-SET,Proxy,Proxy
  - RULE-SET,Domestic,Domestic
  - RULE-SET,Apple,Apple
  - RULE-SET,LAN,DIRECT
  - GEOIP,CN,Domestic
  - MATCH,Others
```
</details>

## Thanks
- [lhie1](https://github.com/lhie1/Rules) / rules
- [Dreamacro](https://github.com/Dreamacro/clash) / Clash

## Reference
- https://lancellc.gitbook.io/clash/clash-config-file/rule-provider

## LICENSE
GPL-3.0
