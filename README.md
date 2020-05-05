Repository contains the following submodules that are required to run the Data Portal:
 - [data-portal-admin](https://github.com/factly/data-portal-admin)
 - [data-portal-api](https://github.com/factly/data-portal-api)
 - [dega-identity](https://github.com/factly/dega-identity)
 - [dega-identity-api](https://github.com/factly/dega-identity-api)

Clone the repository including submodules using the following command:
```
    https://github.com/factly/data-portal --recurse-submodules
```
## Setting up development environment

### Requirements 
Following steps are for Mac OS. Please follow the individual tool documentation guides for other operating systems. 
 - [Skaffold](https://skaffold.dev/): `brew install skaffold`
 - [Docker](https://www.docker.com/): Follow the installation steps from [here](https://docs.docker.com/docker-for-mac/)
 - [Minikube](https://minikube.sigs.k8s.io/docs/): `brew install minikube`
 - [Kubectl](https://kubernetes.io/docs/tasks/tools/install-minikube/): `brew install kubectl`

### Optional

 -  [Cloud Code](https://cloud.google.com/code):  Install Cloud Code extension for your choice of editor for better support for Kubernetes development through your favorite IDE. Follow instructions for installing it on VS Code on the [quick start guide](https://cloud.google.com/code/docs/vscode/quickstart).


### Start the application in development mode

- Start Docker
- Start Minikube: `minikube start`