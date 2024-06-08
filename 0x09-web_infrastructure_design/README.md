# Web Infrastructure Design

## Overview
This project involves designing and explaining different web infrastructures. You'll be creating diagrams for various setups, understanding the roles of each component, and addressing potential issues. The goal is to become proficient in explaining web stacks, redundancy, and infrastructure scaling.

## Project Structure
- **0-simple_web_stack**: Design a simple web infrastructure with one server.
- **1-distributed_web_infrastructure**: Design a distributed web infrastructure with three servers.
- **2-secured_and_monitored_web_infrastructure**: Enhance the distributed infrastructure with security and monitoring features.
- **3-scale_up**: Scale up the infrastructure by adding more servers and components.

## Concepts Covered
- DNS
- Monitoring
- Web Server
- Network Basics
- Load Balancer
- Server
- LAMP Stack (Linux, Apache, MySQL, PHP/Perl/Python)
- SPOF (Single Point of Failure)
- QPS (Queries Per Second)
- High Availability Clusters
- HTTPS
- Firewalls

## Learning Objectives
By the end of this project, you should be able to:
- Draw and explain the web stack you designed.
- Explain the role and functionality of each component.
- Discuss system redundancy and scalability.
- Identify and address potential issues such as SPOF, downtime, and security concerns.

## Tasks

### 0. Simple Web Stack
- **Description**: Design a one-server web infrastructure with a LAMP stack.
- **Components**:
    - 1 server
    - 1 web server (Nginx)
    - 1 application server
    - 1 database (MySQL)
    - 1 domain name (foobar.com) pointing to the server IP (8.8.8.8)
- **Specifics to Explain**:
    - Server, domain name, DNS record type
    - Roles of web server, application server, database
    - Communication between server and user’s computer
    - Issues: SPOF, downtime during maintenance, scalability

### 1. Distributed Web Infrastructure
- **Description**: Design a three-server web infrastructure.
- **Components**:
    - 2 servers
    - 1 web server (Nginx)
    - 1 application server
    - 1 load balancer (HAproxy)
    - 1 database (MySQL)
- **Specifics to Explain**:
    - Purpose of each additional element
    - Load balancer configuration (distribution algorithm, Active-Active vs. Active-Passive)
    - Database Primary-Replica cluster
    - Issues: SPOF, security, lack of monitoring

### 2. Secured and Monitored Web Infrastructure
- **Description**: Secure and monitor the distributed web infrastructure.
- **Components**:
    - 3 firewalls
    - 1 SSL certificate (HTTPS)
    - 3 monitoring clients (data collectors)
- **Specifics to Explain**:
    - Purpose of firewalls, HTTPS, and monitoring
    - Data collection by monitoring tools
    - Monitoring web server QPS
    - Issues: SSL termination at load balancer, single MySQL write server, identical components on all servers

### 3. Scale Up
- **Description**: Scale up the infrastructure by adding a server and another load balancer, and splitting components.
- **Components**:
    - 1 additional server
    - 1 additional load balancer (clustered with the first)
    - Separate servers for web server, application server, database
- **Specifics to Explain**:
    - Purpose of each additional element

## Submission
- Each task requires a whiteboard design and explanation.
- Upload the diagrams to an image hosting service and insert the links into the respective answer files.
- Push the answer files to your GitHub repository.
- Manually review and whiteboard each task with a mentor or staff member.

## Directory Structure
```plaintext
0x09-web_infrastructure_design/
├── 0-simple_web_stack
├── 1-distributed_web_infrastructure
├── 2-secured_and_monitored_web_infrastructure
├── 3-scale_up
├── README.md
