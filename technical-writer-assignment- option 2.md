---
sidebar_label: "Discover Kubectl Troubleshooting Commands"
title: "Discover Kubectl Troubleshooting Commands"
description: "Learn more about the kubectl commands you can use to resolve issues."
hide_table_of_contents: false
tags: ["troublshooting", "nodes"]
---
You can use the `kubectl` command line tool to identify and troubleshoot issues with your Kubernetes Pods. The following are some of the more useful commands:

- `kubectl get pods kubectl get pods --namespace` - returns a list and the status of all available Pods. `--namespace` is optional and returns the current namespaces in a cluster.

- `kubectl logs` - retrieves the logs for the Pod.

- `kubectl exec` - allows you to run commands on containers with the Pod.

- `kubectl debug` - clones a Pod and allows you to run debugging tasks.

To learn more about these and other `kubectl` commands, see the [Getting Started Guide](https://kubernetes.io/docs/reference/generated/kubectl/kubectl-commands#-strong-getting-started-strong-).
