### A part of variables in template.json file we can change the infomation.
### My information for this section
    "region": "ap-southeast-2",
    "source_ami": "ami-0df4b2961410d4cff",
    "instance_type": "t2.micro"

    
### A vars.json file change the information to your information
### For ssh_username atttribute you can change it follow AMI you create
### Reference for this section
<a href="https://alestic.com/2014/01/ec2-ssh-username/">ssh_username</a>
OS/Distro	Official AMI ssh Username	Legacy / Community / Other AMI ssh Usernames
Amazon              Linux	                                ec2-user	
Ubuntu	            ubuntu	                                root
Debian	            admin	                                root
RHEL 6.4 and later	ec2-user	
RHEL 6.3 and earlier	root	
Fedora	            fedora	                            ec2-user, root
Centos	            centos	                                root
SUSE	            ec2-user	                            root
BitNami	            bitnami	
TurnKey	            root	
NanoStack	        ubuntu	
FreeBSD	            ec2-user	
OmniOS	            root	

### Example my information for this section
    "aws_access_key": "AKIAY5FCRTQF****"
    "aws_secret_key": "2rZSADjQkH********JvRMIpPevQhwK"
    "ssh_username": "ubuntu"