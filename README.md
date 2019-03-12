This repository can deploy a complete ELK cluster in GKE

Prerequisites

*An active GCP account with a precreated project. Also the GKE, GCE APIs need to be enabled
*A GKE/Kubernetes cluster already provisioned and accessible

Deployment steps

*First execute the install.sh script which will download, deploy and configure Helm (and Tiller)
*To deploy the chart execute while being in the repository: helm install elk --name=elk-cluster

To cleanup, execute: helm del --purge elk-cluster
