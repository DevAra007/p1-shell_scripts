# Multi-Distribution Apache Web Server Deployment with Remote Execution

## Hands on video demonstration
[Youtube]

## Project Scenario

A large Fitness company operates a website that receives a significant amount of traffic. To ensure high availability and optimal performance, the company decides to deploy its web application across multiple Linux EC2 instances using different Linux distributions. The goal is to leverage the strengths of each distribution and enhance overall system reliability.

To achieve this, they employ a scripted approach for deploying the Apache web server on each instance, adapting the script based on the underlying Linux distribution. The provided script [here](./remote_websetup/multios_websetup.sh) serves as a template for the deployment process, with modular functions for package installation, service management, and artifact deployment.

## Purpose
In this project, I showcase my advanced skills in Linux administration and shell scripting by deploying an Apache web server on 4 Linux EC2 instances with different distributions and creating unique ssh keys for all 4 distros. This project focuses on creating a scalable and resilient web application infrastructure using Amazon Linux, Ubuntu, Debian and Redhat, with an emphasis on remote execution.
