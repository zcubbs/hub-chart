---
layout: default
title: z/Hub - Helm Chart Repo
food: pears
---

### Add the repo

`helm repo add hub-chart https://zcubbs.github.io/hub-chart`

### Install

`helm upgrade --install hub hub-chart/hub-chart`

### Disclaimer

Assumes you are running Traefik v2+ for IngressRoutes.
