---
title: (RUS) Generate a Counting act (INV-6) report
TOCTitle: (RUS) Generate a Counting act (INV-6) report
ms:assetid: ae11ea9f-f07f-4eab-9f28-cd5b0cf9e397
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853218(v=AX.60)
ms:contentKeyID: 50396498
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Generate a Counting act (INV-6) report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the **Print of counting act (INV-6)** form to generate a Counting act INV-6 report as a Microsoft Excel file. You must generate this report to track items that are transferred between warehouses. You must create a counting list of the items in the transfer that have been purchased. The counting list can contain on-hand inventory holdings.

1.  Click **Inventory management** \> **Journals** \> **Item counting** \> **Counting**.

2.  Click **New** to open the **Dimensions display** form.

3.  Select the **Inventory profile** and **Owner** check boxes.
    

    > [!NOTE]
    > <P>You can also select the <STRONG>Batch number</STRONG> and <STRONG>Warehouse</STRONG> check boxes, if these dimensions are applicable.</P>



4.  Click **OK** to create an inventory counting journal for the items in the transfer.

5.  In the **Name** field, select an inventory journal.

6.  Click **Lines** to open the **Journal lines, inventory** form, and then create journal lines for the items in the transfer. For more information, see [Journal lines, Inventory count (form)](https://technet.microsoft.com/en-us/library/aa599389\(v=ax.60\))

7.  Click **Functions** \> **Create counting list** to create a counting list. The **Counted** field is updated with the values that are specified in the **On-hand** field for each line.

8.  Close the form.

9.  In the **Counting** form, click **Print** \> **Counting act (INV-6)**.

10. In the **Date of act completion** field, select the date when the counting process is scheduled to be completed.

11. In the **Start date** field, select the starting date of the inventory counting period.

12. In the **End date** field, select the ending date of the inventory counting period.

13. In the **Order number** field, enter the order number that you are generating the Counting act INV-6 report for.

14. In the **Resolution date** field, select the transaction date of the order that you are generating the Counting act INV-6 report for.
    

    > [!NOTE]
    > <P>The values that are displayed in the <STRONG>Journal</STRONG>, <STRONG>Dimension No.</STRONG>, and <STRONG>Kind of inventory</STRONG> fields are based on the inventory counting transactions. Click <STRONG>Select</STRONG> to modify the values in the <STRONG>Journal</STRONG>, <STRONG>Dimension No.</STRONG>, and <STRONG>Kind of inventory</STRONG> fields, if modification is required. For example, you can modify these fields to generate the report for another journal or another dimension.</P>



15. Click **OK** to generate the Counting act INV-6 report.

## See also

[(RUS) Inventory journal report table (form)](https://technet.microsoft.com/en-us/library/jj839654\(v=ax.60\))

[(RUS) Print of counting act (INV-6) (form)](https://technet.microsoft.com/en-us/library/jj853156\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

