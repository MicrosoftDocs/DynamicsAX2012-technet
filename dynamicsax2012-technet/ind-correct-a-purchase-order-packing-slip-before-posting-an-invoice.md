---
title: (IND) Correct a purchase order packing slip before posting an invoice
TOCTitle: (IND) Correct a purchase order packing slip before posting an invoice
ms:assetid: 98a03250-84bb-4800-b71e-5af81c39e917
ms:mtpsurl: https://technet.microsoft.com/library/JJ664711(v=AX.60)
ms:contentKeyID: 49386042
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- invoice
- purchase
- India
- IND
audience: Application User
ms.search.region: India
---

# (IND) Correct a purchase order packing slip before posting an invoice 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Excise register taxes at the packing slip level are based on the calculation date type that is selected in the General ledger parameters form.

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Select the purchase order for which the packing slip must be corrected. The purchase order must have a status of **Received**.

3.  On the **Action Pane**, on the **Manage** tab, click **Packing slip journal**.

4.  In the **Packing slip journal** form, select the packing slip record and then click **Correction**.

5.  In the **Correct packing slip – Packing slip %1, %2** form, in the **Update** field, enter the new quantity. Click **OK**.

6.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Excise register**.

7.  In the **Excise register inquiry** form, in the **Register** field, select **RG23A Part - I**.

8.  Specify the required data for RG23A – Part I register, and then click **OK** to open the **RG23A Part - I transactions** form. The excise register is updated with three lines that refer to the same packing slip number. Each line has a different register ID and includes the tax amounts that relate to quantity.
    
    The excise register is updated with the following register IDs:
    
      - The original quantity and tax amount
    
      - The reversed quantity and tax amount
    
      - The corrected quantity and tax amount

  


