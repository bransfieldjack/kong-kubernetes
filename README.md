
# Kong deployed on GCP with Kubernetes

![kubernetes-gcp](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/kubernetes.png)

## About:
This is a walk through on how to quickly install Kong on Google Cloud Platforms Kubernetes engine, and expose Kongs management service endpoint to the internet.  

## Setup

### Login to the google cloud platform console and navigate to the marketplace:

![marketplace](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/marketplace.PNG)

### Search for Kong in the solutions search bar:

![search_for_kong](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/search_for_kong.PNG)

### Select Kong to proceed:

![select_kong](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/select_kong.PNG)

### Select configure:

![configure](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/configure_to_proceed.PNG)

### Select create project:

![create_project](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/select_create_project.PNG)

### Wait while Kubernetes configuration setup completes:

![wait_while](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/wait_while_kubernetes.PNG)

### Choose a cluster zone, and create your cluster:

![choose_cluster](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/select_default_cluster_zone.PNG)

### Wait for the cluster setup to complete:

![wait_for_cluster](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/wait_for_cluster.PNG)

### Deploy Kong:

![deploy](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/deploy.PNG)

### Wait for component configuration to complete:

![wait](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/wait.PNG)

### Verify that the deployment has completed with success:

![verify_deploy](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/verify_deploy.PNG)

### Navigate to the services tab:

![services](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/services_and_admin.PNG)

### Select edit:

![edit_service](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/select_edit_service.PNG)

### Navigate to type, and change from clusterIP to LoadBalancer:

![navigate_to_type](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/navigate_to_type.PNG)
![load_balancer](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/load_balancer.PNG)

### Save the configuration return to the service details page. Click on the services tab again and select the management endpoint to verify connectivity:

![connectivity_verify](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/connectivity_verify.PNG)

### You should receive output similar to the following:

![endpoint_output](https://s3-ap-southeast-2.amazonaws.com/kong-gcp-kubernetes/endpoint_output.PNG)
