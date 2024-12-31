---
title: <location_name>
{{- if .Page.IsSection }}
locationName: <location_name>
locationEmoji: <emoji>
{{- end }}
latlon: <lat,lon comma separated>
zoomLevel: <zoomLevel for the map>
date: {{ .Date }}
_build:
  publishResources: false
---
