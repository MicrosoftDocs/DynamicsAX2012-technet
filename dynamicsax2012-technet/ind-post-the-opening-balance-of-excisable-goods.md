---
title: (IND) Post the opening balance of excisable goods
TOCTitle: (IND) Post the opening balance of excisable goods
ms:assetid: c553648e-5231-4759-a396-5bf5837e2fea
ms:mtpsurl: https://technet.microsoft.com/library/JJ664863(v=AX.60)
ms:contentKeyID: 49386193
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Post the opening balance of excisable goods 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Use the movement journal to post the opening balance of the quantity of excisable goods in the Recoverable Goods (RG) register and the Daily stock register (DSA).

1.  Click **Inventory management** \> **Journals** \> **Item transactions** \> **Movement**.

2.  Press CTRL+N to create a new journal and click **Lines**.

3.  On the **Overview** tab, select the item number, the quantity, and the offset account.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa598740(v=ax.60)">Journal lines, Inventory movement (form)</A>.</P>



4.  Click the **Tax information** tab.

5.  View or modify the excise registration number that is attached to the company in the **ECC number** field.

6.  View or modify the excise tariff code that is attached to the item in the **Excise tariff code** field.

7.  Select the excise register that must be updated with the quantity in the **Excise record type** field.
    
      - **RG23A** - RG register for non capital purchases.
    
      - **RG23C** - RG register for capital purchases.

8.  Select the **DSA** check box to update the DSA register with the quantity details. The **DSA** check box is activated for the following two conditions:
    
      - When you select an item that has a **Bill of Material (BOM)** item type in the journal line.
    
      - When you select the **None** option in the **Excise record type** field.

9.  Validate and post the journal. The Part I register of the RG23A, the RG23C, or the RG23D register is updated with the transaction details of the quantity.
    
    For example, a line in the movement journal is created for an item with the following details:
    
      - Cost price – INR 100.00
    
      - Quantity – 10
    
      - Amount – INR 1,000.00
    
      - Excise record type – RG23A
    
    When the movement journal is posted, the RG23A Part I register is updated with the inward quantity 10.00.

## See also

[(IND) RG23A tax details (form)](https://technet.microsoft.com/library/jj678015\(v=ax.60\))

[(IND) RG23C tax details (form)](https://technet.microsoft.com/library/jj677926\(v=ax.60\))

  


