

# K8Studio
![screencast](https://github.com/guiqui/k8Studio/blob/master/Landing2.png)
## About
K8 Studio is a cross-platform client IDE to manage Kubernetes Clusters.
You can deploy easily to EKS, GKE, AKS, IBM Cloud, or your own bare metal. Connect to your cluster and have a graphical representation of your nodes, pods, services, etc. Access logs, element descriptions, and bash terminal with a single click.

For more info visit our website [k8studio](https://k8studio.io)
To watch a demo take a look at [our youtube channel](https://www.youtube.com/channel/UC84bcmR2JVP8MBeLEjXxHIA) that shows how to use the component.


## Join K8Studio Community
You can join our 
[Slack Channel](https://join.slack.com/t/k8studio/shared_invite/enQtNjgxMDU1NzkzMDc0LWM0ZTc3MjU5ZGIzN2MxMDhkOGFjOGNjYmU1YzI3YzRmMjUzNmU5ZjMxZTVlODMwZDY3ODY1NjhlM2NhYjVlODQ) for more information or to contact our team



# Features

#### MULTICLUSTER VIEW
With the multicluster view, you can have quick access to your clusters. This will give you a Multi Cluster summary view, providing you with monitoring information, the applications that have been deployed in the cluster, how many pods are running, and how many are pending or have an error. The first time that you open K8 Studio, the cluster configuration will be read from your local ./kube/config file. Additional Clusters can be added using the interface.
Project
![screencast](https://github.com/guiqui/k8Studio/blob/master/ClusterView.jpg)
#### DEPLOYMENT VIEW
With the interactive deployment cluster view you can quickly visualize the different workloads, their status and configuration, their network topology, their pods, pods status, the pod version running, rollouts and rollbacks. You can change any configuration by simply using the interface to add, delete, edit and push the changes to the cluster, all without needing to remember the right command.
![screencast](https://github.com/guiqui/k8Studio/blob/master/Deployment.png)

#### GRID VIEW
Grid View isn't just about the big picture; it's your gateway to an ocean of in-depth information, helping you understand, troubleshoot, and optimize your Kubernetes infrastructure like never before.\
![screencast](https://github.com/guiqui/k8Studio/blob/master/Grid.png)

#### RBAC MANAGER
Effortlessly handle users, groups, service accounts, and roles using the intuitive RBAC interface in K8Studio. Simplify access control, configure permissions, and efficiently manage role assignments within your Kubernetes environment. With the RBAC Manager, enhancing the security and control of your clusters has never been easier.
![screencast](https://github.com/guiqui/k8Studio/blob/master/Rbac.png)

#### HELM MANAGER
Simplify chart and Helm release management with the K8Studio Helm Manager. Streamline the installation, monitoring, and oversight of your Helm charts, making your Kubernetes operations more efficient.
![screencast](https://github.com/guiqui/k8Studio/blob/master/Helm.png)

#### NODE VIEW
The node cluster view will show you all the nodes that are running, what type of node, the pod and the containers that are running in each pod. For each one of the pods, it will show the status, the services and ingresses. With this information it will draw the network topology showing port, addresses and dependencies, PVCS, PV and Storage Classes will also be displayed showing all the relevant information. Once the view is opened it will be connected to the events of the Kubernetes API which means that the data is live and updated.

#### FILTER AND SEARCH
You can easily search any element in the workspace using the search bar. It will find anything that matches the query by label, name, image name, etc. We also provide a filter interface where you can choose the visible namespaces, labels or object types.

#### TOOLBOX
The Toolbox contains all of the object types available in Kubernetes classified in workloads, network, storage configuration and security. You can select an element in the Toolbox and drag and drop to the Interactive View or the Project Tree. This will create an object and its corresponding file with the right minimal content.

#### QUICK EDITOR
Once an element is selected, the Editor View provides many ways to edit the content of the elements. Our favorite one is the Quick Editor. The Quick Editor gives a structured representation of the YML of the file. Because it is aware of the JSON Schema of the object, it gives you the right suggestion when adding elements, it can validate the file and can provide you with the description of the properties so you can know what they are used for.

The Quick Editor provides access to the many Helpers:

Docker: To quickly find the image that you are looking for.
Label: To find the available labels in your cluster or configuration context.
Volume: To find the PVS, PVCS or storage Classes in your cluster or configuration context.
RBAC: To look for services accounts and understand roles and rules.
Secret: To find the secrets in your cluster or configuration context.
Configmap: To find the Configmaps in your cluster or configuration context.
![screencast](https://github.com/guiqui/k8Studio/blob/master/QuickEditor.png)

#### YML EDITOR
We have also included a YML Editor for all of you that are familiar with YML and the object structure of Kubernetes. The YML Editor includes syntax highlighter and keyword auto-completion. Once a YML file has been edited, the content gets validated, then the interface reflects the changes and K8s Studio updates the files.

#### CONFIGURATION
With the configmap and secret view you can easily manage your configurations, delete, create new ones or modify the key-value pairs. When working with Secret we also help you out with our inline base64 encoder and decoder.

#### SSH AND LOGS
If you have a pod or node selected you can connect with SSH to access the machine or read their logs using our built-in Terminal without needing to remember any command line or address.
Projects
#### EXPORT
The Cluster View gives you many ways of exporting your objects. You can export a selected element to a YAML file or you can dump the full cluster configuration filter by namespaces to the project folder. You also have the option to export the existing view to SVG or HTML to help you out with your documentation.
Projects





