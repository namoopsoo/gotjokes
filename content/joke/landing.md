---
title: "Landing"
date: 2024-05-05T13:19:35-04:00
draft: false
---

# ok

{{ range $.Site.Data.jokesDb.yaml }}
  {{ partial "oneliners.html" . }}
{{ end }}



