---
title: Transfer fixed assets
TOCTitle: Transfer fixed assets
ms:assetid: c3fcf60b-b1ad-42fb-b96b-ac623d9b7f4b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242839(v=AX.60)
ms:contentKeyID: 36059291
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- fixed assets
- asset
- fixed asset
- fixed asset transfer
- assets
- Menu_Items.Action.AssetTransferMass
audience: Application User
ms.search.region: Global
---

# Transfer fixed assets 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to transfer the financial information for a fixed asset when the ownership of or the responsibility for that asset changes. In Microsoft Dynamics AX, a transfer involves changing the financial dimension values for one more of the value models that are associated with the asset. Therefore, although it is commonly referred to as transferring a fixed asset, it is more accurate to say that you’re transferring the value models that are associated with the fixed asset.

You can transfer all the value models that are associated with a fixed asset, or you can select specific value models, such as those that are associated with a posting layer. In either case, the transfer does not change the association between the asset and the value models. The transfer changes only the financial dimensions that are associated with the selected value models.

For example, the financial dimension values for the equipment that is used to maintain your organization’s vehicles include CostCenter, Division, and Department. To transfer a hydraulic lift from the Maintenance department to the Transportation department, you select the appropriate value models. You then enter the existing financial dimension values for CostCenter and Division as the transfer-to dimension values. For the Department dimension, you enter Transportation as the new dimension value.


> [!NOTE]
> <P>The procedure for completing this task changed for cumulative update 7 or later for Microsoft Dynamics AX 2012 R2. The updated procedure also applies to AX 2012 R3. For more information, see the section later in this topic.</P>



## Considerations

