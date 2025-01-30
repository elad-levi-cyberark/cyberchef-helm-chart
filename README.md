# cyberchef-helm-chart
Helm Chart for CyberChef

## Build
```bash
git clone https://github.com/elad-levi-cyberark/cyberchef-helm-chart.git
cd cyberchef-helm-chart
helm package cyberchef-helm-chart
```

## Install
```bash
wget https://github.com/elad-levi-cyberark/cyberchef-helm-chart/releases/download/v0.1.0/cyberchef-helm-chart-0.1.0.tgz
helm install cyberchef cyberchef-helm-chart-0.1.0.tgz
```
