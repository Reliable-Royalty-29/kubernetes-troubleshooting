### Kubectl Commands

- **Label a node**: Adds a label to a specific node.
  ```bash
  kubectl label nodes <node-name> foo=bar
  ```
  *(Labels the node `<node-name>` with `foo=bar`.)*

- **Show node labels**: Displays all nodes and their labels.
  ```bash
  kubectl get nodes --show-labels
  ```
  *(Lists nodes with their labels.)*

- **Get nodes**: Lists all nodes in the cluster.
  ```bash
  kubectl get nodes
  ```
  *(Displays a list of all nodes.)*

- **Get all resources**: Lists all resources in the namespace.
  ```bash
  kubectl get all
  ```
  *(Shows all resources such as pods, services, deployments, etc., in the current namespace.)*

- **Describe a pod**: Provides detailed information about a specific pod.
  ```bash
  kubectl describe pod <pod-name>
  ```
  *(Gives detailed information about the pod named `<pod-name>`.)*

- **Get a service**: Lists information about a specific service.
  ```bash
  kubectl get svc <service-name>
  ```
  *(Displays information about the service named `<service-name>`.)*

- **Get a deployment**: Lists information about a specific deployment.
  ```bash
  kubectl get deployments <deployment-name>
  ```
  *(Displays information about the deployment named `<deployment-name>`.)*

- **Get contexts**: Lists all contexts in the kubeconfig file.
  ```bash
  kubectl config get-contexts
  ```
  *(Lists all contexts in the kubeconfig file.)*

- **Use a context**: Switches the current context to a specified cluster.
  ```bash
  kubectl config use-context <cluster-name>
  ```
  *(Switches the current context to the cluster named `<cluster-name>`.)*



