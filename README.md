# Lotusboard
### UserManual | 用戶手冊

[WIKI](https://github.com/lotusproxy/lotusboard-docker/wiki)

### Go latest-release branch for latest stable, main is for develop purpose
### 转到latest-stable分支以获得最新稳定版本，main用于开发目的

# Modified v2board, probably enhancement
# 修改后的 v2board，可能是增强版

I have no intention in breaking open source license, but i don't understand them, so if you have some suggestion on this please tell me in issue

我无意破坏开源许可证，但我不理解它们，所以如果您对此有任何建议，请在问题中告诉我

# What has been modified | 修改了什么

Hysteria
 - Multiple bugs fixed

VLESS
 - Add vless support
 - Multi GUN mode on grpc
 - other stuffs that Vmess has
 - XTLS supported

Vmess 
 - TLS fingerprint, firefox by default
 - Websocket ed4096(0rtt enabled for xray)
 - Subscription info was translated into English
 - Auto zero encryption when TLS enabled
 

Subscription:

 - ClashVPN mode profile (Proxy all traffic except local and icmp), add &flag=gclh to fetch it

 - Simplified the default clash config
