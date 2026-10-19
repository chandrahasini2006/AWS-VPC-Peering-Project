# AWS VPC Peering Project

## Project Overview
This project demonstrates secure communication between two
Amazon Virtual Private Clouds (VPCs) using AWS VPC Peering.

Completed as part of the EWB Tech AWS Cloud Computing Internship.

## AWS Services Used
- Amazon VPC
- Amazon EC2
- VPC Peering
- Security Groups
- Route Tables
- Internet Gateway

## Network Configuration

| Resource | CIDR / Private IP |
|---|---|
| VPC A | 10.10.0.0/16 |
| Public Subnet A | 10.10.1.0/24 |
| Private Subnet A | 10.10.2.0/24 |
| VPC B | 10.20.0.0/16 |
| Private Subnet B | 10.20.1.0/24 |
| Bastion Host | 10.10.1.10 |
| App-A | 10.10.2.10 |
| App-B | 10.20.1.10 |

## Implementation
1. Created two VPCs with non-overlapping CIDR blocks.
2. Configured public and private subnets.
3. Launched EC2 instances.
4. Configured security groups and route tables.
5. Established VPC peering.
6. Tested connectivity between private instances.
7. Accessed private instances through a bastion host.

## Testing
- Verified the VPC peering connection.
- Tested SSH access through the bastion host.
- Tested connectivity between App-A and App-B.
- Performed a controlled ICMP failure test.
- Restored the security group rule and retested connectivity.

## Project Files
- `AWS_VPC_Peering_Project_Report.pdf`: Detailed project report.
- `screenshots/`: Implementation and testing evidence.

## Learning Outcomes
- VPC and subnet configuration
- Route tables and security groups
- VPC peering
- Bastion host access
- Network troubleshooting

## Author
KADALI CHANDRA HASINI