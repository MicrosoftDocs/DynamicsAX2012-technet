---
title: (LVA) Create and print a sales credit note invoice with bank account details
TOCTitle: (LVA) Create and print a sales credit note invoice with bank account details
ms:assetid: 6b2ea58e-23e7-4903-8ec9-c384609fcedd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ721423(v=AX.60)
ms:contentKeyID: 49729987
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (LVA) Create and print a sales credit note invoice with bank account details [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Press CTRL+N to create a sales order.
    

    > [!NOTE]
    > <P>For more information, see "Create a sales order" and "Sales orders (form)" in the Application and Business Processes Help.</P>
    > <P>The tax registration number details for a customer should be defined in the <STRONG>Customers</STRONG> form (Click <STRONG>Accounts receivable</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Customers</STRONG> &gt; <STRONG>All customers</STRONG>.), on the <STRONG>General</STRONG> tab, under the <STRONG>Identification</STRONG> field group.</P>



3.  In the upper pane of the form, click the **Setup** tab.

4.  In the **Tax exempt number** field, select the tax exempt number of the company.

5.  Click the **Price/Discount** tab and, in the **Bank account** field, select the company bank account.

6.  In the **Bank code for additional currency** field, select the company bank account used for other currency.

7.  In the **Customer bank account** field, select the customer bank account.

8.  Click **Posting** \> **Invoice** to open the **Posting invoice** form.

9.  Click **OK** to post the sales order.

10. In the **Sales order** form, click **Functions** \> **Create credit note** to open the **Create credit note** form.

11. In the upper pane, select the **Mark** check box to select the invoice to be copied to the new order.

12. Click **OK** to create the sales credit note.
    

    > [!NOTE]
    > <P>For more information, see "Copy sales orders (form)" in the Application and Business Processes Help.</P>



13. In the **Sales order** form, click **Inquiries** \> **Invoice** \> **Preview/Print** to view and print the sales credit note invoice.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

