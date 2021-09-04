---
layout: post
title: Legacy Modernization Revolution (Part 2)
image: assets/dist/img/cattle.jpg
excerpt: Changes are afoot in government application development (part 2)
---

In part 1 I discussed how small agile teams can be procured (see the state ADPQ process) to come onto a project and immediately start working with state employees to build working software, learning about the domain and help the state learn about agile. Three other factors that have helped spur the legacy modernization revolution are open source, cloud, DevOps.

## Open Source

We are seeing the model of using open source work well. Possible steps for you to try:

1. Identify a problem that your team might consider developing a customer solution for. (e.g. we have 40 services, but only want to expose 10 to the outside world)

2. Find solid open source project with an active community
(e.g. Kong)

3. Do a proof of concept to see if it meets your needs

4. Find a vendor who will provide support. (e.g. Mashape for Kong)

This helps accelerate the development process by allowing dev teams to pick and choose best of breed tools, integrate them, and avoid having to develop and test these tools themselves.  

Using best of breed open source tools provides a frictionless (little cost to experiment with, no licensing issues) method to reuse software that has already been built and tested elsewhere, thereby accelerating the development process. 

## Cloud

Using the cloud is just a different way of getting servers, networks, and databases (aka infrastructure), right? 

Yes and no. 

Yes -- it allows project teams to get servers much more quickly than historically possible. The project is not held hostage while server needs are defined, orders placed, deliveries occur, and (finally) servers are placed into service. Now, new servers, networks, and other infrastructure can be procured in minutes via a cloud console, or (better) through Ansible code. 

No -- this use of the cloud also involves writing a new type of code that actually defines the infrastructure. So you have the software that is the application, and you have the software that is the infrastructure. 

Since the infrastructure can become a series of software componets (e.g. Ansible scripts, Jenkins scripts, Docker containers, etc.) a single environment can be spun up quickly and torn down just as quickly. Refactor, and do it again. 
Infrastructure is no longer a treasured component of the project, meticulously cared for and fed. Infrastructure becomes like cattle, not pets. 

![cattle, not pets](/assets/dist/img/cattle.jpg)

## DevOps

Through software (e.g. Amazon Cloudformation scripts) environments can be defined, applications deployed, systems monitored. This requires a new type of engineer, someone who knows infrastructure and someone who knows software. These Development Operations (DevOPs) people are the new breed of system admins -- unlike the system admins of days gone by, a DevOps person is enmeshed in the software development process. 