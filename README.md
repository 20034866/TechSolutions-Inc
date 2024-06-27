## CLOUDTECH SOLUTIONS INC
### What does the company do?
The company specializes in managing and operating IT infrastructure for small to medium sized enterprises, focusing on server management, network management,  security and system monitoring. They are currently transitioning from an on-premises server setup to cloud based infrastructure to enhance scalability, cost efficiency, accessibility and disaster recovery.
### What are we trying to solve in this Assignment?
In this assignment, we are addressing the following challenges 
1. Scalability Issues
* Increased Demand:
When there is an increase in demand for the company's software solutions, the current on-premises infrastructure struggles to handle the increased load, leading to performance degradation and longer deployment times.
* New Projects:
Onboarding new projects or clients may sometimes demand more computing capability to meet the needs of the clients. The current setup faces difficulty when it comes to quickly growing the resource allocation to meet these new needs.
* Remote Access:
important documents and other resources, and this results in a number of drawbacks such as when there is a need to complete tasks in minimum time, or when there are certain conditions that require high numbers of employees who may work from homeIt is challenging for employers to allow their employees to have remote access to.
2. Disaster Recovery and Backup
The most important aspect that must be pushed in terms of implementation and management is backups since their absence can lead to catastrophic data loss. However, the establishment of an efficient backup management program is quite a challenge, and procedures involve considerable use of resources.
•	Energy Consumption and Cost:
The servers deployed in large on-premises infrastructure environments are power hogs, and high energy costs lead to even higher project expenses.
•	Vendor Lock-In:
The organization could find itself tied to certain vendors for equipment, systems, and assistance, which is a disadvantage. In general, customization can be possible, but it can even prove to be very time-consuming and demands a certain level of expertise.


### Current infrastructure on high level and problems on high level .
The server framework, besides the fundamental brackets, includes many elements such as a CPU, RAM, hard or solid-state drives, NICs, a stable power source, and a cooling system to avoid heat-related issues. These components monitor the throughput of the system’s traffic by setting up various network protocols and other aspects such as different ports. They make sure that several appliances in the network are linked and the messages in the system are promptly transmitted inside the internal network To shield the whole infrastructure from malicious programs, the company has it installed with a robust anti-virus system, and an intrusion detection system to monitor for possible activities. They also maintain an authentication control and a delegation control system to control the access rights of each member properly.

### Recommended architecture and it benefits.
Organizations can easily migrate to any of the popular clouds like AWS, GCP, Azure or any other of their choice to avail the benefits for the customers We recommend AWS, and thus all comparisons will be based on AWS services.
For the IaaS the company can take advantage of AWS Elastic Compute Cloud (EC2) which is based on virtual machines that offer a selection of operating systems and storage and RAM configurations. Load balancing can be added to EC2 instances so that it can assist in balancing traffic flow in and out of the server. An API Gateway and Route 53 can be used to provide specific domain names for customers according to their requirements. AWS CloudWatch alarms can be configured to prevent the creation of charges/fees in AWS accounts.
In the scope of database hosting, an excellent relational database service is provided by AWS which is called RDS (Relational Database Service). AWS S3 can be used for secure data storage, ensuring data does not leave their environment. AWS Secrets Manager can secure the storage of environment variables and secret keys. For Continuous Integration/Continuous Deployment (CI/CD) processes, Platform as a Service (PaaS) AWS Elastic Beanstalk can be used without the need to handle underlying infrastructure, AWS ECR can store container images, which can be deployed on EC2 instances for each version release.
In terms of the Software as a Service (SaaS) model, the company may create a cloud security management division to supervise the infrastructure. They can then make use of observability tools such as Prometheus for dealings with the monitor and alert dashboards. For email automation, they can use AWS SNS i.e., Simple Notification Service.
Using all the above-mentioned AWS services, any potential client that the company may come across will not experience what previous clients faced. 
##### Here’s how the new architecture addresses each problem:
1. Cost Efficiency:
There are possible solutions to avoid overspending or micromanaging expenses, such as using AWS CloudWatch to identify and track costs and cost management tools like AWS Cost Explorer to calculate clients’ budgets in advance based on possible project costs. Another difficulty that arises with on-premises servers is in making such precise cost predictions. As for the costs in the cloud, we can consider utilizing Optional instances or committed use discounts for predictable workloads. Monitoring our resources’ consumption and adjusting the resource capacity helps avoid the wastage of resources that were purchased in bulk or procured and were not used to their full potential.
 
2. Scaling:
With AWS Load Balancer attached to EC2 instances, traffic can be efficiently distributed among available instances, reducing latency. Auto-scaling maximally makes changes dynamically to the available resources to improve the application’s performance to meet the user’s demand. On the other hand, vertical scaling of on-premises servers is a more complicated process and can often fall short of horizontal scaling’s ideal results. Establishing physical diminishing is also possible when scaling vertically by adding more RAM is easier in the cloud. Also, it can be easily cloned for new projects, and it will not be time-consuming at all.
3. Security and Backup:
To enable a strong network security, AWS keeps the entire network within a single VPC. The information is protected in transit and when stored in the database. Unauthorized physical access is prevented through access controls, and authentication key mechanisms forestall potential attacks. The security monitoring is done on a continuous basis with AWS GuardDuty providing notifications to CloudWatch about any behavioural detections. While on-premises security systems have the disadvantage of physical security threat such as natural disasters which can easily compromise the security of data, on-cloud security data can be backed up in other datacentres or availability zones to avoid exposure.
4. Vendor Lock-In and Accessibility:
This can be in the form of accommodating multiple operating systems, multiple CPU architectures, or supporting multiple hardware vendors without any long-term obligations. VDI enables employees to access virtual desktops from anywhere making it an added advantage in the File and Remote working. The overall administration of the desktop is also made easier in a centralized VDI, and the management of updates, security, and user settings or software is also made easier by the VDI.

### Explaining benefits in terms of cost.
Total Estimated Monthly Cost
Sum of all services:
* Amazon EC2: $7.67
* Amazon RDS: $1.14
* Amazon S3: $0.71
* AWS Secrets Manager: $2.00
* Amazon ECR: $0.24
* Amazon API Gateway: $15.75
* Amazon Route 53: $1.53
* Amazon CloudWatch: $4.75
* Amazon GuardDuty: $8.78
* Amazon SNS: $21.21
 
Total: $63.78 per month 

