---
title: (RUS) Update factures and post invoices for sales orders
TOCTitle: (RUS) Update factures and post invoices for sales orders
ms:assetid: b9edf944-bc8f-4df6-a84f-eceb9ae4759a
ms:mtpsurl: https://technet.microsoft.com/library/JJ733273(v=AX.60)
ms:contentKeyID: 49685241
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- invoice
- packing slip
- facture
audience: Application User
ms.search.region: Russia
---

# (RUS) Update factures and post invoices for sales orders 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can post sales order invoices that are based on packing slips that include different types of order lines. If an invoice has not already been created for an open sales order, you can process the facture update and the invoice at the same time.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a sales order, or select an existing sales order.

3.  In the **Sales order** form, click the **Sell** tab, and then click **Sales order confirmation** to confirm the sales order.

4.  In the **Confirm sales order** form, verify the details of the sales order, and then click **OK**.

5.  In the **Sales order** form, click the **Pick and pack** tab, and then click **Packing slip** to open the **Packing slip posting** form.

6.  Make sure that the **Posting** check box is selected.

7.  Click **OK** to post the packing slip.

8.  In the **Sales order** form, click **Invoice** \> **Facture** to open the **Update facture** form.
    

    > [!NOTE]
    > <P>Sales order lines that are based on categories contain the customs cargo declaration (GTD) number and the country of origin. These details are transferred to the facture journal when you update a facture for a sales order.</P>



9.  Select the posting settings, and then click **OK** to post the facture. Both the invoice and the facture are processed.

## See also

[Sales orders (form)](https://technet.microsoft.com/library/aa585863\(v=ax.60\))

[(RUS) Facture journal (form)](https://technet.microsoft.com/library/jj923567\(v=ax.60\))

  


