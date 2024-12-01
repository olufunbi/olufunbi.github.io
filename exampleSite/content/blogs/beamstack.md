---
title: "Beamstack: An Open source Framework for running Machine Learning Pipelines with Apache Beam"
date: 2024-09-27T23:29:21+05:30
draft: false
github_link: "https://github.com/olufunbi/olufunbi.github.io"
author: "Olufunbi Babalola"
tags:
  - Artificial Intelligence
  - Machine Learning
  - Kubernetes
image: /images/projects/logo-color-new.png
description: ""
toc:
---

### Overview of Beamstack
---
Beamstack is an open-source framework currently under development, aimed at facilitating the deployment of Machine Learning 
and GenAI workflow pipelines with Apache Beam on Kubernetes. Beamstack provides a robust Command Line Interface (CLI) that can potentially reduce 
pipeline deployment complexity and timelines drastically. It also possesses great monitoring and visualization features.  

### Why do you need Beamstack?
---
<img src="/images/blogs/why-beamstack.png"
  class="mt-3 mb-3"
  width="1200">

- **Configurable Deployment Environment**: With minimal steps you can setup Beamstack on your local minikube, bare metal or cloud infrastructure
- **Ease of Deployment with Beam Low-code YAML**: Beamstack adopts a low-code approach towards pipeline deployment which makes the process easier and faster
- **Composable and Reusable Pipeline Components**: Reusable pipeline components designed for easy composition and customization, enabling efficient workflow creation and deployment.
- **Collaborative Setup for Development Teams**: Beamstack’s modular architecture facilitates collaborative setup’s for various technical teams within an organization

### Beamstack Architecure
---
<img src="/images/blogs/architecture-beamstack.png"
  class="mt-3 mb-3"
  width="1200">

### How to use Beamstack
---
<img src="/images/blogs/install.png"
  class="mt-3 mb-3"
  width="1200">

- **Install the binary**: Install the beamstack binary from the releases section on the beamstack Github repository
- **Configre the target environment**: Beamstack initializes your target kubernetes cluster with the necessary components
- **Select YAML package to deploy**: Run and deploy your YAML pipeline by running the beamstack deploy command
- **Monitor your running jobs**: Open the grafana dashboard or runner UI to observe your running jobs

### Beamstack Roadmap
---
Feature Implementation
<img src="/images/blogs/roadmap.png"
  class="mt-3 mb-3"
  width="1200">

Tasks Breakdown
<img src="/images/blogs/tasks.png"
  class="mt-3 mb-3"
  width="1200"> 
