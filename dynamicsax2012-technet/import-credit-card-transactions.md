---
title: Import credit card transactions
TOCTitle: Import credit card transactions
ms:assetid: 124fcf5e-85ce-4ea9-ab14-401e0f17d263
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg230932(v=AX.60)
ms:contentKeyID: 36811395
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Import credit card transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up credit card transactions to be imported automatically on a recurring schedule, or you can manually import the transactions as required. After you import the transactions, you can view any errors in the **Exceptions** form.

## Automatically import credit card transactions

1.  Click **Travel and expense** \> **Periodic** \> **Credit cards** \> **Credit card import from folder**.

2.  On the **General** tab, in the **Directory** field, locate the folder where the credit card transactions are stored.

3.  In the **Format** field, select a format for the folder name.

4.  On the **Batch** tab, click **Recurrence** to define how frequently credit card transactions should be imported, and then click **OK**.

5.  Click **Alerts** to define notifications to send when the status changes for a batch job.

6.  Click **OK** to import the transactions.


> [!NOTE]
> <P>Microsoft Dynamics AX imports transactions in one format per batch job. If you have more than one format to import, you must create separate batch jobs and separate folders to store the credit card transaction data. There should be at least one folder for each format type. If you do not create separate folders, Microsoft Dynamics AX imports all data in the same format. This can cause errors and unprocessed data.</P>



## Manually import credit card transactions

1.  Click **Travel and expense** \> **Periodic** \> **Credit cards** \> **Import a specific credit card file**.

2.  In the **Directory** field, locate and select the folder where the credit card transactions are stored, and then click **OK**.

## View import errors

1.  Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **Exceptions**.

2.  In the **Exceptions** form, on the **Overview** tab, select the exception record. If a resolution is offered, click **Resolve exception**.

3.  Click **Exception help** to see more information about the exception.

  


