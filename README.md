### A part of variables in template.json file we can change the infomation.
### My information for this section
    "region": "ap-southeast-2",
    "source_ami": "ami-0df4b2961410d4cff",
    "instance_type": "t2.micro"

    
### A vars.json file change the information to your information
### For ssh_username atttribute you can change it follow AMI you create
### Reference for this section
<a href="https://alestic.com/2014/01/ec2-ssh-username/">ssh_username</a>
<table class="pure-table pure-table-striped">
<thead>
<tr><th>OS/Distro</th>
<th>Official AMI<br>ssh Username</th>
<th>Legacy / Community / Other AMI<br>ssh Usernames</th>
</tr></thead>
<tbody>
<tr>
  <td><a href="http://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AccessingInstancesLinux.html#AccessingInstancesLinuxSSHClient">Amazon Linux</a></td>
  <td><code>ec2-user</code></td>
  <td></td>
</tr>
<tr>
  <td><a href="">Ubuntu</a></td>
  <td><code>ubuntu</code></td>
  <td><code>root</code></td>
</tr>
<tr>
  <td><a href="https://wiki.debian.org/Cloud#FAQ">Debian</a></td>
  <td><code>admin</code></td>
  <td><code>root</code></td>
</tr>
<tr>
  <td><a href="">RHEL 6.4 and later</a></td>
  <td><code>ec2-user</code></td>
  <td></td>
</tr>
<tr>
  <td><a href="http://aws.typepad.com/aws/2013/04/now-available-red-hat-enterprise-linux-64-amis.html">RHEL 6.3 and earlier</a></td>
  <td><code>root</code></td>
  <td></td>
</tr>
<tr>
  <td><a href="https://alt.fedoraproject.org/cloud/">Fedora</a></td>
  <td><code>fedora</code></td>
  <td><code>ec2-user, root</code></td>
</tr>
<tr>
  <td><a href="http://wiki.centos.org/Cloud/AWS">Centos</a></td>
  <td><code>centos</code></td>
  <td><code>root</code></td>
</tr>
<tr>
  <td><a href="http://aws.amazon.com/partners/suse/">SUSE</a></td>
  <td><code>ec2-user</code></td>
  <td><code>root</code></td>
</tr>
<tr>
  <td><a href="http://wiki.bitnami.com/cloud/how_to_connect_to_your_amazon_instance#How_can_I_access_my_server_as_the_root_user.3f">BitNami</a></td>
  <td><code>bitnami</code></td>
  <td></td>
</tr>
<tr>
  <td><a href="http://www.turnkeylinux.org/forum/support/20111204/password-ec2-instances">TurnKey</a></td>
  <td><code>root</code></td>
  <td></td>
</tr>
<tr>
  <td><a href="http://www.diamondkeys.com/nanostack-faq/">NanoStack</a></td>
  <td><code>ubuntu</code></td>
  <td></td>
</tr>
<tr>
  <td><a href="http://www.daemonology.net/freebsd-on-ec2/">FreeBSD</a></td>
  <td><code>ec2-user</code></td>
  <td></td>
</tr>
<tr>
  <td><a href="http://omnios.omniti.com/wiki.php/Installation#IntheCloud">OmniOS</a></td>
  <td><code>root</code></td>
  <td></td>
</tr>
</tbody>
</table>	

### Example my information for this section
    "aws_access_key": "AKIAY5FCRTQF****"
    "aws_secret_key": "2rZSADjQkH********JvRMIpPevQhwK"
    "ssh_username": "ubuntu"