# cyberchef-helm-chart
[![GitHub Issues](https://img.shields.io/github/issues/elad-levi-cyberark/cyberchef-helm-chart)](https://github.com/elad-levi-cyberark/cyberchef-helm-chart/issues)

Helm Chart for [CyberChef](https://github.com/gchq/CyberChef)

## Build
```bash
git clone https://github.com/elad-levi-cyberark/cyberchef-helm-chart.git
cd cyberchef-helm-chart
helm package .
```

## Install
```bash
wget https://github.com/elad-levi-cyberark/cyberchef-helm-chart/releases/download/v0.1.0/cyberchef-helm-chart-0.1.0.tgz
kubectl create namespace cyberchef
helm install cyberchef cyberchef-helm-chart-0.1.0.tgz -n cyberchef
```
