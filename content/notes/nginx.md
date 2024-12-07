---
title: "Nging Reverse Proxy for SSL"
draft: false
description: "This took me much too long to figure out"
date: 2024-12-06T23:11:33-07:00
hideFeatureImage: false
showHero: false
tags:
- homelab
- nginx
- website
- selfhosted
---
## Nginx Woes

As part of my new website deployment
{{< article link="/posts/homelab/new-website/" >}}
I decided it was finally time to setup SSL encryption for my homelab, and to stop running things over HTTP. Truthfully, in the past I was operating this was out of fear of learning nginx reverse proxy stuff. But after using some ChatGPT prompting, and stackoverflow a time or two, I finally have a working setup! I wanted to document the unique things I needed to do in order to get some of my configurations workings.

## LetsEncrypt Making It Easy