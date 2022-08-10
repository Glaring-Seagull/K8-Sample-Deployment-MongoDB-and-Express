This is a sample K8 deployment for MongoDB with Mongo Express web interface.

To use this collection, run the following commands in the order shown below.

1. kubectl apply -f mongo-secrect.yaml

2. kubectl apply -f mongo-deployment.yaml

3. kubectl apply -f mongo-configmap.yaml

4. kubectl apply -f mongo-express.yaml

If you want to use this sample as a starting point, please make sure to change the secrects!