---
description: XOX headline
---

# AWS security

## About the course

### Overview

In today's world more and more companies decide to move their businesses to a cloud. It means that the success of a company is more dependent on those cloud services. While some security responsibilities are taken by the provider, the configuration and management of the cloud environment is still among the duties of the customer. There are thousands of stories showing that this task is not a trivial one.

During the AWS security course you will learn key security concepts on how to stay secure and compliant using the AWS cloud. The course is designed to be as much practical as possible containing common pitfalls in form of hands-on labs. During the labs you do not only learn how to properly configure AWS services, but you will also find misconfigurations there from an attacker perspective and get to know how to fix it.

Furthermore, we will go through AWS security services -- what they are and how to use them effectively in order to detect and prevent any malicious action. The course also covers what to do once you already got hacked to better prepare you for meeting the wild world.

### Properties

title: **AWS security**

audience: XOX

duration: normal: 1.5 days \(9hrs education time\); extended: 2 days

developed by: Paweł Rzepa

delivery partner: [**Securing**](https://www.securing.pl/en/index.html) _\*\*_

### Prerequisites

* AWS account \(can be free tier\)
* a laptop with: 
  * git \(the exact repositories to clone will be provided before the course\)
  * Terraform
  * AWS CLI

## Agenda

> &ast; - available in extendeted course version

#### Security Basics

* Shared Responsibility Model, Security in AWS 

#### Identity Access Management & Security Policies

* IAM users, IAM groups, profile identities, IAM policies, roles
* Labs: privilege escalation in AWS

#### S3 security

* Bucket policies vs ACLs, conflicting policies, encryption, Cross Region Replication, S3 and CloudFront, pre-signed URLs
* Lab: detecting S3 misconfigurations and detecting leaks in stored data

#### Logging And Monitoring

* CloudTrail, CloudWatch, AWS Config, AWS Inspector & Trusted Advisor
* Labs: Bypassing CloudTrail, Setting up AWS Config and CloudWatch Events to prevent it

#### Virtual Private Clouds

* VPC, NAT instances vs NAT Gateways, NACLs vs Security Groups, Bastions, VPC Flow Logs
* Labs&ast;: setting up VPC and data exfiltration

#### Infrastructure Security
* Lectures&ast;: KMS, Key Pairs in EC2 and LightSail, WAF, AWS Shield

#### Incidence Response in AWS

* Lectures: steps to take after being hacked or loosing keys, reading CloudTrail logs, Pentesting in AWS, AWS Certificate Manager, AWS System Managers, Compliance in AWS



## Trainers

* [pawel.rzepa](https://www.youtube.com/watch?v=MkRYM4HF1h8) @ securing.pl

