<h1>Load and Query DynamoDB-Tables</h1>

<h2>Description</h2>
The project focused on building a dynamic, high-performance data storage solution using Amazon DynamoDB. I utilized the AWS CLI to create and configure tables with multiple attributes, ensuring scalability, low latency, and efficient management of structured and semi-structured data. Amazon DynamoDB is a fully managed NoSQL database designed for high performance, scalability, and reliability. It supports key-value and document
 data models, making it ideal for applications requiring low-latency and
 seamless scaling.
<br />

<h2> How I used Amazon DynamoDB in this project </h2>
 I used Amazon DynamoDB to store and retrieve data efficiently. It provided a
 schema-less structure, automatic scaling, and low-latency performance,
 making it ideal for managing large datasets and handling high-traffic queries
 seamlessly

<h2>Skills Demostrated:</h2>

- <b>Database Design and Management: Efficiently structured and managed DynamoDB tables.</b> 
- <b>AWS CLI Proficiency: Used CLI commands to configure and manage DynamoDB attributes.</b>
- <b>Problem-Solving: Addressed dynamic data storage needs with scalable solutions.</b>
- <b>- <b>Problem-Solving: Addressed dynamic data storage needs with scalable solutions.</b>.</b>
- <b>- <b>Problem-Solving: Addressed dynamic data storage needs with scalable solutions.</b>.</b>
<h2>Utilities used</h2>
<ul>
  <li>AWS console</li>
   <li>DynamoDB</li>
   <li>CLI(command line interface)</li> 
   <li>Cloudshell</li>
</ul>
<h2>Program walk-through:</h2>

<p align="center">
Open your AWS console Navigate to DynamoDB tab: <br/>
 <img src="image/cf-1.png" height="80%" width="80%" alt="key steps"/>
<br />
 
<br />
On the top right corner creat DynamoDB table: DynamoDB tables organise data using items and attributes! Every single item is recorded with a set of attributes. items can have any number of attributes(minimum 1, for the partition key values  <br/>
<img src="image/cf-2.png" height="80%" width="80%" alt="key steps"/>
<br />

<br />
scroll down under the configuration of DynamoDB table to "Read and Write Capacity"   Read capacity unit(RCU) and write capacity units(WCUs)are units that measure my DynamoDB table's performance.DynamoDB pricing is based on RCUs and WCUs,so the more RCU/WCUs consumed,the more expensive the project<br/>
<img src="image/cf-3.png" height="80%" width="80%" alt="key steps"/>
<br />

<br />
Navigate to cloudshell where AWS CLI is installed.: AWS CLI is a tool that lets you manage AWS services using terminal commands. It supports automation through scripts, provides access to AWS APIs, and works across platforms, simplifying tasks like deploying resources and managing configurations <br/>
<img src="image/cf-4.png" height="80%" width="80%" alt="key steps"/>
<br />
<br />
Load Data with CLI: I ran a CLI command in AWS CloudShell that load multiple items of data into the DynamoDB tables i set up in the previous step <br/>
<img src="image/cf-5.png" height="80%" width="80%" alt="key steps"/>
<br />
<br />
 Observing Item Attributes:  <br/>
<img src="image/cf-6.png" height="80%" width="80%" alt="key steps"/>
<br />

</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
