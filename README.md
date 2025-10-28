# openshift-mcp

OpenShift configs for:

* [kubernetes-mcp-server](https://github.com/containers/kubernetes-mcp-server)
* [slack-mcp-server](https://github.com/korotovsky/slack-mcp-server)
* [google_workspace_mcp](https://github.com/taylorwilsdon/google_workspace_mcp)
* [servicenow-mcp](https://github.com/echelon-ai-labs/servicenow-mcp)

Some containers had to be built and temporarily published to a personal Quay account, and have been made public, following [this process](https://www.redhat.com/en/blog/deploy-web-service-openshift).

The latter three need credentials configured in Kubernetes secrets as per the configuration instructions for each of the linked projects; placeholders are given.

## Deployment

[`kubectl apply`](https://kubernetes.io/docs/reference/kubectl/generated/kubectl_apply/)
