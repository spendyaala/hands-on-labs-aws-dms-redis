# Using AWS Data Migration Services to migrate data to Redis Enterprise Cloud on AWS
Hands on labs to gain data migration experience from a typical transactional system to Redis using AWS DMS (Data Migration Service).

# About Redis Enterprise Cloud
Redis Enterprise Cloud (RC) is a DBaaS (Database-as-a-Service) offering from Redis Inc, the home of RedisOSS. RC is build on top of Redis open source and adds support for other data models, like native JSON and search, graph, and timeseries.  In addition it has  enterprise features like Active-Active Geo replication, High Availability - guaranteeing upto 5 9's (99.999%) uptime and the ability to use tiered storage, Redis on Flash, all built in to our managed service.

# About AWS Data Migration Service (DMS)
AWS Database Migration Service (AWS DMS) is a web service that you can use to migrate data from a source data store to a target data store.

# Learning Objectives
* Understand how to deploy Redis Enterprise Cloud on AWS
* Gets hands-on experience with AWS DMS services
* Migrating data from MySQL database to Redis Enterprise Cloud

## Venue
These hands-on workshops are designed for in-person and for virtual experiences.

## Duration
2.5 to 3 hours.

# Pre-requisites
These hands-on labs are intense from technical experience standpoint (Level 200 to 300). These hands-on labs are targeted for Technical stakeholders like Data Engineers, Application Developers, DevOps, Technical Leads, Cloud Solutions Architects, Cloud Migration Architects.  

If you are not in any of the above mentioned roles, it would be a disservice for yourself to go any further beyond this point. But if you are one of those most curious souls who do not shy away from getting hands-dirty, we still welcome you to hop on the journey.

Here are few hard skills that you would want to bring to the table:
- Very comfortable with AWS web console, AWS CLI.
- Very comfortable running SSH terminal session in connecting to remote servers (ec2 machines)
- You breath in and out Docker, Containers etc, all through the day.
- Working knowledge and experience with MySQL.
- No prior knowledge on using Redis Enterprise Cloud or Redis OSS (Open source software) is needed.

You will also bring your own laptop / desktop with a browser. You will also bring your AWS account. But don't worry, AWS is giving credits that you can use to run these labs up until you exhaust these credits. We will also help you with cleanup scripts so that you do not get a surprise bill at the end. More on it in the labs.

# Costs involved
Please understand that doing these hands-on exercises gives you a direct hands-on learning experience of Redis Enterprise Cloud and AWS Cloud services.  However, there are going to be some costs involved, as these exercises will provision cloud resources in AWS.

Important Information : Running this Redis Cluster will cost your around $0.88 per hour. These exercises can take up to 4 hours to complete. Hence, please kindly be informed that you may incur $4.00 (USD)  or more , for doing these exercise, from Redis Inc.

Also, please note  you may also additionally incur AWS cloud resource costs. Hence, its important to do the last exercise in this guide to clean up all resources and to save costs.


# Hands-on exercises

* Exercise 1:	[Migration Architecture Review and VPC Setup](Labs/lab1/README.md) (15 mins)
* Exercise 2:	[Prepare Source System - MySQL](Labs/lab2/README.md) (25 mins)
* Exercise 3:	[AWS DMS - Endpoint Configuration for your source - MySQL](Labs/lab3/README.md) (10 mins)
* Exercise 4:	[Prepare Target System - Redis Enterprise Cloud](Labs/lab4/README.md) (30 mins)
* Exercise 5:	[AWS DMS - Target Endpoint configuration for Redis Enterprise Cloud](Labs/lab5/README.md) (15 mins)
* Exercise 6:	[AWS DMS - Creating Migration Task](Labs/lab6/README.md) (10 mins)
* Exercise 7:	[AWS DMS - Running Migration task](Labs/lab7/README.md) (20 mins)
* Exercise 8:	[Verifying Migration results](Labs/lab8/README.md) (15 mins)
* Exercise 9:	[Cleaning up Cloud Resources](Labs/lab9/README.md) (15 mins)

# Additional resources
## Redis Enterprise Cloud resources
* Start building your Apps today for FREE at [redis.com/try-free](https://redis.com/try-free)
* Redis Enterprise Cloud on [AWS Marketplace](https://aws.amazon.com/marketplace/pp/prodview-mwscixe4ujhkq)
* Checkout our Developer Hub at [developer.redis.com](https://developer.redis.com)
* Want to connect? Email Redis at `aws@redis.com`

## AWS resources
* [Getting started guide](https://docs.aws.amazon.com/dms/latest/userguide/CHAP_GettingStarted.html): Review technical migration documentation
* [Database Migration Services (DMS) Homepage](https://aws.amazon.com/dms/): Highlights DMS features and benefits
* [Migration Pricing](https://aws.amazon.com/dms/pricing): Prices for replication instances, storage, and data transfer
