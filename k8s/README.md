# Kubernetes Deployment

Das Ausrollen in Kubernetes benötigt ein vorbereitetes Container Image für den MCP-Server. Die Quelle für das Image kann ggf. in `production/kustomization.yaml` angepasst werden.

`kubectl -n <namespace> apply -k mcp-server/production`

