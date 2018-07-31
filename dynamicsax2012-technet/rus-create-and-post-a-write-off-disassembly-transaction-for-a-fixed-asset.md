---
title: (RUS) Create and post a write-off disassembly transaction for a fixed asset
TOCTitle: (RUS) Create and post a write-off disassembly transaction for a fixed asset
ms:assetid: 7b0b6f32-40cb-488c-9b68-6aa080c2b955
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678385(v=AX.60)
ms:contentKeyID: 49387616
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Create and post a write-off disassembly transaction for a fixed asset 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



A partial liquidation of a fixed asset can result in a change to the original value of the asset.

1.  Click **Fixed assets (Russia)** \> **Journals** \> **FA journal**.

2.  Press CTRL+N to create a new journal and enter the required details.

3.  Click **Lines**, and then click **New** to record the write-off disassembly transaction.

4.  In the **Add to journal** form, in the **Transaction type** field, select **Partial dismantlement**.

5.  In the **Transaction date** field, enter the transaction date.

6.  In the **FA inventory number** field, enter the identification of the fixed asset.

7.  Click **OK**. The lines are created in the journal.
    

    > [!NOTE]
    > <P>You must enter the transaction details for the other value models for this fixed asset manually, since the balance cost disposal transactions, depreciation, depreciated cost, posting components at market value to the warehouse, and profit or loss from a write-off are created automatically in the main and tax value models.</P>



8.  Click **Functions** \> **Show invisible** to display profit and loss.

9.  Click **Validate** \> **Validate** to validate the journal.

10. Click **Post** \> **Post**. Transactions are created in the ledger and fixed asset account, and the item is posted to the warehouse.
    

    > [!NOTE]
    > <P>The partial take-down transaction is displayed in the <STRONG>Partial take-down</STRONG> field group in the <STRONG>FA Balances</STRONG> form. As a result of a partial fixed asset disassembly with a loss, a line in the <STRONG>Deferrals</STRONG> is created if the corresponding depreciated group has been configured.</P>


  


