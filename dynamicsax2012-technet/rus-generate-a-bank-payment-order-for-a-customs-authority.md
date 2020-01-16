---
title: (RUS) Generate a bank payment order for a customs authority
TOCTitle: (RUS) Generate a bank payment order for a customs authority
ms:assetid: 88ad391d-d0fd-469c-ab11-0598d4550f2a
ms:mtpsurl: https://technet.microsoft.com/library/JJ678448(v=AX.60)
ms:contentKeyID: 49387677
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate a bank payment order for a customs authority 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Journal voucher** form to generate a bank payment order that includes the customs authority code or customs office code. You must create a customer counteragent before you can generate a bank payment order. For more information, see [(RUS) Set up a customs counteragent](rus-set-up-a-customs-counteragent.md).

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a new journal, and then click **Lines**.

3.  Click the **General** tab, and then in the **Offset account type** field, select **Customer**.

4.  In the **Offset account** field, select the customer account that is associated with the customs authority.

5.  In the **Offset-transaction text** field, select a description for the current journal.

6.  Click **Functions** \> **Generate payments** to open the **Generate payments** form to generate a payment order for the current journal. This bank payment order includes the customs office code. For more information, see [(RUS) Generate a payment order in rubles](rus-generate-a-payment-order-in-rubles.md)

7.  Click **Validate** to validate the journal.

8.  Click **Post** \> **Post** to post the journal.

## See also

[Create journal descriptions](create-journal-descriptions.md)

[Journal descriptions (form)](https://technet.microsoft.com/library/aa587702\(v=ax.60\))

  


