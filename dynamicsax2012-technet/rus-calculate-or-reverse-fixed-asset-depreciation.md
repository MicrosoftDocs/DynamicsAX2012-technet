---
title: (RUS) Calculate or reverse fixed asset depreciation
TOCTitle: (RUS) Calculate or reverse fixed asset depreciation
ms:assetid: e8a7f904-27d8-4973-92f7-6d4d5f03e9b3
ms:mtpsurl: https://technet.microsoft.com/library/JJ711730(v=AX.60)
ms:contentKeyID: 49388053
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Calculate or reverse fixed asset depreciation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Use the following procedures to calculate or reverse a fixed asset depreciation.

## Calculate fixed asset depreciation

1.  Click **Fixed assets (Russia)** \> **Journals** \> **FA journal**.

2.  On the **Overview** tab, press CTRL+N to create a new journal.

3.  In the **Name** field, select a journal name.

4.  In the **Description** field, view or modify the description of the journal.

5.  Click **Lines** to open the **Journal voucher** form.

6.  On the **Overview** tab, press CTRL+N to open the **Add to journal** form to create a single depreciation transaction for one fixed asset.
    

    > [!NOTE]
    > <P>Click <STRONG>Group operations</STRONG> &gt; <STRONG>Depreciation</STRONG> to create depreciation transactions for several fixed assets.</P>



7.  In the **Transaction date** field, select the date of the next calculation period. If no depreciation was calculated for the previous periods, depreciation transactions are created in the journal for all months prior to the transaction date, excluding the month of the transaction.

8.  In the **Transaction type** field, select **Depreciation**.

9.  In the **FA number** field, select a fixed asset number.

10. In the **Value model** field, select a fixed asset value model. If you do not select a model, transactions for all value models are created in the journal.

11. In the **Reason code** field, select a reason code.

12. In the **Reason comment** field, view or modify the reason for the depreciation transaction.

13. Click **OK**. Depreciation transactions are created in the journal for all value models that you set up in the **Value models** form.

14. Click **Validate** \> **Validate** to validate the transaction details.

15. Click **Post** \> **Post** to post the journal. Fixed asset and ledger transactions are created.

## Reverse fixed asset depreciation

1.  Click **Fixed assets (Russia)** \> **Journals** \> **FA journal**.

2.  On the **Overview** tab, press CTRL+N to create a new journal.

3.  In the **Name** field, select a journal name.

4.  In the **Description** field, view or modify the description of the journal.

5.  Click **Lines** to open the **Journal voucher** form.

6.  Click **Group operations** \> **Storno of depreciation** to open the **Storno of depreciation** form.

7.  In the **Date of storno** field, select a date for the depreciation reversal.

8.  In the **Accounting** field, select a fixed asset value model.

9.  Click **OK**. Depreciation reversal transactions are created in the journal.

10. Click **Validate** \> **Validate** to validate the transaction details.

11. Click **Post** \> **Post** to post the journal. The fixed asset depreciation transaction is reversed and the ledger transaction is updated accordingly.

  


