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

