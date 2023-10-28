# 📺 Security and Compliance

## Designing for failure

---

# 📺 AWS Shared Responsibility Model

**AWS responsibility “Security of the Cloud”** is responsible for protecting the infrastructure that runs all of the services offered in the AWS Cloud. This infrastructure is composed of the hardware, software, networking, and facilities that run AWS Cloud services.

**Customer responsibility “Security in the Cloud”** will be determined by the AWS Cloud services that a customer selects. This determines the amount of configuration work the customer must perform as part of their security responsibilities. For example, a service such as Amazon Elastic Compute Cloud (Amazon EC2) is categorized as Infrastructure as a Service (IaaS) and, as such, requires the customer to perform all of the necessary security configuration and management tasks.

**Iherited Controls** – Controls which a customer fully inherits from AWS.

- Physical and Environmental controls

**Shared Controls** – Controls which apply to both the infrastructure layer and customer layers, but in completely separate contexts or perspectives. In a shared control, AWS provides the requirements for the infrastructure and the customer must provide their own control implementation within their use of AWS services. Examples include:

**Patch Management** – AWS is responsible for patching and fixing flaws within the infrastructure, but customers are responsible for patching their guest OS and applications.

**Configuration Management** – AWS maintains the configuration of its infrastructure devices, but a customer is responsible for configuring their own guest operating systems, databases, and applications.

**Awareness & Training** - AWS trains AWS employees, but a customer must train their own employees.

**Customer Specific** – Controls which are solely the responsibility of the customer based on the application they are deploying within AWS services. Examples include:

- Service and Communications Protection or Zone Security which may require a customer to route or zone data within specific security environments.

_Check Shared Responsibility Model_ [here](https://aws.amazon.com/compliance/shared-responsibility-model/)

---

# 📺 Locating AWS Compliance Information

AWS customers are responsible for maintaining adequate governance over their entire IT control environment, regardless of how or where IT is deployed. Leading practices include:

- Understanding the required compliance objectives and requirements (from relevant sources)

- Establishing a control environment that meets those objectives and requirements

- Understanding the validation required based on the organization’s risk tolerance

- Verifying the operating effectiveness of their control environment

**Deployment in the AWS Cloud gives enterprises different options to apply various types of controls and various verification methods.**

_Risk and compliance_ [here](https://docs.aws.amazon.com/whitepapers/latest/aws-risk-and-compliance/aws-risk-and-compliance-program.html)

---

# 📺 Encryption Options on AWS

- Encryption at REST, in transit, in motion

_Security Pillar - AWS Well-Architected Framework_ [here](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html)

---

# 📺 AWS Use Rooter

- Enable Multi-factor authentication or MFA

- IAM SOO users

## do not use root for day-to-day operations:

- need the scope of privileges the root user provides

---

# 📺 Multi-factor Authentication (MFA)

## We need to provide multiple authentication in order to provide more safety. This third part can be your phone, your email, finger print etc.

## in AWS we have:

1. Virtual MFA devices: A software app that runs on a phone or other device and emulates a physical device.

2. U2F security key: A device that you plug into a USB port on your computer.

3. Hardware MFA device: A hardware device that generates a six digit numeric code based upon a time-synchronized one-time pass.

_Enabling MFA devices for users in AWS_ [here](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable.html)

---

# 📺 AWS Identity and Access Management (AIM)

## AIM provides the authentication and Authorization control

## AIM is a global service

you dont need to setup for each region

_Temporary security credentials in IAM_ [here](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_temp.html)

---

# 📺 AWS Market place

https://aws.amazon.com/marketplace

Check the products [here](https://aws.amazon.com/marketplace)

---

# 📺 AWS Trusted Advisor

Is the tool AWS provide for management console:

1. Cost Optimization: ways to reduce wastes cloud costs

2. Performance: Ways to improve application responsiveness

3. Security: ways to keep your workload more secure

4. Fault Tolerance: Ways to improve your application uptime

5. Service Limits: Avoid hitting service quota limits
