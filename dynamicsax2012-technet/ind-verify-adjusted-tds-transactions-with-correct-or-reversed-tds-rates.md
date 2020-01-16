---
title: (IND) Verify adjusted TDS transactions with correct or reversed TDS rates
TOCTitle: (IND) Verify adjusted TDS transactions with correct or reversed TDS rates
ms:assetid: d7d0ba34-e759-479a-a6f0-209f313719f5
ms:mtpsurl: https://technet.microsoft.com/library/JJ664927(v=AX.60)
ms:contentKeyID: 49386256
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Verify adjusted TDS transactions with correct or reversed TDS rates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can verify adjusted TDS transactions with correct or reversed TDS rates.

1.  Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**.

2.  Select a vendor account, on the **Vendor** tab, click **Transactions**. The transaction lines with the debit and credit amounts are posted on the original transaction date.

3.  Select the transaction line that contains the adjusted credit amount and then click the **General** tab. The transaction status for the credit amount is displayed as **Adjusted** in the **Transaction status** field.

4.  Click the **Overview** tab, and then select the transaction line that contains the adjusted debit amount. The invoice or payment amount, the TDS amount, and the balance amount in the current currency are shown in the **Amount origin**, **TDS**, and **Amount** fields.

5.  Click the **General** tab. The transaction status of the debit amount is displayed as **Adjusted** in the **Transaction status** field.

6.  To view the results of the transaction, click **Voucher** to open the **Voucher transactions** form, and then click **Posted withholding tax** to open the **Withholding tax transactions** form.

7.  Close the **Withholding tax transactions** form and the **Voucher transactions** form.

8.  In the **Vendor transactions** form, select the transaction line that contains the posted credit amount and then click the **General** tab. The transaction status of the credit amount is displayed as **Posted** in the **Transaction status** field.

9.  Click **Voucher** to open the **Voucher transactions** form and view the posted voucher.

10. Close the forms.

  


