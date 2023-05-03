# CMPE 172 - Lab #10 Notes

# CI Builds

Workflow for CI on GitHub by using the new workload button on GitHub actions
and selecting the Java Gradle workflow. This workflow was then modified with 
the configurations given on Canvas.

![ScreenShot](images/CI-workflow.png)

Build in progress for gumball

![ScreenShot](images/CI-build-progress.jpg)

Build complete for gumball

![ScreenShot](images/CI-build-complete.png)

# GKE 

GKE cluster created

![ScreenShot](images/GKE-cluster.png)

Service account created by using the built-in menu on GCP

![ScreenShot](images/service-account-created.png)

IAM service roles configured to add Kubernetes Engine Developer and Storage Admin roles

![ScreenShot](images/IAM-service-role.png)

GCP Project ID on Dashboard to be entered on GitHub as a variable

![ScreenShot](images/GCP-project-id.png)

Secret Key Created and shown below in the downloaded format to be entered as a variable on GitHub

![ScreenShot](images/secret-key-created.png)

Deployment variables created on GitHub

![ScreenShot](images/deployment-variables-created.png)

Screenshots showing deployment in progress

![ScreenShot](images/deployment-in-progress.png)

![ScreenShot](images/deployment-in-progress-2.png)

Screenshots showing completed deployment

![ScreenShot](images/deployment-complete.png)

Spring Gumball Workload created and Jumpbox created to test the application connectivity

![ScreenShot](images/jumpbox-created.png)

GKE service for gumball running

![ScreenShot](images/GKE-service.png)

GKE ingress created for gumball and running using port 80 and connecting to port 8080 backend

![ScreenShot](images/GKE-ingress.png)

![ScreenShot](images/ingress-status-ok.png)

GKE gumball deployed using GKE

![ScreenShot](images/GKE-gumball-deployed.png)
