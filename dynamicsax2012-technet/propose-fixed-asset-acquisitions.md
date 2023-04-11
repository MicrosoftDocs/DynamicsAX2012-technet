---
title: Propose fixed asset acquisitions
TOCTitle: Propose fixed asset acquisitions
ms:assetid: 0fba6545-ca29-4666-a26c-eb97706806b6
ms:mtpsurl: https://technet.microsoft.com/library/Dn479032(v=AX.60)
ms:contentKeyID: 59632400
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- acquisition
- propose
- propose acquisition
audience: Application User
ms.search.region: Global
---

# Propose fixed asset acquisitions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how acquisition batch proposals work and explains how to create acquisition proposals for fixed assets.

You can create fixed assets from Inventory management, purchase receipts, and vendor invoices. You can also set up the integration between Fixed assets and Accounts payable to automatically create fixed assets from purchase orders or vendor invoices, or to automatically post acquisition transactions for fixed assets. If you don’t automatically create acquisition transactions when you post a vendor invoice, you can create acquisition transactions through acquisition proposals. Acquisition proposals are usually created during the initial setup of the Fixed assets module.

When you propose acquisitions, the acquisition transactions (journal lines) are created. However, the transactions are not yet posted, so you can review them and then post them.

You can create acquisition transactions for fixed assets in the following ways:

  - From the **Acquisition proposal** form. (Click **Fixed assets** \> **Journals** \> **Fixed assets**. Click **Lines**, and then click **Proposals** \> **Acquisition proposal**.)

  - From the **Create acquisition or depreciation proposals for fixed assets** form. (Click **Fixed assets** \> **Periodic** \> **Create fixed assets proposals**.)
    
    When you create acquisition transactions from this form and you select the batch option, you can still use Microsoft Dynamics AX to complete other tasks when the batch is processing.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



## Propose acquisition transactions in batches

Use the **Acquisition proposal** form to create acquisition transactions for a fixed asset or fixed asset group that you select in the query. The fields in the form might change, depending on the selections you make in the query form. The lines have a **Not yet acquired** status, an acquisition date, an acquisition price based on the value model that you selected, and the **Acquisition** transaction type.

To create and later post acquisition transactions for fixed assets, follow these steps:

1.  Click **Fixed assets** \> **Periodic** \> **Create fixed assets proposals**.

2.  In the **Create acquisition or depreciation proposals for fixed assets** form, select the posting layer that the proposal is based on.

3.  In the **Name of journal** field, select the journal where the acquisition transaction lines will be created.

4.  Click **Proposals** and select **Acquisition proposal**.

5.  Click **Select** to create a query to limit and sort the data to include in the proposal.
    
    The following information is displayed:
    
      - The **Fixed asset number** and **Fixed asset number** fields display the fixed asset number and the fixed asset group that the proposal is based on.
    
      - The **Value model** field displays the fixed asset value model information that the proposal is based on.
    
      - The **Status** field displays the asset status that the proposal is based on.

6.  To create acquisition transactions as a batch process, click **Batch** and select the **Batch processing** check box. For more information, see [Create a batch job](create-a-batch-job.md).
    

    > [!WARNING]
    > <P>If you click the <STRONG>Recurrence</STRONG> button, new proposals are not created. Acquisition proposals can’t be set up as recurring batches.</P>



7.  Click **OK** to create the acquisition transactions.
    
    The acquisition proposal creates up to 10,000 asset book entries in one journal.

8.  Review the asset book entries that were created. Click **Fixed assets** \> **Journals** \> **Fixed assets**. Select the journal that was created in the previous step, and then click **Lines**.

  


