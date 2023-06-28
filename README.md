# Lotusboard
### UserManual

[WIKI](https://github.com/lotusproxy/lotusboard-docker/wiki)

### Go latest-release branch for latest stable, main is for develop purpose

# Modified v2board, probably enhancement

I have no intention in breaking open source protocols, but i don't understand them, so if you have some suggestion on this please tell me in issue

# What has been modified

Hysteria
 - Multiple bugs fixed

VLESS
 - Add vless support
 - Multi GUN mode on grpc
 - other stuffs that Vmess has

Vmess 
 - TLS fingerprint, firefox by default
 - Websocket ed4096(0rtt enabled for xray)
 - Subscription info was translated into English
 - Auto zero encryption when TLS enabled
 

Subscription:

 - ClashVPN mode profile (Proxy all traffic except local and icmp), add &flag=gclh to fetch it

 - Simplified the default clash config
