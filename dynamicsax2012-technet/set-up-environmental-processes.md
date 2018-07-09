---
title: Set up environmental processes
TOCTitle: Set up environmental processes
ms:assetid: 575db9a4-04b4-4416-a6ab-b29d105d1688
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208969(v=AX.60)
ms:contentKeyID: 36057330
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up environmental processes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Environmental processes** form to define or modify a business process that affects the environment. A process can represent a vendor that sells you natural gas, the purchase of raw materials, the manufacturing process, the use of natural resources, the flows related to waste or decomposition, or the environment itself. A process is categorized according to the sphere that it belongs to:

  - **Technosphere** – Materials that come from the technosphere are bought or sold, rather than acquired from the environment.

  - **Ecosphere** –The general environment, which is usually specified as being the air, water, or ground.

Spheres provide context for where a process stands in your organization’s ecosystem.

1.  Click **Compliance and internal controls** \> **Common** \> **Environmental sustainability** \> **Environmental processes** \> **Environmental processes**. Click **New**.

2.  Enter a process ID, if necessary.
    

    > [!NOTE]
    > <P>If you set parameters to create process ID numbers automatically, the field is filled in automatically and in some cases is read–only.</P>



3.  Enter a brief description of the process, and then select whether the process belongs to the technosphere or the ecosphere.

4.  In the **Scope** field, select the degree of influence that your organization has over the process:
    
      - **None** – A process that your organization has no control over and does not provide any supplies for.
    
      - **Primary** – A process that your organization has direct control over. For example, manufacturing that is performed by your organization.
    
      - **Secondary** – A process that supplies materials or substances directly to your organization. For example, a utility that supplies gas or electricity.
    
      - **Tertiary** – A process that your organization has no direct control over, but that supplies your organization with some substances. For example, a manufacturer or trading company.

5.  For processes that relate to a primary process, enter the primary process in the **Parent process ID** field. When reports are created, all subprocesses are rolled up into the parent process.

6.  On the **Image** tab, click **Add image** to add an image that represents the process in a visual display.

7.  On the **Relations** tab, click **Add** and select a relation type and relation ID for the process. Creating a relationship to other entities in Microsoft Dynamics AX provides additional information about where a substance flow originates. For example, you can link a process to customers or vendors.
    

    > [!NOTE]
    > <P>If you relate a process to only one vendor and create a purchase order or invoice for that vendor, the process is automatically entered as the source process on the <STRONG>Environment</STRONG> tab on the <STRONG>Purchase order</STRONG> form.</P>



## See also

[Process details (form)](https://technet.microsoft.com/en-us/library/hh227653\(v=ax.60\))

[Set up environmental parameters](set-up-environmental-parameters.md)

[Set up substances for environmental tracking](set-up-substances-for-environmental-tracking.md)

[Set up substance categories](set-up-substance-categories.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

