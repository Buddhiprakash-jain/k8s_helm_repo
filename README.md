# k8s_helm_repo

## Helm Chart for Run the Linux Commands in Browser through Flask.

## Steps to be followed for Accessing the Helm Chart:-
1. Download the folder flask_linux_cmd in your pc.
2. Launch a Kubernetes Cluster on AWS.
3. Copy the flask_linux_cmd folder in k8s_master_node.
4. Run Command "helm install flask_cmd flask_linux_cmd/"
5.  - at the palce of "flask_cmd" you can give any name.
6.  - in last give your chart name(folder name is name of your chart that is "flask_linux_cmd/").
7. Run command "kubectl get svc" and get the port number
8. Search in Browser "https://<instance_public_ip>:<svc_port_number>".
9. finally u can access your page and run linux commands.
10.  

