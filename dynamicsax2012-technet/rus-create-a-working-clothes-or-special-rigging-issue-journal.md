---
title: (RUS) Create a working clothes or special rigging issue journal
TOCTitle: (RUS) Create a working clothes or special rigging issue journal
ms:assetid: 0dba9c82-1c83-401d-9620-6a77a92554f6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ911233(v=AX.60)
ms:contentKeyID: 52075348
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Russia
- special rigging
- issue journal
- working clothes
---

# (RUS) Create a working clothes or special rigging issue journal [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Working clothes/Special rigging/NVFA issue** form to issue an item from the warehouse to an employee. Working clothes, special rigging items, and not valuable fixed assets (NVFAs) are separate assets. When an issue journal is posted, separate cards are created in the **Working clothes**, **Special rigging**, and **Not valuable FAs** forms.

When new working clothes or special rigging items are issued, the following actions occur:

  - A working clothes or special rigging card is created for each journal line, and the lines are updated in the **Working clothes** or **Special rigging** form.

  - The fixed asset (FA) number for the asset is generated based on the number sequence that is specified in the **Fixed asset parameters** form.

  - The quantity of the working clothes or special rigging item is equal to the item quantity that is specified on the journal line. In the **Componentry** form, the quantity of the corresponding item is updated to 1 for each asset that is created.

  - The value models and depreciation group are also updated in the cards. If you select the **Service life by rate** check box in the **FA value models** form, the wearing period, or usage, is determined based on the depreciation groups. If the **Service life by rate** check box is cleared, the wearing period is selected from the issued journal line. The cost is the same for all value models and is selected from the cost price of this item line.

  - The status of the asset is updated to **Scheduled**. Additionally, the acquisition date is updated with the date of the journal transaction, and the acquisition amount is updated with the cost price that is posted for the item line.

When a used working clothes or special rigging card is issued, if the serial number of the card for the issued item has already been filled in the inventory transaction that corresponds to the posted journal line, the following actions occur:

  - The issue journal that was created earlier is searched and copied by using the serial number inventory dimension.

  - The cost price is selected from the item cost price for the base value model.

  - The useful life is updated for the working clothes or special rigging item.

  - The residual wearing or usage period is calculated by subtracting the past lifetime from the lifetime by rate.


> [!NOTE]
> <P>For an issue or reissue transaction, when the journal is posted, fixed asset journals are created and posted automatically. These fixed asset journals contain transactions for putting the asset into operation, depreciation transactions, and write-off transactions.</P>



1.  Click **Fixed assets (Russia)** \> **Journals** \> **Working clothes/Special rigging/NVFA issue**.

2.  Create a new journal. In the **Date** field, select the transaction date.

3.  In the **Acquisition** field, select the fixed asset journal that is used for acquisition transactions.

4.  In the **Depreciation** field, select the fixed asset journal that is used for depreciation transactions.

5.  In the **Warehouse** field, select the warehouse for the transaction.

6.  In the **Person in charge** field, select the identification code of the employee to whom the asset is issued.

7.  In the **Location** field, select the location of the asset.

8.  Click **Lines**.

9.  Create a new journal line. In the **Item** field, select the item code.

10. In the **Quantity** field, enter the item quantity.

11. In the **Type of rate** field, select the type of issue rate for the item.

12. In the **Resource** field, select the resource or resource group that is assigned to the item.
    

    > [!NOTE]
    > <P>The <STRONG>Lifetime</STRONG> field is updated with the useful life of the item for the selected combination of the following: item number, type of rate in the priority unit of the organization unit, job title, and type of work of the employee.</P>



13. On the **Product dimensions** tab, in the **Warehouse** field, select the warehouse where the item is located.

14. In the **Inventory profile** field, select the inventory profile for the item.

15. In the **Batch number** field, select the batch number of the item.

16. In the **Serial number** field, select the serial number of the item.

17. Close the form.

18. In the **Working clothes/Special rigging/NVFA issue journal** form, click **Validate** to validate the journal.

19. Click **FA journals** \> **FA journal (putting into operation)** to put the asset into operation.
    
    –or–
    
    Click **FA journals** \> **FA journal (depreciation)** to depreciate the asset.

20. Click **Close** to post the journal.

To reverse the issue of the working clothes or special rigging item, in the **Working clothes/Special rigging/NVFA issue journal** form, click **Cancel issue**.

## See also

[(RUS) Working clothes/Special rigging/NVFA issue journal (form)](https://technet.microsoft.com/en-us/library/jj911489\(v=ax.60\))

[(RUS) Working clothes/Special rigging/NVFA issue journal lines (form)](https://technet.microsoft.com/en-us/library/jj923266\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

