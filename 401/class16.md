# Readings: AWS: Cloud Servers

### Reading

[AWS EC2](https://aws.amazon.com/ec2/)

- What is an EC2 Instance?
  - Amazon Elastic Compute Cloud (EC2) is a web service offered by Amazon Web Services (AWS) that provides scalable computing capacity in the cloud. It allows users to launch and manage virtual machines, called instances, which can run various operating systems and applications.
- Name 2 use cases for EC2.
  - Run cloud native and enterprise applications
  - Scale for HPC applications
- Provide 1 reason to use ECS instead of a service such as Heroku, Digital Ocean, or Render.com.
  - They are the only cloud service to offer 400 Gbps ethernet networking

[EC2 For Humans](https://www.youtube.com/watch?v=lZMkgOMYYIg)

- Where can we find EC2 on the AWS Console?
  - Under the Compute section
- Explain the general difference between T2 Micro and XL.
  - The t family of Amazon Machine Images (AMIs) are cloud servers which have virtual pc components (cpu, ram, storage, etc.) that offer a general use experience - wheras some other families might be more focused on computation power or storage space. The micro vs xl just explains how powerful each individual virtual component has. For example, the t2.micro offers only 1GB of ram and the t2.xlarge offers 16GB of ram.
- Explain a “Compute Cycle” to a non-technical friend.
  - A compute cycle is a unit of work that a computer processor completes as part of a larger task. It’s like a single step in a longer process, where the computer is doing some kind of work, like running a program or processing data. The amount of time the processor spends working on that task is measured as a compute cycle.


[Elastic Beanstalk](https://www.youtube.com/watch?v=SrwxAScdyT0)

- What is Elastic Beanstalk?
  - Its an aws service that lets you auto deploy your server
- Describe the relationship between EC2 and Elastic Beanstalk.
  - Elastic beanstalk makes the deployment of EC2 servers efforless.
- Name some benefits of using Elastic Beanstalk.
  - It is easily scalable and time efficient.


### Bookmark and Review

[Virtual Machines](https://www.youtube.com/watch?v=yIVXjl4SwVo)

[VMS and the Cloud](https://www.youtube.com/watch?v=l0DfHUWMjsU)

