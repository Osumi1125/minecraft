# Introduction to minecraft. 

## Registration.  
### AWS account
  - Create your AWS account.  
  - Generate your ssh-key pair.   
  - ```$ ssh-keygen```   
  - Tell me your MailAddress and public key.  


## owner's job.  
https://ap-northeast-1.console.aws.amazon.com/ec2/v2/home?region=ap-northeast-1#Instances:   
Register SSH-key to the instance authorized_keys.  
Allow TCP access by fixing Security Group

  

# How to enjoy minecraft 
## Start the EC2 Instance
- Select EC2 -> Instance -> Name: minecraft.  
- State of instances -> Start the instance.  
- copy public IPv4 DNS.  
- exec below command
```
$ ssh -i [Path/to/yourSSH-key] ec2-user@[IPv4 DNS]
[ec2-user@ip-10-0-0-4 minecraft]$ cd minecraft
[ec2-user@ip-10-0-0-4 minecraft]$ sh Minecraft_start.sh
...//wait a moment
[09:40:51] [Server thread/INFO]: Done (56.201s)! For help, type "help" //Minecraft server is running if you can see this output
>
```
  
## Access to the Minecraft
- Multi Play.  
- Access the server.  
- set the IPv4 Adress.  
- ENJOY MINECRAFT


  
## stop the EC2 Instance
- Select EC2 -> Instance -> Name: minecraft.  
- State of instances -> Stop the instance.  
