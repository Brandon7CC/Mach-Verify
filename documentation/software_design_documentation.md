# Mach-Verify Software Design Documentation
###### Project Name: Mach-Verify
###### Date: 20210227
###### Written By: Brandon Dalton and Ethan Smith
---
## Goals
Mach-Verifies goal is to provide users with a one-stop-shop for basic macOS security tools. Our hope is for our users to be confident in the confidentiality, integrity, and avalibility of their macOS systems. We plan to develop the following features for macOS systems:
- Entitlement enumeration: provide our users with a comprehensive look at what sensitive infromation their applications could be accessing.
- Current cyber threat intelligence integration: Current macOS system updates are intrustive to most users and do not sufficiently provide a sense of urgency. By integrating cyber threat intelligence users will be promptly alerted through Mach-Verity of any critical security related vulnerabilities that might be impacting their system and of any known updates that could remediate those vulnerabilities. 

## Context
Today's highly contested cyber environment puts users of all operating systems at risk of exposure to malware of all kinds. The common goal of malware is to defeat a system's security mechanisms. Common reasons why an attacker might want to do this include:
- Financial gain
- Information gathering / manipulation
- Disruption

To do this an adversary could exploit:
- A users trust / ignorance
- Applications
- Operating systems
- Computer component / software supply chains 
- etc... the list goes on

## Proposed Solution
Develop Mach-Verity, a macOS specific tool that provides cyber defense capabilities for our users. Mach-Verity will ensure that our users can be confident in the security posture of their macOS systems and that their privacy is being respected.

## Timeline 
- Documentation Completed: March 5, 2021
- Entitlement enumeration backend capability completed: March 12, 2021
- Entitlement enumeration front end completed: March 19, 2021
- ...