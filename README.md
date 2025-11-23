# Description
EC2 instance created and accessed securely using AWS CLI, custom security groups, and SSH keys.

# EC2 Instance Setup Overview

## EC2 Instance Creation
 The EC2 instance was created using the AWS CLI, selecting the appropriate AMI and instance type.

## Security Group Configuration
 A security group was created and configured with:
 - SSH (Port 22) allowed only for our IP.
 - HTTP (Port 80) allowed only for our IP.
# This ensures the instance remains locked down and secure.

## Key Pair Generation
 A key pair was generated using the CLI to securely authenticate through SSH.

## Connecting via PuTTY
 After converting the key to PPK format, the instance was successfully accessed remotely using PuTTY.

# Purpose
 The main purpose of this setup is to remotely access the EC2 instance using the PuTTY SSH client.
