# Domain 4: Networking and Cloud Security Concepts

## 1. Network Security Fundamentals (Objective 4.1)
* **OSI and TCP/IP Models:**
  * **OSI 7 Layers:** Physical (Bits), Data Link (Frames, MAC addresses, switches), Network (Packets, IP addresses, routers), Transport (Segments, TCP/UDP, ports), Session, Presentation and Application.
  * **TCP/IP 4 Layers:** Network Interface, Internet, Transport and Application.
* **Addressing and Protocols:**
  * **IPv4 vs. IPv6:** IPv4 uses 32-bit addresses (NAT often required); IPv6 uses 128-bit hexadecimal addresses with built-in IPsec support.
  * **Essential Ports:** FTP (20/21), SSH (22), Telnet (23 - insecure), SMTP (25), DNS (53), DHCP (67/68), HTTP (80), POP3 (110), NTP (123), IMAP (143), SNMP (161/162), HTTPS (443) and RDP (3389).
* **Common Network Threats:**
  * **Denial of Service (DoS) and DDoS:** Exhausting bandwidth or system resources to disrupt availability.
  * **On-Path (Man-in-the-Middle) Attacks:** Intercepting or altering communications between two endpoints.
  * **ARP Spoofing and DNS Poisoning:** Corrupting address resolution caches to redirect legitimate traffic to malicious hosts.
  * **Wireless Threats:** Rogue Access Points (unauthorized hardware connected to the corporate network), Evil Twin APs (spoofed SSIDs capturing credentials) and RF jamming.
* **Network Security Controls:**
  * **Firewalls:** Filter inbound and outbound traffic based on stateful inspection, application awareness (NGFW) and default-deny rulesets.
  * **IDS vs. IPS:** Intrusion Detection Systems (IDS) passively monitor and generate alerts; Intrusion Prevention Systems (IPS) sit inline to actively block malicious traffic.
  * **Virtual Private Networks (VPNs):** Establish encrypted tunnels (IPsec or TLS) over untrusted networks to protect confidentiality and integrity.
  * **Wireless Security:** Enforcing WPA3 encryption, disabling WPS and using 802.1X authentication for enterprise Wi-Fi.

## 2. Network Security Architecture (Objective 4.2)
* **Defense-in-Depth:** Layering multiple independent administrative, technical and physical controls so failure of one layer does not compromise the entire environment.
* **Network Segmentation and Isolation:**
  * **VLANs and Subnets:** Dividing flat networks into isolated broadcast domains to restrict lateral movement.
  * **Screened Subnet (DMZ):** Buffer zone hosting public-facing services (web, email or DNS servers) isolated from internal corporate networks by firewalls.
  * **Micro-Segmentation:** Granular workload-level isolation enforcing strict east-west traffic policies inside data centers and cloud environments.
  * **Air-Gapping:** Physical disconnection of ultra-sensitive systems from external or unsecured networks.
* **Zero Trust Architecture:** Security model operating on "never trust, always verify" where every access request is continuously authenticated, authorized and encrypted regardless of network location.
* **Embedded Systems, IoT and ICS:**
  * **Internet of Things (IoT):** Constrained smart devices requiring network isolation, firmware updates and strong default credential changes.
  * **Industrial Control Systems (ICS) and SCADA:** Operational technology (OT) managing critical infrastructure where availability and physical safety take top priority over frequent patching.

## 3. Cloud Security Concepts (Objective 4.3)
* **Essential Cloud Characteristics:** On-demand self-service, broad network access, resource pooling, rapid elasticity and measured service.
* **Cloud Service Models:**
  * **Infrastructure as a Service (IaaS):** Provider manages physical hardware, virtualization and networking; customer manages OS, middleware, applications and data.
  * **Platform as a Service (PaaS):** Provider manages underlying infrastructure and runtime environment; customer manages deployed applications and data.
  * **Software as a Service (SaaS):** Provider delivers fully managed applications over the web; customer manages user access, configurations and data governance.
* **Cloud Deployment Models:**
  * **Public Cloud:** Multi-tenant infrastructure owned and operated by a third-party cloud service provider (CSP).
  * **Private Cloud:** Dedicated infrastructure provisioned exclusively for a single organization (on-premises or hosted).
  * **Hybrid Cloud:** Combined public and private environments connected via encrypted links for workload portability.
  * **Community Cloud:** Shared infrastructure governed by multiple organizations with common regulatory or mission requirements.
* **Shared Responsibility Model:** Security duties are split between the CSP ("security *of* the cloud") and the customer ("security *in* the cloud"). Across every model, the customer always retains accountability for **data protection, identity management and endpoint security**.
* **Cloud and AI Infrastructure Security:** Securing APIs, preventing misconfigured storage buckets, vaulting cloud secrets and isolating AI training and inference workloads.
