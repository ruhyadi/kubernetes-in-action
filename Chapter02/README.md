# Chapter 2

## Installing Minikube on Ubuntu

Minikube is a tool that makes it easy to run Kubernetes locally. Minikube runs a single-node Kubernetes cluster inside a VM on your laptop for users looking to try out Kubernetes or develop with it day-to-day.

### Prerequisites

- 2 CPUs or more
- 2GB of free memory
- 20GB of free disk space
- Internet connection
- Container or virtual machine manager, such as: [Docker](https://www.docker.com/)

### Installation

1. Download the latest version of Minikube:

```bash
curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube-linux-amd64
```

2. Make the binary executable:

```bash
sudo install minikube-linux-amd64 /usr/local/bin/minikube && rm minikube-linux-amd64
```

3. Start Minikube:

```bash
minikube start
```

4. Verify the installation:

```bash
minikube status
```

5. Stop Minikube:

```bash
minikube stop
```