# Demo Mongo K8s project
1. MongoDB(DB pod with internal service pod) + MongoExpress(Frontend pod)
2. Config Map to storeDB URL
3. Secret to store DB User + DB Pwd
4. Create a deployment.yaml to save the env variable on the pod (e.g. ConfigMap and Secret)
5. We also need External service to call the frontend pod(Mongo Express) with URL and port number.
6. 