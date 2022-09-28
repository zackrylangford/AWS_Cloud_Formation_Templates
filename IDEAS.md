### Ideas for new templates and potential scripts for CloudFormation


### Script Ideas

### 1. Script to launch a VM and walk through with questions to simply input what you want without having to remember all that you should put in. 

This could basically do all of the work for you, it could ask you questions and give you options and walk you through everything, 
and then it would launch the VM in the place that you want it to go. Example: 1. What operating system would you like to launch? (Linux, Windows). 2. What
type of Linux or Windows OS would you like to run (Linux 2, Ubuntu, or if it was Windows). It could then ask information on subnets, security groups, EIP, etc, 
and then take that information and put it into a CloudFormation template and then run the CLI script to launch all of that stuff. You could really play around 
and try and customize it or figure out how it would interact with your current set up. Could it pull the information from your AWS account to give up to date 
information on the subnets/VPC and stuff like that so you wouldn't have to update the script? 

Process for the program: 1. Write a CloudFormation Template. 2. Write a Script that could write this out. It would have to be Linux machine based, I don't know 
if there is a way to make it work in Windows. I'm sure their is, but I don't know how that would be done. 

### Template Ideas

1. Launch a VM to host a website (add script into the user data)

2. Launch a VM to host a Wordpress site 

3. 