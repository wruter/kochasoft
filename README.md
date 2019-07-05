# kochasoft Demo K8S Application with Doker

This small application show how to build and deploy a containerized Go web server
application using [Kubernetes](https://kubernetes.io).

This directory contains:

- `main.go` contains the HTTP server implementation. It responds to all HTTP
  requests with a  `Hello, world!` response.
- `Dockerfile` is used to build the Docker image for the application.

This application is available as two Docker images, which respond to requests
with different version numbers from official Google registries:

- `gcr.io/google-samples/hello-app:1.0`
- `gcr.io/google-samples/hello-app:2.0`
