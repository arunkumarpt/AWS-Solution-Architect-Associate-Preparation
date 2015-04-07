# AWS Solution Architect

## A deep dive in to traditional vs AWS cloud

### Traditional 

A traditional approach would have the below steps 
  - setting up data center
  - racks
  - internet (connect  to multiple provides - blend)
  - Equipments
  - configure it
  - move to different datacenter for redundancy

### AWS approach is much simpler than traditional
  -  Select region
  -  availability zone
  -  provision
  -  configure
  -  expand to other zones
  -  other region

### Basic comparison
  - cost
  - pas as you go
  - elastic computing (add server on need basis and remove after use - automatic)
  - scalable
  - sucrity complaince are offered(PCI,HIPAA).

## Understand the below topics before starting AWS 
  - Vertical vs horizontal scaling
  - web server vs application server
```
http://javarevisited.blogspot.com/2012/05/5-difference-between-application-server.html
http://www.diffen.com/difference/Application_Server_vs_Web_Server
```


## Core AWS services

###Traditionional to AWS mapping to understand AWS architecture


| Technology stack | on-premises                     | AWS                       |
| -----------------|:--------------------------------:| ----------------------------:|
| Network      | VPN,MPLS,VLAN, Routing tables | Amazon VPC,VPN,AWS Direct connect,routing tables |
| Security     | Firewalls,SSL,user groups etc      | AWS security groups, Cloud HSM, s3 SSE, cloudtrial etc |
| Storage | DAS,SAN,NAS,SSD      |  Amazon EBS, s3, EC2 Instance storage (SSD) |
| Computer | Hardware, virtualization | EC2|
Content Delivery|CDN (http://searchaws.techtarget.com/definition/content-delivery-network-CDN)|Cloud Front|
|Data base|DB2,MS SQL Server,My SQL, Mongo DB, Couchbase etc |Amazon RDS,Dynamo DB,MS SQL Server,MySQL,Postgres SQL etc|
|Load balancing| Hardware and software balancing, HA proxy (https://www.digitalocean.com/community/tutorials/an-introduction-to-haproxy-and-load-balancing-concepts)| Elastic load balancing,software and hardware balancing,HA proxy|
|Scaling|Clustering,Zookeeper| Auto scaling,software clustering|
|DNS| DNS providers| Amazon route 53|
|Analytics| Hadoop, Cassandra,spark | Amazon elastic map reduce|
|Data warehousing|Specialized HW/SW |Amazon redshift|
|Messaging and workflow | Messaaging and workflow software | Amazon SQS,SNS,SWF|
|Caching|memcached,SAP Hana (http://en.wikipedia.org/wiki/SAP_HANA),(http://memcached.org/)| Amazon Elastic Cache|
|Archiving| Tape Library,tape storage |Amazon Glacier|
|Email|Email software| Amazon simple Email Storage|
|Identity Management| LDAP| AWS IAM,LDAP|
|Deployment|Chef,Puppet|AMIs,CloudFormation,OpsWorks,Elastic Beanstalk|
|Management and Monitoring| CA,BMC,Rightscale| AWS cloudwatch,cloudtrial|


#The security model in AWS

```
http://d0.awsstatic.com/whitepapers/Security/AWS%20Security%20Whitepaper.pdf
```






