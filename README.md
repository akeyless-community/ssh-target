# ssh-target

## Purpose

To deploy a linux VM into a Kubernetes cluster using TrustedUserCA and connecting to the VM using SSH certificates

## Preparation

- Click the green `Use this template` button to create a copy of this repo for your own use.
- Edit the ca.pub file to have your own public key of an RSA 2048 or higher encryption key
- Deploy the ssh-target into your cluster

## Install the Workload

Deploy into cluster using kubectl and Kustomize

```sh
kubectl apply -k .
```
