---
title: (BRA) Cancel a vendor fiscal document
TOCTitle: (BRA) Cancel a vendor fiscal document
ms:assetid: 440ddb6c-7a6b-43a4-bad0-eded6ef030b5
ms:mtpsurl: https://technet.microsoft.com/library/JJ710479(v=AX.60)
ms:contentKeyID: 49384370
author: Khairunj
ms.date: 05/09/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.PurchCopying
- Forms.PurchTable
- Brazil
- (BRA)
- fiscal document
- Cancel fiscal document
- vendor fiscal document
- BR-00044
audience: Application User
ms.search.region: Brazil
---

# (BRA) Cancel a vendor fiscal document 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can cancel incorrect vendor fiscal documents that are generated and issued by a legal entity for nontaxpayer vendors. When you cancel an incorrect vendor fiscal document, a negative purchase order is created. When you post a negative purchase order and run the fiscal book integration process, all of the tax, ledger, and financial transactions that are related to the purchase order are reversed in the fiscal books.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select a purchase order that has a purchase type of **Returned order** and an approval status of **Approved** or **Confirmed**.

3.  On the **Action Pane**, on the **Purchase** tab, click **Cancel fiscal document** to open the **Cancel fiscal document** form. For more information, see [(BRA) Cancel vendor fiscal document (form)](https://technet.microsoft.com/library/jj923387\(v=ax.60\)).

4.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Reason code** field, select the identification code of the reason to cancel the vendor fiscal document.

5.  In AX 2012 R3 and cumulative update 6 or later for AX 2012 R2: In the **Reason comment** field, enter or update the reason to cancel the vendor fiscal document.
    

    > [!NOTE]
    > <P>The reason for the cancellation must contain a minimum of 15 characters.</P>



6.  Select the vendor invoices that you want to cancel.

7.  Click **OK** to create negative purchase orders for the selected vendor invoices.

8.  On the **Action Pane**, click **Invoice** \> **Invoice**.

9.  In the **Vendor invoice** form, click **Post** \> **Post** to post the invoice.

## See also

[(BRA) Cancel a purchase complementary fiscal document](bra-cancel-a-purchase-complementary-fiscal-document.md)

[(BRA) Vendor invoice (modified form)](https://technet.microsoft.com/library/jj898464\(v=ax.60\))

[(BRA) Cancel a customer fiscal document](bra-cancel-a-customer-fiscal-document.md)

  


