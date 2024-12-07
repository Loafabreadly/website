---
date: {{ .Date }}
draft: true
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
description: "Change this description"
hideFeatureImage: false #Hide the featured image when viewing this page from a list
showHero: false #Hide the hero image when viewing the page itself
tags:
- default
- tag
---
