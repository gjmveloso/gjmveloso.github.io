---
comments: true
title:
date: {{ .Date }}
draft: true
slug: {{ anchorize (delimit (after 3 (split (replace .BaseFileName "_" "-") "-")) "-") }}
---
