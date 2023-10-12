# homelab_longhorn

## Installation

### Add Longhorn chart repository.

```
helm repo add longhorn https://charts.longhorn.io
```

### Update local Longhorn chart information from chart repository.

```
helm repo update
```


### Install Longhorn chart.

```
kubectl create namespace longhorn-system
helm install longhorn longhorn/longhorn --namespace longhorn-system
```
