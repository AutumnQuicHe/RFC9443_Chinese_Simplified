---
title: "摘要"
anchor: "Abstract"
weight: 10
rank: "h2"
---

RFC 7983为实时传输协议（Real-time Transport Protocol，RTP）接受方定义了一种方案，将到达单个端口的报文传输层安全（Datagram Transport Layer Security，DTLS）、NAT会话遍历工具集（Session Traversal Utilities for NAT，STUN）、安全实时传输协议（Secure Real-time Transport Protocol，SRTP）/安全实时传输控制协议（Secure Real-time Transport Control Protocol，SRTCP）、ZRTP、以及环NAT中继遍历（Traversal Using Relays around NAT，TURN）通道的数据包解除复用。
本文更新RFC 7983及5764，以支持QUIC包在单个接受套接字（socket）上进行多路复用。
