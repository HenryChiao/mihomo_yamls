# url 里填写自己的订阅,名称不能重复
proxy-providers:
  provider1:
    url: ""
    type: http
    interval: 86400
    health-check: {enable: true,url: "https://www.gstatic.com/generate_204",interval: 300}
    override:
      additional-prefix: "[provider1]"

  provider2:
    url: ""
    type: http
    interval: 86400
    health-check: {enable: true,url: "https://www.gstatic.com/generate_204",interval: 300}
    override:
      additional-prefix: "[provider2]"

proxies: 
  - name: "直连"
    type: direct
    udp: true

mixed-port: 7890
ipv6: true
allow-lan: true
unified-delay: false
tcp-concurrent: true
external-controller: 127.0.0.1:9090
external-ui: ui
external-ui-url: "https://github.com/MetaCubeX/metacubexd/archive/refs/heads/gh-pages.zip"

find-process-mode: strict
global-client-fingerprint: chrome

profile:
  store-selected: true
  store-fake-ip: true

sniffer:
  enable: true
  sniff:
    HTTP:
      ports: [80, 8080-8880]
      override-destination: true
    TLS:
      ports: [443, 8443]
    QUIC:
      ports: [443, 8443]
  skip-domain:
    - "Mijia Cloud"
    - "+.push.apple.com"

tun:
  enable: true
  stack: mixed
  dns-hijack:
    - "any:53"
    - "tcp://any:53"
  auto-route: true
  auto-redirect: true
  auto-detect-interface: true

dns:
  enable: true
  ipv6: true
  enhanced-mode: fake-ip
  fake-ip-filter:
    - "*"
    - "+.lan"
    - "+.local"
    - "+.market.xiaomi.com"
  default-nameserver:
    - tls://223.5.5.5
    - tls://223.6.6.6
  nameserver:
    - https://doh.pub/dns-query
    - https://dns.alidns.com/dns-query

proxy-groups:

  - name: 默认
    type: select
    proxies: [自动选择,直连,香港,台湾,日本,新加坡,美国,其它地区,全部节点]

  - name: Google
    type: select
    proxies: [默认,香港,台湾,日本,新加坡,美国,其它地区,全部节点,自动选择,直连]

  - name: Telegram
    type: select
    proxies: [默认,香港,台湾,日本,新加坡,美国,其它地区,全部节点,自动选择,直连]

  - name: Twitter
    type: select
    proxies: [默认,香港,台湾,日本,新加坡,美国,其它地区,全部节点,自动选择,直连]

  - name: 哔哩哔哩
    type: select
    proxies: [默认,香港,台湾,日本,新加坡,美国,其它地区,全部节点,自动选择,直连]

  - name: 巴哈姆特
    type: select
    proxies: [默认,香港,台湾,日本,新加坡,美国,其它地区,全部节点,自动选择,直连]

  - name: YouTube
    type: select
    proxies: [默认,香港,台湾,日本,新加坡,美国,其它地区,全部节点,自动选择,直连]

  - name: NETFLIX
    type: select
    proxies: [默认,香港,台湾,日本,新加坡,美国,其它地区,全部节点,自动选择,直连]

  - name: Spotify
    type: select
    proxies:  [默认,香港,台湾,日本,新加坡,美国,其它地区,全部节点,自动选择,直连]

  - name: Github
    type: select
    proxies:  [默认,香港,台湾,日本,新加坡,美国,其它地区,全部节点,自动选择,直连]

  - name: 国内
    type: select
    proxies:  [直连,默认,香港,台湾,日本,新加坡,美国,其它地区,全部节点,自动选择]

  - name: 其他
    type: select
    proxies:  [默认,香港,台湾,日本,新加坡,美国,其它地区,全部节点,自动选择,直连]

  #分隔,下面是地区分组
  - name: 香港
    type: select
    include-all: true
    exclude-type: direct
    filter: "(?i)港|hk|hongkong|hong kong"

  - name: 台湾
    type: select
    include-all: true
    exclude-type: direct
    filter: "(?i)台|tw|taiwan"

  - name: 日本
    type: select
    include-all: true
    exclude-type: direct
    filter: "(?i)日|jp|japan"

  - name: 美国
    type: select
    include-all: true
    exclude-type: direct
    filter: "(?i)美|us|unitedstates|united states"

  - name: 新加坡
    type: select
    include-all: true
    exclude-type: direct
    filter: "(?i)(新|sg|singapore)"

  - name: 其它地区
    type: select
    include-all: true
    exclude-type: direct
    filter: "(?i)^(?!.*(?:🇭🇰|🇯🇵|🇺🇸|🇸🇬|🇨🇳|港|hk|hongkong|台|tw|taiwan|日|jp|japan|新|sg|singapore|美|us|unitedstates)).*"

  - name: 全部节点
    type: select
    include-all: true
    exclude-type: direct

  - name: 自动选择
    type: url-test
    include-all: true
    exclude-type: direct
    tolerance: 10

rules:
  - RULE-SET,private_ip,直连,no-resolve
  - RULE-SET,github_domain,Github
  - RULE-SET,twitter_domain,Twitter
  - RULE-SET,youtube_domain,YouTube
  - RULE-SET,google_domain,Google
  - RULE-SET,telegram_domain,Telegram
  - RULE-SET,netflix_domain,NETFLIX
  - RULE-SET,bilibili_domain,哔哩哔哩
  - RULE-SET,bahamut_domain,巴哈姆特
  - RULE-SET,spotify_domain,Spotify
  - RULE-SET,cn_domain,国内
  - RULE-SET,geolocation-!cn,其他

  - RULE-SET,google_ip,Google
  - RULE-SET,netflix_ip,NETFLIX
  - RULE-SET,telegram_ip,Telegram
  - RULE-SET,twitter_ip,Twitter
  - RULE-SET,cn_ip,国内
  - MATCH,其他

rule-anchor:
  ip: &ip {type: http, interval: 86400, behavior: ipcidr, format: mrs}
  domain: &domain {type: http, interval: 86400, behavior: domain, format: mrs}
rule-providers:
  private_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/private.mrs"
  cn_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/cn.mrs"
  biliintl_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/biliintl.mrs"
  ehentai_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/ehentai.mrs"
  github_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/github.mrs"
  twitter_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/twitter.mrs"
  youtube_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/youtube.mrs"
  google_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/google.mrs"
  telegram_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/telegram.mrs"
  netflix_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/netflix.mrs"
  bilibili_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/bilibili.mrs"
  bahamut_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/bahamut.mrs"
  spotify_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/spotify.mrs"
  pixiv_domain:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/pixiv.mrs"
  geolocation-!cn:
    <<: *domain
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geosite/geolocation-!cn.mrs"

  private_ip:
    <<: *ip
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geoip/private.mrs"
  cn_ip:
    <<: *ip
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geoip/cn.mrs"
  google_ip:
    <<: *ip
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geoip/google.mrs"
  netflix_ip:
    <<: *ip
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geoip/netflix.mrs"
  twitter_ip:
    <<: *ip
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geoip/twitter.mrs"
  telegram_ip:
    <<: *ip
    url: "https://raw.githubusercontent.com/MetaCubeX/meta-rules-dat/meta/geo/geoip/telegram.mrs"