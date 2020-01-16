---
title: (RUS) Enter a type of by-product
TOCTitle: (RUS) Enter a type of by-product
ms:assetid: 0a389e30-50ec-4321-a573-973aa46eb7e8
ms:mtpsurl: https://technet.microsoft.com/library/JJ711376(v=AX.60)
ms:contentKeyID: 49387194
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Enter a type of by-product 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Kinds of by-product** form to enter a type of by-product. You also specify the number of the general ledger account that is used to write off the cost of the scrap that you receive from production.

1.  Click **Production control** \> **Setup** \> **Kinds of by-product**.

2.  Click **New** to create a by-product line.

3.  In the **Kind of by-product** field, enter a type of by-product.

4.  In the **Name** field, enter a description for the type of by-product.

5.  Select the **Defective product** check box to indicate that the by-product is a defective product.

6.  Select the **Scrap** check box to write off the cost of the defective product after you receive the product from production.
    

    > [!NOTE]
    > <P>The <STRONG>Warehouse</STRONG>, <STRONG>Loss account</STRONG>, and <STRONG>Loss account (physical)</STRONG> fields are available only when you select this check box.</P>



7.  In the **Costing rule** field, select the cost calculation rule that is used to calculate the cost of by-products or defective products. The following options are available:
    
      - **Fixed price** – The cost is calculated based on the value in the **Released products** form.
    
      - **Calculated price** – The cost is calculated based on the cost calculation method for production orders that is selected in the **Costing method** field in the **Production control parameters** form.
    
      - **By-product** – The cost is calculated based on the cost calculation rule that is selected in the **Costing rule** field in the **By-product** form.

8.  In the **Warehouse** field, enter the warehouse to use to store the scrap.

9.  In the **Loss account** field, select the general ledger account to use to write off the cost of the scrap.

10. In the **Loss account (physical)** field, select the offset account to use to update the quantity of the scrap that is issued.

## See also

[(RUS) Kinds of by-product (form)](https://technet.microsoft.com/library/jj711686\(v=ax.60\))

  


