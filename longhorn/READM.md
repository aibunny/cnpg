# longhorn

Depends on prometheus CRDs.

https://artifacthub.io/packages/helm/longhorn/longhorn

helm repo add longhorn https://charts.longhorn.io
helm repo update

helm upgrade --install longhorn longhorn/longhorn --namespace longhorn-system -f values.yaml --create-namespace
