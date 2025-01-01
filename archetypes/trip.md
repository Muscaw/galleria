---
title: <location_name>
{{- if .Page.IsSection }}
locationName: <location_name>
locationEmoji: <emoji>
{{- end }}
latlon: <lat,lon comma separated>
zoomLevel: <zoomLevel for the map>
date: {{ .Date }}
keepZoomLevel: false
draft: true
_build:
  publishResources: false
---
