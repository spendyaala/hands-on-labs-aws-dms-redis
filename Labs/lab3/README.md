# Lab 3 - AWS DMS - Endpoint Configuration for your source - MySQL

## Objectives

In this exercise, you will
* Create an AWS DMS Replication instance
* Create an AWS DMS endpoint that points to MySQL database server
* Test endpoint Connection

## Creating AWS DMS Replication instance
1. Its time to login into your AWS Web Console.
Make sure you choose the right region of your choice. In this case, I chose us-west-2 (Oregon)

Go ahead and search for DMS service and select it.

lab3-a.png

2. In the AWS DMS Dashboard, select Replication Instance and go ahead and create a Replication instance.

Choose a Name, Description, Instance Class and storage, as shown.

lab3-b.png

3. VPC Configurations:
* You are going to launch this Replication instance in the same VPC as your source database system : MySQL is running.  So, choose the VPC you created in the previous exercises.
* Choose MultiAZ to a single AZ option as this is only for a learning exercise.
* You can uncheck the ”Publicly accessible” flag to NO, so that this Replication instance is only accessible via private network.
* Choose the Replication subnet to a default one suggested.
* Select AZ as us-west-2a
* Leave “default” for VPC Security Group

lab3-b.png


## Summary
<Summary place holder>

![](images/lab-end.png)
