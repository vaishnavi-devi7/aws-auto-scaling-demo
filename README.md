# aws-auto-scaling-demo
Demonstrates AWS Auto Scaling with EC2 instances and an Application Load Balancer. The ALB distributes traffic, while Auto Scaling dynamically adds or removes EC2 instances based on demand

# AWS Auto Scaling Demo with Application Load Balancer

## Overview
This project demonstrates how AWS Auto Scaling dynamically manages EC2 instances and distributes traffic using an Application Load Balancer (ALB). Multiple EC2 servers run Nginx web pages, and the ALB automatically routes requests based on instance availability.

## Services Used
- AWS EC2
- AWS Auto Scaling
- AWS Application Load Balancer
- Security Groups
- Nginx Web Server

## Deployment Steps
1. Launch EC2 instances (Server-1 & Server-2) using a Launch Template
2. Install Nginx and upload HTML pages for each server
3. Create an Auto Scaling Group to maintain desired instance count
4. Configure scaling policies (min, max, desired capacity)
5. Create an ALB and attach the Auto Scaling group
6. Access ALB DNS name in a browser and refresh to see traffic distributed among multiple servers

## Outcome
- Traffic is automatically routed to healthy EC2 instances
- Auto Scaling dynamically adjusts the number of instances based on demand
- Demonstrates high availability and fault-tolerance

## Technologies
AWS EC2, Auto Scaling, Application Load Balancer, Nginx, Security Groups

