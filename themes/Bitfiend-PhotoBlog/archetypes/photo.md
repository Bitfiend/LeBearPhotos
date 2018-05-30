---
id: {{ .Name }}
title: {{ replace .Name "-" " " }}
file: {{ .Name }}.ext
createdDay: {{ now.Format "Monday" }}
createdDate: {{ now.Format "January 2, 2006" }}
description: Descirption of the photo.
photographer: Linda Belcher
camera: 
tags: []
albums: []
draft: true
---
