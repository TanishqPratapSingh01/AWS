# What is AWS (Amazon Web Services)?

## Introduction

**Amazon Web Services (AWS)** is a cloud computing platform provided by Amazon that offers a wide range of services for building, deploying, and managing applications over the internet.

Instead of purchasing and maintaining physical servers, storage devices, and networking equipment, developers and organizations can use AWS to access these resources on demand and pay only for what they use.

AWS was launched in **2006** and has become one of the world's leading cloud computing platforms, serving millions of customers, from startups to large enterprises.

---

# Why Do We Need AWS?

Traditionally, companies had to build and maintain their own data centers.

This required:

- Purchasing expensive servers
- Setting up networking equipment
- Managing storage systems
- Hiring infrastructure engineers
- Paying for electricity and cooling
- Replacing hardware when it failed

This approach was expensive, time-consuming, and difficult to scale.

AWS solves these problems by providing cloud infrastructure that can be accessed through the internet.

Instead of buying hardware, you simply rent the resources you need.

---

# What is Cloud Computing?

Cloud computing is the delivery of computing services such as servers, storage, databases, networking, and software over the internet.

Instead of running applications on your own computer or company server, they run on cloud servers managed by a cloud provider like AWS.

Think of it like renting an apartment instead of buying a house.

- Buying a house = Buying your own servers
- Renting an apartment = Using cloud services like AWS

You only pay for what you use.

---

# Key Features of AWS

AWS provides many benefits for developers and businesses.

### Scalability

Resources can be increased or decreased depending on application traffic.

For example:

- During a sale, an e-commerce website can handle millions of users.
- After the sale, resources can be reduced to save costs.

---

### High Availability

AWS has multiple data centers around the world.

If one server fails, another server can continue serving users.

This helps keep applications available with minimal downtime.

---

### Pay-as-You-Go Pricing

You only pay for the resources you actually use.

There is no need to purchase expensive hardware in advance.

---

### Security

AWS provides built-in security features including:

- Identity and Access Management (IAM)
- Data encryption
- Firewalls
- Multi-Factor Authentication (MFA)
- Security monitoring

---

### Global Infrastructure

AWS operates data centers across multiple countries.

Applications can be deployed close to users to reduce latency and improve performance.

---

# Common AWS Services

AWS offers more than 200 services. Some of the most commonly used services are:

| Service | Purpose |
|----------|---------|
| EC2 | Virtual servers for running applications |
| S3 | Object storage for files, images, and backups |
| RDS | Managed relational databases |
| Lambda | Run code without managing servers |
| IAM | Manage users, roles, and permissions |
| CloudWatch | Monitor applications and infrastructure |
| VPC | Create private virtual networks |
| CloudFront | Content Delivery Network (CDN) |
| Elastic Beanstalk | Deploy web applications easily |
| ECR | Store Docker container images |

---

# Real-Life Example

Imagine you have developed an online shopping website.

Your application includes:

- React Frontend
- Node.js Backend
- MongoDB Database
- Product Images

Using AWS, you could deploy your application like this:

```
Users
   │
   ▼
CloudFront (CDN)
   │
   ▼
React Frontend (S3)
   │
   ▼
Node.js API (EC2)
   │
   ▼
MongoDB Database
```

Whenever customers visit your website:

1. The frontend is loaded from AWS S3.
2. API requests are sent to an EC2 server.
3. The server communicates with the database.
4. Product images are delivered quickly using CloudFront.

---

# Example Scenario

Suppose you build a portfolio website.

Without AWS:

```
Your Laptop
      │
      ▼
Website runs only while your laptop is ON.
```

Problems:

- Users cannot access the website if your laptop is off.
- Slow internet connection.
- Difficult to scale.
- Limited reliability.

With AWS:

```
Users
      │
      ▼
AWS Cloud Server
      │
      ▼
Portfolio Website
```

Now:

- The website is available 24/7.
- Faster response times.
- Easy to handle more visitors.
- No need to keep your laptop running.

---

# AWS and CI/CD

AWS is commonly used in CI/CD pipelines.

Example workflow:

```
Developer Writes Code
        │
        ▼
Push Code to GitHub
        │
        ▼
GitHub Actions
        │
        ▼
Run Tests
        │
        ▼
Build Application
        │
        ▼
Deploy to AWS
        │
        ▼
Application Available to Users
```

In this workflow:

- GitHub Actions automates the pipeline.
- AWS hosts the application.
- Users receive the latest version automatically.

---

# Advantages of AWS

- Easy to use
- Highly scalable
- Reliable infrastructure
- Global availability
- Strong security features
- Cost-effective pricing
- Wide range of cloud services
- Supports modern DevOps practices

---

# Limitations of AWS

- Can become expensive if resources are not managed properly.
- Large number of services can be overwhelming for beginners.
- Learning cloud architecture takes time.
- Incorrect security configurations can expose applications.

---

# When Should You Use AWS?

AWS is commonly used when you need to:

- Host websites
- Deploy web applications
- Store files and images
- Build REST APIs
- Run databases
- Host Docker containers
- Automate deployments using CI/CD
- Build scalable cloud applications

---

# Interview Questions

### 1. What is AWS?

AWS (Amazon Web Services) is a cloud computing platform that provides on-demand services such as servers, storage, databases, networking, and deployment tools over the internet.

---

### 2. Why is AWS used?

AWS is used to build, deploy, and manage applications without maintaining physical infrastructure.

---

### 3. What is the biggest advantage of AWS?

The biggest advantage is its ability to scale resources on demand while following a pay-as-you-go pricing model.

---

### 4. Name some popular AWS services.

- Amazon EC2
- Amazon S3
- AWS Lambda
- Amazon RDS
- IAM
- CloudWatch
- CloudFront

---

# Summary

AWS (Amazon Web Services) is a cloud computing platform that enables developers and businesses to build, deploy, and manage applications using cloud infrastructure instead of physical hardware.

It provides services such as virtual servers, storage, databases, networking, security, and monitoring, allowing applications to scale efficiently while reducing infrastructure costs.

AWS is widely used in modern software development, DevOps, and CI/CD pipelines because it offers reliable, secure, and globally accessible cloud services.
