# Route Table Configuration

## Public Subnet Route Table
0.0.0.0/0 → Internet Gateway

## Application Subnet Route Table
0.0.0.0/0 → NAT Gateway

## Database Subnet Route Table
No internet route configured.

### Security Reason
Database should not communicate directly with internet.
