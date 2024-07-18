<!---
Copyright (c) 2022-present, FriendliAI Inc. All rights reserved.
-->

<h2><p align="center">Grafana Templates for Friendli Container on Kubernetes</p></h2>

The following templates are provided.

- **friendli-engine-dashboard-k8s.json**: Combines all metrics from Friendli Engine pods discovered.
- **friendli-engine-dashboard-per-pod.json**: Allows users to select a specific Friendli Engine pod.

> [!NOTE]
> The Grafana instance must be connected to a Prometheus instance (or a Prometheus-compatible data source) which is configured to scrape metrics from Friendli Container pods.
>
> The dashboard template works with Grafana v8.0.0 or later versions. We recommend using Grafana v10.0.0 or later for the best experience.
