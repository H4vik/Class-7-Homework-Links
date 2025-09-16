1. Create NEW security group, do not use default
Inbound - group uses HTTP and source ipv4, description is webpage
- add rule http
Outbound - rules do not touch

Tags - useful for organization as well as tracking resurce useage acrros the office
2. create EC2
- click launchinstances
- Give instance a name
- Leave as AMI Linux
- leave instance type
- create new key pair type and leave RSA
- leave is .pem for windows 10 and newer,
- network settings, select existing security group
- scroll down to advanced user data and attach script from github
3. copy publc DNS, make it into a useable link, and paste the link into chat.
