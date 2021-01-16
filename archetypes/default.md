---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
type: album
albumthumb: "thumb.jpeg"
<!-- resources section only needed to add descriptions. Can be deleted -->
resources:
- src: ALBUMNAME/IMG_.jpeg
  alt: alt text
  phototitle: photo metadata
  description: Description
---
