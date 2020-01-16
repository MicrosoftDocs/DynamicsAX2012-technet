---
title: Planning security for Microsoft Dynamics AX
TOCTitle: Planning security for Microsoft Dynamics AX
ms:assetid: 1d7f1bc2-0553-4695-8de7-b45aeb445930
ms:mtpsurl: https://technet.microsoft.com/library/Dn385335(v=AX.60)
ms:contentKeyID: 56554588
author: Khairunj
ms.date: 06/11/2014
mtps_version: v=AX.60
---

# Planning security for Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Security planning for a Microsoft Dynamics AX 2012 system starts before deployment and continues throughout the life cycle of Microsoft Dynamics AX. It requires an understanding of potential security threats and of the industry best practices for confronting each type of threat. This topic outlines an approach to planning that matches threats with defenses in each level of your computer infrastructure, placing the greatest levels of protection around your organization’s most valuable assets.

## Assess your threats

An organization’s computer security strategy starts with an assessment of its most valuable assets and operational capabilities – its core business processes or provided services. These assets and capabilities will include the following, in descending order of importance:

  - Business, customer, and financial data

  - Continuity of business operations

  - Computer code and other intellectual property (IP)

  - Network connectivity

  - Integrity of public-facing web sites

  - Physical infrastructure

In a typical Microsoft Dynamics AX deployment, these assets and capabilities will be associated with computers that are distributed across public and private networks, and that have varying degrees of security. The following diagram illustrates the network topology and physical arrangement of a simple Microsoft Dynamics AX deployment, with the unsecured Internet at the top and increasingly secured enterprise environments as you move down.

![Dynamics AX deployment topology](images/Dn385335.Security_topology(AX.60).png "Dynamics AX deployment topology")

The components of this Microsoft Dynamics AX system extend across several distinct security domains, including the public Internet (top), a perimeter network (also known as a DMZ, demilitarized zone, and screened subnet; middle), and an intranet (bottom). Users access public-facing business services from across the Internet by means of web browsers, point-of-sale terminals, or virtual private network (VPN) clients. An external firewall (located in a secured server facility along with the organizations other server and network equipment) filters and directs incoming network traffic based on the packet protocol and destination port. Protected by this firewall, the organization’s perimeter network contains the public-facing servers – Terminal Services, Enterprise Portal for Microsoft Dynamics AX, DNS, and so on – that handle access from external clients. Separating the perimeter network from the organization’s intranet is a second firewall that directs and filters traffic based on the source, port, and application. Behind this firewall, the intranet contains computers running the rich client or Enterprise Portal, the Application Object Server (AOS), the Help server, the internal Enterprise Portal server, the databases, and other servers.

Next, develop a threat model that lists possible attackers, goals, exploits, and targets. Details will vary depending on the nature of your organization, but a general model of enterprise-level adversaries might resemble the following.

![Range of security threats](images/Dn385335.Security_threats(AX.60).png "Range of security threats")

After this threat model is mapped to potential targets in your organization, you will have a framework for identifying threats, recognizing vulnerabilities, prioritizing by return on investment (ROI), and planning countermeasures. In the following table, some sample goals of potential attackers are juxtaposed with the assets and operations that would be threatened, and with the priority of the resulting threat.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Goal</p></th>
<th><p>Targets</p></th>
<th><p>Priority</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Theft of IP</p></td>
<td><p>Databases</p></td>
<td><p>High</p></td>
</tr>
<tr class="even">
<td><p>Theft of financial info</p></td>
<td><p>Databases, network, Microsoft Dynamics AX access</p></td>
<td><p>High</p></td>
</tr>
<tr class="odd">
<td><p>Disruption of operations</p></td>
<td><p>Network, server computers</p></td>
<td><p>High</p></td>
</tr>
<tr class="even">
<td><p>Exposure of sensitive info</p></td>
<td><p>Network, office computers</p></td>
<td><p>Medium</p></td>
</tr>
<tr class="odd">
<td><p>Website defacement</p></td>
<td><p>Public web server</p></td>
<td><p>Low</p></td>
</tr>
</tbody>
</table>


Based on the potential cost to the organization, greater resources should be devoted to protecting the databases than the public-facing web server. The protection of financial data requires that multiple attack vectors be taken into account: network intruders attacking the databases from outside the organization, and also insiders with access to Microsoft Dynamics AX client computers and other intranet resources.

## Plan your countermeasures

To confront potential threats, Microsoft follows industry standards in recommending a layered, heavily redundant approach to security known as defense in depth. Defense in depth is based on the insight that any defensive measure can be defeated by a sufficiently determined adversary. Rather than trusting a single defense, such as a firewall that sits in front of otherwise vulnerable targets, defense in depth relies on multiple defenses that are understood primarily as delaying tactics. An effective implementation of defense in depth buys the defender time to respond to an attack before irretrievable losses are suffered.

After you have prioritized your organizational assets and operations, identified your potential attackers, and established what assets could be targeted, the next step of planning is to select appropriate countermeasures for each component of your system.

The following diagram matches the Microsoft Dynamics AX system topology that was already described with a layered defense that applies the most resources to the most valuable assets.

