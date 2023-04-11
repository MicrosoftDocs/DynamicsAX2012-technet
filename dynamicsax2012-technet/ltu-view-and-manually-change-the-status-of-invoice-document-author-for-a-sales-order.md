---
title: (LTU) View and manually change the status of invoice document author for a sales order
TOCTitle: (LTU) View and manually change the status of invoice document author for a sales order
ms:assetid: db93620d-c881-4fdc-9eb6-2073d5abc7ab
ms:mtpsurl: https://technet.microsoft.com/library/JJ665208(v=AX.60)
ms:contentKeyID: 49386789
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Lithuania
---

# (LTU) View and manually change the status of invoice document author for a sales order 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

A posted sales invoice has an author, which is the company. When items are returned to the company, the customer, the vendor, or the company can sign the invoice. If the customer or the vendor authors the returning invoice, the document author must be changed for that invoice.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Inquiries** \> **Journals** \> **Invoice journal**.
    
    –or–
    
    Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Double-click a customer from the list to open the **Customers** form. Click **Invoice** and **Invoice journal** to open the **Invoice journal** form.

2.  Select the invoice for which to change the status, and then click **Function** \> **Change document author** to open the **Change document author** form.

3.  In the **New document author** field, select the author for the invoice from the following options:
    
      - **Company** – The invoice is approved by the company.
    
      - **Customer** – The returned invoice is signed by the customer.

4.  Click **OK** to apply the author change and return to the **Invoice journal** form.

5.  Press CTRL+S or close the form.

## See also

[(LTU) Customer payment journal lines (modified form)](https://technet.microsoft.com/library/jj665039\(v=ax.60\))

  


