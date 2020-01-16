---
title: (RUS) Calculate restored VAT and revenue amounts
TOCTitle: (RUS) Calculate restored VAT and revenue amounts
ms:assetid: fed5a4b4-1b50-4b2b-b31e-2cce5c178de7
ms:mtpsurl: https://technet.microsoft.com/library/JJ733515(v=AX.60)
ms:contentKeyID: 49685479
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate restored VAT and revenue amounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use this procedure to calculate restored value-added tax (VAT) amounts and revenue amounts. You can calculate restored VAT amounts by using the following methods:

  - **Mixed** – Facture lines that have direct costs are not multiplied by the coefficient. The VAT amount is calculated based on the proportion of sold quantities to purchased quantities.

  - **By factor** – Facture lines that have direct costs are multiplied by the coefficient, similarly to lines that have indirect costs.

You update a list of incoming invoices to define direct and indirect costs. Based on the sales invoices that are posted, you calculate the total revenue, domestic market revenue, export revenue, tax-exempt revenue, and revenue share on export and tax-exempt operations for the specified period.

Use the **VAT restoring journal** form to create, approve, and cancel a VAT restoring journal to calculate restored VAT and revenue amounts.

1.  Click **Accounts receivable** \> **Periodic** \> **Sales book** \> **VAT restoring journal**.

2.  In the **Date in the period** field, select the date in the reporting period to display the VAT details for.
    

    > [!NOTE]
    > <P>Transactions of both <STRONG>Direct</STRONG> and <STRONG>Indirect</STRONG> expense types are displayed on the <STRONG>VAT restoration</STRONG> tab. Transactions that have a <STRONG>Direct</STRONG> expense type are calculated by using the ratio of purchased item quantities to sold item quantities. Transactions that have an <STRONG>Indirect</STRONG> expense type are calculated by multiplying the export coefficient by the incoming VAT that is processed for the current period.</P>



3.  Click **Restore VAT procedure** \> **1. Update inventory links** to open the **Update inventory links** form.

4.  Click **Select** to open the **Inquiry** form, enter the selection criteria, and then click **OK**.

5.  In the **Update inventory links** form, click **OK** to update details of the inventory transactions for the purchases and sales.

6.  Click **Restore VAT procedure** \> **2. Update the journal** to open the **Update VAT restoring amounts** form.

7.  Select the **Update revenue amounts** check box to update the revenue amount.

8.  Select the **Delete previous calculation** check box to delete previous calculations.

9.  Click **OK** to update the restored VAT amounts for the specified period. You can verify the following updated information:
    
      - In the **VAT restoring journal** form, verify the total revenue, export revenue, domestic market revenue, revenue that is not subject to VAT, and export and tax-exempt percentage.
    
      - On the **VAT distribution** tab, verify the ratio of restored VAT for each export facture. This information is used for VAT declaration and the processing of incoming VAT, if the export is confirmed in the current period. The information is also used if the confirmation term has expired, but the confirmation has not yet been received.
    
      - In the lower pane, on the **Customer invoice lines** tab, verify the line amounts.
    
      - In the upper pane, on the **Revenue calculation** tab, verify the details of the invoice accounts that have the revenue amounts.
    
    You can make any changes that are required in the **VAT restoring journal** form. Then click **Apply changes** to save the changes.

10. Click **Restore VAT procedure** \> **3. Approve the journal** to approve the restored VAT journal.
    

    > [!NOTE]
    > <P>After you approve the journal, the data cannot be modified. The <STRONG>Approved</STRONG> check box is selected.</P>



11. On the **VAT restoration** and **Revenue calculation** tabs, select the **Include** check box for the facture to include in the calculation of restored VAT amounts and revenue amounts.

12. Click **Restore VAT procedure** \> **Cancel approvement of the journal** to cancel the VAT restoration journal that was approved for the processing of outgoing VAT.
    

    > [!NOTE]
    > <P>You can cancel a restored VAT journal only if no outgoing VAT is processed during a specific period.</P>



## More information about how restored VAT amounts and revenue are calculated

