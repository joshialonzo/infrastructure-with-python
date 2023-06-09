
# AWS

## AWS Cloud Practitioner Exam

* Validates overall understanding of the AWS Cloud.
* Industry-recognized credential validating knowledge.
* Broad understanding of the AWS Cloud, but no hands-on tasks.
* All multiple-choice questions.

## AWS Cloud Practitioner Exam Domains

1. Cloud concepts
    * Define the AWS Cloud and its value proposition
    * Identify aspects of AWS Cloud economics
    * Describe different cloud architecture design principles
2. Security and compliance
    * Define AWS shared responsability model
    * Define AWS Cloud security and compliance concepts
    * Identify AWS access management capabilities
    * Identify resources for security report
3. Technology
    * Define method of deploying and operating IT applications in the AWS Cloud
    * Define the AWS global infrastructure
    * Identify the core AWS services
    * Identify ways to contact support
4. Billing and pricing
    * Need to be able to remember the different pricing models for AWS
    * Recognize various account structures in AWS billing and pricing
    * Identify resources available for billing support

## Cloud concepts domain

* Define the AWS Cloud and its value proposition.
* Identify aspects of AWS Cloud economics.
* List the different cloud architecture design principles.

### Questions

* What exactly is cloud computing?
* What makes it different from legacy IT infrastructure?
* How is the way you pay for resources different from buying and setting up the hardware in your own on-premises data centers?
* Well-architected framework
* Types of cloud computing
* Types of cloud computing deployments
* Advantages of cloud computing (over legacy IT infrastructure)

## Introduction to Cloud Computing

* The Cloud = The Internet
* The internet = Worlwide network of interconnected devices
* Devices = Computers, Servers, Cell phones, Tablets, or Amazon Alexas
* Any device can be connected to any other device through internet
* Connections = Cables and Wireless
* Cables = TV Cables, Optic fiber Cables, or Copper telephone wires
* Browser -> Request -> ISP -> Request -> Server -> Web Host
* Web Host -> Packets -> Browser

## Cloud Computing

* On-demand delivery of:
    * compute
    * database storage
    * application
    * and other IT resources
* Utilizes a pay-as-you-go model - pay only for what you use, when you use them
    * Provides more flexibility
* Most transactions utilize "buy first to use" such as computer or car
* Traditionally, you need a procurement process to get the hardware
* Before: Fixed costs
* Now: Variable costs

### Cloud Computing characteristics

* Instantaneous access
* Access resources where and when you want
* More flexible and affordable than legacy IT infrastructure
* Affordable for organizations and individuals with smaller budgets

## AWS CLI

See the credentials of your cloud environment

```bash
aws sts get-caller-identity
```

Devops Cloud world is like planet Earth 🌍
Earth has Countries, States, Cities 🌐
Cloud has Regions, Availability zones, Data Centers ⛅

Earth has a Home for you, your own space 🏡
Cloud has VPC for you, your own space 📦

Each country has one default Flag 🇮🇳
Each Region has one default VPC 🗳

Home is partioned into small Rooms 🎛
VPC is partioned into small Subnets 💠

Each State is mapped to a Pincode 🔢
Each AZ is mapped to a Subnet ❇

If a Country has 12 states, it gonna have their 12 capitals, mapped to the 12 states, inside a one default Country ◀
If a Region has 6 AZ, it gona have 6 subnets, mapped to those 6 AZ's inside 1 default VPC ⏪

https://medium.com/@mohitmishra3333/cloud-services-using-home-example-eccf4a70f12f