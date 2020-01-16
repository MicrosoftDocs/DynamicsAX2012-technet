---
title: (IND) Specify dates to calculate excise tax in invoices and journals
TOCTitle: (IND) Specify dates to calculate excise tax in invoices and journals
ms:assetid: 8e46cf53-d4b3-4dd9-b5d7-c6cd639d8a30
ms:mtpsurl: https://technet.microsoft.com/library/JJ678045(v=AX.60)
ms:contentKeyID: 49386006
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Specify dates to calculate excise tax in invoices and journals 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can specify the date that must be used to calculate excise tax in invoices and journals.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  Click **Sales tax**, and in the **Vendor calculation date type** field, specify when the excise tax on purchase transactions should be calculated. The following options are available:
    
      - **Delivery date** – For a purchase invoice, calculate the excise tax based on the date when the product receipt is posted. In journals, calculate the excise tax based on the date when the invoice is posted.
    
      - **Document date** – For a purchase invoice, calculate the excise tax based on the document date for the product receipt. For journal transactions, calculate the excise tax based on the document date that is entered on the **Invoice** tab in the **Journal voucher** form.
    
      - **Invoice date** – For both purchase invoices and journals, calculate the excise tax based on the date when the invoice is posted.
    

    > [!NOTE]
    > <P>If you post an invoice and do not update the item receipt, the excise tax is calculated based on the invoice date.</P>



3.  In the **Customer calculation date type** field, specify when the excise tax on sales transactions should be calculated. The following options are available:
    
      - **Delivery date** – Calculate the excise tax in the sales invoice based on the date when the product receipt is posted. Calculate the excise tax in journals based on the date when the invoice is posted. If you post an invoice and do not update the packing slip, the excise tax is calculated based on the invoice date.
    
      - **Invoice date** – In both sales invoices and journals, calculate the excise tax based on the invoice posting date.

## See also

[Calculation date type example](https://technet.microsoft.com/library/aa556805\(v=ax.60\))

[(IND) General ledger parameters (modified form)](https://technet.microsoft.com/library/jj677901\(v=ax.60\))

  


