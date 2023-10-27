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

_Risk and compliance_ [here](https://docs.aws.amazon.com/whitepapers/latest/aws-risk-and-compliance/aws-risk-and-compliance-program.html/)

---
