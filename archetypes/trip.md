---
title: <location_name>
{{- if .Page.IsSection }}
locationName: <location_name>
locationEmoji: <emoji>
{{- else }}
showOnWorldMap: true
{{- end }}
latlon: <lat,lon comma separated>
zoomLevel: <zoomLevel for the map>
date: {{ .Date | dateFormat "2006-01-02" }}
image: <Image>
keepZoomLevel: false
draft: true
_build:
  publishResources: false
---
