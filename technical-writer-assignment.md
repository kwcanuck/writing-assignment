---
sidebar_label: "Troubleshoot a Kubernetes Pod with Kubectl"
title: "Troubleshoot a Kubernetes Pod with Kubectl"
description: "Learn how to troublshoot and resolve issues on a Kubernetes Pod"
hide_table_of_contents: false
tags: ["troublshooting", "nodes"]
---

When you experience an error within a Kubernetes Pod, you can run the `get pods` and `logs` `kubectl` commands to identify and troubleshoot issues. An alternative to these commands is the `debug` command. See [kubectl debug](https://kubernetes.io/docs/reference/kubectl/generated/kubectl_debug/)

## Prerequisites

- The Kubernetes command-line tool, `kubectl`. To install and set up `kubectl`, see [Install tools](https://kubernetes.io/docs/tasks/tools/) in the Kubernetes documentation.

## Debug Steps

1. In `kubectl`, run the following command to identify your existing Pods:

    ```bash
   kubectl get pods --namespace
   ```

2. Run the following command to retrieve the logs for all containers within the Pod:

    ```bash
   kubectl logs "$POD_NAME"
   ```
3. Review the logs and then identify and correct any issues.

4. Optional. Run the `kubectl exec` command to perform corrective actions on a container. See [kubectl exec](https://kubernetes.io/docs/reference/kubectl/generated/kubectl_exec/).
 
## Resources

- Common issues and their solutions
