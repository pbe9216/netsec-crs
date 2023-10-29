# Network Security - Case study 3

## Objectives

The goal of this project is to use the knowledge acquired in the network security fundamentals module and explore more advanced topics. In this project you'll need to deep dive into a specific technology. While making you think about the overall design, you'll also get into some intricacies to have a working prototype. In this project, students will explore and implement an advanced web infrastructure security setup incorporating HTTP/3, load balancing, SSL termination, and Intrusion Detection Systems (IDS). The goal is to create a highly secure, efficient, and monitored web environment.

## Description

DGH Corporation, a leading car manufacturing company, stands at the forefront of innovation and quality in the automotive industry. With a strong commitment to excellence, DGH has established itself as a trusted name in the market. As part of their expansion strategy, DGH Corporation operates a sophisticated web portal dedicated to their network of resellers. This portal serves as a pivotal platform for facilitating seamless communication, transactions, and collaboration between DGH Corporation and its valued resellers.

However, in the ever-evolving landscape of cybersecurity threats, ensuring the robustness and integrity of online platforms is paramount. Recognizing the need to fortify their web portal against potential vulnerabilities, DGH Corporation has undertaken a proactive approach. After a meticulous security audit, the company has decided to implement cutting-edge technologies to bolster the security of their online infrastructure.

In response to DGH Corporation's security concerns and aspirations for a safer online environment, you, as consultants, are entrusted with the critical task of fortifying their web portal.

After meeting with the resellers application team, you understand that they publish a HTTP front-end. This HTTP frontend will be transitioning from HTTP/2 to HTTP/3 in the next infrastructure. Hence testing must be done accordingly. The application team would like to insert some load balancers to better handle the multiple frontends. These load-balancers should also terminate the TLS sessions to offload that out of the application stack.

On its side, the network team indicated that the web portal is currently protected by a dedicated firewall cluster. Today all servers are in the same VLAN, routed at the firewall. Today, the log are exported to a Splunk server.

## Tasks

Your mission is to introduce the security measures listed.
- Insert a load balancer in the topology (design and configurations)
- Describe and understand HTTP/3 / QUIC
- Terminate SSL at load-balancer
- Recommend where and how to install the IDS
- Detail how to install and operate IDS
- Test the setup in PoC environment

## Deliverables

A report should be produced detailing

- The load balancer placement and configuration
- The IDS placement and configuration
- which solutions have been chosen,
- some sample test cases to validate solution is working
- as a bonus how this will be integrated in the splunk environment

A presentation to give to the customer
