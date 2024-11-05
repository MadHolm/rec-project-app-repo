# rec-project-app-repo
For a showcase project - fully automated deployment of infrastracture and application.

Full description of the architecture can be found here: https://github.com/MadHolm/rec-project-infra-repo/blob/main/README.md

Deployed application uses an available docker image from Google registry - http://us-docker.pkg.dev/cloudrun/container/hello 
Changing link to a different image in the deployment.yaml will result in deployment of another application.

Backend is configured to support HTTPS traffic to the application using an external Kubernetes Load Balancer as well as the GKE managed certificate with boar.best domain. 
