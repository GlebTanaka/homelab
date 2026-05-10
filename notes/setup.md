# Initial Setup

## Installed Ubuntu Server
- Installed on both iMacs
- Enabled the OpenSSH service

## Networking
- Configured static IP addresses with netplan
- Replaced deprecated `gateway4` with `routes`

## SSH
- Verified SSH access from the client machine

## k3s Cluster
- Initialized the first `k3s` cluster
- Set up the main node as the initial control plane
- Confirmed the cluster is reachable and operational
- Verified node status with `sudo kubectl get nodes`
- Verified system pods with `sudo kubectl get pods -A`

## Cluster Verification
- Ran `sudo kubectl get nodes`
- Expected result: the main node appears in the list and shows `Ready`
- Ran `sudo kubectl get pods -A`
- Expected result: system pods in the `kube-system` namespace are running

## NodePort Exposure
- Exposed the NGINX service through a NodePort named `hello-nginx-nodeport`
- Verified the service with `kubectl get svc`
- Confirmed that `hello-nginx-nodeport` is listed as `NodePort`
- Confirmed that the service exposes port `80:31408/TCP`

## Browser Verification
- Checked the exposed NGINX service in a browser
- Confirmed that it is reachable from `imac1`
- Confirmed that it is reachable from `imac2`
