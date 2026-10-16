---
title: "Running Casdoor on Kubernetes: Official Helm Chart and Configuration as Code"
url: "https://casdoor.ai/blog/casdoor-on-kubernetes/"
date: "2026-10-07"
feed_url: "https://casdoor.ai/blog/rss"
---
Casdoor has an official Helm chart. It lives in the main repository under manifests/casdoor, is published with every Casdoor release to GHCR, and is listed on Artifact Hub. Starting with Casdoor v4.18.0, the chart can also hold your organizations, applications, users and providers as declarative configuration: change them in the values file, run helm upgrade, and the running pods apply the change without a restart.
