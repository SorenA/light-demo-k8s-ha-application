# Light Demo - Kubernetes - HA Application

An example of a HA application using Kubernetes.

Deployment manifests are located in the `/k8s` directory.

Included is three backend services and one frontend service.  
All services are routed using Traefik and configured with liveless &amp; readiness probes.

The frontend is set up to keep requesting the backend APIs, feel free to kill pods and servers to test the scheduling capabilities of Kubernetes.
