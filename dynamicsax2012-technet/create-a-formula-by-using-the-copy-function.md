---
title: Create a formula by using the copy function
TOCTitle: Create a formula by using the copy function
ms:assetid: 7289c270-709c-490d-84df-76ebc5e52f90
ms:mtpsurl: https://technet.microsoft.com/library/Hh352211(v=AX.60)
ms:contentKeyID: 36687845
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create a formula by using the copy function 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create a formula that includes the same ingredients as an existing formula, but with minor differences. To create the formula lines, you can use the **Copy** function to copy an existing formula that has most of the ingredients that you need. You can then make any necessary changes to the individual lines in the new version. By using the **Copy** function, you do not have to create multiple formulas that are almost identical.

1.  Click **Inventory and warehouse management** \> **Common** \> **Formula**.

2.  In the upper grid, press CTRL+N to create a new formula.

3.  Enter information to identify the formula.

4.  Enter the site information.

5.  In the **Versions** grid, select the item number for this formula version.

6.  Enter information to identify the formula version.

7.  Click **Lines** to create the formula lines.

8.  In the **Formula line** form, click **Functions** and select **Copy**.

9.  In the **Formula copying** form, select whether you want to copy from base data or production.
    
      - To copy from base data, select the item number that the formula is attached to, the configuration to be copied from, and the formula number.
    
      - To copy from production, enter the batch order number from which to copy.

10. In the **Formula copying** form, select whether you want to copy to base data or to production.
    
      - To copy to base data, enter a formula number to be copied to.
    
      - To copy to production, enter the batch order number to be copied to.

11. In the **Setup** area, you can mark whether the formula should replace or add data on the formula line or in the production.

12. Click **Approve formula** to open the **Approve BOM or formula** form. Select the approving employee, and then click **OK**.

13. In the **Versions** grid, click **Approve** to open the **Approve version** form. Select the approving employee, and then click **OK**.

14. Click **Activation** to make the formula version active.

## See also

[Approve BOM or formula (class form)](https://technet.microsoft.com/library/hh227377\(v=ax.60\))

[(PM) Approve formula version (class form)](https://technet.microsoft.com/library/hh242740\(v=ax.60\))

[Formula (form)](https://technet.microsoft.com/library/hh328668\(v=ax.60\))

[Formula copying (form)](https://technet.microsoft.com/library/hh352338\(v=ax.60\))

[Formula line (form)](https://technet.microsoft.com/library/hh352331\(v=ax.60\))

  


