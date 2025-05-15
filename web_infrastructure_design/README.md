# Web Infrastructure Design

A collection of web infrastructure design exercises focused on building scalable, secure, and monitored systems.

## Overview

This directory contains four progressive tasks that demonstrate the evolution of web infrastructure from simple single-server setups to complex distributed systems.

## Tasks

### 0-simple_web_stack
Design a basic one-server web infrastructure hosting www.foobar.com using a LAMP stack.

**Components:**
- 1 server with Nginx, application server, application files, and MySQL
- Domain configuration with www record pointing to server IP

### 1-distributed_web_infrastructure  
Expand to a three-server infrastructure with load balancing.

**Additional Components:**
- HAproxy load balancer
- 2 web servers with identical configurations
- Database replication setup

### 2-secured_and_monitored_web_infrastructure
Add security and monitoring to the distributed setup.

**Security & Monitoring:**
- 3 firewalls for network protection
- SSL certificate for HTTPS
- 3 monitoring clients for data collection

### 3-scale_up
Further scale the infrastructure with component separation.

**Scaling Features:**
- Separate servers for web, application, and database tiers
- Load balancer clustering
- Dedicated component hosting

## Requirements

- Create whiteboard diagrams for each task
- Take screenshots of completed diagrams
- Upload images to hosting service
- Include image links in answer files
- Submit GitHub file links

## Key Concepts

- **LAMP**: Linux, Apache/Nginx, MySQL, PHP stack
- **SPOF**: Single Point of Failure
- **QPS**: Queries Per Second
- Load balancing algorithms
- Database replication
- SSL termination
- System monitoring

## Evaluation

Each task requires:
- Complete infrastructure diagram
- Explanation of component roles
- Identification of potential issues
- Understanding of scaling implications

## Time Limit

30 minutes per whiteboard session with mentor review.