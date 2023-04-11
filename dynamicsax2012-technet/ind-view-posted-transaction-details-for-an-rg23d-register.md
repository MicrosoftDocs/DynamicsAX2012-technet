---
title: (IND) View posted transaction details for an RG23D register
TOCTitle: (IND) View posted transaction details for an RG23D register
ms:assetid: f4274e13-0890-4436-872d-21fb0456b406
ms:mtpsurl: https://technet.microsoft.com/library/JJ710954(v=AX.60)
ms:contentKeyID: 49386366
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) View posted transaction details for an RG23D register 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



RG23D is an excise register that is maintained by the dealer to enter transaction details for purchase transactions and sales transactions of goods eligible for excise duty. In the **RG23D details** form, you can view the details of the quantity of the goods sold or purchased and the excise duty applicable as entered for the RG23D register.

1.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **Excise** \> **Excise register**.

2.  Select the Excise control code (ECC) number for Company's address in the **ECC Number** field.

3.  Select the tax settlement period for the selected ECC number in the **Sales tax settlement period** field.

4.  Select **RG23D** in the **Register** field to view the RG23D register transactions.

5.  Select the starting and ending dates for the period in the **From Date** and the **To Date** fields.

6.  Click **OK** to open the **RG23D transactions** form.

7.  Click **Inquiries** and select **RG23D details**.

8.  You can view the following details in this register:
    
      - The date of the transaction.
    
      - The item number for the item the transaction is posted for.
    
      - The quantity of the item purchased in the **Receipt quantity** field.
    
      - The CENVAT credit amount. The value in this field is the excise duty amount for the purchase transaction that is posted for which RG23D ID is generated.
    
      - The quantity of the item sold for the transaction that is posted in the **Issue quantity** field.
    
      - The CENVAT credit transfer amount. The value in this field is the excise duty amount for the sales transaction that is posted for which RG23D ID is generated.

## See also

[(IND) Excise register inquiry (form)](https://technet.microsoft.com/library/jj710979\(v=ax.60\))

[(IND) RG23D details (form)](https://technet.microsoft.com/library/jj677843\(v=ax.60\))

  


