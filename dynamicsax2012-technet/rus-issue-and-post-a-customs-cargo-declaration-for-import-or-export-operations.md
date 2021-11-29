---
title: (RUS) Issue and post a customs cargo declaration for import or export operations
TOCTitle: (RUS) Issue and post a customs cargo declaration for import or export operations
ms:assetid: f1087bae-e61b-44dc-9a27-5080e8deedd6
ms:mtpsurl: https://technet.microsoft.com/library/JJ733404(v=AX.60)
ms:contentKeyID: 49685271
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Issue and post a customs cargo declaration for import or export operations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **GTD issue** form to issue a customs cargo declaration (GTD) for import or export operations. You must first create the customs journal lines for a transaction. After a customs cargo declaration is issued, the status of the journal is changed to **Issued**. A new value for the GTD inventory dimension is created in the **Inventory dimensions** form. The inventory transactions that are associated with the customs journal have the GTD value in the inventory dimension. If the GTD number or date is corrected, you can cancel the issue of a GTD by using the **GTD issue cancelling** form. The status of the journal is changed to **In progress** after the GTD issue is canceled.


> [!NOTE]
> <P>When you create a customs journal that is based on an open purchase order, the lines that belong to the purchase order are updated with the GTD that is issued for the related import operations.</P>



The status of a journal is changed to **Posted** after a GTD is posted. The corresponding general ledger, vendor, and tax transactions are created based on the rules for customs payments. A facture of the **GTD** type is created for the import customs journal.

1.  Click **Inventory management** \> **Common** \> **All customs journals**.

2.  Create a customs journal, or double-click an existing customs journal.

3.  On the **Customs journal lines** FastTab, click **Create lines** to open the **Create customs journal lines.** form.

4.  In the upper pane, select the **Choose** check box to mark the purchase order or vendor invoices for the import operations to include in the customs journal. You can select a purchase order if **On order** is selected in the **Receipt transactions status** field in the **Terms of delivery** form. If **Purchased** is selected in the **Receipt transactions status** field, you can create journal lines for vendor invoices.
    

    > [!NOTE]
    > <P>You can create custom journal lines for a customer packing slip if <STRONG>Standard</STRONG> is selected as the type of posting for the journal in the <STRONG>Posting type</STRONG> field in the <STRONG>Create customs journal</STRONG> form. If <STRONG>Postponed passing of property</STRONG> is selected in the <STRONG>Posting type</STRONG> field, you can create custom journal lines for customer invoices.</P>



5.  Click **OK** to transfer the invoice data to the **Customs journal** form and close the **Create customs journal lines** form.

6.  In the **Customs journal** form, click the **Manage** tab.

7.  On the **Action Pane**, in the **Generate** action group, click **GTD issue**.

8.  In the **GTD number** field, enter the customs cargo declaration number that is specified by the customs authorities.

9.  In the **Issue date** field, select the date when the customs cargo declaration is issued.

10. Select the **Posting** check box to indicate that the customs cargo declaration can be posted while it is being issued.
    

    > [!NOTE]
    > <P>You can also post a customs cargo declaration by using the <STRONG>GTD posting</STRONG> form. The status of the journal is changed to <STRONG>Posted</STRONG>. The corresponding general ledger, vendor, and tax transactions are created based on the rules for customs payments.</P>



11. Click **OK** to issue and post the customs cargo declaration and close the form.


> [!NOTE]
> <P>You can use a similar process to issue and post a customs cargo declaration for export operations.</P>



## See also

[(RUS) Set up the terms of delivery for customs clearance of items](rus-set-up-the-terms-of-delivery-for-customs-clearance-of-items.md)

[(RUS) Terms of delivery (modified form)](https://technet.microsoft.com/library/jj733176\(v=ax.60\))

  


