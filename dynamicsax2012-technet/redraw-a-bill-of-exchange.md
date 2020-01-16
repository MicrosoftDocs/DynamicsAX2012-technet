---
title: Redraw a bill of exchange
TOCTitle: Redraw a bill of exchange
ms:assetid: 0c93b46e-b565-4c62-a10f-24bd5d713c54
ms:mtpsurl: https://technet.microsoft.com/library/Aa569757(v=AX.60)
ms:contentKeyID: 36966695
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Redraw a bill of exchange 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When a protested bill of exchange has been resolved, you can use a redraw bill of exchange journal to settle the protested bill of exchange. A new transaction is created that has a **Redrawn** status for the protested bill of exchange.


> [!NOTE]
> <P>To complete the bill of exchange cycle, you must remit and settle the redrawn bill of exchange. For more information, see <A href="remit-a-bill-of-exchange.md">Remit a bill of exchange</A> and <A href="settle-a-bill-of-exchange.md">Settle a bill of exchange</A>.</P>



1.  Click **Accounts receivable** \> **Journals** \> **Bill of exchange** \> **Redraw bill of exchange journal**.

2.  Create a journal, and then click **Lines**.

3.  Select the customer account for the invoice that corresponds to the bill of exchange that is being redrawn.

4.  Click **Functions** \> **Settlement** to open the **Settle open transactions** form.

5.  On the **Overview** tab, select the **Mark** check box for an open, protested transaction.

6.  Close the form.

7.  In the **Journal voucher** form, click the **Bill of exchange** tab. Verify that the information is correct.

8.  Click **Post** \> **Post**.
    
    The **Bill of exchange journal** inquiry form shows the redrawn bill of exchange. The form also shows a related line that has a **Redrawn** status and a sequence number of 2 or more. In the **Bills of exchange statistics** inquiry form, the number in the **Redrawn bills** row is increased, and the number in the **Protested bills** row is decreased.

When the journal is posted, the bill of exchange summary account is debited and the protested bill of exchange summary account is credited.


> [!NOTE]
> <P>If you receive a message that mentions posting restrictions, you might be set up to post only journals that you created. For more information, see <A href="https://technet.microsoft.com/library/hh227598(v=ax.60)">Posting restrictions (form)</A>.</P>



## See also

[Remit a bill of exchange](remit-a-bill-of-exchange.md)

[Protest a bill of exchange](protest-a-bill-of-exchange.md)

[Settle a bill of exchange](settle-a-bill-of-exchange.md)

[Journal header (form)](https://technet.microsoft.com/library/aa557917\(v=ax.60\))

[Bills of exchange statistics (form)](https://technet.microsoft.com/library/aa572115\(v=ax.60\))

  


