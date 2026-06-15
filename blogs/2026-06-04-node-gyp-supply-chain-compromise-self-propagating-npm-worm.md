---
title: "Node-gyp Supply Chain Compromise: A Self-Propagating npm Worm That Hides in binding.gyp"
url: "https://snyk.io/blog/node-gyp-supply-chain-compromise-self-propagating-npm-worm-binding-gyp/"
date: "2026-06-04"
author: ""
feed_url: "https://snyk.io/blog/feed/"
---
Snyk disclosed a new npm worm that abuses binding.gyp to trigger node-gyp during package installation, allowing malicious packages to run code without lifecycle scripts. The worm steals credentials, persists access in GitHub, and self-propagates by infecting other maintainers in the npm ecosystem.
