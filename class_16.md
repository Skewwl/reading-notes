# 401 class_16

## AWS EC2

- What is an EC2 Instance?

A virtual server for running applications in the cloud on AWS.

- Name 2 use cases for EC2.

  - scale high performance computing applications
  - can run cloud native applicaitons for high performance

- Provide 1 reason to use EC2 instead of a service such as Heroku, Digital Ocean, or Render.com.

EC2 has different instance types optimized for different use cases. These instance types differ in terms of CPU, memory, storage, and networking capabilities. You can choose the instance type that best matches your application's requirements.

## EC2 For Humans

- Where can we find EC2 on the AWS Console?

Services -> Compute -> EC2

- Explain the general difference between T2 Micro and XL.

  - T2 Micro: T2 Micro instances are part of the "T2" family and are designed for low to moderate workloads. They have a small amount of CPU and memory resources.
  - T2 XL: T2 XL instances, on the other hand, are also part of the "T2" family but are larger in size and offer more CPU and memory resources.

- Explain a “Compute Cycle” to a non-technical friend.

Imagine your computer or any electronic device like a bicycle. When you pedal a bicycle, it moves forward, right? In the same way, when you use your computer, it's doing something, like running a program, opening a web page, or calculating something. Now, think of a "compute cycle" as one full pedal rotation on your bicycle. It's a tiny unit of work that your computer does when it's processing information. Just like pedaling makes your bike move forward, a compute cycle helps your computer do things like show you a picture, play a video, or solve a math problem.

## Elastic Beanstalk

- What is Elastic Beanstalk?

Service that deploys manages and scales web apps and services.

- Describe the relationship between EC2 and Elastic Beanstalk.

Elastic Beanstalk is like an application assistant that will monitor your EC2 app and auto-scale it for you.

- Name some benefits of using Elastic Beanstalk.

App health monitoring, provisioning, laod balancing & auto scaling.
