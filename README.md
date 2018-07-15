# CTM_aws_webapp

This project uses ansible to create two ec2 instances, install apache, create a simple webserver with an index page that shows the ec2 instance ID  
The project will also create a load balancer that will round robin between the 2 apache web servers.

## Pre-requists
There are several python packages required, they can be installed using pip.  
You can install pip (on Ubuntu) via the below command.
```
sudo apt install python-pip
```
Now pip is installed, you can install boto (an api to AWS)
```
sudo pip install boto
sudo pip install boto3
```
Now install ansible
```
sudo apt install ansible
```

### Configure boto
create a .boto file in your home dir and add your aws access key and secret.
````
[Credentials]
aws_access_key_id = YOUR_ACCESS_KEY
aws_secret_access_key =  YOUR_SECRET_KEY
````


