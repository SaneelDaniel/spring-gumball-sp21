# spring-gumball ci/cd example

In this lab, I explored how to setup a CI/CD pipeline with github actions, and Google Cloud Platform.

It is especially interesting to see how easily the workflow can not only be managed, but also tested, and deployed with such a pipeline. 

The automation tools and the templates provided by github are also quite impressive. 

## CI Workflow:

- Set up the CI workflow action to be triggered on push to the main branch.
- It attempts to build the jar file, and on successful completion, it uploads the file.

### Screenshot (CI Workflow)

![ci-workflow](images/ci-workflow.png)

## CD Workflow

### Screenshots

- GCP Service Accoucnt & JSON Service Account Key

![service-accounts](images/service-accounts.png)

![service-keys](images/spring-service-keys.png)

- GitHub Action Secrets

![action-secrets](images/github-secrets.png)

- GKE Cluster

![gke-cluster](images/gke-cluster.png)

- V1 Github Release

![v1-release](images/v1-release.png)

- All Github Workflows

![git-workflows](images/all-actions.png)

- Build & Deploy Action Workflow

![cd-workflows](images/cd-workflow.png)

- GKE Workload

![gke-workload](images/gke-workload.png)

- GKE Service

![gke-service](images/gke-service.png)

- GKE Ingress

![gke-ingress](images/gke-ingress.png)

- GKE Ingress Details

![gke-ingress-details](images/ingress-details.png)

- Gumball Live

![gumball-live](images/gumball-hosted.png)
