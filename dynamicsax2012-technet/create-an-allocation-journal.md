---
title: Create an allocation journal
TOCTitle: Create an allocation journal
ms:assetid: db977a53-bc71-49ba-8c01-e513373dd814
ms:mtpsurl: https://technet.microsoft.com/library/Ff395363(v=AX.60)
ms:contentKeyID: 36059668
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- allocations
- allocations journal
audience: Application User
ms.search.region: Global
---

# Create an allocation journal 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Process allocation request** form to create an allocation journal. You can create an unlimited number of allocation journals by using this form. Before you can create an allocations journal, you must create an allocation rule by using the **Ledger allocation rule** form. For more information, see [Create an allocation rule](create-an-allocation-rule.md).


> [!NOTE]
> <P>If you create an allocation rule that has an allocation method of <STRONG>Basis</STRONG>, you must also create a ledger allocation basis rule.</P>



1.  Click **General ledger** \> **Periodic** \> **Process allocation request**.

2.  Select an allocation rule.

3.  In the **As of date** field, select the date by which to include ledger amounts for allocation.

4.  In the **GL posting date** field, select the date when the allocation journal will be posted to the general ledger.

5.  In the **Zero source** field, select the action to be taken if a zero-source amount is generated during the allocation process.
    
      - **Process** – Create destination distributions, where applicable.
    
      - **Stop** – Display an error message to indicate that a zero-source amount is selected, and stop the allocation process.

6.  In the **Proposal options** field, select to view the journal details or post the allocation results to the general ledger.

7.  In the **Reason code** field, you can select a code to indicate the reason for the allocation.

8.  Click **OK** to create the allocation journal.

## See also

[Ledger allocation rule (form)](https://technet.microsoft.com/library/ff395357\(v=ax.60\))

[Ledger allocation rule source (form)](https://technet.microsoft.com/library/ff395365\(v=ax.60\))

[Ledger allocation rule destination (form)](https://technet.microsoft.com/library/ff395369\(v=ax.60\))

[Process allocation request (form)](https://technet.microsoft.com/library/ff395361\(v=ax.60\))

  


