---
title: Set up a button grid
TOCTitle: Set up a button grid
ms:assetid: 83a6931a-99de-42b2-8db1-6dc477614f84
ms:mtpsurl: https://technet.microsoft.com/library/Hh597148(v=AX.60)
ms:contentKeyID: 39519204
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a button grid 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

A button grid is a group of similar buttons, such as buttons for products, operations, or payments. Microsoft Dynamics AX for Retail POS can display up to five button grids in a screen layout.

When you create a new button grid, buttons are created based on the number of columns and rows that you specify. For example, if you create a grid that has 4 columns and 5 rows, 20 buttons are created. These buttons can then be configured for specific operations.

The button grid retains information about its appearance on the register, such as the color of buttons, and the features that are visible and hidden on the Retail POS screen. The button grid also retains information about the functions that the buttons run.

1.  Click **Retail** \> **Setup** \> **POS** \> **Button grids**.

2.  In the **Button grid** form, click **New** to create a new grid.

3.  On the **General** FastTab, specify information about the grid.

4.  Click **Designer**.
    

    > [!NOTE]
    > <P>You can only use the Designer if you have been granted special permissions to the database. For more information, see this <A href="https://go.microsoft.com/fwlink/?linkid=267571">TechNet article</A>.</P>



5.  On the **Visual layout** tab, click **New design**.

6.  In the **Rows** and **Columns** fields, enter the number of rows and columns of buttons that the button grid contains.

7.  Right-click each button, click **Button properties**, and then configure the button:
    
      - To delete a button, select the button, and then click **Delete button**.
    
      - To add a button, right-click in an empty part of the grid, and then click **New button**.
    
      - To add a row of buttons, right-click anywhere in the grid, and then click **Add row**. Retail adds a new row at the bottom of the grid.
    
      - To add a column of buttons, right-click anywhere in the grid, and then click **Add column**. Retail adds a new column on the right side of the grid.
    
      - To delete a row of buttons, right-click a button in the row, and then click **Delete row**.
    
      - To delete a column of buttons, right-click a button in the column, and then click **Delete column**.

## See also

[About setting up screen layouts](about-setting-up-screen-layouts.md)

  


