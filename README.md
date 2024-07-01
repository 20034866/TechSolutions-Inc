## TECHSOLUTIONS-INC

### Tagline – Private Cloud, Delivered Locally 
### Business Type – Small & Medium sized Enterprise (SME)
### Industry – Cloud Computing
### Headquarters – Cork, Ireland

### Mission Statement - CloudTech Solutions is a small and dedicated enterprise, providing cloud services to the upcoming and newly formed organization using on-premises data centers, ensuring privacy, control, and performance to its clients tailored specifically to their needs.

### Business Idea – CloudTech Solutions is a small enterprise providing local support to up-and-coming newly formed companies, catering to their personal needs and requirements. With their on-premises data centers and servers, they can handle and deliver public, private, and hybrid cloud while focusing on Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS).  


### What does the company do?
CloudTech Solutions is a small enterprise providing local support to up-and-coming newly formed companies, catering to their personal needs and requirements. With their on-premises data centers and servers, they can handle and deliver public, private, and hybrid cloud while focusing on Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS). They offer on-premises private cloud solutions, Hybrid cloud integration, Manage hosting services, Custom IT infra solutions for thier clients, and provide consulting and support services. 


### What are we trying to solve in this Assignment?
In this assignment, we are addressing the following challenges faced by CloudTech Solutions
1. Scalability Issues related to demands, new projects, and remote access.
2. Disaster Recovery and Backup
3. Energy Consumption and its cost
4. Vendor lock-in


### Current infrastructure 
The SME operates all its computing processes on an on-premises server located within the organization's premises. This robust architecture can handle a significant network load. The system's components are as follows:
1. Server Hardware:
The server framework, besides the fundamental brackets, includes many elements such as a CPU, RAM, hard or solid-state drives, NICs, a stable power source, and a cooling system to avoid heat-related issues.
2. Network Components:
These components monitor the throughput of the system’s traffic by setting up various network protocols and other aspects such as different ports. They make sure that several appliances in the network are linked and the messages in the system are promptly transmitted inside the internal network.
3. Operating System:
The company uses Ubuntu Linux as its primary operating system.
4. Server Software:
The server contains the software environment to support any kind of application. It features a Nginx HTTP server as a Web server for hosting those Web applications, an application server, and a PostgreSQL Database Management System for Create, Read, Update, and Delete operations. Also, it has applications that can be used in storing and sharing files and backing up software in cases of data loss.
5. Security Components:
To shield the whole infrastructure from malicious programs, the company has it installed with a robust anti-virus system, and an intrusion detection system to monitor for possible activities. They also maintain an authentication control and a delegation control system to control the access rights of each member properly.
6. Management and Monitoring Tools:
Monitoring tools are also highlighted as an essential component that the company should implement. Some of the tools they use include Nagios for monitoring and alerting services for servers, switches, applications, and services. Also, they use Puppet to manage and automate the server picture.



### Recommended architecture and it benefits.
Organizations can easily migrate to any of the popular clouds like AWS, GCP, Azure, or any other of their choice to avail the benefits for the customers We recommend AWS, and thus all comparisons will be based on AWS services.
For the IaaS the company can take advantage of AWS Elastic Compute Cloud (EC2) which is based on virtual machines that offer a selection of operating systems and storage and RAM configurations. Load balancing can be added to EC2 instances so that it can assist in balancing traffic flow in and out of the server. An API Gateway and Route 53 can be used to provide specific domain names for customers according to their requirements. AWS CloudWatch alarms can be configured to prevent the creation of charges/fees in AWS accounts.
In the scope of database hosting, an excellent relational database service is provided by AWS which is called RDS (Relational Database Service). AWS S3 can be used for secure data storage, ensuring data does not leave their environment. AWS Secrets Manager can secure the storage of environment variables and secret keys. For Continuous Integration/Continuous Deployment (CI/CD) processes, Platform as a Service (PaaS) AWS Elastic Beanstalk can be used without the need to handle underlying infrastructure, AWS ECR can store container images, which can be deployed on EC2 instances for each version release.
In terms of the Software as a Service (SaaS) model, the company may create a cloud security management division to supervise the infrastructure. They can then make use of observability tools such as Prometheus for dealings with the monitor and alert dashboards. For email automation, they can use AWS SNS i.e., Simple Notification Service.
Cost Efficiency:
There are possible solutions to avoid overspending or micromanaging expenses, such as using AWS CloudWatch to identify and track costs and cost management tools like AWS Cost Explorer to calculate clients’ budgets in advance based on possible project costs. Another difficulty that arises with on-premises servers is in making such precise cost predictions. As for the costs in the cloud, we can consider utilizing Optional instances or committed use discounts for predictable workloads. Monitoring our resources’ consumption and adjusting the resource capacity helps avoid the wastage of resources that were purchased in bulk or procured and were not used to their full potential.
 Scaling:
With AWS Load Balancer attached to EC2 instances, traffic can be efficiently distributed among available instances, reducing latency. Auto-scaling maximally makes changes dynamically to the available resources to improve the application’s performance to meet the user’s demand. On the other hand, vertical scaling of on-premises servers is a more complicated process and can often fall short of horizontal scaling’s ideal results. Establishing physical diminishing is also possible when scaling vertically by adding more RAM is easier in the cloud. Also, it can be easily cloned for new projects, and it will not be time-consuming at all.
Security and Backup:
To enable a strong network security, AWS keeps the entire network within a single VPC. The information is protected in transit and when stored in the database. Unauthorized physical access is prevented through access controls, and authentication key mechanisms forestall potential attacks. The security monitoring is done on a continuous basis with AWS GuardDuty providing notifications to CloudWatch about any behavioural detections. While on-premises security systems have the disadvantage of physical security threat such as natural disasters which can easily compromise the security of data, on-cloud security data can be backed up in other datacentres or availability zones to avoid exposure.
Vendor Lock-In and Accessibility:
This can be in the form of accommodating multiple operating systems, multiple CPU architectures, or supporting multiple hardware vendors without any long-term obligations. VDI enables employees to access virtual desktops from anywhere making it an added advantage in the File and Remote working. The overall administration of the desktop is also made easier in a centralized VDI, and the management of updates, security, and user settings or software is also made easier by the VDI. 



### Details of cost (in months and dollars).
EC2 instance for web server                 - USD 60.74
EC2 instace for application server          - USD 60.30
EC2 instance for database server            - USD 30.08
EC2 instance for file storage               - USD 15.04
EC2 instance for development and testing    - USD 15.04
EC2 instance for backup and maintainence    - USD 7.52
Elastic LoadBalancer                        - USD 74.83
RDS production database                     - USD 2420.32
RDS for development and testing             - USD 733.68 

Total monthly cost in dollars               - USD 2806.15

Total yearly cost in dollars                - USD 33673.80

As we can see from the monthly cost, its quite feasible and less as compared to the on-premises setup.
