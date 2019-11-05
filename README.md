

# K8 Studio
![screencast](https://media.giphy.com/media/eHjRZn9eoX6Ca670dD/giphy.gif)
## About
K8 Studio is a cross-platform client IDE to manage Kubernetes Clusters.
You can deploy easily to EKS, GKE, AKS, IBM Cloud or your own bare metal. Connect to your cluster and have a graphical representation of your nodes, pods, services, etc. Access logs, element descriptions and bash terminal with a single click.



 To watch a demo take a look at [video](https://youtu.be/ac2jRN1vbkQ) that shows how to use the component.
 
## Installation
Download the right version.

| OS            | Version   | Link                        |
| ------------- |:-------:| -----------------------------------:|
| Mac         | 0.2.12  | [download](https://github.com/guiqui/k8Studio/releases/download/v0.2.12/K8Studio-0.2.12-osx.dmg)  |
| Window           | 0.2.12     | [download](https://github.com/guiqui/k8Studio/releases/download/v0.2.12/K8Studio-Setup.0.2.12.exe)          |
| Linux Debian          | 0.2.12   | [download](https://github.com/guiqui/k8Studio/releases/download/v0.2.12/K8Studio-0.2.12-amd64-linux.deb) |
| Linux Rpm          | 0.2.12   | [download](https://github.com/guiqui/k8Studio/releases/download/v0.2.12/K8Studio-0.2.12-x86_64-linux.rpm) |


# Features

#### MULTICLUSTER VIEW
With the multicluster view you can have quick access to your clusters. This will give you a Multi Cluster summary view giving you monitoring information, the applications that have been deployed in the cluster, how many pods are running and how many are pending or have an error. The first time that you open K8 Studio the cluster configuration will be read from your local ./kube/config file. Additional Clusters can be added using the interface.
Projects
#### DEPLOYMENT VIEW
With the interactive deployment cluster view you can quickly visualises the different workloads, their status and configuration, their network topology, their pods, pods status, the pod version running, rollouts and rollbacks.You can change any configuration by simple using the interface to add, delete, edit and pushing the changes to the cluster.All without needing to know or remember the right command line.
Projects
#### NODE VIEW
The node cluster view will show you all the nodes that are running, what type of node, the pod and containers that are running in each pod. For each one of the pods, it will show the status. It will show the services, ingresses and policies. With this information it will draw the network topology showing port, addresses and dependencies, PVCS,PV and Storage Classes will also be displayed showing all the relevant information. Once the view is opened it will be connected to the events of the Kubernetes API which means that the data is live and updated.
Projects
FILTER AND SEARCH
You can easily search any element in the workspace using the search bar. It works as a google search bar and it will find anything that matches the query by label, name, image name, etc. We also provide a filter interface where you can choose the visible namespaces, labels or object types.
Projects
#### TOOLBOX
The Toolbox contains all of the object types available in Kubernetes classified in workloads, network, storage configuration and security. You can select an element in the Toolbox and drag and drop to the Interactive View or the Project Tree. This will create an object and its corresponding file with the right minimal content.
Projects
#### MAGIC TREE
Once an element is selected, the Editor View provides with many ways of editing the content of the elements. Our favourite one is the Magic Tree. The Magic Tree gives a structured representation of the YML of the file. Because it is aware of the JSON Schema of the object, it gives you the right suggestion when adding elements, can validate the file and can provide you with the description of the properties so you can know what they are used for.

The Magic Tree provides access to the many Helpers:

Docker: To quickly find the image that you are looking for.
Label: To find the available labels in your cluster or configuration context.
Volume: To find the PVS, PVCS or storage Classes in your cluster or configuration context.
RBAC: To look for services accounts and understand roles and rules.
Secret: To find the secrets in your cluster or configuration context.
Configmap: To find the Configmaps in your cluster or configuration context.
Projects
#### YML EDITOR
We have also included a YML Editor, for all of you that are familiar with YML and the object structure of Kubernetes. The YML Editor includes syntax highlighter and keyword auto-completion. Once a YML file has been edited, the content gets validated, then the interface reflects the changes and K8s Studio updates the files.
Projects
#### CONFIGURATION
With the configmap and secret view you can easily manage your configurations, delete, create new ones or modify the key value pairs.When working with secrest we also help you out with our inline base64 encoder and decoder.
Projects
#### RBAC EDITOR
The Cluster View provides a comprehensive RBAC Editor. You can add user accounts, service accounts, cluster roles and roles. You can bind users to roles and you can have a view of the rules applied to the users.Also you can easily visualize the combinations of permissions that a Service account or a role has.
Projects
#### SSH AND LOGS
If you have a pod or node selected you can connect with SSH to access the machine or read their logs using our built in Terminal.No need to remember any command line or address.
Projects
#### EXPORT
The Cluster View gives you many ways of exporting your objects. You can export a selected element to YAML file or you can dump the full cluster configuration filter by namespaces to project folder. You also have the option to export the existing view to SVG or HTML to help you out with your documentation.
Projects

# Tutorials

[Interface Overview](https://youtu.be/TJyXtB5t3cU)

[Creating or Registering a Cluster](https://youtu.be/nnBabVRyDQY)

[Creating a Deployment](https://youtu.be/L3PsJ5sVcFE)

[Creating a Service](https://youtu.be/W5zAcbnmT3A)

[Creating an Ingress](https://youtu.be/hrEdRGBYdso)


