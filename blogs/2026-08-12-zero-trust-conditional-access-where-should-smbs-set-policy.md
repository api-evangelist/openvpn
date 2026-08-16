---
title: "Zero Trust Conditional Access: Where Should SMBs Set Policy?"
url: "https://blog.openvpn.net/zero-trust-conditional-access-smb"
date: "2026-08-12"
author: "Rohit Kalbag"
feed_url: "https://blog.openvpn.net/rss.xml"
---
Key Takeaways NIST SP 800-207 splits the policy decision point (PDP) from the policy enforcement point (PEP) — deciding and enforcing are different jobs, and they don't have to live in the same product. A healthy SMB architecture has one authoritative PDP and several PEPs that inherit from it — not three products each writing their own rules. Practical split: the identity provider owns identity and session context, PKI owns device identity, and ZTNA owns what a session can reach and for how long.
