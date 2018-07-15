# CTM_aws_webapp

This project uses ansible to create two ec2 instances, install apache, create a simple webserver with an index page that shows the ec2 instance ID  
The project will also create a load balancer that will round robin between the 2 apache web servers.

## Pre-requists
There are several python packages required, they can be installed using pip.  
You can install pip (on Ubuntu) via the below command.
```
sudo apt install python-pip
```
