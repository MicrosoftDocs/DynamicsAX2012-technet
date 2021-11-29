---
title: Create an estimate project
TOCTitle: Create an estimate project
ms:assetid: 97f9011a-0e30-4f74-a13e-a880dd2201e7
ms:mtpsurl: https://technet.microsoft.com/library/Aa498437(v=AX.60)
ms:contentKeyID: 36811420
author: Khairunj
ms.date: 08/29/2014
mtps_version: v=AX.60
f1_keywords:
- estimate project
- WIP structure
audience: Application User
ms.search.region: Global
---

# Create an estimate project 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An Estimate project is used as a container to group various control parameters that are used for the estimation process. These control parameters are used to track WIP and manage revenue recognition.

Use the **Estimate projects** form to identify which projects should be defined as Estimate projects.


> [!NOTE]
> <P>An Estimate project is always based on an existing project, but multiple projects can refer to a single Estimate project. Only Fixed-price and Investment projects can be attached to Estimate projects.</P>



1.  Depending on your version of the program, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R2 or AX 2012 R3: Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**. Open a Fixed-price or Investment project. In the **Project** form, on the **Revenue recognition** FastTab, right-click the **Estimate project ID** field, and then click **View details**.
    
      - Otherwise: Click **Project management and accounting** \> **Common** \> **Projects** \> **Estimate projects**.

2.  On the **Action Pane**, in the **New** group, click **Estimate project**.

3.  On the **General** FastTab, in the **Estimate project ID** field, select a project for which you want to calculate estimates.

4.  Optional: In the **Description** field, modify the description of the Estimate project.

5.  In the **Cost template** field, select a cost template for the Estimate project.

6.  In the **Period code** field, to specify how frequently estimates are calculated, select one of the period types that have been created for your organization.

7.  To attach additional projects to the Estimate project, on the **Projects** FastTab, select a project in the **Remaining projects** list, and then click **Add**.
    

    > [!NOTE]
    > <P>To detach a project from an Estimate project, select the project in the <STRONG>Selected projects</STRONG> list, and then click <STRONG>Remove</STRONG>.</P>



## See also

[Estimate (form)](https://technet.microsoft.com/library/aa590971\(v=ax.60\))

[Estimate projects (form)](https://technet.microsoft.com/library/aa599196\(v=ax.60\))

[Create estimate (class form)](https://technet.microsoft.com/library/aa553468\(v=ax.60\))

[About maintaining estimates](about-maintaining-estimates.md)

[Attach a project to an estimate](attach-a-project-to-an-estimate.md)

  


