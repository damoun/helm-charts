<h1 align="center">
  <br><img src="project-logo.svg" height="192px">
  <br>
  Helm Charts
  <br>
</h1>

<h4 align="center">My own public Helm Charts repository.</h4>

<p align="center">
  <a href="https://github.com/damoun/helm-charts/actions/workflows/lint-test.yaml">
      <img src="https://github.com/damoun/helm-charts/actions/workflows/lint-test.yaml/badge.svg">
  </a>
  <a href="https://github.com/damoun/helm-charts/actions/workflows/release.yaml">
      <img src="https://github.com/damoun/helm-charts/actions/workflows/release.yaml/badge.svg">
  </a>
</p>

<p align="center">
  <a href="#getting-started">Getting Started</a>
  <a href="#chart-sources">Chart Sources</a>
</p>

# Getting Started

Add my repository to helm and use one of my chart:

```
helm repo add damoun https://charts.damoun.dev
helm install speedtest-exporter damoun/speedtest-exporter
```

# Chart Sources

* `damoun/transmission`: Chart for Transmission bittorrent client.
* `damoun/home-assistamt`: Chart for [Home Assistant](https://www.home-assistant.io).
* `damoun/gickup`: Chart for [Gickup](https://github.com/cooperspencer/gickup) command line.
* `damoun/proxmox-exporter`: Chart for Prometheus [Proxmox exporter](https://github.com/prometheus-pve/prometheus-pve-exporter).
* `damoun/speedtest-exporter`: Chart for Prometheus [Speedtest exporter](https://github.com/danopstech/speedtest_exporter).
