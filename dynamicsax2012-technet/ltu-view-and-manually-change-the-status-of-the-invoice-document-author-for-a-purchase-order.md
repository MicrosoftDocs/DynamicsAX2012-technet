---
title: (LTU) View and manually change the status of the invoice document author for a purchase order
TOCTitle: (LTU) View and manually change the status of the invoice document author for a purchase order
ms:assetid: 9d0bb8d1-7f85-44c6-9480-bfe06ab0f614
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665147(v=AX.60)
ms:contentKeyID: 49386728
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (LTU) View and manually change the status of the invoice document author for a purchase order 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A posted purchase invoice has an author, which is the company. When items are returned, the customer, the vendor, or the company can sign the invoice. If the customer or the vendor authors the returning invoice, the document author must be changed for that invoice.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts payable** \> **Inquiries** \> **Journals** \> **Invoice journal**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Double click a vendor account to open the **Vendors** form. Click **Invoice** to open the **Invoice journal** form.

2.  Select the invoice for which to change the status, and then click **Function** \> **Change document author** to open the **Change document author** form.

3.  In the **New document author** field, select the author for the invoice from the following options:
    
      - **Company** – The invoice is approved by the company.
    
      - **Vendor** – The returned invoice is signed by the vendor.

4.  Click **OK** to apply the author change and return to the **Invoice journal** form.

5.  Press CTRL+S or close the form.

## See also

[(LTU) Purchase invoice journal (modified form)](https://technet.microsoft.com/en-us/library/jj665048\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

