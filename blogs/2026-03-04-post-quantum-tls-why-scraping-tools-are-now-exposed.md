---
title: 'Post-Quantum TLS: Why Scraping Tools Are Now Exposed'
url: https://scrapfly.io/blog/posts/post-quantum-tls-bot-detection
date: '2026-03-04'
author: ''
feed_url: https://scrapfly.io/blog/rss/
---
Post-quantum TLS is now a live bot detection signal. Modern browsers send X25519MLKEM768 key shares by default, and scrapers that don’t are increasingly exposed before HTTP starts. For teams that don’t want to maintain a PQ-aware TLS stack themselves, Scrapfly handles browser-grade TLS fingerprinting at the infrastructure level.
