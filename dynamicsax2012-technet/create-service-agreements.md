---
title: Create service agreements
TOCTitle: Create service agreements
ms:assetid: a834770c-18d3-4f24-a012-2c0589fb1243
ms:mtpsurl: https://technet.microsoft.com/library/Aa550309(v=AX.60)
ms:contentKeyID: 36058885
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- service
- agreement
- contract
audience: Application User
ms.search.region: Global
---

# Create service agreements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to use features in the **Service management** and the **Project management and accounting** modules to create service agreements.

## Create a service agreement from Service management

1.  Click **Service management** \> **Common** \> **Service agreements** \> **Service agreements**.

2.  Click the **Service agreement** button to create a new service-agreement line in the form header. Enter a description, select a reference to a project in the **Project ID** field, and fill in the rest of the fields and lines for the service agreement. For more information about completing the form, see [Service agreements (form)](https://technet.microsoft.com/library/aa617823\(v=ax.60\)).

3.  Click the **Setup** tab and select **Service objects** or **Service tasks** to create service object relations or service task relations for the service agreement. The service objects and tasks that you have created relations for can be attached on the lines of the service agreement.

4.  In the lower half of the **Service agreements** form, create service-agreement lines by copying lines from a service template, another service agreement, or manually creating the service-agreement lines.


> [!NOTE]
> <P>If you copy lines into the service agreement from another service agreement, you can indicate whether you also want to copy service-object and service-task relations. If you copy these relations, they are added to any existing relations on the service agreement. If you copy service-agreement lines from a service template, the service-object and service-task relations are automatically copied as service-object relations and service-task relations on the new service-agreement lines.</P>



## Create a service agreement from Project

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Select the project from the list and click the **Maintain** tab. On the Action Pane, click **Service** and select **Service agreement**.

2.  Follow the steps in the section titled Create a service agreement from Service management procedure, as described earlier in this topic, starting with step 2. The project reference will be entered automatically.

## See also

[Create service task relations](create-service-task-relations.md)

[Copy service templates lines](copy-service-templates-lines.md)

[Create service-agreement lines manually](create-service-agreement-lines-manually.md)

  


