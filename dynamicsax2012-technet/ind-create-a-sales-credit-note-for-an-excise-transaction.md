---
title: (IND) Create a sales credit note for an excise transaction
TOCTitle: (IND) Create a sales credit note for an excise transaction
ms:assetid: e1c31c80-c4af-4dc1-862e-578ab462e7d8
ms:mtpsurl: https://technet.microsoft.com/library/JJ710898(v=AX.60)
ms:contentKeyID: 49386313
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Create a sales credit note for an excise transaction 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



When a customer returns goods and you create a credit note for the order, the calculated excise amount is reversed.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select a sales order and then on the **Action Pane**, on the **Sell** tab, in the **Create** group, click **Credit note** to create a credit note in the **Create credit note** form.

3.  Select the **Tax as per original invoice** check box to apply the tax rate for excise as it was on the date the original order was invoiced.

4.  Select the transactions to include on the credit note.

5.  Click **OK** to post the credit note.
    
    You cannot modify the value in the **Direct settlement** field on the **Tax information** tab. When you post the sales credit note, the excise amounts are debited to the excise payable accounts regardless of whether you close the excise settlement period or not. The procedure for invoicing the credit note is the same as for invoicing an excisable returned item.

## See also

[(IND) Sales orders (modified form)](https://technet.microsoft.com/library/jj677998\(v=ax.60\))

[(IND) Copy sales orders (modified form)](https://technet.microsoft.com/library/jj664849\(v=ax.60\))

[(IND) Copy purchase orders (modified form)](https://technet.microsoft.com/library/jj664580\(v=ax.60\))

  


