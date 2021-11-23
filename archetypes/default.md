---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: true
description: "きょうなにがありましたか"
cover: post/{{ replace .Name "-" "" | urlize }}/
---

