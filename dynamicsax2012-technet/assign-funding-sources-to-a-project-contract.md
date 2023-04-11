---
title: Assign funding sources to a project contract
TOCTitle: Assign funding sources to a project contract
ms:assetid: 568fecf3-c135-4ba5-a11e-c94130af6c1f
ms:mtpsurl: https://technet.microsoft.com/library/Hh208967(v=AX.60)
ms:contentKeyID: 36057324
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- advanced funding
- funding source
- project contract
- funding type
audience: Application User
ms.search.region: Global
---

# Assign funding sources to a project contract 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **Project contracts**.

2.  Create or open a project contract, and then select the **Funding sources** FastTab.

3.  Click **Add**.

4.  In the **Funding type** column, select whether this funding source is a customer, an internal operational organization, a grant, or an on-hold account.
    

    > [!NOTE]
    > <P>On-hold funding is a funding source into which you can record transactions until additional funding can be obtained or until you decide to bear the costs internally.</P>



5.  In the **Customer** column, select the entity that you want to use as a funding source for the project contract.

6.  In the **Funding source ID** column, enter the name that you want to use to identify this funding source. The name can be the same as a customer identification number or name, or any other name that you want.
    

    > [!NOTE]
    > <P>The content of this field is displayed on transactions and in reports to identify the funding source.</P>



7.  To change the default address and language that were specified when you made a selection in the **Customer** field, change the selections in the **Invoice address** and **Language** fields.

8.  To change the financial dimensions or payment options for a funding source, select the funding source in the grid and then click **Details**.

9.  Repeat steps 3 through 8 for each funding source that you want to apply to the project contract.

After you designate a customer, grant, or internal organization as a funding source, it can be included in the funding rules and funding limits that you create in the **Funding limits** and **Funding rules** FastTabs.

## See also

[About project contract funding](about-project-contract-funding.md)

[Project contracts (form)](https://technet.microsoft.com/library/aa586038\(v=ax.60\))

[Funding source details (form)](https://technet.microsoft.com/library/hh209607\(v=ax.60\))

[Create a project contract](create-a-project-contract.md)

  


