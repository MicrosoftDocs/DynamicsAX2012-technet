---
title: (RUS) Create a receipt transaction for the deferral
TOCTitle: (RUS) Create a receipt transaction for the deferral
ms:assetid: c6f4818d-f23b-4730-a31f-42c2ddbd8745
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711588(v=AX.60)
ms:contentKeyID: 49387912
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- receipt
- (RUS)
- Russia
- deferral
audience: Application User
ms.search.region: Russia
---

# (RUS) Create a receipt transaction for the deferral 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Journal voucher** form to create a receipt transaction for a deferral that was manually created. When you post the receipt transaction for the deferral, the status of the deferral is updated to **In process**.

1.  Click **General ledger** \> **Journals** \> **Deferrals journal**.

2.  In the **Name** field, select a journal name, and then click **Lines** to open the **Journal voucher** form.

3.  Press CTRL+N to open the **Create new line** form.

4.  In the **Transaction date** field, select the transaction date.

5.  In the **Transaction type** field, select **Receipt**.

6.  In the **Deferral ID** field, select a deferral to create a receipt transaction for.

7.  In the **Model number** field, select the model number for the deferral.

8.  Click **OK**. Voucher lines are created for the selected deferral in the **Journal voucher** form.

9.  Click **Validate** \> **Validate**, and then click **Post** \> **Post** to validate and post the journal.

10. Click **General ledger** \> **Common** \> **Deferrals**. To view the transaction details in the **Deferrals transactions** form, click **Deferrals models** \> **Transactions**.

## See also

[(RUS) Deferrals models (form)](https://technet.microsoft.com/en-us/library/jj678655\(v=ax.60\))

  


