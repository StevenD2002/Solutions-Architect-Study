## Act as a firewall
- Controls how traffic is allowed into or out of EC2 Instances
- Security GRoups only contain allow rules
Security groups rules can reference IP
- Regulate access to ports
- Authurised IP ranges
- Cotnrol of inbound network


Rules Contain:
- Type
- Protocol
- Port ranges

- By defualt, allow all outbound traffic
- they can be attached to multiple Instances
- Locked down to a region/ vpc combo
- Lives "outside" of ec2 Instances
- Good to maintain one seperate security group for SSH access
- Timeouts usually are security group issues
- Connection refused errors however, are application errors or it isnt launched
- All inbound traffic is blocked by default


### How to reference security groups from other security groups
- 


## classic ports to know
- 22 = SSH
- 21 = FTP
- 22 = SFTP -> upload files using SSH
- 80 = HTTP - access unsecured websites
- 443 = HTTPS - access secured websites
- 3389 = RDP (Remote DEsktop Protocol) -  log into a windows instance
