# projet-sec-res
A student project, where we deploy, configure, and secure a simulated enterprise network.

# Resouces:
GNS3 images.
https://github.com/hegdepavankumar/Cisco-Images-for-GNS3-and-EVE-NG/tree/main

OpenSwitch:
https://www.openvswitch.org/download/

# Entreprise network architecture

## Phase 1
https://brezular.com/2017/09/07/enterprise-network-on-gns3-part-1-introduction/


### Used images
- Arista vEOS versions 4.31.2F
- Cisco vIOS version 15.2
- Cisco Firewall ASAv version 9.9.1
- Cisco c7200
- Linux-microcore version 6.4


## Phase 2

In this phase we will be testing the security of our network infrastructure via exploiting any vulnerabilities that could be found, assessing our defense mechanisms, and improving our overall security.

### Red Team

We needed to connect PCs by an Ethernet cable , the first one contain the targeted architecture and the second one is the Attacker machine. W realised the following attacks.

 1. ARP Poisoning Attack
	 - Insider attack within the campus.

 1. Reverse Shell Attack
	 - External attack against the DMZ zone.

### Blue Team

To ensure all security systems are up-to-date and correctly configured.