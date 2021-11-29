---
title: (RUS) Set up an inventory unit and unit operator to calculate the storage service amount
TOCTitle: (RUS) Set up an inventory unit and unit operator to calculate the storage service amount
ms:assetid: 3618a5f5-dead-4ef0-82bd-062f9cb823b8
ms:mtpsurl: https://technet.microsoft.com/library/JJ733199(v=AX.60)
ms:contentKeyID: 49685167
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up an inventory unit and unit operator to calculate the storage service amount 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up an inventory unit to calculate the storage service amount. You can also use the **Unit operations** form to set up formulas to calculate the storage service amount.

1.  Click **Organization administration** \> **Setup** \> **Units** \> **Units**.

2.  Press CTRL+N to create a new inventory unit to calculate the storage service amount.

3.  In the **Unit** field, enter the identification code of the unit.

4.  In the **Description** field, enter the name of the unit.

5.  In the **Decimal precision** field, enter the maximum number of decimal places that the unit is calculated to.

6.  Click **Storage calculation** to open the **Unit operations** form.

7.  Press CTRL+N to create a new mathematical operator to calculate the storage service amount.

8.  In the **Operator** field, select a mathematical operator, such as **+**, **-**, **\***, or **/**.

9.  In the **Line type** field, select the line type to calculate the storage service amount. The following options are available:
    
      - **Constant** – The value of the constant.
    
      - **Net weight** – The total weight of the stored item, excluding the packaging weight.
    
      - **Gross weight** – The total weight of the stored item, including the packaging weight.
    
      - **Quantity** – The number of stored items.
    
      - **Volume** – The volume of the stored items.
    
      - **Days** – The total number of days for the storage calculation.
        

        > [!NOTE]
        > <P>You must enter the number of days for the storage calculation.</P>



10. In the **Data** field, enter a constant value that is used to calculate the storage service amount.
    

    > [!NOTE]
    > <P>Enter a value in this field only if you selected <STRONG>Constant</STRONG> in the <STRONG>Line type</STRONG> field.</P>



## See also

[Units (form)](https://technet.microsoft.com/library/hh209233\(v=ax.60\))

[(RUS) Unit operations (form)](https://technet.microsoft.com/library/jj665247\(v=ax.60\))

[(RUS) Create a calculation item and assign an inventory unit to the item](rus-create-a-calculation-item-and-assign-an-inventory-unit-to-the-item.md)

  


