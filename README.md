# cloudformation_network_foundation
This template build an basic AWS Network with the following resources:
- VPC
- Subnets (optional): 2 Public, 2 Private subnets.
- Internet Gateway (optional)
- S3 Endpoint
- Route Tables: 1 Public (if Public Subnets exists), 1 Private (if Private Subnet exists)
- S3 Endpoint Route
- Internet Gateway Route (if Internet Gateway exists)