When transferring fixed assets, keep in mind the following considerations:

  - When you transfer the value models that are associated with a fixed asset, accounting transactions are created. Therefore, if the main account is suspended for the financial dimensions that you are transferring to or transferring from, the value models can’t be transferred. For more information, see [Main accounts - chart of accounts (form)](https://technet.microsoft.com/en-us/library/hh209695\(v=ax.60\)).

  - A transfer must create a combination of financial dimension values that is valid according to the advanced rule structures for the chart of accounts.

  - You can transfer only value models that have an **Open** status. You can’t transfer value models for a fixed asset that has not yet been acquired, or that has been sold or scrapped, suspended, closed, or transferred to a low-value pool.

  - You can use the **Value models** form to view or change the status of a value model. To do this, select the fixed asset on the **Fixed assets** list page, and then, on the **Action Pane**, click **Value models**. You can view or change the value in the **Status** field. For more information, see [Value models (form)](https://technet.microsoft.com/en-us/library/aa590830\(v=ax.60\)).

  - When you transfer a fixed asset by using the procedures in this topic, a record of the transfer is created. If you do not need a record of the transfer, you can use the **Value models** form to update the default financial dimensions of the fixed asset. When you do this, a transfer entry is not created or displayed on the **Fixed asset transfer history** form. For more information, see [Value models (form)](https://technet.microsoft.com/en-us/library/aa590830\(v=ax.60\)) and [Fixed assets transfer history (form)](https://technet.microsoft.com/en-us/library/hh227638\(v=ax.60\)).

  - You can reverse the most recent transfer of a fixed asset, although you can’t reverse a transfer that has already been reversed. For more information, see [Reverse a transaction](reverse-a-transaction.md).


> [!WARNING]
> <P>The complete set of financial dimension values changes when a transfer occurs. In the earlier example, if you entered Transportation for the Department value and left CostCenter and Division blank, and if your account structure allowed blank values for CostCenter and Department, the transfer would result in each value model having the new value for Department and a blank value for Division and CostCenter.</P>



## Transfer a fixed asset in cumulative update 6 or an earlier update for Microsoft Dynamics AX 2012

If you are using cumulative update 6 or earlier, you can transfer one fixed asset at a time. The asset must have at least one value model that has an **Open** status.

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select the fixed asset to transfer.

3.  On the **Action Pane**, click the **Transfer fixed asset** button to open the **Fixed asset transfer** form.
    
    If you selected an asset that does not have a value model that has an **Open** status, the form is empty.

4.  On the **Value models** tab, select the value models to include in the transfer.
    
      - Select a single value model if you want to select different financial dimension values for each value model.
    
      - Select multiple value models if you want the financial dimension values to be the same for the selected value models.
    
    To review the current financial dimension values for a value model, select the value model, and then click the **Financial dimensions** tab.

5.  In the **Transfer date** field, enter the date to use for the accounting transaction that is created for the transfer. You can enter any date in the current fiscal year.

6.  In the **Transfer to financial dimensions** field group, select the financial dimension values that the fixed asset will be transferred to.

7.  If the **Public Sector** configuration key is selected, select a transfer-from account and a transfer-to account. These are the main accounts in the general ledger that the fixed asset is being transferred between. The transfer-from account will have a debit entry, and the transfer-to account will have a credit entry. The two accounts must balance if the **Require the dimension to be balanced** check box is selected for the dimensions in the **Financial dimensions** form.

8.  Optional: In the **Transfer comments** field, enter comments about the transfer.

9.  Click **OK**.

10. In the confirmation form, verify that the values are correct, and then click **Transfer** to complete the transfer. For more information, see [Fixed asset transfer confirmation (form)](https://technet.microsoft.com/en-us/library/hh209459\(v=ax.60\)).

## Transfer up to 100 fixed assets at a time in Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2

If you are usingMicrosoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you can transfer up to 100 fixed assets at a time from the **Fixed assets** list page.


> [!NOTE]
> <P>Your system may have been configured to allow more or fewer than 100 assets to be transferred from the <STRONG>Fixed assets</STRONG> list page. If you need additional information about the system configuration, contact a system administrator.</P>



1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select one or more fixed assets to transfer.

3.  On the **Action Pane**, click **Transfer fixed assets**.
    
    Any value model that doesn’t have an **Open** status can’t be transferred and won’t be shown in the **Transfer fixed assets** form.

4.  Select the value models to transfer. For each value model, review the values in the **Transfer from financial dimensions** fields.

5.  In the **Transfer to financial dimensions** field group, select the financial dimension values that the selected value models will be transferred to.

6.  If the **Public Sector** configuration key is selected, select a transfer-from account and a transfer-to account. These are the main accounts in the general ledger that the fixed assets are being transferred between. The transfer-from account will have a debit entry, and the transfer-to account will have a credit entry. The two accounts must balance if the **Require the dimension to be balanced** check box is selected for the dimensions in the **Financial dimensions** form.

7.  In the **Transfer date** field, enter the date to use for the accounting transactions that will be created for the transfer. You can enter any date in the current fiscal year.

8.  Optional: In the **Transfer comments** field, enter comments about the transfer.

9.  When you have entered the necessary information for the fixed assets that you are transferring, click **OK**.

10. In the confirmation form, verify that the values are correct, and then click **Transfer** to complete the transfers. For more information, see [Fixed asset transfer confirmation (form)](https://technet.microsoft.com/en-us/library/hh209459\(v=ax.60\)).
    
    If any value model that is listed in the **Transfer fixed assets** form can’t be transferred, none of the selected value models transfer, with one exception: A value model that can’t be transferred because the transfer-from and transfer-to financial dimensions are the same does not prevent other value models from being transferred.

## Use the mass transfer option in Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2

If you are using Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2, you can transfer any number of fixed assets at the same time by using the mass transfer option that is in the **Periodic** section of the **Fixed assets** area page.

When you use this option, you specify query criteria to select the assets to transfer. You can also print a report of the query results before you transfer the assets. You can use the report to make sure that you selected the correct assets. However, because you can select assets that can’t be transferred, and because errors can occur during the transfer, you shouldn’t use the report as an audit or confirmation report.

The mass transfer process automatically divides the assets into groups for processing. These groups are called threads. The number of assets in each thread depends on the system configuration, but about 200 is typical. The use of threads provides better system performance during the transfer. However, if an error occurs as a thread is being processed, no assets in that thread are transferred.

There are other situations that can prevent an asset from being transferred, as well. If an asset has no value models that have an **Open** status, the asset is not transferred. However, this situation does not prevent other assets from being transferred. Similarly, if an asset is being transferred to the same financial dimension values that it is being transferred from, the asset isn’t transferred because it already has the new financial dimension values. No error occurs, and this situation does not prevent other assets from being transferred.

The conditions in the following list cause errors during transfer. If an error occurs in a thread, no assets in that thread are transferred. However, an error in one thread does not prevent assets in other threads from being transferred.

  - A database error occurs.

  - The main account is suspended for the financial dimensions that you are transferring to or transferring from.

  - The transfer would create a combination of financial dimension values that is not valid according to the advanced rule structures for the chart of accounts.

  - The transfer uses blank values for financial dimensions that are not configured to allow blanks according to the chart of accounts.

For example, you select 1,000 assets for transfer, and the system divides the selected assets into five threads of 200 assets. All the assets that are in four of the threads transfer without encountering errors. Two assets in thread 5 can’t be transferred because the main account for the transfer-from financial dimensions is suspended. As a result, no assets in thread 5 are transferred. At the end of the batch process, 800 of the selected assets have been transferred, and 200 have not been transferred.

1.  Click **Fixed assets** \> **Periodic** \> **Mass transfer**.

2.  If the **Public Sector** configuration key is selected, select a transfer-from account and a transfer-to account. These are the main accounts in the general ledger that the fixed asset is being transferred between. The transfer-from account will have a debit entry, and the transfer-to account will have a credit entry. The two accounts must balance if the **Require the dimension to be balanced** check box is selected for the dimensions in the **Financial dimensions** form.

3.  In the **Transfer date** field, enter the date to use for the accounting transactions that are created for the transfers. You can enter any date in the current fiscal year.

4.  Optional: In the **Transfer comments** field, enter comments about the transfer.

5.  In the **Transfer to financial dimensions** field group, select the financial dimension values that the asset value models will be transferred to.

6.  Click the **Select** button. Enter the criteria to select the asset value models to transfer, and then click **OK**.
    
    To be selected by the query, a value model has to have an **Open** status and meet all the criteria that you specify. For example, you specify fixed asset numbers 180 through 950, and asset group FURN. The query selects the open value models for fixed assets that have a number between 180 and 950 and that are in asset group FURN. Value models for an asset in asset group FURN and that has an asset value number of 155 is not be selected.
    
    To transfer all the assets in asset group FURN and all the assets that have a fixed asset number between 180 and 950, you have to perform two transfers: one for the asset group and another for the fixed asset numbers.

7.  Optional: On the **Batch** tab, schedule the report to be printed or the transfer to be done at a convenient time.

8.  After you set up the selection criteria, take one of the following actions:
    
      - To print a report that lists the assets and value models you selected, select **Print a report of the selected assets**, set the print destination, and then click **OK**.
        
        You can use the report to verify that the query selected the assets and value models that you intend to transfer. However, because you can select assets that can’t be transferred, and because errors can occur during the transfer, you shouldn’t use the report as an audit or confirmation report.
    
      - To transfer the selected assets, select **Transfer the selected value models**, and then click **OK**.

9.  Click **Home** \> **Inquiries** \> **Batch jobs** \> **My batch jobs**.

10. The **Batch job** form includes one line for each thread of the mass transfer job. Select any thread that has a status of **Ended**, and then click **Log**.

11. Review the Infolog message for the thread. If any thread failed, correct the errors described in the message, and then repeat the transfer.

## See also

[Fixed asset records](fixed-asset-records.md)

[Transfer fixed assets (form)](https://technet.microsoft.com/en-us/library/hh209220\(v=ax.60\))

[Fixed assets transfer history (form)](https://technet.microsoft.com/en-us/library/hh227638\(v=ax.60\))

[Financial dimensions (form)](https://technet.microsoft.com/en-us/library/hh209534\(v=ax.60\))

  


