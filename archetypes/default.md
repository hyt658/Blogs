---
title: "{{ replace .Name "-" " " | title }}"
keywords: "{{replace .Name "-" ","}}"
date: {{ .Date }}

share: false
followme: false
nav: false
url: "{{ lower .Name }}.html"
---



