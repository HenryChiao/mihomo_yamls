# 📂 通用进阶配置 (General Config)

[🔙 返回主页](../README.md)

> 🤖 自动技术分析 | 24 个配置文件

## ⚔️ 配置横向对比

| 特性 | `AIB.yaml` | `AIO.yaml` | `MihomoPro_Config.yaml` | `OneTouch_Config.yaml` | `clash-fallback-dialer.yaml` | `clash-fallback-std.yaml` | `clash-fallback.yaml` | `clash-all-fallback.yaml` | `clash-fallback-all.yaml` | `Clash.yaml` | `config.yaml` | `MihomoAIO.yaml` | `MihomoProMax.yaml` | `MihomoProPlus.yaml` | `ConfigForClash.yaml` | `mihomo.yaml` | `config.yaml` | `Clash_Sample.yaml` | `config.yaml` | `configfull_NoAd.yaml` | `configfull_lite.yaml` | `configfull.yaml` | `mihomo_single.yaml` | `mihomo_multi.yaml` |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **大小** | 11.0 KB | 11.1 KB | 22.6 KB | 12.4 KB | 16.3 KB | 17.3 KB | 15.9 KB | 17.2 KB | 18.6 KB | 27.3 KB | 27.5 KB | 30.1 KB | 27.5 KB | 28.0 KB | 49.3 KB | 17.8 KB | 13.8 KB | 12.5 KB | 12.8 KB | 33.5 KB | 17.5 KB | 33.9 KB | 17.8 KB | 18.1 KB |
| **混合端口** | 7890 | 7890 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7893 | 7890 | 7890 | 7893 | 7893 | 7893 | 7892 | 0 | 7890 | 7892 | 7890 | 7890 | 7890 | 7890 | 7897 | 7897 |
| **面板地址** | 0.0.0.0:9090 | 0.0.0.0:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | :9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 127.0.0.1:9090 | 0.0.0.0:9090 | 127.0.0.1:9090 | :9090 | 0.0.0.0:9090 | - | 0.0.0.0:9090 | 0.0.0.0:9090 | 0.0.0.0:9090 | - | - |
| **运行模式** | rule | rule | rule | rule | rule | rule | rule | rule | rule | Rule | rule | rule | rule | rule | rule | rule | rule | rule | rule | rule | rule | rule | rule | rule |
| **TUN 模式** | ✅ | ✅ | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **策略组** | **24** | **24** | **52** | **15** | **35** | **36** | **34** | **53** | **61** | **27** | **96** | **61** | **54** | **54** | **62** | **31** | **29** | **22** | **26** | **59** | **47** | **62** | **55** | **55** |
| **规则数** | **34** | **34** | **40** | **23** | **43** | **43** | **43** | **42** | **53** | **68** | **30** | **52** | **45** | **44** | **62** | **34** | **33** | **25** | **23** | **95** | **38** | **96** | **27** | **27** |

## 📄 配置详情

### 👤 666OS

