---
title: (IND) Post an opening balance in an excise register using inventory journal
TOCTitle: (IND) Post an opening balance in an excise register using inventory journal
ms:assetid: 959f3508-4bfb-4849-b007-def4ad27ae2f
ms:mtpsurl: https://technet.microsoft.com/library/JJ664703(v=AX.60)
ms:contentKeyID: 49386033
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Post an opening balance in an excise register using inventory journal 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the movement journal to post the opening balance of the quantity of excisable goods in the RG register.

Example:

A line in the movement journal is created for an item with the following details:

  - Cost price: 100.00

  - Quantity: 10

  - Amount: 1000.00

  - Excise record type: RG23A

When the movement journal is posted, the RG23A Part I register is updated with the inward quantity, which is 10.00.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Inventory management** \> **Journals** \> **Item transactions** \> **Movement**.

2.  Create a new journal, and then click **Lines**.

3.  Select the item number in the **Item number** field, the quantity in the **Quantity** field, and the offset account in the **Offset account** field.

4.  Click the **Tax information** tab.

5.  In the **ECC number** field, modify the default excise registration number that is attached to the company, if required.

6.  In the **Excise tariff code** field, modify the excise tariff code that is attached to the item, if required.

7.  Select the excise register that must be updated with the quantity in the **Excise record type** field from the following options:
    
      - **RG23A**
    
      - **RG23C**
    
      - **RG23D**

8.  Select **DSA** check box to update the DSA register with the quantity details. The **DSA** check box is activated for the following two conditions:
    
      - When you select the **Bill Of Material (BOM)** item type in the journal line.
    
      - When you select the **None** in the **Excise record type** field.

9.  Validate and post the journal. The Part I register of the RG23A, the RG23C, or the RG23D register is updated with the transaction details of the quantity.

## See also

[(IND) RG23A item details (form)](https://technet.microsoft.com/library/jj664747\(v=ax.60\))

[(IND) RG23D details (form)](https://technet.microsoft.com/library/jj677843\(v=ax.60\))

[(IND) Inquiries for RG23A registers](ind-inquiries-for-rg23a-registers.md)

[(IND) Inquiries for RG23C registers](ind-inquiries-for-rg23c-registers.md)

[(IND) Inquiries for RG23D registers](ind-inquiries-for-rg23d-registers.md)

  