You can apply either of these methods to restore a VAT amount to the budget:

  - **Direct** – Use this method if the VAT amount was deducted on the material or asset and is known. The restored VAT amount is calculated by using one of the following formulas:
    
      - In the case of a fixed asset, the VAT amount that was deducted is multiplied by the export, or tax-exempt, coefficient for the current period. The export coefficient is calculated as follows:
        
        (Product output/mileage of object usage in export (tax-exempt activity) in the current period) / (Difference between common Product output/mileage and Product output/mileage of object usage in export (tax-exempt activity) in previous periods)
    
      - In the case of the sale of partial goods, the VAT was deducted as a proportion of the sold quantity to the actual quantity.

  - **Indirect** – Use this method if the reason for the purchase of the materials is not known, and if the VAT amount that was deducted is not known. The restored VAT amount is calculated by using the following formula:
    
    (Incoming VAT on every facture of the current period) \* (Export revenue share of the total revenue of the same period)
    
    If fixed assets were disposed of, or written off, earlier, VAT amounts are restored based on the net book value of the fixed asset. The restored VAT amounts are calculated by using the following formula:
    
    (VAT amount that was accepted earlier to deduction on the fixed asset) \* (Balance of the fixed asset cost on accounting data, excluding the reevaluation amount) / (Original fixed asset cost on accounting data)
    

    > [!NOTE]
    > <P>If the fixed asset is of the <STRONG>Realty</STRONG> type, the VAT amount is restored for a period of 10 years. This period starts from the time of depreciation. The coefficient considers the share of export revenue during the year.</P>



  - The revenue share on export operations is calculated by using the following formula:
    
    Export revenue / Total revenue
    
    Export revenue is the amount that is calculated on export invoices for the period. Total revenue is the amount that is calculated on all invoices for the period.

  - The revenue share on tax-exempt operations is calculated by using the following formula:
    
    Tax-exempt revenue / Total revenue

  - The restored VAT amount for fixed assets is calculated by using the following formula:
    
    (VAT amount that was accepted earlier to deduction on the fixed asset) \* (Balance of the fixed asset cost on accounting data, excluding the reevaluation amount) / (Original fixed asset cost on accounting data)

## Setting up fixed asset parameters to restore VAT amounts

  - Set up fixed asset parameters, fixed asset groups, and fixed asset posting profiles. For more information, see [(RUS) Set up fixed asset parameters](rus-set-up-fixed-asset-parameters.md) and [(RUS) Set up fixed asset posting profiles](rus-set-up-fixed-asset-posting-profiles.md).

  - Set up value models, depreciation methods, and depreciation groups. For more information, see[(RUS) Set up depreciation methods](rus-set-up-depreciation-methods.md), [(RUS) Set up depreciation groups](rus-set-up-depreciation-groups.md).

  - Create an item with an item type of **Fixed asset**. Also, register the fixed asset and put the fixed asset into operation. For more information, see [(RUS) Create and post a budget journal for a fixed asset acquisition](rus-create-and-post-a-budget-journal-for-a-fixed-asset-acquisition.md).

  - Create, post, and update a facture for the purchase order for the item. On the **General** tab, you must specify the estimated output or mileage value in the **Output/mileage** field in the **Fixed assets** form.

  - Create product output or mileage for a fixed asset.

  - Depreciate, and then write off the fixed asset. For more information, see [(RUS) Depreciate fixed assets](rus-depreciate-fixed-assets.md).

  - Process incoming VAT and calculate restored VAT amounts.

  - Process the outgoing VAT for factures that have restored VAT amounts, then close the sales and purchase books. For more information, see [(RUS) Perform an outgoing VAT processing transaction](rus-perform-an-outgoing-vat-processing-transaction.md), [(RUS) Create a sales book](rus-create-a-sales-book.md) and [(RUS) Create a purchase book](rus-create-a-purchase-book.md).

## See also

[(RUS) Settle inventory transactions for restored VAT](rus-settle-inventory-transactions-for-restored-vat.md)

  


