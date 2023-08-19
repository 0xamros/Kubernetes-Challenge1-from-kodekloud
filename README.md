# Kubernetes-Challenge1-from-kodekloud
# 1- martin
## Task 1.1: Build User Information for Martin in kubeconfig

### User Information for Martin
- User: martin
- Client Key: /root/martin.key
- Client Certificate: /root/martin.crt

Note: Make sure not to embed the client key and certificate within the kubeconfig file.

## Task 1.2: Create a New Context called 'developer'

### New Context 'developer'
- User: martin
- Cluster: kubernetes

# 2- developer-role
## Task 2.1: the required permissions for the 'developer-role' in the 'development' namespace of our Kubernetes cluster. The 'developer-role' is responsible for managing various resources within the namespace.
- 'developer-role', should have all(*) permissions for services in development namespace

- 'developer-role', should have all permissions(*) for persistentvolumeclaims in development namespace

- 'developer-role', should have all(*) permissions for pods in development namespace

# 3- developer-rolebinding
## Task 3.1:
- create rolebinding = developer-rolebinding, role= 'developer-role', namespace = development

- rolebinding = developer-rolebinding associated with user = 'martin'

# 4- kube-config
## Task 4.1:
- set context 'developer' with user = 'martin' and cluster = 'kubernetes' as the current context.

# 5- 
