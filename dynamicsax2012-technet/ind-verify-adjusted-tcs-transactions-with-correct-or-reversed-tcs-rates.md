---
title: (IND) Verify adjusted TCS transactions with correct or reversed TCS rates
TOCTitle: (IND) Verify adjusted TCS transactions with correct or reversed TCS rates
ms:assetid: 6a2ea039-07ab-4f52-bffa-7292c8442209
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677895(v=AX.60)
ms:contentKeyID: 49385859
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Verify adjusted TCS transactions with correct or reversed TCS rates 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can verify the adjusted Tax collected at source (TCS) transactions with correct or reversed TCS rates.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**.

2.  Select a customer, and on the **Customer** tab, click **Transactions**.

3.  On the **Customer transactions** form, select the transaction line that contains the adjusted credit amount, and then click the **General** tab. The transaction status of the credit amount is displayed as **Adjusted** in the **Transaction status** field.

4.  Click the **Overview** tab and select the transaction line that contains the adjusted debit amount. The invoice or payment amount, the TCS amount, and the balance amount in the current currency are shown in the **Amount origin**, **TCS**, and **Amount** fields.

5.  Click the **General** tab. The transaction status of the debit amount is displayed as **Adjusted** in the **Transaction status** field.

6.  To view the results of the transaction, click **Voucher** to open the **Voucher transactions** form, and then click **Posted withholding tax** to open the **Withholding tax transactions** form.

7.  Close the **Withholding tax transactions** form and the **Voucher transactions** form.

8.  In the **Customer transactions** form, select the transaction line that contains the posted credit amount and then click the **General** tab. The transaction status of the credit amount is displayed as **Posted** in the **Transaction status** field.

9.  Click **Voucher** to open the **Voucher transactions** form and view the posted voucher.

10. Close the forms.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

