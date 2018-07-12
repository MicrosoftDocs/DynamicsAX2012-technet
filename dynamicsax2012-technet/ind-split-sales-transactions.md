---
title: (IND) Split sales transactions
TOCTitle: (IND) Split sales transactions
ms:assetid: 0e200024-7b09-493b-b29e-84a11cb728f2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664485(v=AX.60)
ms:contentKeyID: 49385564
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Split sales transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In a sales transaction, you can split a sales order confirmation, a picking list, a packing slip, or a sales invoice. A split can be based on the site, delivery addresses, and multiple excise registration numbers for an organization that has an active site.

1.  Click **Accounts receivable** \> **Setup** \> **Accounts receivable parameters**.

2.  Click **Summary update**.

3.  Select the following check boxes in the **Split based on** field group to split the document based on multiple delivery addresses and multiple registration numbers:
    
      - **Confirmation** – If you generate a sales order confirmation that has multiple delivery addresses and multiple registration numbers, the confirmation is split based on the number of delivery addresses and registration numbers.
    
      - **Picking list** – If you generate a picking list that has multiple delivery addresses and multiple registration numbers, the picking list is split based on the number of delivery addresses and registration numbers.
    
      - **Packing slip** – If you generate a packing slip that has multiple delivery addresses and multiple registration numbers, the packing slip is split based on the number of delivery addresses and registration numbers.
    
      - **Invoice** – If you generate a sales invoice that has multiple delivery addresses and multiple registration numbers, the sales invoice is split based on the number of delivery addresses and registration numbers.
    
    If you do not select the check boxes in the **Split based on** field group, only one sales order confirmation, picking list, packing slip, or invoice is created. This occurs even though the delivery addresses or the registration numbers are different. The document that is created has the delivery address or registration number of the first record in the sales order.
    
    If a sales document or a purchase document has a single delivery address but multiple registration numbers, the document is split based on the number of registration numbers only. Similarly, if a document has a single registration number but multiple delivery addresses, the document is split based on the number of delivery addresses only.

4.  Close the form.

  


