# kubernetes-nginx-manifest and how to manually run them using the kubectl CLI 

# kubectl apply -f nginx-deployment.yaml

# kubectl apply -f nginx-service.yaml

# kubectl apply -f nginx-configmap.yaml

# kubectl apply -f nginx-secret.yaml

# Base 64 encoding and decoding 

echo -n "Hello, World!" | base64

# Decode 

echo -n "SGVsbG8sIFdvcmxkIQ==" | base64 -d
