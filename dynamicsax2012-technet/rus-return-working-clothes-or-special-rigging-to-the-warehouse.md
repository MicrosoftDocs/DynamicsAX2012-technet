---
title: (RUS) Return working clothes or special rigging to the warehouse
TOCTitle: (RUS) Return working clothes or special rigging to the warehouse
ms:assetid: ce2d7273-c8be-4163-9d46-19726e9bd335
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ923593(v=AX.60)
ms:contentKeyID: 52075437
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Russia
- special rigging
- working clothes
---

# (RUS) Return working clothes or special rigging to the warehouse [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to return a working clothes item or special rigging item to a warehouse.

1.  Click **Fixed assets (Russia)** \> **Common** \> **Working clothes**. Double-click an existing working clothes item.
    
    –or–
    
    Click **Fixed assets (Russia)** \> **Common** \> **Special rigging**. Double-click an existing special rigging item.

2.  Click **Componentry** \> **Componentry**.

3.  Select the fixed asset item or component that is required, and then click **Add to remains**.

4.  In the **Quantity** field, enter the remaining quantity of the item.

5.  Click **OK** to add the working clothes item or special rigging item to item remainders. The lines that are marked in the upper pane of the **Componentry** form are moved to the lower pane.

6.  In the lower pane, click **Calculating prices** to calculate the balance value, depreciation, and depreciated cost for each item that is returned. The calculations are based on the price calculation method that is selected.

7.  Close the forms.

8.  Click **Fixed assets (Russia)** \> **Journals** \> **FA journal**.

9.  Create a new fixed asset (FA) journal.

10. In the **Name** field, select a journal name.

11. Click **Lines**.

12. Click **New** to open the **Add to journal** form.

13. In the **Transaction date** field, select the transaction date.

14. In the **Transaction type** field, select **Disposal (dismantlement)**.

15. In the **FA inventory number** field, select the inventory number of the fixed asset.

16. Click **OK**. The value model lines for the asset record are created in the journal.

17. Click **Validate** \> **Validate** to validate the journal.

18. Click **Post** \> **Post** to post the journal.

## See also

[(RUS) Special rigging (form)](https://technet.microsoft.com/en-us/library/jj923264\(v=ax.60\))

[(RUS) Working clothes (form)](https://technet.microsoft.com/en-us/library/jj923545\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

