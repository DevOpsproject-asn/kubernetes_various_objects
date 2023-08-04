# kubernetes_various_objects
# kubectl apply -f < manifestfilename >
# Pod creating on kubernetes cluster
# RC ( ReplicationController  responsible for managing the pod lifecycle ) created object.
# RS(ReplicaSet is the next-generation Replication, only differnce is selector support. Means ReplicaSet supports the new set-based selector requirements as described in the labels  whereas a Replication Controller only supports equality-based selector requirements) created object
# Deploment RollingUpdate create for slowly slowly create pod and slowly slowly delete the pod, it's high availabilty without cluster downtime it's replace new pods.
# Deployment Recreate strategy create, it's at time all pod delete it and receate all pod again. So somedowntime is their in this Deployment strategy.
# Resources Requests & limit set up on Deployment pods. We can manage the cluster resources by using set this Resources requests & limits.
