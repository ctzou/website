---
title: Learning environment
main_menu: true
weight: 20
---

<!-- overview -->

This page helps you set up Kubernetes to learn more about it. If you wanted to run real workloads on Kubernetes, read the [Production Environment](/docs/setup/production-environment/) setup guide.

<!-- body -->

## kind

[`kind`](https://kind.sigs.k8s.io/docs/) lets you run Kubernetes on
your local computer. This tool requires that you have
[Docker](https://docs.docker.com/get-docker/) installed and configured.

The kind [Quick Start](https://kind.sigs.k8s.io/docs/user/quick-start/) page
shows you what you need to do to get up and running with kind.

<a class="btn btn-primary" href="https://kind.sigs.k8s.io/docs/user/quick-start/" role="button" aria-label="View kind Quick Start Guide">View kind Quick Start Guide</a>

## minikube

Like `kind`, [`minikube`](https://minikube.sigs.k8s.io/) is a tool that lets you run Kubernetes
locally. `minikube` runs a single-node Kubernetes cluster on your personal
computer (including Windows, macOS and Linux PCs) so that you can try out
Kubernetes, or for daily development work.

You can follow the official
[Get Started!](https://minikube.sigs.k8s.io/docs/start/) guide if your focus is
on getting the tool installed.

<a class="btn btn-primary" href="https://minikube.sigs.k8s.io/docs/start/" role="button" aria-label="View minikube Get Started! Guide">View minikube Get Started! Guide</a>

Once you have `minikube` working, you can use it to
[run a sample application](/docs/tutorials/hello-minikube/).


## {{% heading "whatsnext" %}}

- Make sure to [install `kubectl`](/docs/tasks/tools/#kubectl) as well.

- If you still can't decide, pick `minikube` and start with [Hello Minikube](/docs/tutorials/hello-minikube/).

- Already familiar with Kubernetes? Learn how to deploy a cluster for a
[production environment](https://k8s.io/docs/setup/production-environment/).
That guidance is also useful if you want to deploy an environment that matches a production setup.

