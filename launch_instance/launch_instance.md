# An introduction to how to launch an EC2 instance quickly
<font color="blue">Now, we show to launch an EC2 instance step by step.
First of all, after we login the AWS, we will see the first picture below, which is the dashboard of the AWS.
Now, we click the EC2 button.</font>
![ picture one ](/launch_instance/pic001.JPG)

<font color="blue">After you chose EC2 in the dashboard showing on the above, you will see the following picture two.
Click the "Launch instance" button to go to the launch process.
</font>
![ picture two ](/launch_instance/pic002.JPG)

<font color="blue">The first step is to choose an Amazon machine image (AMI).
Picture three show that there are some AMI options. In this example, we selected the ubuntu 16.04 AMI.
</font>
![ picture three ](/launch_instance/pic003.JPG)

<font color="blue">After we chose the AMI, step two, we need to choose an instance type which is the specification of the virtual machine.
We chose t2.micro type for the convenient reason.
</font>
![ picture four ](/launch_instance/pic004.JPG)

After we chose the instance type, we clicked the "Review and launch" button. 
Then we will see the following picture. You will see a warning there.
This is because you did not set up a more secure setting for SSH login.
AWS does not want you to allow all source ip to be able to login to your instance.
Therefore, you need to change the setting of the ssh login source ips.
Thus, we clicked "Edit security group" hyper link.
![ picture five ](/launch_instance/pic005.JPG)

After we clicked the "Edit security group", we will see the following picture.
A good way to set the source ip is to choose "My IP" directly.
After we set source ip to MY IP, we clicked "Review and launch".
![ picture six ](/launch_instance/pic006.JPG)

Then we will see the following picture which is a successful page. 
Then we scroll down the page, we will see a hyperlink which can go to instance page.
We clicked the hyperlink to go to the instance page. 
![ picture seven ](/launch_instance/pic007.JPG)

Then we will see the folloing page. You will the instance we just launched is the last one in the button.
This instance has not set a name. Now we set a new name for it. Then it will look like the next picture.
![ picture eight ](/launch_instance/pic008.JPG)


![ picture nine ](/launch_instance/pic009.JPG)
