---
title: (LTU) Generate a customer payment using the local payment transfer (LT) export format
TOCTitle: (LTU) Generate a customer payment using the local payment transfer (LT) export format
ms:assetid: c975cc04-39d4-4ff2-b56c-d1e5c1b4339d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665188(v=AX.60)
ms:contentKeyID: 49386769
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (LTU) Generate a customer payment using the local payment transfer (LT) export format 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new journal, and then enter the required details.

3.  Click **Lines** to open the **Journal voucher** form. Create payment journal lines or select open transactions to settle.
    

    > [!NOTE]
    > <P>For more information, see "Create and validate a journal and journal lines" in the Application and Business Process Help.</P>



4.  Enter the required details.

5.  Click the **Payment** tab.

6.  In the **Method of payment** field, select the method of payment with the **Local Payment transfer (LT)** export format.

7.  In the **Payment purpose** field, enter the purpose of the payment.

8.  In the **Payment priority** field, select a value for the payment.

9.  Click **Functions** \> **Generate payments** to open the **Generate payments** form.

10. Click **Payment method,** and then in the **Method of payment** field, select the customer method of payment. Or, click **Export format,** and then in the **Export format** field, select the format for export of payments.

11. In the **Bank account** field, select the bank account number.

12. Check the **Show format dialog** checkbox to review the selected export format before generating payments.

13. Click **Select** to specify details for the journal lines.

14. Click **Dialog** and enter the required details. Click **OK**.

15. In the **Generate payments** form, click **OK** to generate the payment transfer.

## See also

[(LTU) Customer payment journal lines (modified form)](https://technet.microsoft.com/en-us/library/jj665039\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

