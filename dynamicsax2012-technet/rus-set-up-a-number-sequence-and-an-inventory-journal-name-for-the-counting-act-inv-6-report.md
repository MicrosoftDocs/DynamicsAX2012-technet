---
title: (RUS) Set up a number sequence and an inventory journal name for the Counting act INV-6 report
TOCTitle: (RUS) Set up a number sequence and an inventory journal name for the Counting act INV-6 report
ms:assetid: a5783822-9b27-4662-abdb-cbe7bafb3775
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678566(v=AX.60)
ms:contentKeyID: 49387794
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up a number sequence and an inventory journal name for the Counting act INV-6 report [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to set up a number sequence and an inventory journal name for the Counting act INV-6 report. You can use the **Inventory and warehouse management parameters** form to set up a number sequence for the Counting act INV-6 report. For more information, see [(RUS) Inventory and warehouse management parameters (modified form)](https://technet.microsoft.com/en-us/library/jj733200\(v=ax.60\)).

You can use the **Journal names, inventory** form to create a new inventory journal name and to set up the Counting act INV-6 report for the inventory journal name. For more information, see [Journal names, Inventory (form)](https://technet.microsoft.com/en-us/library/aa552692\(v=ax.60\)).

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  Click the **Number sequences** link.

3.  In the **Number sequence code** field, select a number sequence for the **Counting act (INV-6)** reference that is specified in the **Reference** field.

4.  Close the form.

5.  Click **Inventory management** \> **Setup** \> **Journals** \> **Journal names, inventory**.

6.  Create a journal name. For more information, see [Set up journal names](set-up-journal-names.md).

7.  In the **Journal type** field, select **Counting**.

8.  Click the **Reports** FastTab.

9.  In the **Available** field, select **Counting act (INV-6)**, and then click **Add report.** to include the report in the **Selected** field.
    

    > [!NOTE]
    > <P>If the <STRONG>Available</STRONG> field is blank, click <STRONG>Update</STRONG> to update the list of available reports.</P>



## See also

[(RUS) Set up an inventory profile for a transferable item](rus-set-up-an-inventory-profile-for-a-transferable-item.md)

[(RUS) Inventory profiles (form)](https://technet.microsoft.com/en-us/library/jj733188\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

