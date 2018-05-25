# Introduction
This project is to demonstrate Chef Automate V2 integration/interaction.
To demonstrate this - our setup has a Chef Server, a Chef Automate V2 server and two test boxes on AWS -one running Ubuntu and the other running Windows.
We will initiate a compliance check from the Chef Compliance Server on the two nodes. We would expect to see the Compliance report on the Chef Automate V2 portal.

# Server Details
## Chef Automate
IP: 13.54.84.148  
URL: https://ec2-13-54-84-148.ap-southeast-2.compute.amazonaws.com/event-feed
## Chef Server
IP: 13.211.142.207  
URL:
## Test Ubuntu Node
IP: 54.82.231.156  
AMI: ubuntu/images/hvm-ssd/ubuntu-xenial-16.04-amd64-server-20180522 (ami-a4dc46db)  
Username: ubuntu  
Password: _will be shared verbally_  
## Test Windows Node
IP: 54.173.26.198  
AMI: Windows_Server-2016-English-Full-Base-2018.05.09 (ami-f0df538f)  
Username: Administrator  
Password: _will be shared verbally_  

# Learnings
