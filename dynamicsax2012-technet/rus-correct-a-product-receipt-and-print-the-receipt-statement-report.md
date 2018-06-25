---
title: (RUS) Correct a product receipt and print the receipt statement report
TOCTitle: (RUS) Correct a product receipt and print the receipt statement report
ms:assetid: 7095a360-4178-41f1-8cae-70723a9fdbf2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733238(v=AX.60)
ms:contentKeyID: 49685205
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- product receipt
- (RUS)
- Correct a product receipt
- print receipt statement
- receipt statement
---

# (RUS) Correct a product receipt and print the receipt statement report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Product receipt correction** form to correct and post a product receipt that is already posted. When you post a corrected product receipt, the original product receipt is canceled, and a new version of an M-4, M-7, TORG-1, TORG-2, or TORG-3 receipt statement report is created. The new version of the receipt statement report is created only if the corrected receipt contains a minimum of one line with a non-zero received quantity. You can also print the new version of the receipt statement report.

## Correct a product receipt

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**. Select a purchase order that a product receipt is posted for, and then on the **Receive** tab, in the **Journals** group, click **Product receipt**. Select a product receipt, and then click **Correct**.
    
    –or–
    
    Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Product receipt**. Select a product receipt line, and then click **Correct**.

2.  Select the **Preserve receipt statement** check box to use the receipt statement document type and the number of the original product receipt for the corrected product receipt.
    

    > [!NOTE]
    > <P>The <STRONG>Receipt statement form type</STRONG> and <STRONG>Document about deviation</STRONG> fields are not available when the <STRONG>Preserve receipt statement</STRONG> check box is selected.</P>



3.  If you did not select the **Preserve receipt statement** check box, in the **Receipt statement form type** field, select one of the following options to indicate whether the receipt statement is related to items or materials:
    
      - **Receipt statement for materials** – The receipt statement is related to materials.
    
      - **Receipt statement for items** – The receipt statement is related to items.

4.  In the **Document about deviation** field, select one of the following options to indicate whether an M-7, TORG-1, TORG-2, or TORG-3 report is generated:
    
      - **Receipt statement for materials M-7** – The M-7 receipt statement for materials report is generated.
        

        > [!NOTE]
        > <P>This option is available only when you select <STRONG>Receipt statement for materials</STRONG> in the <STRONG>Receipt statement form type</STRONG> field.</P>

    
      - **Receipt statement for items TORG-1** – The TORG-1 receipt statement for items report is generated.
    
      - **Receipt list for items TORG-2** – The TORG-2 receipt list for items report is generated.
    
      - **Receipt list for items TORG-3** – The TORG-3 receipt list for items report is generated.

5.  In the lower pane, on the **Lines** tab, in the **Deviation** field, enter or modify the deviation in the quantity of the inventory items. By default, this field is updated with the deviation in the quantity of the inventory items that is specified in the **Deviation** field on the purchase order lines.

6.  Click **OK** to post the product receipt.

## Print receipt statement reports

1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Product receipt**. Select a product receipt line, and then click **Preview/Print** \> **Printable documents**.
    
    –or–
    
    Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Product receipt**. Select a product receipt line, and then click **History**. Click **Preview/Print** \> **Printable documents**.
    
    –or–
    
    Click **Inventory management** \> **Periodic** \> **Transfer orders**. Click **Inquiries** \> **Transfer order history**. Click **Print** \> **Printable documents**.

2.  Select a product receipt line, and then click **Print** to print the receipt statement report that corresponds with the selected product receipt.

## See also

[(RUS) About product receipt corrections](rus-about-product-receipt-corrections.md)

[(RUS) Product receipt correction (modified form)](https://technet.microsoft.com/en-us/library/jj733510\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

