# k8sinaction
Kubernetes for common YAML files

This repo contains a collection of YAML files; which is a way how Kubernetes objects are represented in the Kubernetes API. YAML files are name/value pairs which is convenient to use when you are trying to set up configuration information.

The section of YAML files consists of the below things:

1. The **apiVersion** and **kind** of object to be used
2. The **metadata** will have the information like
   1. Name of the pod
   2. Label used to identify the pod
3. Finally, this will have the information which make up the pod. The **spec** property includes any containers, port or other pieces that Kubernetes needs to know about, as well as properties such as to restart the container if it fails or restart the pod, if it gets deleted.