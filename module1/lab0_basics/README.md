Instance ID (Homework)
1. i-0b5463bd86a82cd51 - t3.micro

AWS Region - United States (N.California)

What instance type did you launch?
t3.micro
How many vCPUs and how much RAM does your dashboard show?
2 vCPU(s)
181Mi used / 913Mi total
What is the current CPU utilization?
0% busy (approx.) | 2 vCPU(s)
Did the dashboard appear automatically after SSH login?
Yes


2. i-0f4a73b7fe1b7a83a - t3.micro

AWS Region - United States (N.California)

What instance type did you launch?
t3.micro
How many vCPUs and how much RAM does your dashboard show?
2 vCPU(s)
175Mi used / 913Mi total
What is the current CPU utilization?
0% busy (approx.) | 2 vCPU(s)
Did the dashboard appear automatically after SSH login?
Yes

3. i-03a3fee50b38e39c2 - t3.micro

AWS Region - United States (N.California)

What instance type did you launch?
t3.micro
How many vCPUs and how much RAM does your dashboard show?
2 vCPU(s)
182Mi used / 913Mi total
What is the current CPU utilization?
0% busy (approx.) | 2 vCPU(s)


This was hard at first, then it got easier. I made my security groups for the entire exercise. Actually made three security groups. I made sure the two inbound rules reflected the expectations for SSH and HTTP, with source types set to anywhere-IPv4. I did not touch the outbound rules. I made three different security groups for my EC2 Instance launches. I started by creating a template named SEIR_foundations_lab0. I made sure to pick Amazon Linux as my AMI. I created a key pair and selected it. I also chose one of the three security groups I made for all three exercises. After finishing the top section and making sure everything was in order. I expanded the Advanced details section and pasted the entire script from the SEIR_EC2_user data.sh section. After that, I saved my launch template and verified it was saved and existed in EC2. After Verification, I selected my template and clicked the action to launch it. I verified the region, AMI, network, security group, key pair, and user data configuration. After Verification, I launched my instance and waited until it was officially up and running. Once it was up and running, I connected using EC2. I clicked Connect, reviewed all the data, then clicked Connect again, and it succeeded; my dashboard loaded. I recorded the data on my dashboard and repeated this process two more times. It got easier and easier. I did run into a problem I couldn’t solve. My account wasn't eligible for the free tier. I chose the cheapest tier from the list and used it as the option for this exercise.


Did the dashboard appear automatically after SSH login?
Yes
