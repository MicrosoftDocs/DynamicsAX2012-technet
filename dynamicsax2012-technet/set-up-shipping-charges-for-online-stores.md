---
title: Set up shipping charges for online stores
TOCTitle: Set up shipping charges for online stores
ms:assetid: e2aa075c-89d0-414d-b967-1a92fded3560
ms:mtpsurl: https://technet.microsoft.com/library/JJ728714(v=AX.60)
ms:contentKeyID: 49556619
author: tonyafehr
ms.date: 05/01/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up shipping charges for online stores 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

In **Retail**, you can define the following types of shipping charges for online orders:

  - A fixed amount for a range of order totals. This includes free shipping for order totals above a specified amount.

  - A fixed amount for each item.

  - A charge that is provided by the shipping carrier, which you can mark up by a specified percentage.

  - A percentage of the total.

You can also define a shipping charge for a mode of delivery, a group of modes of delivery, or all modes of delivery.


> [!NOTE]
> <P>Before you can specify shipping charges, you must create modes of delivery. For information, see <A href="https://technet.microsoft.com/library/aa619881(v=ax.60)">Modes of delivery (form)</A>.</P>



1.  Click **Retail** \> **Setup** \> **Charges** \> **Auto charges**.

2.  Click **New**, and then, in the **Level** field, select **Line**.

3.  In the **Account code** and **Customer relation** fields, do one of the following:
    
      - If you want the shipping charges to apply to a specific customer, select **Table** in the **Account code** field, and then, in the **Customer relation** field, select the customer.
    
      - If you want the shipping charges to apply to a group of customers, select **Group** in the **Account code** field, and then, in the **Customer relation** field, select the group.
    
      - If you want the shipping charges to apply to all customers, select **All** in the **Account code** field.

4.  In the **Mode of delivery code** and **Mode of delivery relation** fields, do one of the following:
    
      - If you want the shipping charges to apply to a specific mode of delivery, select **Table** in the **Mode of delivery code** field, and then, in the **Mode of delivery relation** field, select the mode of delivery.
    
      - If you want the shipping charges to apply to a group of modes of delivery, select **Group** in the **Mode of delivery code** field, and then, in the **Mode of delivery relation** field, select the group.
    
      - If you want the shipping charges to apply to all modes of delivery, select **All** in the **Mode of delivery code** field.

5.  On the **Lines** FastTab, click **Add**.

6.  In the **From amount** and **To amount** fields, specify the transaction totals to which the shipping charge applies.
    
    For example, if you want all orders below 100.00 to be charged 5.00 for shipping, and orders of 100.00 or more to have free shipping, add two lines that contain the following values:
    
      - On the first line, enter **0** in the **From amount** field, enter **100** in the **To amount** field, and enter **5** in the **Charges value** field.
    
      - On the second line, enter **100** in the **From amount** field, leave the **To amount** field blank, and enter **0** in the **Charges value** field.

7.  If you want the shipping carrier to provide the shipping charge , in the **Category** field, select **External**.

8.  For information about the other fields on the **Lines** FastTab, see [Auto charges (form)](https://technet.microsoft.com/library/aa582856\(v=ax.60\)).

## See also

[Set up modes of delivery](set-up-modes-of-delivery.md)

[Set up shipping charges for retail stores](set-up-shipping-charges-for-retail-stores.md)

  


