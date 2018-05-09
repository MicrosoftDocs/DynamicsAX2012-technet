---
title: (RUS) Create vendor tax agent transactions
TOCTitle: (RUS) Create vendor tax agent transactions
ms:assetid: 159d0cd6-7ff7-4890-a139-6b60d29b63c8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711416(v=AX.60)
ms:contentKeyID: 49387234
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Create vendor tax agent transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can define a vendor as a tax agent in the **Vendors** form and perform transactions with this vendor.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Press CTRL+N to create a vendor tax agent, and enter the necessary information.

3.  On the **General** tab, select the **Tax agent** check box to define the vendor as a tax agent.

4.  In the **Vendor type** field, select the type of vendor from the following options:
    
      - **Blank** – If the vendor is not a tax agent.
    
      - **Non resident** – If the vendor is a foreigner.
    
      - **State authority** – If the vendor is a governmental or municipal authority.

5.  In the **VAT operation code** field, select the operation code for VAT declaration.

6.  Press CTRL+S or close the form.

7.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

8.  Press CTRL+N to create a purchase order for the vendor tax agent. Enter the necessary information.

9.  Click the **Header** view, and then, on the **Setup** tab, in the **VAT operation code** field, view or modify the code for VAT declarations.

10. Click **Posting** \> **Invoice** to open the **Posting invoice** form.

11. In the **Invoice** field, enter the invoice number.

12. Click **OK** to post the invoice.

## See also

[(RUS) Purchase orders (modified form)](https://technet.microsoft.com/en-us/library/jj733294\(v=ax.60\))

[(RUS) Create and print factures for VAT deductions](rus-create-and-print-factures-for-vat-deductions.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

