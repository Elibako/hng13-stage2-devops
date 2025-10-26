README

Welcome to the Blue/Green Deployment Guide with NGINX project! This README provides a comprehensive overview of the project, setup instructions, usage guidelines, and other essential information to help you implement and manage blue/green deployments using NGINX.

Project Overview

This project demonstrates how to implement blue/green deployment strategies using NGINX as a reverse proxy and load balancer. It aims to minimize downtime and reduce risk during application updates by running two identical production environments (blue and green) and switching traffic between them.

Features

Seamless traffic switching between blue and green environments.

Configuration examples for NGINX to support blue/green deployments.

Step-by-step guide to set up and manage deployments.

Supports zero downtime deployments and rollback capabilities.

Installation

Follow these steps to set up the blue/green deployment environment:

Clone the repository:

git clone https://github.com/Elibako/hng13-stage2-devops.git
cd hng13-stage2-devops

Configure your blue and green application environments.

Set up NGINX with the provided configuration files.

Reload or restart NGINX to apply the new configuration:

sudo nginx -s reload

Usage

Deploy your application to both blue and green environments.

Use NGINX to route traffic to the active environment.

When ready to deploy a new version, update the inactive environment.

Switch traffic to the updated environment by modifying the NGINX configuration.

Reload NGINX to apply the changes without downtime.

Contributing

We welcome contributions! To contribute:

Fork the repository.

Create a feature branch.

Submit a pull request with a clear description of your changes.


Contact

For questions or feedback, please open an issue on GitHub or contact the maintainer at your-email@example.com.

Thank you for using the Blue/Green Deployment Guide with NGINX! Feel free to customize this README to better fit your specific deployment needs.