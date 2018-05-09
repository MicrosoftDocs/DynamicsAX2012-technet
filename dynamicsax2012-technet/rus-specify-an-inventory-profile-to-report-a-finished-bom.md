---
title: (RUS) Specify an inventory profile to report a finished BOM
TOCTitle: (RUS) Specify an inventory profile to report a finished BOM
ms:assetid: b9c817e7-95c3-4dde-8cbf-302ef70d8a71
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711547(v=AX.60)
ms:contentKeyID: 49387872
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Specify an inventory profile to report a finished BOM 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

When you create a bill of materials (BOM) journal to report a BOM as finished, the value of the **Inventory profile** field is specified on the BOM journal lines. The BOM journal lines correspond to the BOM lines as follows:

  - If the **Inventory profile** field is not active for the specified item, the dimension value is not specified.

  - If the **Inventory profile** field is specified on the BOM lines, the value of the **Inventory profile** field is specified on the BOM journal lines.

  - If the **Inventory profile** field is specified in the **Bills of materials** area in the **Inventory and warehouse management parameters** form, the specified value of the dimension inventory profile is entered on the BOM journal lines.

<!-- end list -->

1.  Click **Product information management** \> **Common** \> **Released products**. On the **Action Pane**, on the **Product** tab, click **Product**.

2.  In the **Product type** field, select **Item** to create a BOM for an item and to report the BOM as finished. Then click **OK**. For more information, see [About reporting BOMs as finished](about-reporting-boms-as-finished.md).

3.  Double-click a product line to open the **Released product details** form.

4.  On the **Action Pane**, on the **Engineer** tab, in the **Process** group, click **Report as finished**.

5.  In the **Report as finished** form, click the **Inventory dimensions** tab, and then in the **Inventory profile** field, select the inventory profile.

6.  Click **OK** to report a BOM as finished.

## See also

[(RUS) Report BOM as finished (modified form)](https://technet.microsoft.com/en-us/library/jj733179\(v=ax.60\))

[Report a BOM as finished](report-a-bom-as-finished.md)

[(RUS) BOM line (modified form)](https://technet.microsoft.com/en-us/library/jj711372\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

