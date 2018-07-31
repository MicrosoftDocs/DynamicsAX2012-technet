---
title: (RUS) Allocate miscellaneous charges to redraw debt to third parties
TOCTitle: (RUS) Allocate miscellaneous charges to redraw debt to third parties
ms:assetid: e336bb2f-2bb0-4329-be73-bf94ad0f01dd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853240(v=AX.60)
ms:contentKeyID: 50396520
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Allocate miscellaneous charges to redraw debt to third parties 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to allocate miscellaneous charges to redraw debt to third parties by using the **Invoice journal** form.

1.  Click **Accounts payable** \> **Journals** \> **Invoices** \> **Invoice journal**.

2.  Select an invoice line that has been posted, and then click **Charges** \> **Allocation** to open the **Charges allocation** form.

3.  In the **Allocation mode** field, select **Redraw debt**.

4.  Click **Choose**, and then specify the selection criteria that are used to allocate the expenses for customers or vendors to the **Allocation base** field group. Click **OK** to create the lines.
    

    > [!NOTE]
    > <P>You can also create the lines manually in the <STRONG>Allocation base</STRONG> field group.</P>



5.  In the upper pane, on the **Overview** tab, select the **Select** check box to select a purchase invoice that has been posted.

6.  In the lower pane, on the **Overview** tab, select the **Select** check box to select the lines that the miscellaneous charges are allocated to.

7.  Click **Allocation** to allocate the miscellaneous charges.
    

    > [!NOTE]
    > <P>The allocation amount and the code for the miscellaneous charge are displayed in the right pane.</P>



8.  In the right pane, in the **Amount** field, modify the amount that is allocated to the selected lines.

9.  Click **Post**.

10. Select the **Credit correction** check box to post the allocation as a storno transaction. If you clear this check box, the allocation is created as a reverse transaction.

11. Select the **Create invoice for payment** check box to create an invoice for payment when you post the allocation.

12. Click **OK** to post the allocation.

## See also

[(RUS) Allocate miscellaneous charges to write off costs](rus-allocate-miscellaneous-charges-to-write-off-costs.md)

  


