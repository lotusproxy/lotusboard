# Lotusboard

# AD

We've made a backend for hysteria which is newly supported by v2board upstream, lotusboard fixed them and open PRs to upstream

Bodhi at https://github.com/lotusproxy/bodhi

# Go latest-release branch for latest stable, main is for develop purpose

# Modified v2board, probably enhancement

I have no intention in breaking open source protocols, but i don't understand them, so if you have some suggestion on this please tell me in issue

# What has been modified

Vmess
 
 - TLS fingerprint, randomized by default
 - Websocket ed4096(0rtt enabled for xray)
 - Subscription info was translated into English
 - Auto zero encryption when TLS enabled **This is bascially VLESS**

Subscription:

 - ClashVPN mode profile (Proxy all traffic except local and icmp), add &flag=gclh to fetch it

 - Simplified the default clash config

# Install with docker

[Read Docs](https://github.com/lotusproxy/lotusboard-docker/wiki)
