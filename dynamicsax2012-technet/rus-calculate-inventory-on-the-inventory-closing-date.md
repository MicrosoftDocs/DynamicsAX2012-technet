---
title: (RUS) Calculate inventory on the inventory closing date
TOCTitle: (RUS) Calculate inventory on the inventory closing date
ms:assetid: 7fbba664-b1f3-4fa5-be85-01e87920dcaa
ms:mtpsurl: https://technet.microsoft.com/library/JJ733246(v=AX.60)
ms:contentKeyID: 49685213
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate inventory on the inventory closing date 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Calculation on-hand inventory on date** form to calculate and save the on-hand inventory data by dimensions on a specified date of closing. Inventory calculation on the specified inventory closing date generates item remainders by dimensions combinations. To generate the Inventory balance turnover report efficiently, you must calculate the inventory. The calculation of the inventory collects data for the inventory balance turnover on the closing date.

1.  Click **Inventory management** \> **Periodic** \> **Closing and adjustment**.

2.  Click **Close procedure** \> **3. Close** to open the **Close inventory** form.

3.  Click **OK** to close the inventory for the previous period.
    

    > [!NOTE]
    > <P>You can select the <STRONG>Run recalculation after closing</STRONG> check box to perform an inventory recalculation that uses the same parameters that are used to close the inventory. For more information, see <A href="run-inventory-close.md">Run inventory close</A>.</P>



4.  Close the form.

5.  Click **Inventory management** \> **Periodic** \> **On-hand inventory on date**.

6.  In the **Date of on-hand calculation** field, select the date for on-hand inventory calculation. This date must be equal to the inventory closing date that is specified in the **Close inventory** form.
    

    > [!NOTE]
    > <P>In the <STRONG>Closing and adjustment</STRONG> form, on the <STRONG>Session</STRONG> tab, select the <STRONG>Calculation on-hand inventory on date</STRONG> check box to make sure that on-hand inventory is calculated on the inventory closing date.</P>



7.  Click **OK** to calculate the on-hand inventory on the inventory closing date and to close the calculation in the **On-hand inventory on date** form.

  