![Countermeasures to security threats](images/Dn385335.Security_countermeasures(AX.60).png "Countermeasures to security threats")

Moving from the Internet (at the top of the diagram) downward through levels within the enterprise, the security policy accrues deepening layers of protection and monitoring, as represented by the vertical bars on the right. Note that the most valuable business assets are afforded the most protections. The first four types of security measure apply to all assets across the organization:

  - Leadership, training, and awareness

  - Operational security policies

  - Network security

  - Host-based defenses

The next three are specific to on-premises hardware and software:

  - Physical security

  - Application-based security

  - Database security

The rest of this section describes each of these categories and explains how they fit together into a comprehensive security plan.

## Security categories

## Leadership, training, and awareness

Management commitment to security is crucial to the success of a security plan. Applying security measures requires human and financial resources, and the enforcement of consistent policies throughout the organization. Ideally, an executive-level security chief should be responsible for the planning, implementation, and ongoing supervision of the security policy, and for serving as the single point of contact. 

Employees also need to be engaged with the planning process, thoroughly trained in the security issues and best practices appropriate for their roles, and aware that the welfare of the organization depends on their awareness and loyalty.

## Operational security policies

Operational security policies are open-ended and vary from one organization to another. These policies regulate the interactions of outsiders and employees with business assets.

  - **Principle of least privilege** – Users (and personnel generally) should be given the minimum security privileges that they require to carry out their approved tasks. This principle can be applied equally well to computer and application access, network access, and physical access. Exceptions, if truly needed, should be cross-checked using segregation of duties.

  - **Segregation of duties** – No organizational process should be under the control of a single employee. Instead, sign-offs by multiple employees should be required at each stage in any process. This policy protects against both fraud and errors. For example, an inside attacker attempting to obtain bulk financial information should face barriers created by Microsoft Dynamics AX role-based security. In addition, honest employees should be prevented by their roles from seeing or exposing sensitive data such as credit card numbers. 

  - **Logging computer access** – Access to restricted servers and software applications should be logged electronically, and the logs should be regularly audited. The information retained should include the identity of the user and the time and duration of the user session. Access that deviates from an employee’s normal or expected pattern, including higher than normal computer processing workloads, should be investigated.

  - **Domain-controlled password strength and expiration policies (including service accounts)** – Policies enforcing password strength and expiration can help minimize damage in the case of stolen or inadvertently leaked passwords. Consider using service account passwords that expire to prevent server assets from being exposed to attacks from insiders.

  - **Domain-controlled computer access policies** – Domain policies offer a centralized way of designing and controlling access based on the principle of least privilege. Restrictions might be based on the user, host, time, location, or application.

  - **Software installation policies** – Unauthorized software installed by employees inside the intranet might create a security hazard. Aside from the possibility of introducing actual malware, employees who do this might deliberately or inadvertently circumvent network and host-based security measures, or interfere with the operation of authorized software. Domain restrictions can reduce these threats, but employee training and awareness should be regarded as the first line of defense

  - **Encrypted internal and external data exchange** – The organization’s internal and external electronic data exchanges (email, telephone, business records and data, and so on) should be protected by strong encryption. Reliable encryption means encryption performed by on-premises computers. Information encrypted by third parties or on remote server hosts (such as cloud storage) should not be considered safe. Furthermore, the protection of message content by encryption should not be confused with the use of secure channels provided by VPNs or HTTPS – for maximum security, these measures should be used in tandem. We strongly recommend hiring a reputable security consultant when planning and implementing an encryption policy.

  - **External access over HTTPS or VPN** – Remote access to the organization’s servers should only be allowed over HTTPS (for connecting via Enterprise Portal) or over a VPN (for connecting via Terminal Services to a rich client). Both methods provide a secure tunnel for communications between the user’s remote client computer and the on-premises Microsoft Dynamics AX services. However, unless the content itself is encrypted, it will be available as clear text at both ends of the secure connection. For information about securing Enterprise Portal access, see [Configure Enterprise Portal to use Secure Sockets Layer](configure-enterprise-portal-to-use-secure-sockets-layer.md).

  - **Restrictions on devices** – Unless the security impact of an employee-owned device is validated by your IT department and the device is approved for workplace use, it might be a security hazard. In environments demanding very high data security, the presence of portable storage media (USB thumb drives, portable disk drives, optical media, and so on) might not be acceptable. Domain controls on the types of devices that can connect to on your intranet might be advisable, especially if there is wireless support.

## Network security

1.  **Firewalls** – Firewalls filter network access based on rules. They are broadly divided into network and application firewalls, depending on the level of the OSI stack they work on. Any aspect of network communications, including sources, destinations, packet types, and timing, can be controlled. Dynamic firewalls can adjust rules automatically in response to hostile network traffic such as distributed denial of service (DDOS) attacks. Though generally deployed as dedicated network appliances, firewalls can also be implemented in software as a host-based defense. For information about using host-based firewalls with Microsoft Dynamics AX, see [Firewall settings for Microsoft Dynamics AX components](firewall-settings-for-microsoft-dynamics-ax-components.md).

