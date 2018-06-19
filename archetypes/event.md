---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }} # start date
expiryDate: {{ .Date }} # expire date
draft: true


type: event
allday: true
---