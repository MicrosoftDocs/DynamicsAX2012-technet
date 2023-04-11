---
title: (ITA) Calculate fiscal LIFO journal lines
TOCTitle: (ITA) Calculate fiscal LIFO journal lines
ms:assetid: 254ad970-adaf-4205-b4d8-0a1f98e365ab
ms:mtpsurl: https://technet.microsoft.com/library/Aa496817(v=AX.60)
ms:contentKeyID: 36056192
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- calculate fiscal LIFO
- fiscal LIFO
audience: Application User
ms.search.region: Italy
---

# (ITA) Calculate fiscal LIFO journal lines 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

1.  Click **Inventory management** \> **Journals** \> **Fiscal LIFO** \> **Fiscal lifo internal**.

2.  Select a journal line, and then click the **General** tab.

3.  In the **End date** field, enter the ending date of the period that the report should cover. The **Start date** field is automatically updated with a date one year before the ending date.

4.  To include work in progress (WIP) in the report, select the **Include work in progress** check box.

5.  To use the normal value as the basis for the calculation, select the **Use normal value** check box.

6.  Click **Calculate lines** to open the **Fiscal LIFO calculation engine - Internal** form, where you can verify your selections, and then click **OK**.

WIP is not calculated if no quantity has been received into the warehouse, even though you define in the journal that you want to calculate WIP. If, for example, a production has been started and EUR 10,000 has been posted, but nothing has been reported as finished, the WIP value is not included in the calculation of the inventory value.


> [!NOTE]
> <P>If you do not select the <STRONG>Use normal value</STRONG> check box, the normal value is not calculated, even though the journal lines include items where you have requested either manual or automatic calculation of normal value.</P>



## Calculation of normal value and WIP

To apply normal value or include work in progress (WIP) in the calculation of the inventory value, you must set up the normal value and the WIP calculation before you process your journal lines.

## Set up normal value calculation

1.  Click **Inventory management** \> **Setup** \> **Inventory** \> **Fiscal LIFO reporting group**.

2.  In the **Fiscal LIFO reporting group** form, select the **Normal value calculation** field.

3.  Select one of the following options:
    
      - **Never** – Normal value is never calculated for this group.
    
      - **Automatic** – If the deviation percent stated in the **Deviation percent** field in the **Inventory and warehouse management parameters** form is exceeded, normal value is applied. The deviation percent is the percentage that the value calculated for the period exceeds the average value of the items. You select the calculation period in the **Calculation period** field in the **Inventory and warehouse management parameters** form.
    
      - **Manual** – The normal value entered in the **Normal value** field is applied as the value of the items for the current year and for all previous years.


> [!NOTE]
> <P>To apply the normal value for individual items, you can select these options on the <STRONG>Manage costs</STRONG> tab in the <STRONG>Released product details</STRONG> form.</P>



## Set up WIP calculation

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  On the **General** tab, select the **Fiscal LIFO WIP period** field and enter the number of days. The number of days determines how long the production period can be before the work in progress value of a production is included as part of the inventory value.


> [!NOTE]
> <P>If the period between the scheduled start and finish dates of a production is longer than the fiscal LIFO WIP period, WIP is included as part of the inventory value. If this period is shorter than the fiscal LIFO WIP period, WIP is not included. You enter the fiscal LIFO WIP period in the <STRONG>Fiscal LIFO WIP period</STRONG> field.</P>



## View fiscal LIFO journal lines

  - In the **Fiscal lifo internal** or the **Fiscal LIFO annual municipal report** form, click **Lines**.

## Delete fiscal LIFO journal lines

  - In the **Fiscal lifo internal** or the **Fiscal LIFO annual municipal report** form, click **Delete lines**.

## See also

[(ITA) Set up fiscal LIFO reporting groups](ita-set-up-fiscal-lifo-reporting-groups.md)

[(ITA) About fiscal LIFO workflow](ita-about-fiscal-lifo-workflow.md)

  


