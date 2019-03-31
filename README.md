# Palo-Alto-lab-in-AWS
Tips on spinning up a PA in AWS

1. Create an AWS account [HERE](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html?refid=em_127222)
> Amazon offer a Free Tier which for a period offers access to certain resources at no cost.  Unfortunately the Palo Alto VM is not within the Free Tier.  So you will be charged the hourly cost.

>AWS has a [marketplace](https://aws.amazon.com/marketplace) where you can purchase various AMI's (Amazon Machine Images) to launch within your AWS infrastructure. The AWS Marketplace enables qualified partners to market and sell their software to AWS Customers. AWS Marketplace is an online software store that helps customers find, buy, and immediately start using the software and services that run on AWS.

> An AMI is a template that contains the software configuration (operating system, application server, and applications) required to launch an AWS instance. 
2. Log in to AWS and navigate to the [AWS Marketplace](https://aws.amazon.com/marketplace)
3. [Search](https://aws.amazon.com/marketplace/search/results?x=0&y=0&searchTerms=palo+alto) for `palo alto`
4. From the results, click on `VM-Series Next-Generation Firewall Bundle 1` then click on `Continue to Subscribe`
5. Follow the prompts and note the costs.
> To save cost power down your instance when not in use.  
6. At this stage you might get a warning stating your account needs to be verified, if so follow the process.
7. Depending on where you are in the process you might see a button to launch your new Palo Alto instance, you can use this to launch the firewall, or continue below.
8. From the AWS Marketplace, select your name (top right) then `Your Marketplace Account` then `Manage your software subscriptions` 
9. 
