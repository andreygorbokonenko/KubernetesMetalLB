# KubernetesMetalLB
Kubernetes Web App Deployment with MetalLB on Bare Metal

install Docker
```bash
sudo apt install docker.io
```
Login to Docker Registry on GitHub
```bash ghcr.io
sudo docker login --username <username> --password <token> ghcr.io
```
Build Docker and mark it for the Registry on GitHub
```bash
sudo docker build . -t ghcr.io/andreygorbokonenko/<app-name>:v2
```
Push Container to Docker Registry on GitHub
```bash
sudo docker push ghcr.io/andreygorbokonenko/ag-app:v2
```
