---
title: Create a letter of guarantee request for a sales quotation
TOCTitle: Create a letter of guarantee request for a sales quotation
ms:assetid: 218e1615-c3c7-4b7d-bd55-8547868c1221
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208472(v=AX.60)
ms:contentKeyID: 36056166
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Create the letter of guarantee request for a sales quotation
- Letter of guarantee request for a sales quotation
audience: Application User
ms.search.region: Global
---

# Create a letter of guarantee request for a sales quotation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A letter of guarantee can be issued for a sales quotation transaction between a principal and a beneficiary. After the sales quotation is created, the principal can create a letter of guarantee request for the beneficiary and submit it to the bank. When the bank approves the request, the letter of guarantee is issued to the beneficiary. For more information, see [About letter of guarantee](about-letter-of-guarantee.md) and [Activate the letter of guarantee](activate-the-letter-of-guarantee.md).

## Create a sales quotation

Use the **Create quotation** form to create a sales quotation with the **Bank document type** as **Letter of guarantee**.

1.  Click **Sales and marketing** \> **Common** \> **Sales quotations** \> **All quotations**.

2.  Click **Sales quotation** to create a new sales quotation.

3.  In the **Account** field, select the customer that has requested the letter of guarantee.

4.  Click the **General** FastTab and in the **Bank document type** field, select **Letter of guarantee**. Enter any other required details.

5.  Click **OK** to close the **Create quotation** form and return to the **Sales quotation** form.

## Create a letter of guarantee request for a sales quotation

You can request a letter of guarantee for a customer using the **Sales quotation** form. After you make a request, you must submit the request to the bank for approval.

1.  In the **Sales quotation** form, click the **Lines** FastTab.

2.  Click **Add line** to create a sales quotation line for an item, and then specify the following: **Item number**, **Quantity**, **Site**, **Unit**, and **Unit price**.

3.  On the Action Pane, click the **Quotation** tab.

4.  In the **Bank document** group, click **Letter of guarantee** to open the **Letter of guarantee** form. For information about how to create the request, submit it to the bank, and issue the letter of guarantee to the beneficiary, see [Request and issue the letter of guarantee](request-and-issue-the-letter-of-guarantee.md).

5.  Close the forms to save your changes.

## See also

[Liquidate, extend, or cancel a letter of guarantee](liquidate-extend-or-cancel-a-letter-of-guarantee.md)

[Increase or decrease the letter of guarantee value](increase-or-decrease-the-letter-of-guarantee-value.md)

[Letter of guarantee (form)](https://technet.microsoft.com/en-us/library/hh227662\(v=ax.60\))

  


