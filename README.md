<h1>How to migrate database in AWS</h1>

<h2>Description</h2>
In this project I will be demonstrating how to migrate a simple web application from an on-premises environment into AWS. The on-premises environment is a virtual web server simulated using EC2 and a self-managed MariaDB database server also simulated via EC2.
<br />


<h2>Services Used</h2>

- <b>VPC</b>
- <b>EC2</b>
- <b>RDS</b> 
- <b>DMS</b>

<h2>Environments Used </h2>

- <b>AWS</b>

<h2>Program walk-through:</h2>
<H3>Step 1 - Implement private connectivity between the environments</H3>

<H3>Step 2 - Create & Configure the AWS Side infrastructure</H3>

From here I provision the EC2 instance which function as the AWS web server.

This screenshot shows that all the WordPress assets has been copied from this server to the AWS EC2 instance.



<H3>Step 3 - Migrate Database</H3>



In this section I created subnet groups, replication instance, endpoints and database migration tasks.

<img src="https://i.imgur.com/x3mLIuG.png" height="80%" width="80%" alt="Image 13"/>

<h2>YouTube Demonstration </h2>

[How to migrate database in AWS](https://www.youtube.com/watch?v=fuCb0CeHvdI)


<h2>Learning Outcome</h2>
From completing this project I was  able to understand how Azure Sentinel works and the benefits from using it in your environment.

Azure Sentinel is a scalable, cloud-native security information event management (SIEM) and security orchestration automated response (SOAR) solution. 
Azure Sentinel collects data from different data sources, performs data correlation, data visualization and processed the data in a single dashboard. It helps to collect, detect, investigate and respond to security threats and incidents.



</p>

