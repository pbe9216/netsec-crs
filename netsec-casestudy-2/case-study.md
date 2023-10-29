# Network Security - Case study 2

## Objectives

The goal of this project is to use the knowledge acquired in the network security fundamentals module and explore more advanced topics. In this project you'll need to deep dive into a specific technology. While making you think about the overall design, you'll also get into some intricacies to have a working prototype. In this project student dig in honeypots.

## Description

XYZ Corporation, a leading technology company, has recently experienced a rise in cyber threats and attacks. As a network security professional, your task is to design and implement an advanced honeypot system to detect and analyze these threats effectively. A honeypot is a security mechanism set up to detect, deflect, or counteract attempts at unauthorized use of information systems.

Currently XYZ Corporation is located in North America and has two datacenters, one in Chicago, IL (CHI1) and one in Vancouver, CA (YVR1). These two datacenters hosts XYZ core product, a CRM application that is distributed in SaaS mode. The company is relying on Azure TM (Traffic Manager) to perform GSLB tasks to send the resquest to both datacenters.

Both datacenters have they own public IPs and own DMZ that hosts a stack of firewalls, local load-balancers (that also performs TLS session termination), web application firewalls (WAF), web frontend servers and some reverse proxies (diagram attached).

As said, the SOC would like to setup a honeypot system to provide more insight about external threats. They have reached to the network team to help in this matter.

## Tasks

Below is the list of mandatory points to tackle in this exercise, but any other relevant suggestions are welcomed.
- Research honeypot technologies and best practices
- Assess the current architecture and suggest where to place the honeypot system(s),
- Define and argument what kind of honeypot is best adapted to this use case,
- Create a proof-of-concept of the solution and in a virtual environment
- Provide some sample test cases to demonstrate how the solution operates and how detection is achieved
- It is important to outline how 

## Deliverables

A report should be produced detailing 
- the honeypot solutions landscape,
- the placement of the honeypot(s) in the architecture,
- which solution has been chosen,
- how the solution will be setup (low level implementation guide),
- how the solution operates using sample tests

A presentation to give to the customer 

