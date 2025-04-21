

# Usage:

helm repo add virium https://virer.github.io/virium-helm-repo/charts/
helm repo update
helm search repo virium
helm install 1 virium --namespace=virium --create-namespace -f values.yaml 