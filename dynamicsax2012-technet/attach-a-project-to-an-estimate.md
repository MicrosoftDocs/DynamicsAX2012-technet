---
title: Attach a project to an estimate
TOCTitle: Attach a project to an estimate
ms:assetid: c837b747-71fb-4447-aaa3-558c6b4d6cf5
ms:mtpsurl: https://technet.microsoft.com/library/Aa550866(v=AX.60)
ms:contentKeyID: 36059317
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project
- estimate
- estimate project ID
audience: Application User
ms.search.region: Global
---

# Attach a project to an estimate 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An Estimate project is used as a container to group together various control parameters that are used for the estimation process. By attaching a project to an Estimate project, you can track the project’s WIP and manage revenue recognition.

## Attach a project to an estimate (method one)


> [!NOTE]
> <P>This procedure does not apply if Microsoft Dynamics AX 2012 R2 is installed.</P>



1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Estimate projects**.

2.  Select the Estimate project to attach a project to.

3.  On the **Action Pane**, on the **Estimate project** tab, in the **Maintain** group, click **Edit**.

4.  In the **Estimate projects** form, on the **Projects** FastTab, select the project to attach to the Estimate project, and then click the left arrow (**\<**).


> [!NOTE]
> <P>Only projects that belong to the same project group as the Estimate project can be attached to the Estimate project.</P>



## Attach a project to an estimate (method two)


> [!NOTE]
> <P>This procedure applies to all versions of Microsoft Dynamics AX 2012.</P>



1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Select the Fixed-price or Investment project to attach to an Estimate project.

3.  On the **Action Pane**, on the **Project** tab, in the **Maintain** group, click **Edit**.

4.  Depending on your version of the program, do one of the following:
    
      - In Microsoft Dynamics AX 2012 R2: In the **Projects** form, on the **Revenue recognition** FastTab, in the **Estimate project ID** field, select the Estimate project that you want the project attached to.
    
      - Otherwise: In the **Projects** form, on the **Setup** FastTab, in the **Estimate project ID** field, select the Estimate project that you want the project to be attached to.


> [!NOTE]
> <P>Only Estimate projects that belong to the same project group as the Fixed-price or Investment project are available for selection.</P>



## See also

[Create an estimate project](create-an-estimate-project.md)

[Change the Estimate project that a project is attached to](change-the-estimate-project-that-a-project-is-attached-to.md)

[Estimate projects (form)](https://technet.microsoft.com/library/aa599196\(v=ax.60\))

[Projects (form)](https://technet.microsoft.com/library/aa585245\(v=ax.60\))

  


