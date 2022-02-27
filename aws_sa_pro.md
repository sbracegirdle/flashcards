# AWS Solution Architect Pro

## VPC

<details>
  <summary>What is Transit Gateway?</summary>
  
  Transit gateway is a managed service that eases connection of a large number of VPCs.
  
</details>


<details>
  <summary>What are the key Transit Gateway concepts?</summary>
  
  - Attachments
  - Route tables
  - Route propagation
</details>

<details>
  <summary>What is a VPC endpoint?</summary>
  
  Entry point in your VPC to a service. Horizontally scaled, redundant and HA VPC device. There's two types; gateway and interface.
</details>

<details>
  <summary>What is a Interface type endpoint?</summary>
  
  ENI with private IP, serves as entry point for traffic destined to a service owned by AWS.
</details>

<details>
  <summary>What is a Gateway type endpoint?</summary>
  
   Gateway type endpoints are available only for AWS services including S3 and DynamoDB. These endpoints will add an entry to your route table you selected and route the traffic to the supported services through Amazon’s private network. 
</details>

<details>
  <summary>Egress-only Internet Gateway?</summary>

  A stateful gateway to provide egress only access for IPv6 traffic from the VPC to the Internet.
</details>

<details>
  <summary>Virtual private gateway?</summary>

  The Amazon VPC side of a VPN connection.
</details>

## EBS

<details>
  <summary>How do you backup a MySQL database running on an instance store?</summary>

  By copying it to S3, or by attaching an EBS volume and exporting the database.
</details>

<details>
  <summary>How can you create an AMI from an instance store volume?</summary>

  By using the AWS CLI tools to create a bundle for the volume and upload to S3. Then register an AMI to the file in S3.
</details>

<details>
  <summary>What are the EBS volume types?</summary>

  - Provisioned IOPS SSD (io2 Block Express, io2, and io1)
  - General Purpose SSD (gp3 and gp2)
  - Throughput Optimized HDD (st1)
  - Cold HDD (sc1)
</details>

## EFS

Mount targets?
