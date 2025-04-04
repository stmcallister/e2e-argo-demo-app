# E2E-Demo
This is a project that illustrates how to configure and execute end-to-end testing of a [k3s](https://k3s.io/) Kubernetes cluster using [Cypress](https://www.cypress.io/) and the [ngrok Kubernetes Operator](https://ngrok.com/docs/k8s/).

The application contains two containers, one for the frontend and one for the backend. There is also a container with the Cypress test code.

The Kubernetes configuration code is in [e2e-argo-demo-app](https://github.com/stmcallister/e2e-argo-demo-config).

C-sharp application used in this demo is heavily inspired by the project over at [Kubernetes Hands-on Workshop](https://github.com/robrich/kubernetes-hands-on-workshop) by Rob Richardson.
