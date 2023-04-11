---
title: (IND) Set up automatically allocated charges for a charges code, vendor, and item combination in transactions
TOCTitle: (IND) Set up automatically allocated charges for a charges code, vendor, and item combination in transactions
ms:assetid: b85f064a-2c11-4c12-bed1-7f6a0dc6d25f
ms:mtpsurl: https://technet.microsoft.com/library/JJ664835(v=AX.60)
ms:contentKeyID: 49386165
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Set up automatically allocated charges for a charges code, vendor, and item combination in transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can define automatically allocated charges for a specific vendor, a specific charges group, or all vendors.

1.  Click **Accounts payable** \> **Setup** \> **Charges** \> **Automatic charges**.

2.  In the **Level** field, select **Line**.

3.  Press CTRL+N to create a charge for the line level.

4.  In the **Account code** field, select one of the following options:
    
      - **Table**
    
      - **Group**
    
      - **All**

5.  In the **Vendor relation** field, select the vendor account or charges group that the charges apply to.
    

    > [!NOTE]
    > <P>You can select a vendor account in the <STRONG>Vendor relation</STRONG> field only if <STRONG>Table</STRONG> is selected in the <STRONG>Account code</STRONG> field.</P>



6.  In the **Item code** field, select an option.

7.  In the **Item relation** field, select the item or group that the miscellaneous charges apply to.

8.  Click the **Lines** tab.

9.  In the **Charges code** field, select the charges code to attach to the vendor relation.

10. Select the category, and then enter a value for the charge category.

11. If the charge is an assessable charge, and the assessable charge is used to calculate tax, select the **Assessable value** check box.
    

    > [!NOTE]
    > <P>When the <STRONG>Assessable value</STRONG> check box is selected, the charge amount that is calculated based on the <STRONG>Assessable value pct.</STRONG> field is not financially updated. However, the actual charges are financially accounted.</P>



12. In the **Assessable value pct.** field, enter the percentage of the assessable charge.

13. Enter the other required details.

## See also

[(IND) Auto charges (modified form)](https://technet.microsoft.com/library/jj664811\(v=ax.60\))

[(IND) Create a purchase order and post charges](ind-create-a-purchase-order-and-post-charges.md)

  


