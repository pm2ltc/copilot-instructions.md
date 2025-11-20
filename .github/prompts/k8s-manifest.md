Generate Kubernetes manifests with the following standards:

- Use Deployment + Service unless specified.
- Set resource requests/limits.
- Add liveness and readiness probes.
- Use non-root container security context.
- Place config in ConfigMap/Secret where appropriate.
- Keep YAML compact and clean.
