# Reading Logs Exercise
Logs are an important part of troubleshooting and understanding deployment behavior.

https://kubernetes.io/docs/reference/kubectl/cheatsheet/
# Kubernetes Logs
Kubernetes logs are available in the cluster. For a given container's logs, you can run the command `kubectl logs <POD_NAME> -c <CONTAINER_NAME>`.

For this exercise, we will be running a pod with one container. Thus, running `kubectl logs <POD_NAME>` is sufficient.

## Instructions
While running the `admin-api` deployment, execute the command to show the logs in the pod. This should output the logs that are being generated by the pod. You should see a series of health check queries being made. In up to 2 sentences, why do you think health check queries are being called?