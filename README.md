# fantastic-octo-fiesta

## Congratulations on making it to the next step in the interview process

  As part of the assessment, we'd like you to demonstrate your expertise in configuring Azure services to support multiple software development teams and setting up essential components like virtual networks, subnets, load balancing, monitoring, and databases. Additionally, we'd like to gauge your familiarity with Infrastructure as Code (IaC) practices.

Imagine you have determined that a new environment must be configured as show below.

### Task 1: Virtual Network Setup

Create a virtual network (VNet) named "DevVNet" in Azure.
Within the VNet, set up three subnets: "Web", "App", and "Database".
Define appropriate address ranges for each subnet to ensure isolation and efficient IP management.

### Task 2: Load Balancing and High Availability

Set up an internal load balancer named "AppLB" to distribute traffic to the "Web" and "App" subnets.
Configure the load balancer to ensure high availability and fault tolerance for the application.
Implement health probes to monitor the availability of backend services.

### Task 3: Database Configuration

Deploy an Azure SQL Database instance named "DevDB" within the "Database" subnet.
Configure appropriate firewall rules to allow access from the "App" subnet only.
Implement geo-replication for disaster recovery and data redundancy.

### Task 4: Monitoring and Logging

Set up Azure Monitor to collect telemetry data from all resources in the virtual network.
Configure alerts to notify the operations team when specific performance thresholds are exceeded.

Submission Guidelines:

Utilize an Infrastructure as Code (IaC) tool of your choice (e.g., Azure Resource Manager templates, Terraform) to automate the deployment of the entire infrastructure described above.

Provide documentation explaining your approach and rationale for each task.
Include the IaC code or templates used to achieve the infrastructure setup.

Submit your solution as a GitHub repository, Azure DevOps repository, or other suitable version control platform.

Note: Feel free to use Azure's free tier for services, and ensure that sensitive information is not included in your submission.

Please complete the tasks and submit your solution within the next week. If you have any questions or need clarification on any aspect of the assessment, don't hesitate to reach out.
