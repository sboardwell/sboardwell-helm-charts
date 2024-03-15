# sboardwell-helm-charts

Packaging helm charts for use elsewhere.

Standing on the shoulders of giants.

## Usage

```sh
# add
helm repo add sboardwell-helm-charts https://sboardwell.github.io/sboardwell-helm-charts

# update
helm repo update

# search
helm search repo sboardwell-helm-charts

# install and delete - e.g. mailcatcher
helm install mailcatcher sboardwell-helm-charts/mailcatcher-helm
helm delete mailcatcher
```
