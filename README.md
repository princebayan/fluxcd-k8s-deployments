bootstrap FluxCD on your Kubernetes cluster with the newly created GitHub repository:
```shell
flux bootstrap github \
  --owner=YOUR_GITHUB_USERNAME \
  --repository=REPO_NAME \
  --branch=main \
  --path=./clusters/my-cluster \
  --personal
```
Replace YOUR_GITHUB_USERNAME with your GitHub username and REPO_NAME with the name of your GitHub repository.

For Example: 
```shell
flux bootstrap github \
  --owner=princebayan \
  --repository=fluxcd-k8s-deployments \
  --branch=main \
  --path=./clusters/my-cluster \
  --personal
```