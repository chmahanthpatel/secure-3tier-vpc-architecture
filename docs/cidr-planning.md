# CIDR Planning

## VPC CIDR
10.0.0.0/16

## Subnet Allocation

| Layer | AZ1 | AZ2 |
|-------|------|------|
| Public | 10.0.1.0/24 | 10.0.2.0/24 |
| Application | 10.0.3.0/24 | 10.0.4.0/24 |
| Database | 10.0.5.0/24 | 10.0.6.0/24 |

### Design Rationale
- /16 provides scalability.
- /24 subnets isolate application tiers.
- Separate database subnets enhance security.