2.  **Forward and reverse proxies**– Proxy servers, located in the perimeter network, insert mediating services between two computers, enabling transactions to be filtered, altered, or logged. A forward proxy passes packets from the intranet to the Internet, whereas a reverse proxy passes them from the Internet to the intranet. Most perimeter-hosted services play the role of a reverse proxy. A forward proxy lets administrators control services that users can connect to from the intranet. In this way, for example, sites known to be spreading malware can be blocked.

3.  **Perimeter network (DMZ)** – A perimeter network contains servers that communicate directly with the Internet, and that have limited access to internal assets such as databases. In a Microsoft Dynamics AX deployment, the services provided might include HTTP/HTTPS, Terminal Services, and public-facing Enterprise Portal services. External connections are filtered by a firewall and forwarded to one of the perimeter network servers rather than to an intranet computer. The perimeter server processes the packets delivered to it and communicates with back-end services, but there is no communication between the Internet and the back end. The internal firewall accepts packets only from designated hosts in the perimeter and passes them to the intranet only if they meet security rules.

4.  **Isolated sub-networks** – The principle of least privilege can be applied to the architecture of the organization’s local area network (LAN). You can segregate groups or duties by placing their computer resources on mutually non-routable subnets.

For detailed information about all of these considerations, see [Network Security](http://technet.microsoft.com/en-us/library/cc716269.aspx) on TechNet.

## Host-based defenses

  - **Local software firewall** – Client-side software firewalls can provide some of the same protection from network attacks as dedicated hardware firewalls. An example that comes with Microsoft Windows-based consumer computers is Windows Firewall, which uses application-based rules to block both incoming and outgoing communication that is unexpected or prohibited. Numerous third-party vendors also provide firewall software, much of it free, intended for use on consumer computers.

  - **Intrusion detection system (IDS) and file integrity monitoring (FIM)** – IDS and FIM software alert administrators to irregularities in network access and file integrity, respectively. A rule-based IDS can immediately give notice when a system comes under attack. A FIM package can spot changes to system or application files that might be a tip-off to the activities of an intruder.

  - **Antivirus software** – Up-to-date antivirus software should be installed on all organization computers, whether on-premises or off-premises.

  - **Logging** – Although intruders might erase signs of their presence in a computer’s logs, it is good policy to inspect the system logs periodically to ensure that no anomalies have been detected.

  - **Software updates** – Regular software updates, particularly security updates, should be applied as a part of domain policy.

  - **Full-disk encryption** – Where practical, full-disk encryption can prevent data from falling into the wrong hands if the physical security of a computer is compromised. This is especially useful for laptops and other client computers used off-premises.

## Physical security

Strong locks, reinforced doors, and other measures to prevent unauthorized physical access to computer hardware are fundamental security measures. Layers of physical security should include:

  - Restricted access to buildings where servers are housed, possibly enforced by security personal, logging of persons entering and leaving, video surveillance, smart cards, biometric authentication, motion sensors and alarms, and so on. The value of the assets being protected should guide decisions about the measures required.

  - Highly restricted access to rooms where servers are actually situated.

  - Video surveillance inside server rooms.

  - Locking enclosures on computer equipment to prevent theft or easy access to internal components.

  - Banning or disabling uncontrolled means of inserting or extracting data (optical drives, USB ports, and so on).

  - Use of BIOS passwords.

  - Secure, off-premises storage of computer event logs that can be compared with local logs to look for irregularities and discrepancies.

  - Case locks and biometric or smart-card logons for workstations.

  - Secure storage of portable devices.

## Application-based security

Microsoft Dynamics AX 2012 provides a role-based security framework to assign and restrict user permissions inside Microsoft Dynamics AX. For full documentation about the configuration and use of role-based security, see [Set up user security in Microsoft Dynamics AX](set-up-user-security-in-microsoft-dynamics-ax.md).

## Database security

For information about Microsoft Dynamics AX 2012 database security, see [Data security in Microsoft Dynamics AX](data-security-in-microsoft-dynamics-ax.md).

## Resources

## Microsoft security resources on TechNet

[Security Tech Center](http://technet.microsoft.com/en-us/security/)

[Microsoft Security Blog](http://blogs.technet.com/b/security/)

[Security Guidance](http://technet.microsoft.com/en-us/library/cc184906.aspx)

[Microsoft Security Bulletins](http://technet.microsoft.com/en-us/security/bulletin)

## Other security resources

[\[NIST\] Computer security Division / Computer Security Resource Center](http://csrc.nist.gov/)

[\[NSA\] Security Configuration Guides](http://www.nsa.gov/ia/mitigation_guidance/security_configuration_guides/index.shtml)

[\[NSA\] Defense in Depth: A practical strategy for achieving Information Assurance in today’s highly networked environment](http://www.nsa.gov/ia/_files/support/defenseindepth.pdf) (PDF)

[\[NSA\] The 60 Minute Network Security Guide (First Steps Towards a Secure Network Environment)](http://www.nsa.gov/ia/_files/support/i33-011r-2006.pdf) (PDF)

  


