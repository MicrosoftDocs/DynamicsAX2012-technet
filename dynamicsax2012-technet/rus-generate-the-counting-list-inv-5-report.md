---
title: (RUS) Generate the Counting list (INV-5) report
TOCTitle: (RUS) Generate the Counting list (INV-5) report
ms:assetid: 564044ca-8f6d-4131-b939-29144364de66
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ853181(v=AX.60)
ms:contentKeyID: 50396462
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Generate the Counting list (INV-5) report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Counting** list form to generate the Counting list (INV-5) report to track items that are in storage. The Counting list (INV-5) report contains the following information:

  - The name of the vendor

  - The identification number of the officials who are involved in the item counting process

  - The description, ID, count, dimensions, weight, and total cost of the items that are in storage

  - The statement number and date of the acceptance report in storage (MX-1) that is generated during the inventory counting period

  - The storage period and storage location for the items

  - The starting and ending dates for the inventory count

  - The date and number of the inventory counting order

The Counting list (INV-5) report is generated in Microsoft Excel format.

1.  Click **Inventory management** \> **Journals** \> **Item counting** \> **Counting**.

2.  Press CTRL+N to create a new inventory counting journal, or select an inventory journal for bailment.

3.  Click **Lines** to open the **Journal lines, inventory** form, and create journal lines. For more information, see [Journal lines, Inventory count (form)](https://technet.microsoft.com/en-us/library/aa599389\(v=ax.60\)).

4.  Click **Functions** \> **Create counting list** to create the counting list. The **Counted** field is updated with the values that are specified in the **On-hand** field for each line.

5.  Close the form.

6.  In the **Counting** form, click **Print** \> **Counting list**.

7.  Click **OK** to generate the Counting list (INV-5) report. You can also view and print the Counting list (INV-5) report from the **Inventory journal report table** form.

## See also

[(RUS) Set up officials for the counting list (INV-5)](rus-set-up-officials-for-the-counting-list-inv-5.md)

[(RUS) Inventory journal report table (form)](https://technet.microsoft.com/en-us/library/jj839654\(v=ax.60\))

  


