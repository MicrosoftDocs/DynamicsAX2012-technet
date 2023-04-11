---
title: Adjust charges on vendor invoices
TOCTitle: Adjust charges on vendor invoices
ms:assetid: de71b8a4-2bc2-4b30-899b-3ed0f7df8272
ms:mtpsurl: https://technet.microsoft.com/library/Aa551276(v=AX.60)
ms:contentKeyID: 36655950
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Adjust charges on vendor invoices 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this information to enter and allocate charges to multiple lines on a posted vendor invoice. Before you begin, the number sequence for **Charges voucher** must be specified in the **Accounts payable parameters** form.

1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.

2.  Select the invoice to adjust.

3.  Click **Charges** \> **Adjustment**.

4.  Select the allocation method in the **Charges allocation** field.
    

    > [!NOTE]
    > <P>This step applies only if the charge is a fixed amount.</P>



5.  In the **Posting date** field, enter the date of posting in the ledger.

6.  In the **Allocate charges to lines** field, specify whether to allocate charges to all lines, positive lines, or negative lines.

7.  Select the **Stocked** check box to allocate charges only to inventoried order lines.

8.  In the **Charges code** field, select the code for the charge.
    
    The default description is based on the definition of the charge in the **Charges code** form. Modify the text in the **Description** field if you need to.

9.  Enter a value in the **Charges value** field and specify how to calculate the charge in the **Category** field (**Fixed**, **Pcs.**, **Percent**, or **Intercompany percent**).

10. Optional: Select **Show selections and clear specific lines** to exclude specific lines from this allocation.
    

    > [!NOTE]
    > <P>This check box is not available if no charges have been set up.</P>

    
    When you select this check box, a grid is displayed that includes only lines that match the criteria in the **Allocate charges to lines** and the **Stocked** fields. For example, if you select **Positive lines** and **Stocked**, only lines that are both positive and inventoried will be displayed in the grid. Any lines for which the full quantity has already been designated as having been received are not displayed.
    
    You can exclude specific lines from allocation by clearing the **Include** check box for each line that should be excluded.
    

    > [!IMPORTANT]
    > <P>To exclude specific lines from allocation, leave the grid open when you click <STRONG>OK</STRONG>.</P>



11. Click **OK** to adjust the charges to the lines.

## See also

[Account for vendor invoice variance due to charges](account-for-vendor-invoice-variance-due-to-charges.md)

[Allocate charges (form)](https://technet.microsoft.com/library/hh697725\(v=ax.60\))

[Charges transactions (form)](https://technet.microsoft.com/library/aa633876\(v=ax.60\))

[Vendor invoice journal (form)](https://technet.microsoft.com/library/aa587621\(v=ax.60\))

  


