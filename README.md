# DevOps Project - Vprofile Project Stack Setup on AWS Cloud using Ansible for Cloud Automation

This is a DevOps project for vprofile project stack setup on AWS Cloud using [Ansible](https://www.ansible.com/) for Cloud Automation. This project is a continuation of [_vprofile-project-ansible-aws-vpc_](https://github.com/durrezahmed/vprofile-project-ansible-aws-vpc) project.

[Link](https://github.com/durrezahmed/vprofile-project-devops) for vprofile app repository.

## Scenario - Current Situation:

- Operations Team

- Deploy / Setup Infrastructure

- Manages OS, Cloud, VMs etc

- Regular Provisioning Requests and Changes

## Problem - Issues with Current Situation:

- Complete Infrastructure Setup is Complex

- Not Repeatable

- Difficult to Track

- Chances of Human Error

- Managing Manually is a time consuming task

## Solution - Fix:

- Configuration Management of Infrastructure

- Automatic Setup (No Human Errors)

- Centralize Change Management

- Version Control (IaC)

- Repeatable

- Reusable

## Tools used in the Project:

- [**Ansible**](https://www.ansible.com/) - Configuration Management of VPC

- [**AWS Cloud Platform**](https://aws.amazon.com/) - VPC Setup with Bastion Hosts

## Steps:

- Setup VPC (Secure & HA)

- Provision EC2 Instances, ELB, Security Groups etc

- Provision Vprofile Stack on EC2 instances:

  - Build Artifact

  - MySQL

  - Memcached

  - RabbitMQ

  - Tomcat

  - Nginx

## Usage (Flow of Execution):

1. Login to AWS - [Link](https://aws.amazon.com/marketplace/management/signin) to Login to your AWS Account

2. Create `EC2 Instance` to Run Ansible Playbooks

3. Install `Ansible`

4. Install `Boto`

5. Setup `EC2 Role` for Ansible

6. Fetch Source Code from Project Repository

7. Execute `VPC` Playbook

8. Playbook to launch `EC2` , `ELB` , `Security Group` for vprofile project

9. Get into vprofile `VPC`

10. Playbooks for vprofile Stack Setup
