# Security Group Design

## ALB-SG
- Allow HTTP (80) from 0.0.0.0/0

## App-SG
- Allow HTTP from ALB-SG
- Allow SSH from Bastion-SG

## DB-SG
- Allow MySQL (3306) from App-SG only

### Principle Used
Least Privilege Access
