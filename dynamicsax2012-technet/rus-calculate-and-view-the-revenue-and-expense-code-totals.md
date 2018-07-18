---
title: (RUS) Calculate and view the revenue and expense code totals
TOCTitle: (RUS) Calculate and view the revenue and expense code totals
ms:assetid: 9d348f6b-8dad-49a8-816d-3a3fff1b6ab1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923568(v=AX.60)
ms:contentKeyID: 52075414
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate and view the revenue and expense code totals 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you calculate the totals of the revenue and expense codes, the calculation results are presented in a hierarchical structure that resembles the directory of revenue and expenses. In the **Totals on codes** form, you can double-click the cells to view the register lines that contain the data that is used in the calculations. In the **Register lines** form, you can click **Source** to view an index of the primary documents. After you calculate the totals, you can validate the figures that appear on the tax statement report by comparing those figures with the primary documents. Online analytical processing (OLAP) is used to calculate and display the totals of the revenue and expense codes.

Before you calculate the totals of the revenue and expense codes, generate and calculate the tax register journals.

1.  Click **General ledger** \> **Journals** \> **Tax register journal**.

2.  Select the journal to calculate the totals for.

3.  Click **Totals on codes** \> **Show** to view the totals of the revenue and expense codes after calculation by using the standard OLAP view.
    
      - The revenue or expense codes that totals have been calculated for are displayed in a hierarchical structure on the left side of the form. A total is displayed for each revenue or expense code.
    
      - The registers that are included in the calculations are listed horizontally in the upper section of the form. A total is displayed for each register.
    
      - The total for the revenue or expense code in the register is displayed in a cell at the intersection of the revenue or expense code and the register. If the specified register is not set to calculate the code, the cell is empty. If the calculation is performed, but the amount for the revenue or expense code register is 0 (zero), the cell displays 0.
        

        > [!NOTE]
        > <P>To view the register lines that were used to calculate the total that is displayed in the cell, double-click a cell that is between the register and the revenue or expense code.</P>



## See also

[(RUS) Tax register journal (form)](https://technet.microsoft.com/en-us/library/jj856114\(v=ax.60\))

  