#### 📝 MihomoPro_Config.yaml
- **路径**: `666OS/MihomoPro_Config.yaml` | **大小**: 22.6 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/666OS/MihomoPro_Config.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (52个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 🔧 故障转移 | `fallback` |
| 👆 国外流量 | `select` |
| 👆 国内流量 | `select` |
| 👆 兜底流量 | `select` |
| 👆 直接连接 | `select` |
| 👆 网络测试 | `select` |
| 👆 抖快书定位 | `select` |
| 👆 Emby服 | `select` |
| 👆 油管视频 | `select` |
| 👆 奈飞视频 | `select` |
| 👆 国际媒体 | `select` |
| 👆 新闻媒体 | `select` |
| 👆 电报消息 | `select` |
| 👆 推特社交 | `select` |
| 👆 社交平台 | `select` |
| 👆 人工智能 | `select` |
| 👆 货币平台 | `select` |
| 👆 游戏平台 | `select` |
| 👆 微软服务 | `select` |
| ... | 还有 32 个 |
</details>

#### 📝 OneTouch_Config.yaml
- **路径**: `666OS/OneTouch_Config.yaml` | **大小**: 12.4 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/666OS/OneTouch_Config.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (15个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 一键连 | `select` |
| 🔧 故障转移 | `fallback` |
| 👆 人工智能 | `select` |
| 👆 社交平台 | `select` |
| 👆 国际媒体 | `select` |
| 👆 国内流量 | `select` |
| 👆 手动选择 | `select` |
| 👆 直接连接 | `select` |
| ♻️ 香港自动 | `url-test` |
| ♻️ 台湾自动 | `url-test` |
| ♻️ 日本自动 | `url-test` |
| ♻️ 狮城自动 | `url-test` |
| ♻️ 韩国自动 | `url-test` |
| ♻️ 美国自动 | `url-test` |
| ♻️ 欧洲自动 | `url-test` |
</details>

---

### 👤 ClashConnectRules

#### 📝 Clash.yaml
- **路径**: `ClashConnectRules/Clash.yaml` | **大小**: 27.3 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/ClashConnectRules/Clash.yaml)
- **模式**: Rule | **TUN**: 🚫 | **IPv6**: 🚫
<details>
<summary>🔍 策略组 (27个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 🚀 节点选择 | `select` |
| 👆 🚀 手动切换 | `select` |
| ♻️ ♻️ 自动选择 | `url-test` |
| 👆 🇭🇰 Hong Kong | `select` |
| 👆 🇯🇵 Japan | `select` |
| 👆 🇺🇸 United States | `select` |
| 👆 🇸🇬 Singapore | `select` |
| 👆 🇹🇼 Taiwan | `select` |
| 👆 🇰🇷 Korea | `select` |
| 👆 🇬🇧 United Kingdom | `select` |
| 👆 🇩🇪 Germany | `select` |
| 👆 🇫🇷 France | `select` |
| 👆 🌍 Other Regions | `select` |
| 👆 🌐 国际流量 | `select` |
| 👆 🎯 国内流量 | `select` |
| 👆 🚫 国内广告 | `select` |
| 👆 🚫 国外广告 | `select` |
| 👆 🤖 AI服务 | `select` |
| 👆 📹 YouTube | `select` |
| 👆 Ⓜ️ 微软服务 | `select` |
| ... | 还有 7 个 |
</details>

---

### 👤 HenryChiao

#### 📝 MihomoAIO.yaml
- **路径**: `HenryChiao/MihomoAIO.yaml` | **大小**: 30.1 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/HenryChiao/MihomoAIO.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (61个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 🔧 故障转移 | `fallback` |
| 👆 国外流量 | `select` |
| 👆 国内流量 | `select` |
| 👆 兜底流量 | `select` |
| 👆 直接连接 | `select` |
| 👆 网络测试 | `select` |
| 👆 UKwifi | `select` |
| 👆 抖快书定位 | `select` |
| 👆 Emby服 | `select` |
| 👆 油管视频 | `select` |
| 👆 奈飞视频 | `select` |
| 👆 迪士尼+ | `select` |
| 👆 Max | `select` |
| 👆 Prime Video | `select` |
| 👆 Apple TV+ | `select` |
| 👆 TikTok | `select` |
| 👆 哔哩哔哩 | `select` |
| 👆 Spotify | `select` |
| 👆 国外媒体 | `select` |
| ... | 还有 41 个 |
</details>

#### 📝 MihomoProMax.yaml
- **路径**: `HenryChiao/MihomoProMax.yaml` | **大小**: 27.5 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/HenryChiao/MihomoProMax.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (54个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 🔧 故障转移 | `fallback` |
| 👆 国外流量 | `select` |
| 👆 国内流量 | `select` |
| 👆 兜底流量 | `select` |
| 👆 直接连接 | `select` |
| 👆 网络测试 | `select` |
| 👆 UKwifi | `select` |
| 👆 抖快书定位 | `select` |
| 👆 Emby服 | `select` |
| 👆 油管视频 | `select` |
| 👆 奈飞视频 | `select` |
| 👆 国际媒体 | `select` |
| 👆 新闻媒体 | `select` |
| 👆 电报消息 | `select` |
| 👆 推特社交 | `select` |
| 👆 社交平台 | `select` |
| 👆 人工智能 | `select` |
| 👆 货币平台 | `select` |
| 👆 游戏平台 | `select` |
| ... | 还有 34 个 |
</details>

#### 📝 MihomoProPlus.yaml
- **路径**: `HenryChiao/MihomoProPlus.yaml` | **大小**: 28.0 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/HenryChiao/MihomoProPlus.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (54个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 默认代理 | `select` |
| 🔧 故障转移 | `fallback` |
| 👆 国外流量 | `select` |
| 👆 国内流量 | `select` |
| 👆 兜底流量 | `select` |
| 👆 直接连接 | `select` |
| 👆 网络测试 | `select` |
| 👆 UKwifi | `select` |
| 👆 抖快书定位 | `select` |
| 👆 Emby服 | `select` |
| 👆 油管视频 | `select` |
| 👆 奈飞视频 | `select` |
| 👆 国际媒体 | `select` |
| 👆 新闻媒体 | `select` |
| 👆 电报消息 | `select` |
| 👆 推特社交 | `select` |
| 👆 社交平台 | `select` |
| 👆 人工智能 | `select` |
| 👆 货币平台 | `select` |
| 👆 游戏平台 | `select` |
| ... | 还有 34 个 |
</details>

---

### 👤 JohnsonRan

#### 📝 AIB.yaml
- **路径**: `JohnsonRan/AIB.yaml` | **大小**: 11.0 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/JohnsonRan/AIB.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (24个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 节点选择 | `select` |
| 🔧 自动选择 | `fallback` |
| 👆 Speedtest | `select` |
| 👆 Emby | `select` |
| 👆 AI | `select` |
| 👆 Steam | `select` |
| 👆 Apple | `select` |
| 👆 Github | `select` |
| 👆 Telegram | `select` |
| 👆 Google | `select` |
| 👆 YouTube | `select` |
| 👆 Tracker | `select` |
| 👆 Porns | `select` |
| 👆 Bilibili | `select` |
| 👆 Microsoft | `select` |
| 👆 ADBlock | `select` |
| 👆 MATCH | `select` |
| ♻️ 香港 | `url-test` |
| ♻️ 美国 | `url-test` |
| ♻️ 新加坡 | `url-test` |
| ... | 还有 4 个 |
</details>

#### 📝 AIO.yaml
- **路径**: `JohnsonRan/AIO.yaml` | **大小**: 11.1 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/JohnsonRan/AIO.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (24个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 节点选择 | `select` |
| 👆 自建 | `select` |
| 👆 代理链 | `select` |
| 👆 Speedtest | `select` |
| 👆 Emby | `select` |
| 👆 AI | `select` |
| 👆 Steam | `select` |
| 👆 Apple | `select` |
| 👆 Github | `select` |
| 👆 Telegram | `select` |
| 👆 Google | `select` |
| 👆 YouTube | `select` |
| 👆 Tracker | `select` |
| 👆 Porns | `select` |
| 👆 Bilibili | `select` |
| 👆 Microsoft | `select` |
| 👆 ADBlock | `select` |
| 👆 MATCH | `select` |
| ♻️ 香港 | `url-test` |
| ♻️ 美国 | `url-test` |
| ... | 还有 4 个 |
</details>

---

### 👤 Lanlan13-14

#### 📝 configfull_NoAd.yaml
- **路径**: `Lanlan13-14/configfull_NoAd.yaml` | **大小**: 33.5 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/Lanlan13-14/configfull_NoAd.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (59个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 节点选择 | `select` |
| 👆 YouTube | `select` |
| 👆 FCM | `select` |
| 👆 GoogleVPN | `select` |
| 👆 Google | `select` |
| 👆 Meta | `select` |
| 👆 AI | `select` |
| 👆 GitHub | `select` |
| 👆 OneDrive | `select` |
| 👆 Microsoft | `select` |
| 👆 Telegram | `select` |
| 👆 Discord | `select` |
| 👆 Talkatone | `select` |
| 👆 LINE | `select` |
| 👆 Signal | `select` |
| 👆 TikTok | `select` |
| 👆 NETFLIX | `select` |
| 👆 DisneyPlus | `select` |
| 👆 HBO | `select` |
| 👆 Primevideo | `select` |
| ... | 还有 39 个 |
</details>

#### 📝 configfull_lite.yaml
- **路径**: `Lanlan13-14/configfull_lite.yaml` | **大小**: 17.5 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/Lanlan13-14/configfull_lite.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (47个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 节点选择 | `select` |
| 👆 YouTube | `select` |
| 👆 Google | `select` |
| 👆 Meta | `select` |
| 👆 AI | `select` |
| 👆 GitHub | `select` |
| 👆 OneDrive | `select` |
| 👆 Microsoft | `select` |
| 👆 Telegram | `select` |
| 👆 TikTok | `select` |
| 👆 NETFLIX | `select` |
| 👆 DisneyPlus | `select` |
| 👆 HBO | `select` |
| 👆 Apple | `select` |
| 👆 Emby | `select` |
| 👆 哔哩哔哩 | `select` |
| 👆 哔哩东南亚 | `select` |
| 👆 巴哈姆特 | `select` |
| 👆 Spotify | `select` |
| 👆 国内媒体 | `select` |
| ... | 还有 27 个 |
</details>

#### 📝 configfull.yaml
- **路径**: `Lanlan13-14/configfull.yaml` | **大小**: 33.9 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/Lanlan13-14/configfull.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (62个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 节点选择 | `select` |
| 👆 YouTube | `select` |
| 👆 FCM | `select` |
| 👆 GoogleVPN | `select` |
| 👆 Google | `select` |
| 👆 Meta | `select` |
| 👆 AI | `select` |
| 👆 GitHub | `select` |
| 👆 OneDrive | `select` |
| 👆 Microsoft | `select` |
| 👆 Telegram | `select` |
| 👆 Discord | `select` |
| 👆 Talkatone | `select` |
| 👆 LINE | `select` |
| 👆 Signal | `select` |
| 👆 TikTok | `select` |
| 👆 NETFLIX | `select` |
| 👆 DisneyPlus | `select` |
| 👆 HBO | `select` |
| 👆 Primevideo | `select` |
| ... | 还有 42 个 |
</details>

---

### 👤 echs-top

#### 📝 mihomo.yaml
- **路径**: `echs-top/mihomo.yaml` | **大小**: 17.8 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/echs-top/mihomo.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (31个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 PROXY | `select` |
| 👆 PROXYDNS | `select` |
| 👆 AD | `select` |
| 👆 SPEEDTEST | `select` |
| 👆 FCM | `select` |
| 👆 BOTTEST | `select` |
| 👆 TELEGRAM | `select` |
| 👆 META | `select` |
| 👆 TWITTER | `select` |
| 👆 TIKTOK | `select` |
| 👆 NETFLIX | `select` |
| 👆 SPOTIFY | `select` |
| 👆 BILIBILI | `select` |
| 👆 YOUTUBE | `select` |
| 👆 AI | `select` |
| 👆 PIXIV | `select` |
| 👆 GITHUB | `select` |
| 👆 ONEDRIVE-DL | `select` |
| 👆 STEAM-CN | `select` |
| 👆 GOOGLE | `select` |
| ... | 还有 11 个 |
</details>

---

### 👤 fufu

#### 📝 ConfigForClash.yaml
- **路径**: `fufu/ConfigForClash.yaml` | **大小**: 49.3 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/fufu/ConfigForClash.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: 🚫
<details>
<summary>🔍 策略组 (62个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 🚀 默认代理 | `select` |
| 👆 📢 谷歌推送 | `select` |
| 👆 💬 即时通讯 | `select` |
| 👆 📰 新闻社交 | `select` |
| 👆 🎨 语言模型 | `select` |
| 👆 🎬 流媒体集 | `select` |
| ♻️ 🎬 流媒自动 | `url-test` |
| 👆 ⚡ 速度测试 | `select` |
| 👆 📲 电报消息 | `select` |
| 👆 🎙 语音社群 | `select` |
| 👆 🍎 苹果新闻 | `select` |
| 👆 📮 推特推特 | `select` |
| 👆 🌈 晒照片墙 | `select` |
| 👆 ✨ ChatGPT | `select` |
| 👆 ✨ Claude | `select` |
| 👆 ✨ Gemini | `select` |
| 👆 ✨ Copilot | `select` |
| 👆 📀 媒体影院 | `select` |
| 👆 🎶 声田音乐 | `select` |
| 👆 🎶 油管音乐 | `select` |
| ... | 还有 42 个 |
</details>

---

### 👤 iKeLee

#### 📝 Clash_Sample.yaml
- **路径**: `iKeLee/Clash_Sample.yaml` | **大小**: 12.5 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/iKeLee/Clash_Sample.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (22个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 游戏选择 | `select` |
| 👆 全球选择 | `select` |
| 👆 境外下载 | `select` |
| 👆 AI | `select` |
| 👆 TikTok | `select` |
| 👆 SpeedtestIntl | `select` |
| 👆 App Store | `select` |
| 👆 Apple账户 | `select` |
| 👆 TestFlight | `select` |
| 👆 1Password | `select` |
| 👆 Netflix | `select` |
| 👆 Emby | `select` |
| 🔧 兜底后备策略 | `fallback` |
| ♻️ 香港自动策略 | `url-test` |
| ♻️ 台湾自动策略 | `url-test` |
| ♻️ 日本自动策略 | `url-test` |
| ♻️ 韩国自动策略 | `url-test` |
| ♻️ 新国自动策略 | `url-test` |
| ♻️ 美国自动策略 | `url-test` |
| ♻️ 英国自动策略 | `url-test` |
| ... | 还有 2 个 |
</details>

---

### 👤 liandu2024

#### 📝 clash-fallback-dialer.yaml
- **路径**: `liandu2024/clash-fallback-dialer.yaml` | **大小**: 16.3 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/liandu2024/clash-fallback-dialer.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (35个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 AI | `select` |
| 👆 Stream Media | `select` |
| 👆 GitHub | `select` |
| 👆 Reddit | `select` |
| 👆 Nvidia | `select` |
| 👆 Apple | `select` |
| 👆 Microsoft | `select` |
| 👆 Games | `select` |
| 👆 Crypto | `select` |
| 👆 Test | `select` |
| 👆 Block | `select` |
| 👆 国外 | `select` |
| 👆 国内 | `select` |
| 👆 其他 | `select` |
| 👆 所有-手动 | `select` |
| ♻️ 所有-自动 | `url-test` |
| 👆 香港-链式前置 | `select` |
| 🔧 香港-故转 | `fallback` |
| 👆 香港-手动 | `select` |
| ♻️ 香港-自动 | `url-test` |
| ... | 还有 15 个 |
</details>

#### 📝 clash-fallback-std.yaml
- **路径**: `liandu2024/clash-fallback-std.yaml` | **大小**: 17.3 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/liandu2024/clash-fallback-std.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (36个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 AI | `select` |
| 👆 Meta AI | `select` |
| 👆 Perplexity | `select` |
| 👆 Stream Media | `select` |
| 👆 GitHub | `select` |
| 👆 Reddit | `select` |
| 👆 Nvidia | `select` |
| 👆 Apple | `select` |
| 👆 Microsoft | `select` |
| 👆 Games | `select` |
| 👆 Crypto | `select` |
| 👆 Test | `select` |
| 👆 Block | `select` |
| 👆 国外 | `select` |
| 👆 国内 | `select` |
| 👆 其他 | `select` |
| 👆 所有-手动 | `select` |
| ♻️ 所有-自动 | `url-test` |
| 🔧 香港-故转 | `fallback` |
| 👆 香港-手动 | `select` |
| ... | 还有 16 个 |
</details>

#### 📝 clash-fallback.yaml
- **路径**: `liandu2024/clash-fallback.yaml` | **大小**: 15.9 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/liandu2024/clash-fallback.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (34个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 AI | `select` |
| 👆 Stream Media | `select` |
| 👆 GitHub | `select` |
| 👆 Reddit | `select` |
| 👆 Nvidia | `select` |
| 👆 Apple | `select` |
| 👆 Microsoft | `select` |
| 👆 Games | `select` |
| 👆 Crypto | `select` |
| 👆 Test | `select` |
| 👆 Block | `select` |
| 👆 国外 | `select` |
| 👆 国内 | `select` |
| 👆 其他 | `select` |
| 👆 所有-手动 | `select` |
| ♻️ 所有-自动 | `url-test` |
| 🔧 香港-故转 | `fallback` |
| 👆 香港-手动 | `select` |
| ♻️ 香港-自动 | `url-test` |
| 🔧 台湾-故转 | `fallback` |
| ... | 还有 14 个 |
</details>

#### 📝 clash-all-fallback.yaml
- **路径**: `liandu2024/clash-all-fallback.yaml` | **大小**: 17.2 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/liandu2024/clash-all-fallback.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (53个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 ChatGPT | `select` |
| 👆 Claude | `select` |
| 👆 Meta AI | `select` |
| 👆 Perplexity | `select` |
| 👆 GitHub | `select` |
| 👆 Telegram | `select` |
| 👆 Twitter(X) | `select` |
| 👆 WhatsApp | `select` |
| 👆 Facebook | `select` |
| 👆 Steam | `select` |
| 👆 Game | `select` |
| 👆 YouTube | `select` |
| 👆 TikTok | `select` |
| 👆 Disney | `select` |
| 👆 Netflix | `select` |
| 👆 HBO | `select` |
| 👆 Spotify | `select` |
| 👆 Crypto | `select` |
| 👆 Amazon | `select` |
| 👆 Apple | `select` |
| ... | 还有 33 个 |
</details>

#### 📝 clash-fallback-all.yaml
- **路径**: `liandu2024/clash-fallback-all.yaml` | **大小**: 18.6 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/liandu2024/clash-fallback-all.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: ✅
<details>
<summary>🔍 策略组 (61个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 ChatGPT | `select` |
| 👆 Gemini | `select` |
| 👆 Copilot | `select` |
| 👆 Perplexity | `select` |
| 👆 Claude | `select` |
| 👆 Meta AI | `select` |
| 👆 Grok | `select` |
| 👆 Groq | `select` |
| 👆 GitHub | `select` |
| 👆 Reddit | `select` |
| 👆 Telegram | `select` |
| 👆 WhatsApp | `select` |
| 👆 Facebook | `select` |
| 👆 BiliBili | `select` |
| 👆 YouTube | `select` |
| 👆 TikTok | `select` |
| 👆 Netflix | `select` |
| 👆 HBO | `select` |
| 👆 Disney | `select` |
| 👆 Amazon | `select` |
| ... | 还有 41 个 |
</details>

---

### 👤 liuran001

#### 📝 config.yaml
- **路径**: `liuran001/config.yaml` | **大小**: 13.8 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/liuran001/config.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (29个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 节点选择 | `select` |
| 👆 dns | `select` |
| 👆 广告拦截 | `select` |
| 👆 境外AI | `select` |
| 👆 Apple | `select` |
| 👆 Google | `select` |
| 👆 Telegram | `select` |
| 👆 Twitter | `select` |
| 👆 Pixiv | `select` |
| 👆 ehentai | `select` |
| 👆 巴哈姆特 | `select` |
| 👆 YouTube | `select` |
| 👆 NETFLIX | `select` |
| 👆 TikTok | `select` |
| 👆 Spotify | `select` |
| 👆 Github | `select` |
| 👆 Steam | `select` |
| 👆 OneDrive | `select` |
| 👆 微软服务 | `select` |
| 👆 国内 | `select` |
| ... | 还有 9 个 |
</details>

---

### 👤 qichiyuhub

#### 📝 config.yaml
- **路径**: `qichiyuhub/config.yaml` | **大小**: 12.8 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/qichiyuhub/config.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: 🚫
<details>
<summary>🔍 策略组 (26个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 🚀 默认代理 | `select` |
| 👆 📹 YouTube | `select` |
| 👆 🍀 Google | `select` |
| 👆 🤖 ChatGPT | `select` |
| 👆 👨🏿‍💻 GitHub | `select` |
| 👆 🐬 OneDrive | `select` |
| 👆 🪟 Microsoft | `select` |
| 👆 🎵 TikTok | `select` |
| 👆 📲 Telegram | `select` |
| 👆 🎥 NETFLIX | `select` |
| 👆 💶 PayPal | `select` |
| 👆 🐟 漏网之鱼 | `select` |
| 👆 🇭🇰 香港节点 | `select` |
| 👆 🇯🇵 日本节点 | `select` |
| 👆 🇸🇬 狮城节点 | `select` |
| 👆 🇺🇲 美国节点 | `select` |
| 🔧 🔯 香港故转 | `fallback` |
| 🔧 🔯 日本故转 | `fallback` |
| 🔧 🔯 狮城故转 | `fallback` |
| 🔧 🔯 美国故转 | `fallback` |
| ... | 还有 6 个 |
</details>

---

### 👤 wanswu

#### 📝 config.yaml
- **路径**: `wanswu/config.yaml` | **大小**: 27.5 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/wanswu/config.yaml)
- **模式**: rule | **TUN**: 🚫 | **IPv6**: ✅
<details>
<summary>🔍 策略组 (96个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 手动选择 | `select` |
| 👆 直接连接 | `select` |
| 👆 Claude | `select` |
| 👆 Gemini | `select` |
| 👆 OpenAI | `select` |
| 👆 Disney | `select` |
| 👆 Netflix | `select` |
| 👆 Spotify | `select` |
| 👆 TikTok | `select` |
| 👆 YouTube | `select` |
| 👆 Emby | `select` |
| 👆 Github | `select` |
| 👆 Google | `select` |
| 👆 Microsoft | `select` |
| 👆 OneDrive | `select` |
| 👆 Twitter(X) | `select` |
| 👆 Telegram | `select` |
| 👆 WhatsApp | `select` |
| 👆 Steam | `select` |
| 👆 香港 | `select` |
| ... | 还有 76 个 |
</details>

---

### 👤 yyhhyyyyyy

#### 📝 mihomo_single.yaml
- **路径**: `yyhhyyyyyy/mihomo_single.yaml` | **大小**: 17.8 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/yyhhyyyyyy/mihomo_single.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: 🚫
<details>
<summary>🔍 策略组 (55个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 🎯 节点选择 | `select` |
| 👆 手动选择 | `select` |
| 👆 智能选择 | `select` |
| 👆 ✈️ 电报信息 | `select` |
| 👆 🤖 AIGC | `select` |
| 👆 🍎 苹果服务 | `select` |
| 👆 Ⓜ️ 微软服务 | `select` |
| 👆 🇭🇰 - Auto | `select` |
| 👆 🇯🇵 - Auto | `select` |
| 👆 🇰🇷 - Auto | `select` |
| 👆 🇸🇬 - Auto | `select` |
| 👆 🇺🇸 - Auto | `select` |
| 👆 🇬🇧 - Auto | `select` |
| 👆 🇫🇷 - Auto | `select` |
| 👆 🇩🇪 - Auto | `select` |
| 👆 🇹🇼 - Auto | `select` |
| ♻️ 🇭🇰 - 自动选择 | `url-test` |
| ♻️ 🇯🇵 - 自动选择 | `url-test` |
| ♻️ 🇰🇷 - 自动选择 | `url-test` |
| ♻️ 🇸🇬 - 自动选择 | `url-test` |
| ... | 还有 35 个 |
</details>

#### 📝 mihomo_multi.yaml
- **路径**: `yyhhyyyyyy/mihomo_multi.yaml` | **大小**: 18.1 KB | [查看源码](https://github.com/HenryChiao/mihomo_yamls/blob/main/THEYAMLS/General_Config/yyhhyyyyyy/mihomo_multi.yaml)
- **模式**: rule | **TUN**: ✅ | **IPv6**: 🚫
<details>
<summary>🔍 策略组 (55个)</summary>

| 名称 | 类型 |
| :--- | :--- |
| 👆 🎯 节点选择 | `select` |
| 👆 手动选择 | `select` |
| 👆 智能选择 | `select` |
| 👆 ✈️ 电报信息 | `select` |
| 👆 🤖 AIGC | `select` |
| 👆 🍎 苹果服务 | `select` |
| 👆 Ⓜ️ 微软服务 | `select` |
| 👆 🇭🇰 - Auto | `select` |
| 👆 🇯🇵 - Auto | `select` |
| 👆 🇰🇷 - Auto | `select` |
| 👆 🇸🇬 - Auto | `select` |
| 👆 🇺🇸 - Auto | `select` |
| 👆 🇬🇧 - Auto | `select` |
| 👆 🇫🇷 - Auto | `select` |
| 👆 🇩🇪 - Auto | `select` |
| 👆 🇹🇼 - Auto | `select` |
| ♻️ 🇭🇰 - 自动选择 | `url-test` |
| ♻️ 🇯🇵 - 自动选择 | `url-test` |
| ♻️ 🇰🇷 - 自动选择 | `url-test` |
| ♻️ 🇸🇬 - 自动选择 | `url-test` |
| ... | 还有 35 个 |
</details>

---
