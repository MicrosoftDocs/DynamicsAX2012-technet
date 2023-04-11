---
title: (BRA) Create and post a free text invoice that has charges for a fixed asset line
TOCTitle: (BRA) Create and post a free text invoice that has charges for a fixed asset line
ms:assetid: 6c0c4dde-193a-4672-b88c-955912b813a2
ms:mtpsurl: https://technet.microsoft.com/library/JJ710532(v=AX.60)
ms:contentKeyID: 49384423
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- miscellaneous charges
- free text invoice
- fixed asset
- (BRA)
- Create free text invoice
- post free text invoice
- BR - 00016
audience: Application User
ms.search.region: Brazil
---

# (BRA) Create and post a free text invoice that has charges for a fixed asset line 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can create and post a free text invoice with charges for a fixed asset invoice line. Charges include amounts such as invoice fees, freight, and insurance.

You must set up charges before you can create and post a free text invoice with charges. For more information, see [Create charges codes](create-charges-codes.md) and [Define auto charges](define-auto-charges.md).

## Create a free text invoice that has charges for a fixed asset line

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  On the **Action Pane**, on the **Invoice** tab, click **Free text invoice** to create a free text invoice. For more information, see [(BRA) Create and post a free text invoice](bra-create-and-post-a-free-text-invoice.md).

3.  In the **Free text invoice** form, on the **Action Pane**, on the **Invoice** tab, click **Line view**.

4.  In the **Invoice lines** area, select a free text invoice line, and then click the **Line details** FastTab.

5.  Click the **General** tab, and then in the **Fixed asset number** field, select the ID number of the fixed asset for which the free text invoice line is created.

6.  In the **Invoice lines** area, click **Charges** to open the **Charges transactions** form.

7.  In the **Charges code** field, select the code of the charge that is applied to the selected free text invoice line.

8.  In the **Category** field, select one of the following options to indicate the method that is used to calculate the charge:
    
      - **Fixed** – The charge is entered as a fixed amount on the line. These charges can be used in the order header and on order lines.
    
      - **Pcs.** – The charge is based on the unit. These charges can be used only on order lines.
    
      - **Percent** – The charge is entered as a percentage on the line. These charges can be used in the order header and on order lines.
    
      - **Intercompany percent** – The charge is entered as a percentage on the line for intercompany orders. These charges can be used only on order lines.

9.  In the **Charges value** field, enter the value attached to the category of the charge.

10. In the **Description** field, update the description of the charges code.

11. In the **Sales tax group** and **Item sales tax group** fields, select the sales tax group and the item sales tax group.

## Post a free text invoice that has changes for a fixed asset line

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select the free text invoice for a fixed asset to post.

3.  On the **Action Pane**, on the **Invoice** tab, click **Post** to open the **Post free text invoice** form.

4.  Click the **Bill of lading** tab, and then in the **Volume type** and **Volume quantity** fields, enter the volume type and volume quantity that are used in an invoice posting.
    

    > [!NOTE]
    > <P>The <STRONG>Bill of lading</STRONG> tab is available only if the <STRONG>Service invoice</STRONG> check box is not selected on the <STRONG>Fiscal information invoice line</STRONG> tab on the <STRONG>Line details</STRONG> FastTab in the <STRONG>Free text invoice</STRONG> form.</P>



5.  Click **OK** to post the free text invoice.

## See also

[Free text invoice (form)](https://technet.microsoft.com/library/aa556897\(v=ax.60\))

[Charges transactions (form)](https://technet.microsoft.com/library/aa633876\(v=ax.60\))

  


