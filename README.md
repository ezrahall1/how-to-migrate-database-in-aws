<h1>How to migrate database in AWS</h1>

<h2>Description</h2>
This project will feature the migration journey of a fundamental web application from an on-premises environment to AWS. The existing on-premises setup involves a virtual web server simulated on EC2 and a self-managed MariaDB database server, both replicated within the AWS EC2 infrastructure. The demonstration will meticulously guide through the steps of transitioning the web application, emphasizing the migration from on-premises to cloud-based services on AWS. By highlighting the process of replicating the virtual server and database environment, the project aims to provide a comprehensive overview of the migration process while leveraging Amazon EC2 for enhanced scalability and flexibility.
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


<img src="https://i.imgur.com/jQdxUHp.png" height="60%" width="60%" alt="Image 1"/>

<img src="https://i.imgur.com/IV6ym3L.png" height="80%" width="80%" alt="Image 2"/>

<H3>Step 2 - Create & Configure the AWS Side infrastructure</H3>

<img src="https://i.imgur.com/eFynHjp.png" height="60%" width="60%" alt="Image 3"/>


<img src="https://i.imgur.com/rUQGEMX.png" height="60%" width="60%" alt="Image 4"/>

From here I provision the EC2 instance which function as the AWS web server.
<img src="https://i.imgur.com/iDixIP9.png" height="60%" width="60%" alt="Image 5"/>

This screenshot shows that all the WordPress assets has been copied from this server to the AWS EC2 instance.
<img src="https://i.imgur.com/XHmCevs.png" height="60%" width="60%" alt="Image 6"/>


<H3>Step 3 - Migrate Database</H3>

In this section I created subnet groups, replication instance, endpoints and database migration tasks.
<img src="https://i.imgur.com/7s4modn.png" height="60%" width="60%" alt="Image 7"/>


<h2>YouTube Demonstration </h2>

[How to migrate database in AWS](https://www.youtube.com/watch?v=fuCb0CeHvdI)


</p>

