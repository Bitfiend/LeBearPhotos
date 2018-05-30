---
id: {{ .Name }}
title: {{ replace .Name "-" " " | title }}
file: {{ .Name }}.md
createdDay: {{ now.Format "Monday" }}
createdDate: {{ now.Format "January 2, 2006" }}
description: Description of the Album.
draft: true
coverPhoto:
---
