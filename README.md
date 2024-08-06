# Cloud-Work
Multi cloud Infrastructure Work

I’ve successfully completed a project where I set up and hosted a dynamic web application using Kubernetes and Amazon EKS. This project deepened my understanding of container orchestration. Here’s an overview:

Project Highlights:

• Version Control: Used Git and GitHub for seamless collaboration.
• Containerization: Created Dockerfiles and containerized the application.
• AWS Setup: Configured AWS services including ECR, RDS, and Secret Manager.
• ECR Integration: Built and pushed Docker images to Amazon ECR.
• Data Management: Migrated application data to Amazon RDS.
• Kubernetes Tools: Managed clusters with kubectl, eksctl, and Helm.
• Security: Secured sensitive information with AWS Secrets Manager.
• Cluster Setup: Deployed and managed an EKS cluster.
• Deployment: Deployed applications using Kubernetes manifests.
• DNS Configuration: Set up DNS for seamless application access.
• VPC Setup: Created a VPC with subnets, NAT gateways, and route tables.
• Command Line Operations: Executed setup and deployment via terminal commands.
• EC2 Instance Connect Endpoint: Secured data migration, terminating the instance post-migration.


Understanding AWS EKS and Worker Nodes:

• Control Plane: AWS EKS manages the Kubernetes control plane, which includes the API server and the etcd database. This is fully managed by AWS, ensuring high availability and scalability.
• Worker Nodes: The worker nodes, which run the actual application workloads, are EC2 instances registered with the EKS cluster. Set up Auto Scaling groups to manage the number of worker nodes based on demand, ensuring the application can handle varying loads efficiently.
• Networking: Configured networking settings to ensure secure and efficient communication between the control plane and worker nodes, and among the worker nodes themselves.
• Monitoring and Logging: Integrated CloudWatch for monitoring and logging, enabling us to keep track of the performance and health of the EKS cluster.

Key Learning Outcomes:
• Integrated Docker and Kubernetes with AWS services.
• Practiced container orchestration and management.
• Enhanced skills in secure secret management and data migration.
• Deepened understanding of EKS, worker nodes, control planes, and networking.
• Adapted the LAMP (Linux, Apache, MySQL, PHP) stack to a cloud-native architecture.
• Designed and implemented a robust VPC from scratch.
