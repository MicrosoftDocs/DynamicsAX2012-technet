---
title: Set up and run a standard cost conversion
TOCTitle: Set up and run a standard cost conversion
ms:assetid: 260d7aa4-e68d-4125-986c-dd5c42c5a01f
ms:mtpsurl: https://technet.microsoft.com/library/Gg230996(v=AX.60)
ms:contentKeyID: 36056196
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up and run a standard cost conversion 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Perform the following tasks to set up and run a standard cost conversion. It is assumed that you have already completed the prerequisites for a standard cost conversion.

1.  Define a standard cost conversion record and the associated costing version.
    
    Use the **Standard cost conversions** form to create a conversion record. A new conversion record can only be created when existing conversion records have been completed.
    
    The duration of the planned transition period is defined by the transition start date and the planned conversion date. A planned transition period can be as short as a single day. The intended purpose of a planned transition period is to allow for sufficient time to perform the multiple steps in the conversion process. An inventory close must be performed one day before the transition start date so that settlements are completed before starting the conversion process. You can change the transition start date so that it reflects a date occurring one day after an existing inventory close, or perform an inventory close, so that the dates are correctly aligned.
    
    When entering a conversion record, you will also enter a user-defined identifier for a new costing version that will contain the standard costs for converted items. Saving the conversion record information will automatically create the costing version.

2.  Review and change the newly created costing version for the conversion record.
    
    The newly created costing version is dedicated to the conversion record, as reflected in a costing type of conversion. The dedicated costing version behaves like a costing version for standard costs, and it will contain the item cost records for items that are associated with the conversion record. The dedicated costing version for a conversion record has the following characteristics, which should be reviewed and edited as necessary.
    
      - Version identifier − The identifier reflects the information that is entered on the conversion record for the costing version ID.
    
      - Version name − The name is at first blank, and you can optionally enter a name.
    
      - Costing type − Standard cost.
    
      - Block changes − No. You can enter cost records into the costing version until you change the status of the conversion record to **Ready**. A **Ready** status means that the selected items have been checked, and that changes to cost records should not be permitted.
    
      - Activation − No. You cannot manually activate a pending cost record in the dedicated costing version. Activation occurs when you successfully perform the conversion.
    
      - From date − The from date reflects the planned conversion date that is entered on the conversion record.
    
      - Site − Blank. A blank allows cost records to be entered for any site.
    
      - Allowed contents − Only cost records can be entered.
    
      - Fallback principle − Blank. Enter a fallback principle of **Active** when you require cost information that has been activated in other costing versions. For example, the cost information about components, cost categories, and indirect costs may be required to calculate the costs of manufactured items.
    
      - Fall back version − Blank.
    
    Item cost information in the dedicated costing version can only be maintained from the **Standard cost conversions** form. You cannot use the **Costing version setup** form or the **Costing version maintenance** form to calculate costs for the costing version during conversion. These forms can be used to maintain the dedicated costing version after successfully performing the conversion.

3.  Identify the items being converted to standard cost.
    
    Use the **Standard cost conversions** form to identify the individual items that you want to convert to standard cost. You can add multiple items by using the **Add items to standard cost conversion** form. As a general guideline, you should include all manufactured items in a single conversion record so that costs will be correctly calculated.

4.  Enter or calculate the pending standard cost for each item that is being converted.
    
    Use the **Price** form to enter pending standard costs in the dedicated costing version for purchased items and transfer items. Cost records are site-specific, and an item's pending costs must be entered for every site.
    
    Use the **Price** form to calculate pending standard costs for manufactured items. A manufactured item's pending costs should be calculated for every manufacturing site, or manually entered when the site represents a transfer site.
    
    Some items may have product dimension of color, size, or configuration. In the **Standard cost conversions** form, the **Use cost price by variant** check box displays the standard cost for every combination of product dimensions. When this check box is cleared, you only must enter a pending cost for the item.

5.  Check and resolve any issues for the items that are being converted.
    
    Use the **Standard cost conversion checks** report to identify issues for the items that are being converted. When an item does not have an issue, its status in the conversion record is changed to **Checked**. When an item has an issue, you must resolve the issue and then run the report again until its status is changed to **Checked**. When you cannot resolve an item's issues in a timely manner, you can optionally delete the item from the conversion record and convert the item at a future time.

6.  Change the status of the conversion record to **Ready**.
    
    Changing the status of the conversion record to **Ready** performs a final check before it runs a standard cost conversion. The status will only change to **Ready** when the following conditions have been met:
    
      - Each item in the conversion record has a status of **Checked**.
    
      - An inventory close must have been performed on a date that is one day before the transition start date. You can change the transition start date, or perform an inventory close, to align the dates correctly.

7.  Perform a backup of the database before conversion.
    
    The backup lets you restore the database if errors are encountered in the conversion process.

8.  Perform the conversion process when the conversion record has a **Ready** status.
    
    The conversion process requires that an inventory close be performed on a date that is one day before the planned conversion date. This step makes sure that back-dated transactions cannot be entered in the transition period. If an inventory close has not yet been performed, the system asks if you want to perform one as part of the conversion process.
    
    The conversion process proceeds with one item at a time, starting with the items lowest in a product structure (based on the item's low-level code). After successful conversion of an item, the item's status in the conversion record changes to **Converted**. If the conversion process is interrupted, items that have not been successfully converted will still have a status of **Checked**.
    
    Successful completion of the conversion process has the following impacts.
    
      - The status of the conversion record changes from **Ready** to **Completed**, and the status of each selected item changes from **Checked** to **Converted**.
    
      - The item model group for converted items has been changed so that it reflects a new group that has a standard cost inventory model.
    
      - The standard costs for converted items have been enabled in the dedicated costing version.
    
      - The costing type of the costing version changes from conversion to standard cost, and the costing version now acts just like any other costing version for standard costs.

9.  Validate and reconcile the inventory values for the converted items.
    
      - Analyze revaluation variances. Use the **Variance analysis statement** report to view inventory revaluation variances for the converted items. You can also use the **Standard cost transactions** form to view the inventory revaluation transactions for the converted items with inventory.
    
      - Analyze inventory value before the transition start date. Use the **Inventory value by inventory dimension** report to view inventory values for the converted items, with an As on date that reflects one day before the transition start date.
    
      - Analyze inventory value before the conversion date. Use the **Inventory value by inventory dimension** report to view inventory values for the converted items, with an As on date that reflects one day before the conversion date.
    
      - Analyze inventory value at the conversion date. Use the **Type of the amount** report to view inventory value as of the conversion date. Use the report option for from and to dates, so that they both match the conversion date. The report selection criteria should reflect the converted items.
    
      - Analyze backdated inventory movements. Use the **Type of the amount** report to view backdated inventory movements that were entered after the conversion. Use the report option for from and to dates, so that they correspond to the transition start date and the conversion date, minus one day. The report selection criteria should reflect the converted items. The report displays inventory movements made at standard cost during the transition period.

## See also

[About inventory close](about-inventory-close.md)

[About standard cost conversion](about-standard-cost-conversion.md)

[About prerequisites for a standard cost conversion](about-prerequisites-for-a-standard-cost-conversion.md)

  


