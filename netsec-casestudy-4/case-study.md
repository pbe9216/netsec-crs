# Network Security - Case study 4

## Objectives

The goal of this project is to use the knowledge acquired in the network security fundamentals module and explore more advanced topics. In this project you'll need to deep dive into a specific technology. While making you think about the overall design, you'll also get into some intricacies to have a working prototype. In this project, students will explore how to intercept, decrypt and observe a TLS protected network traffic.

## Description

MLK Corporation, a prominent food industry leader, finds itself deeply intertwined with DHZE, the regulatory authority overseeing sample analysis and legal compliance. Within this partnership, MLK runs critical scheduled jobs, exporting lists of analyzed samples daily. The export is using and HTTPS connection from the MLK network to the DHZE network. To maintain security and prevent any leak of confidential information, MLK Corporation aims to establish an TLS decryption system. It will be coupled with cutting-edge deep packet inspection tools.

The MLK corporation is interconnected through a partner landing zone that is secured with a pair of firewall in cluster. These firewalls control access to and from the partner.
This ensure notably, that only outgoing connections are allowed. While the firewall can embed some functions the company would like to study what would be necessary to decrypt these communications. Ideally, they would like to get a proof of concept.

## Tasks

Your mission is to do a PoC for TLS decrpytion.
- set up the PoC environment
- Describe and understand how to do TLS interception (in regard to TLS version)
- Define a suitable architecture
- Define how this can scale (bandwidth wise)
- Detail how you would perform data capture

## Deliverables

A report should be produced detailing this proof of concept, from theory to practice.
