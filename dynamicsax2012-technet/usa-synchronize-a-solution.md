---
title: (USA) Synchronize a solution
TOCTitle: (USA) Synchronize a solution
ms:assetid: b1189a3d-e0ff-4155-941b-2f1a57ad2046
ms:mtpsurl: https://technet.microsoft.com/library/Hh242714(v=AX.60)
ms:contentKeyID: 36058968
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: USA
---

# (USA) Synchronize a solution 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can synchronize information between a Sites Services for Microsoft Dynamics ERP solution web site and Microsoft Dynamics AX. For example, after you change the documents or records that the solution uses. Depending on how synchronization jobs are set up, you can wait for the next regular synchronization job to run, or you can synchronize manually. You can also change the synchronization schedule. Typically, IT staff sets up or changes the synchronization schedule. These tasks might require administrator privileges.


> [!IMPORTANT]
> <P>To allow Microsoft Dynamics AX and Sites Services to synchronize data, you must enable change tracking for your database. For more information, see <A href="https://msdn.microsoft.com/library/bb964713.aspx">Configuring and Managing Change Tracking</A>.</P>



## Synchronize a solution manually

1.  Click **Procurement and sourcing** \> **Setup** \> **Sites Services** \> **Available solutions**.

2.  In the list of solutions on the left, select a solution.

3.  Click **Synchronize**.

## Change the synchronization schedule

1.  Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

2.  On the **Overview** tab, select the synchronization job whose schedule you want to change.
    
    The Sites Services jobs are named "Synchronization job – \<name of the solution\>."

3.  Click **Recurrence**, and then change the settings that you want.

## See also

[(USA) Create a Sites Services solution](usa-create-a-sites-services-solution.md)

[(USA) Activate or deactivate a solution](usa-activate-or-deactivate-a-solution.md)

[(USA) Create and manage site pages](usa-create-and-manage-site-pages.md)

[(USA) Update a solution](usa-update-a-solution.md)

  


