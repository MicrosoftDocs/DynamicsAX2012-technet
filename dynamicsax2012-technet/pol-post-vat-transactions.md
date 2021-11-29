---
title: (POL) Post VAT transactions
TOCTitle: (POL) Post VAT transactions
ms:assetid: c9fb7fd6-c7b8-43ec-a81f-0df9829fdadf
ms:mtpsurl: https://technet.microsoft.com/library/JJ711267(v=AX.60)
ms:contentKeyID: 49387085
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Post VAT transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Click **New**, and then, in the **Name** field, select the journal to which the value-added tax (VAT) receivable transaction is posted.
    

    > [!NOTE]
    > <P>For a VAT payable transaction, select the name of the journal to which the payable transaction is posted, and then click <STRONG>Post</STRONG> &gt; <STRONG>Post</STRONG>.</P>



3.  Click **Lines**, and then, in the **Journal voucher** form, on the **Overview** tab, in the **Account type** field, select **Customer**.

4.  In the **Account** field, select the customer account to which the VAT receivable transaction is posted.

5.  On the **General** tab, in the **Offset account** field group, select the offset account type and the offset account for the transaction.

6.  In the **Amount** field group, in the **Credit** field, enter the transaction amount.

7.  Enter any remaining information about the VAT transaction on the **General** tab.

8.  Click **Functions** \> **Settlement**, and then, in the **Settle open transactions** form, on the **Overview** tab, select the **Mark** check box for each transaction that is ready for settlement. Close the form.

9.  In the **Journal voucher** form, click **Post** \> **Post** to post the journal.

  


