# terraform-gke

[![CIS](https://app.soluble.cloud/api/v1/public/badges/4df8f225-4ce7-4391-8729-cf63f1b4a05a.svg)](https://app.soluble.cloud/repos/details/github.com/ayoinc/terraform-gke)  [![IaC](https://app.soluble.cloud/api/v1/public/badges/36e4418a-9b53-42e0-a722-851bdee2a0db.svg)](https://app.soluble.cloud/repos/details/github.com/ayoinc/terraform-gke)  

Launch and manage a GKE cluster using Terraform.

## Launch GKE Cluster

```
$ terraform init
$ terraform plan
$ terraform apply
```

## Launch Demo Application

First, you will need to authenticate to the cluster, then you can run the following:

```
$ kubectl apply -f deployment.yaml
$ kubectl apply -f service.yaml
$ kubectl apply -f ingress.yaml
```

*Note: It will take 5 minutes for the load balancer to provision*

## Questions?

Open an issue.
