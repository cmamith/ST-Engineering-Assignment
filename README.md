# Nginx Helm Chart

This Helm chart deploys an Nginx server on Kubernetes, with support for enabling HTTPS through the values.yaml file and exposing the Nginx landing page on a NodePort.

Please note that i have edited only the service , ingress , deployment templates as this was the requirement, the others are left as default for now, the values.yaml has been changed as per the requirement

## Prerequisites

- Kubernetes cluster
- Helm 3.x

## Installation

1. Clone the repository:

   ```shell
   git clone <repository_url>


## Change to the working directory
   
    cd deploy-nginx
    customize as per requirement in nginx.yaml and then install the helm chart using the command helm install nginx ./




