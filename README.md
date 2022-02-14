# Redis
Setup redis cluster 
https://artifacthub.io/packages/helm/bitnami/redis-cluster 

## Set redis addr in values.yaml, use following format: 
```
<redis-service>.<redis-namespace>:<port> 
```

# Registry
Set all necessary variables in values.yaml 

Set AWS S3 bucket options and access key  
Generate htpasswd file and paste it as configmap in values.yaml  

