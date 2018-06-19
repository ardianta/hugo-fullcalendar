---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }} # start date
expiryDate: {{ .Date }} # expire date
draft: true

output: ["JSON", "html"]
type: event
allday: true
---