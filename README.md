## Create a VPC using cloudformation Stack template 
https://s3.us-west-2.amazonaws.com/amazon-eks/cloudformation/2020-10-29/amazon-eks-vpc-private-subnets.yaml

2. Create roles for EKS-Cluster and eksNodeGroup
   EKS-Cluster - AmazonEKSClusterPolicy
   WorkerNode - AmazonEKSWorkerNodePolicy, AmazonEKS_CNI_Policy, AmazonEC2ContainerRegistryReadOnly

   
