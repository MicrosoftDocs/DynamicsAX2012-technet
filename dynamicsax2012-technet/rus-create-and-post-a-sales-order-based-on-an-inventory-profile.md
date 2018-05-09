---
title: (RUS) Create and post a sales order based on an inventory profile
TOCTitle: (RUS) Create and post a sales order based on an inventory profile
ms:assetid: 41a81e96-8532-40b0-b6e8-f5b1fac40826
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ733207(v=AX.60)
ms:contentKeyID: 49685175
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create and post a sales order based on an inventory profile 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Sales order** form to post a packing slip, invoice, and facture for a sales order. The inventory profile on the sales order line must belong to the kind of activity that is selected in the sales order, unless the kind of activity is **Unspecified**. The posting profile on the sales order line is defined in the **Inventory profile - posting profile** form. Therefore, if the inventory profile is selected, the corresponding posting profile is selected automatically.

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Create a sales order.

3.  Click **Line view**, and then, on the **Sales order lines** FastTab, click **Add lines** to open the **Create lines** form. When you select the **Split order lines by inventory profiles** check box in the **Accounts receivable parameters** form, the sales order lines are split by inventory profile, based on the priorities that are set up in the **Inventory profiles** form and the **On-hand inventory** form.

4.  On the **Existing items** tab, in the **Kind of activity** field, select **Unspecified**, **Basic**, **Commission agent**, **Principal's agent**, or **Bailee** as the profile type. You can view the related transactions for the selected kind of activity.

5.  In the **Sales quantity** field, enter the number of sales units.

6.  Click **Create** to create sales order lines.

7.  In the **Sales order** form, click **Header view**.

8.  Click the **Setup** FastTab, and then, in the **Kind of activity** field, select **Basic**, **Commission agent**, **Principal's agent**, or **Bailee** as the profile type.

9.  In the **Inventory profile** field, select the required inventory profile.

10. Select the **Use compatible inventory profiles** check box to use the inventory profiles on order lines that are compatible with the inventory profile that is specified in the order.

11. Click the **Pick and pack** tab, and then click **Packing slip** to update the packing slip.

12. Click **OK** to post the packing slip.

13. Click **Invoice** \> **Invoice** to open the **Posting invoice** form.
    

    > [!NOTE]
    > <P>The <STRONG>Kind of activity</STRONG> field on the <STRONG>Overview</STRONG> tab of the <STRONG>Posting invoice</STRONG> form is updated based on the inventory profiles on the lines.</P>



14. Click **OK** to post the sales invoice.

15. Click **Invoice** \> **Facture** to open the **Update facture** form.

16. Select the factures to update, and then click **OK** to update the facture for the sales order. You can view the updated kind of activity in the **Invoice journal** and **Facture journal** forms. For more information, see [(RUS) Customer invoice journal (modified form)](https://technet.microsoft.com/en-us/library/jj711658\(v=ax.60\)) [(RUS) Facture journal (form)](https://technet.microsoft.com/en-us/library/jj923567\(v=ax.60\))

## See also

[(RUS) Sales orders (modified form)](https://technet.microsoft.com/en-us/library/jj733272\(v=ax.60\))

[(RUS) Update factures and post invoices for sales orders](rus-update-factures-and-post-invoices-for-sales-orders.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

