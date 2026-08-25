---
title: "Azure VPN Gateway SSTP Retirement: The Real Migration Path"
url: "https://blog.openvpn.net/azure-vpn-gateway-sstp-retirement-migrate-access-server"
date: "2026-08-18"
author: "Rohit Kalbag"
feed_url: "https://blog.openvpn.net/rss.xml"
---
That change clears the deadline. It doesn't change the fact that you're still on a gateway with a hard 128-connection SSTP ceiling, SKU-bound P2S scaling, no cross-cloud reach, and a policy model that stops at the route table. If you're going to touch every client anyway — and switching from SSTP to OpenVPN on the gateway requires exactly that — it's worth spending an afternoon evaluating whether the gateway should stay in the path at all.
