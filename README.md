# Harbor Demo with Cypress E2E Testing

This repository demonstrates how to create Kubernetes virtual cluster environments for every pull request. On each new PR, a Uffizzi cluster is created, and the Harbor application is deployed to the cluster. A comment is posted to the PR issue along with results from Cypress tests. When the pull request is closed or merged, the Uffizzi cluster and all data is destroyed.
