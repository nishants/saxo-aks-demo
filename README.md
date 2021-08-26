### TODO

- Create an API with .net5 boilerplate
- Dockerize the service
- Create kubernetes manifest
- Deploy on azure
- Create pre-requisite
- Run on windows



### About

This is a one hour  tutorial to setup your first service on Azure Kubernetes Service. We will create a simple service and talk about basics of docker and kubernetes. You need no prior experience with Docker/Kubernetes or Azure for this.

In this tutorial we focus on just creating a simple web service. There is another tutorial that demonstrates creating a streaming server with gRPC and Websockets here https://github.com/dotnet-school/dotnet-streaming-aks.



### Pre-requisite

- **.NET 5 SDK**

  > We will use .NET5 boileplates to create a smaple service.
  >
  > Download and install from  https://dotnet.microsoft.com/download/dotnet/5.0

- **Docker Desktop** 

  > To build and publish images to docker repository. 
  >
  > Download and install from https://www.docker.com/products/docker-desktop.

- **Kubectl**

  > To run command against kubernetes cluster on AKS.
  >
  > Download and install from : https://kubernetes.io/docs/tasks/tools/

- **Azure Portal Account**

  > Signup to create you azure account here https://signup.azure.com/signup

- **Azure CLI**

  > To be able to connect to azure via cli. You can skip this and use Azure cloud shell instead. But is recommended to help you follow along the steps in this tutorial.
  >
  > Download and install from https://docs.microsoft.com/en-us/cli/azure/install-azure-cli

