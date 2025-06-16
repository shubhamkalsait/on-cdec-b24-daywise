## Interview Questions

Linux - 
------


1. TOP - Output
5 Rows - User Time UpTime LoadAverage 1 5 15
TASK
MEM
CPU
SMEM
USER S PID PI NI PPID SHR IDL CPU MEM CMND

2. SCP vs RSYNC
3. Hlink vs Slink
4. HTTP vs HTTPS
4a. Telnet vs SSH

5. Kernel version
uname -r

6. new file, execute remove

7. Password Policies
/etc/shadow -> 9 Fields

8. 19 Dirs

9. Ports 2000 
NFS - 2049
FTP - 20/21
Telnet - 23
SMTP - 25

10. How to schedule backup of Linux Database Server for every Saturday at 2 AM?
cron 
periodic scheduler 
crontab -e 
min hr date mon days script
0 2 * * sat mysqldump -h localhost -u user -predhat database > mysqldump.sql 

11. How to remove dir /opt/new-dir?
What? rm 
Why? rmdir (empty), rm -r
How? (Command Syntax, Command Example, Exact Command) rm -rvf DirPath, rm -rvf /opt/new-dir

12. If you have given 1000 Computer and you have to install OS on these computer?
Ans. OS Install > Image .iso > Network Booting

13. If Linux Webserver, not able to access website? How to troubleshoot?
- Firewall / securityGroup
- Network Issue
- Service Down
- Heavy Traffic 
- Static Public IP
- resource heavy utilize (CPU, MEM, STorage) -- logs 
- Log Rotation 

14. Boot Process in Linux?

-------------------------

AWS
-----------
WHat? WHy? How(Service - resources, Resources - Steps) ?

1. What is IAM?

User / Roles

USER - Those / programatic access or console access
GROUPS - Permision
POLICIES - Bunch Permission written JSON
ROLES - Machine / temp access  service to another service

2. What is S3?
simple storage service, object storage service
global service / buckets region specific
buckets - containers to store our objects
unlimited storage
anywhere, sensory, webservice static, automate backups
durability 99.99999999%, availability, 99.99, Scalability - charges

3. Lifecycle of S3 objects? / Storage Classes / Optimize s3 storage Cost?
lifecycle policy - optimize the storage cost of the s3 objects
transist the object from one storage class to another storage class after perticular period

STORAGE CLASS (USE CASE)
FA - Standard, Reduced redudancy 
Intelligent Tiering
IFA - STandardIA, OneZone IA
Archive - Flexible Glacier, Glacier, Deep Glacier

default Standard -> 30 days StandardIA -> 30Days OneZone -> 30Days Glacier -> 90Days DeepGlacier

4. Status Checks? 1/2 Status Check? (3/3)

5. Explain AutoScaling? Vertical Scaling vs Horizantal Scaling
WHat?
Why?
How? 

Static Dynamic Scheduled
LT - AMI, IT, SG, ADCON, KEY, STORAGE
ASG - CAPACity of GROUp - Desired, Max, Min
AutoScaling Policy - Target Average Policy - Alarm - Condition - Action 

6. LoadBalacing Service
AWS Service -> Balancing the load on targets
Target Group
LoadBalancer - 4 Classic HTTP/HTTPS/TCP/UDP,layer4 Transport TCP/UDP NLB,layer 7 HTTP/HTTPS ALB listernrule, Layer 3 Network GLB

7. EBS volume and types

8. AMI Types

9. Instance Types

10. What is VPC Peering?
VPC Peering Connection (Requester VPC ---> Accepter VPC)
both vpc difference CIDR
Route Table Subnets of both VPCs

11. VPC Endpoint?

12. NAT Gateway?
What? Why? How?
Public Subnet 
New Route Table
Route NAT Gateway
Associate Private Subnet
Flow of Internet

12. NAT Gateway vs NAT Instance?
AWS Resource 
Manually Server - Instance / AMI 

13. ROuting Policy route53

14. Cloudwatch Resources

15. Why we choose Serverless? RDS

---------------

Linux and AWS Important Question
DevOps

Git,
PULL vs FETCH vs CLONE
rebase vs restore vs 
git cherrypick
github and gitlab
Branching strategy
Dev branch code push


Jenkins
---------
1. Jenkins job backup
2. Different Deployment Strategies
3. Explain your pipeline

Docker
---------
1. Entrypoint vs CMD vs RUN
2. What is Dockerfile?
What why how? INSTRUCTIONS / Deplpy JAVA 
3. How to optimize dockerimage 
- Multistage
- Reduce RUN instruction
- use smaller base image
- Remove unnnecesary files
4. ARG vs VAR

Kubernetes
----------
1. What is Ingress
2. Deployment vs StatefulSet
3. Deployment and Service
4. Different service types
5. Architecture of Kubernetes
6. Taint and Tolerence


Terraform
-------------
1. How to secure terraform.tfstate file
2. Terraform import
3. Terraform destroy --target aws_instance.my_instance
comment configuration of resource my_instance
terraform apply
4. Terraform refresh


Monitoring Tool - 

CloudWatch -

Metrics Collection
Dashboard
Alerting
Log Management

DataDog
Grafana 
Prometheus
ElasticSearch  Logstash Kibana



Scripting - Bash Scripting
GCP azure python 

Project - Sat 



Rent - 130000 - 150000 - 145000 including
Increament - 5%
Deposit - 3 month - 4 month 
Lockin - 1 Year -
Total bond-3 year - 