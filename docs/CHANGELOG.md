# ChangeLog

### 2.4.9

- Add WebDAV synchronize support
- Fix crash when restart VPN after rename profile
- Fix fetch ip info failed after VPN established
- Improve save profile speed
- Fix update profile last modify time no changing

### 2.4.8

- Improve ui compatibility with tablet devices
- Add network speed display on status bar icon
- Add Public IP visibility toggle
- Prompt to restart VPN when selecting profile
- Bug fixed

### 2.4.7

- Fix profile import issue cause by policy-regex-filter
- Improve profile name guess imported by url
- Fix UI tab double click issue
- Fix profile name contains slash cause crash
- Update sample.conf
- Bug fixed

### 2.4.6

- Bug fixed

### 2.4.5

- Support policy-regex-filter and hidden in proxy group
- Fix global outbound make network unavailable
- Hide notification in lockscreen
- Make VMESS AEAD disable by default
- Update UI
- Bug fixed

### 2.4.4

- Support udp-relay in socks5/shadowsocks/vmess/trojan proxy
- Fix import vmess url failed if contains slash
- Fix some crash issue

### 2.4.3

- Improve traffic throughput
- Update bypass apps ui, add search support
- Fix ss proxy with domain cause stop VPN failed
- Update UI

### 2.4.2

- Fix policy path issue
- Add Indonesian support
- Improve profile decode performance
- Fix huge profile cause crash
- Only use English app entrance name

### 2.4.1

- Fix gradle 7.0.1 cause R8 error
- Update libuv/v2fly library

### 2.4.0
Fix socks5 proxy not working without authorization
Add policy-path support
Support surge3:///install-config?url=xxx
Support enhanced mode domain rules
Support decode http/socks5 proxy as TLS-based proxy
Update GEOIP library

### 2.3.5(82)

- Fix some profile import issue, support more import format
- Fix column size not synchronize between proxy group tabs
- Fix notification click not working
- Don't count speedometer into active tcp connection count
- Change UI back to 4 tabs in main ui

### 2.3.4(81)

- Add fuzzy search in recent requests ui
- Update item ui in recent requests
- Sort bypass app by toggle state
- Support trojan:// proxy url
- Support import multiple proxy url divided by space, vertical line and enter
- Support switch app launcher title to english
- Support proxy column size switch

### 2.3.3(80)

- Add active connection count display in dashboard
- Support vmess:// and ss:// url
- Add Profile FileProvider support
- Add VMESS AEAD support settings

### 2.3.2(79)

- Support vmess AEAD
- Support long press to copy traffic info in recent request list
- Fix update profile last modify time not changing
- Fix profile modify not working
- Update translation

### 2.3.1(78)

- Fix open vpn failed with rule-set profile

### 2.3.0(77)

- Add skip-proxy config support
- Fix change global proxy not working when VPN is on
- Add direct proxy in global outbound mode
- Add tools tab
- Support custom dns server port in dns-server config
- Support decode 1/0 as Boolean in profile
- Fix long profile list selection duplicate issue
- Bug fixed

### 2.2.1(76)

- Add skip TLS verify setting
- Fix whitelist mode not working issue

### 2.2.0(75)

- Add bypass config support
- Reduce APK size
- Add proxy_test_url support
- Add profile sample in profile list menu

### 2.1.0(74)

- Add recent request support
- Add profile viewer(not support editing yet)
- Integrate QRCode scanner, not need to download zxing scanner

### 2.0.2(73)

- Update all locale app name to [Surfboard]
- Fix crash issue on Android 7.0 and lower version
- Update light theme UI, support switch theme in settings
- Fix global outbound speed test not working
- Fix crash when vmess proxy name boxed with double quote
- Fix UI issue

### 0.9.19(50)

- Fix network metered issue on Android 10
- Fix speed test issue
- Allow fetching profile using current profile
- Add test-timeout/internet-test-url/proxy-test-url support
- Remember proxygroup toggle state
- Avoid displaying toast when fetch toast failed

### 0.9.18(49)

- Rewrite tcp handler for better memory usage
- Add proxygroup toggle function
- Add Notification Channel Setting entrance
- Bug fix

### 0.9.16(47)

- Fix ss tcp speedtest issue
- Add Tile and app shortcut support
- Fix email feedback crash
- Update speedtest ui
- Bugs fixed

### 0.9.14(45)

- Improve throughput performance(Up to 300Mbps+)
- Bugs fixed

### 0.9.13(44)

- Fix second launch crash issue
- Update proxy group grid ui
