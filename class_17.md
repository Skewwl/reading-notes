# class_17

## AWS S3

- What is Amazon S3?

Amazon Simple Storage Service (Amazon S3) is an object storage service offering industry-leading scalability, data availability, security, and performance.

- Name some use cases for Amazon S3.

  - Run big data analytics, artificial intelligence (AI), machine learning (ML), and high performance computing (HPC) applications to unlock data insights.
  - Build fast, powerful mobile and web-based cloud-native apps that scale automatically in a highly available configuration.

- Name some benefits of using Amazon S3.

S3 is easily scalable and has built in security.

## AWS Lambda Basics

- What is AWS Lambda?

AWS Lambda is a serverless computing service provided by Amazon Web Services (AWS). Users of AWS Lambda create functions, 'self-contained applications' written in one of the supported languages and runtimes, and upload them to AWS Lambda, which executes those functions in an efficient and flexible manner.

- Name some use cases for AWS Lambdas.

Functions that can serve web pages and make calls to APIs.

- Describe “serverless” to a non-technical friend.

Serverless doesn’t mean that there are no servers involved: it just means that the servers, the operating systems, the network layer and the rest of the infrastructure have already been taken care of, so that you can focus on writing application code.

## CDN

- What is a CDN?

A Content Delivery Network (CDN) is a geographically distributed group of servers that work together to provide fast delivery of Internet content. A CDN allows for the fast transfer of data needed for loading Internet content including HTML pages, javascript files, stylesheets, images, and videos.

- How does a CDN work with relation to the website visitor?

CDNs work through servers nearest to the website visitor respond to the request. The content delivery network copies the pages of a website to a network of servers that are spread out at geographically different locations, caching the contents of the page. When a user requests a webpage that is part of a content delivery network, the CDN will redirect the request from the originating site’s server to a server in the CDN that is closest to the user and deliver the cached content. CDNs will also communicate with the originating server to deliver any content that has not been previously cached.

- What are the benefits of employing a CDN?

The speed is improved by distributing content closer to the website visitors by using a nearby CDN server, causing visitors to experience faster page loading times. Also, it helps protect your website against certain forms of cyber attacks.
