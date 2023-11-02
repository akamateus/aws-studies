# 📺 AWS Regions, Availability Zones & Edge Locations

- Region: Physical location, 26 regions. Choose the best location based on your end-user(costumers). Your data is isolated in a region by default.
  _Important fact:_ AWS regions contain 2 or more AZs.

- Availability Zones: Is a logical zone, made by one or more data centers.

---

# 📺 Multi-Region Use Cases

1. Compliance Requirements: Data Residency, Company Policy, Business Reasons

2. AWS Service Availability: Are the services you require available here/there?

3. Regions closest to your customers: Reduced application latency (Happy costumers)

4. Regional Costs: Check the price differences of services and data transfer

---

# 📺 AWS Service Categories

## Amazon EC2

Hypervisor

Horizontal Scaling or Vertical Scaling

---

# 📺 AWS EC2 Instance types & Serverless Compute on Amazon Web Services

_Check the Instance Types_ [here](https://aws.amazon.com/pm/ec2/?trk=b59ef3d1-61fa-4eea-9a0b-96fbd6584e69&sc_channel=ps&ef_id=Cj0KCQjw-pyqBhDmARIsAKd9XIO82ID1IwteU4A7FztJy3u2v8LczBKwWm4DMojU9z_dJO0l0gU0uFwaArNHEALw_wcB:G:s&s_kwcid=AL!4422!3!645133569804!e!!g!!amazon%20ec2%20instance!19579892353!148838338441)

_Amazon Elastic Container Service_ [here](https://aws.amazon.com/ecs/): Amazon Elastic Container Service (ECS): Is a fully managed container orchestration service that helps you to more efficiently deploy, manage, and scale containerized applications. It deeply integrates with the AWS environment to provide an easy-to-use solution for running container workloads in the cloud and on premises with advanced security features using Amazon ECS Anywhere.

_Check the AWS Lambda_ [here](https://aws.amazon.com/pm/lambda/?trk=5e541ab3-2fcc-4151-9e08-fdea53dc7fb8&sc_channel=ps&ef_id=Cj0KCQiAuqKqBhDxARIsAFZELmKTw-AO4Rgas0muqz8ayKzsF446Ja2e25xxrvXBLzC0-U1GUhIBcWAaAhFzEALw_wcB:G:s&s_kwcid=AL!4422!3!651541907473!e!!g!!aws%20lambda!19836375769!150670855801): By combining AWS Lambda with other AWS services, developers can build powerful web applications that automatically scale up and down and run in a highly available configuration across multiple data centers – with zero administrative effort required for scalability, back-ups, or multi-data center redundancy.

_Amazon EKS_ [here](https://aws.amazon.com/eks/): Amazon Elastic Kubernetes Service (Amazon EKS) is a managed Kubernetes service to run Kubernetes in the AWS cloud and on-premises data centers. In the cloud, Amazon EKS automatically manages the availability and scalability of the Kubernetes control plane nodes responsible for scheduling containers, managing application availability, storing cluster data, and other key tasks. With Amazon EKS, you can take advantage of all the performance, scale, reliability, and availability of AWS infrastructure, as well as integrations with AWS networking and security services. On-premises, EKS provides a consistent, fully-supported Kubernetes solution with integrated tooling and simple deployment to AWS Outposts, virtual machines, or bare metal servers.

---

# 📺 EC2 Auto Scaling Groups (ASG)
