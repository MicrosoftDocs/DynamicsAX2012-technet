---
title: (BRA) Cancel a customer fiscal document
TOCTitle: (BRA) Cancel a customer fiscal document
ms:assetid: 7f583608-bba6-4a05-ad02-77acd8dfb491
ms:mtpsurl: https://technet.microsoft.com/library/JJ710546(v=AX.60)
ms:contentKeyID: 49384437
author: tonyafehr
ms.date: 05/06/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SalesTable
- Forms.SalesCopying
- BRA
- Brazil
- fiscal document
- cancel a customer fiscal document
- customer fiscal document
- BR-00044
audience: Application User
ms.search.region: Brazil
---

# (BRA) Cancel a customer fiscal document 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can cancel an incorrect customer fiscal document by using the **Cancel fiscal document** form. When you cancel a fiscal document, the fiscal document is marked as canceled, and all of the ledger transactions and financial transactions are reversed.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.
    
    –or–
    
    Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select a sales order to cancel.

3.  On the **Action Pane**, click the **Sell** tab, and then click **Cancel fiscal document** to open the **Cancel fiscal document** form. For more information, see [(BRA) Cancel customer fiscal document (form)](https://technet.microsoft.com/library/jj933503\(v=ax.60\)).

4.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Reason code** field, select the identification code of the reason that is used to cancel the customer fiscal document.

5.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Reason comment** field, enter or update the reason to cancel the fiscal document.
    

    > [!NOTE]
    > <P>The reason for the cancellation must contain a minimum of 15 characters.</P>



6.  On the **Invoice** tab, select the **Mark** check boxes to select individual sales order lines. Alternatively, you can select the **Select all** check box to select all of the sales order lines.

7.  Click **OK** to create transactions that have negative quantities.

8.  On the **All sales orders** list page, select the transactions that have negative quantities.

9.  On the **Action Pane**, click the **Invoice** tab, and then click **Invoice** to open the **Posting invoice** form.

10. Select the **Posting** and **Print invoice** check boxes to post and print the invoice.

11. Click **OK** to cancel the sales order, and to reverse all of the ledger and financial transactions.

## See also

[(BRA) Sales posting (modified form)](https://technet.microsoft.com/library/jj853383\(v=ax.60\))

[(BRA) Cancel a vendor fiscal document](bra-cancel-a-vendor-fiscal-document.md)

  


