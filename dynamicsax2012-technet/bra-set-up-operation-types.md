---
title: (BRA) Set up operation types
TOCTitle: (BRA) Set up operation types
ms:assetid: f93f0083-2c8f-4260-aab4-24aae3280076
ms:mtpsurl: https://technet.microsoft.com/library/JJ822923(v=AX.60)
ms:contentKeyID: 50117582
author: tfehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BRA
- Brazil
- operation types
- set up operation types
- BR - 00024
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up operation types 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can classify sales and purchase operations based on whether they generate accounting entries, generate inventory movement, or create customer or vendor transactions. The tax calculations vary, depending on the outcome of an operation. Therefore, you must define the different operation types for a legal entity.

1.  Click **Organization administration** \> **Setup** \> **Brazil** \> **Operation type**.

2.  Create an operation type.

3.  In the **Operation type** and **Name** fields, enter the identification code and name of the operation type.

4.  Select the **Create inventory movements** check box to indicate that the operation type generates inventory movement.
    

    > [!NOTE]
    > <P>To create inventory-related ledger transactions, you must select the <STRONG>Post physical inventory</STRONG> and <STRONG>Post financial inventory</STRONG> check boxes on the <STRONG>Setup</STRONG> FastTab in the <STRONG>Item model groups</STRONG> form.</P>



5.  Select the **Create customer/vendor transactions** check box to indicate that the operation type creates customer or vendor transactions.

6.  In the **Item account** field, select the default posting account that is used for the operation type in the ledger.

7.  In the **Customer** field group, in the **Posting profile** field, select the customer posting profile for the operation type.

8.  In the **Vendor** field group, in the **Posting profile** field, select the vendor posting profile for the operation type.

You cannot modify an operation type that is attached to a posted sales or purchase order.

## See also

[(BRA) Operation type (form)](https://technet.microsoft.com/library/jj822922\(v=ax.60\))

[(BRA) Create and post a sales order](bra-create-and-post-a-sales-order.md)

[(BRA) Create and post a free text invoice](bra-create-and-post-a-free-text-invoice.md)

[(BRA) Create and post a purchase order](bra-create-and-post-a-purchase-order.md)

  


