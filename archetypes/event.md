---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }} # start date
expiryDate: {{ dateFormat "2006-01-02T15:04:05" (now.AddDate +1 0 0) }} # expire date
draft: true

output: ["JSON", "html"]
type: event
allday: true
---