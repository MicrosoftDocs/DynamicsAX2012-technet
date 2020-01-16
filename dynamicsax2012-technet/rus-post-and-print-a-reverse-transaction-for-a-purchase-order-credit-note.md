---
title: (RUS) Post and print a reverse transaction for a purchase order credit note
TOCTitle: (RUS) Post and print a reverse transaction for a purchase order credit note
ms:assetid: f07df8df-ebc3-46e9-82da-725dad573364
ms:mtpsurl: https://technet.microsoft.com/library/JJ678592(v=AX.60)
ms:contentKeyID: 49388074
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Post and print a reverse transaction for a purchase order credit note 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can post a purchase order credit note transaction as a reverse transaction by selecting the **Credit correction** check box in the **Posting invoice** and **Posting packing slip** forms. As a result, the warehouse operation is marked as **Storno** in the **Transactions** form, and a credit transaction is created for the vendor transaction. The reversed vendor transaction can be posted as a correction transaction in the General ledger.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Setup** \> **Accounts payable parameters**.

2.  On the **Updates** area, select the **Credit note as correction** check box to post the vendor credit note transaction as a reverse transaction.
    

    > [!NOTE]
    > <P>When you select this check box, the <STRONG>Credit correction</STRONG> check box is selected by default in the <STRONG>Posting packing slip</STRONG> and <STRONG>Posting invoice</STRONG> forms.</P>



3.  Press CTRL+S or close the form.

4.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

5.  Press CTRL+N to create a purchase order, and enter the required information.
    

    > [!NOTE]
    > <P>For more information, see "Create a purchase order" in the Applications and Business Processes Help.</P>



6.  Click **Posting** \> **Invoice** to open the **Posting invoice** form.

7.  In the **Invoice** field, enter the invoice number.

8.  Click **OK** to post the invoice.
    

    > [!NOTE]
    > <P>For more information, see "Purchase posting (form)" in the Applications and Business Processes Help.</P>



9.  In the **Purchase order** form, click **Purchase order line** \> **Credit note** to open the **Create credit note** form.

10. On the **Invoice** tab, select the **Select All** check box to select the transactions for the credit note.

11. Click **OK** to return to the **Purchase order** form.

12. Click **Posting** \> **Invoice**.
    

    > [!NOTE]
    > <P>The <STRONG>Credit correction</STRONG> check box is selected by default in the <STRONG>Posting invoice</STRONG> form, on the <STRONG>Other</STRONG> tab.</P>



13. In the **Invoice** field, enter the invoice number.

14. Click **OK** to post the invoice. You can view the purchase order transaction in the **Transactions** form. The **Storno** check box will be selected on the **Overview** tab.
    

    > [!NOTE]
    > <P>For more information, see "Inventory voucher transactions (form)" in the Applications and Business Processes Help.</P>



15. In the **Purchase order** form, click **Inquiries** \> **Invoice** to open the **Invoice journal** form for the selected purchase order.

16. Select the journal line to print.

17. Click **Preview/Print** to print the report.
    

    > [!NOTE]
    > <P>For more information, see "Invoice journal (form)" in the Applications and Business Processes Help.</P>


  


