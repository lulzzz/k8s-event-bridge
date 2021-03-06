# Kubernetes Event Bridge
[![Netlify Status](https://api.netlify.com/api/v1/badges/c85c7f9a-6bb1-47bc-b04e-8bd9140edd30/deploy-status)](https://app.netlify.com/sites/k8s-event-bridge-staging/deploys)
[![CodeFactor](https://www.codefactor.io/repository/github/tomkerkhove/k8s-event-bridge/badge)](https://www.codefactor.io/repository/github/tomkerkhove/k8s-event-bridge)

A simple event bridge for Kubernetes native events

# Concept
Kubernetes Event Bridge will subscribe for events inside the Kubernetes cluster and forward CNCF Cloud Events to a sidecar of choice, in this case an Azure Event Grid proxy.

![Kubernetes Event Router Concept](./media/concept-event-router.png)
