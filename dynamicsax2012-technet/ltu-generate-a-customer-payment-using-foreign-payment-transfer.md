---
title: (LTU) Generate a customer payment using Foreign Payment Transfer
TOCTitle: (LTU) Generate a customer payment using Foreign Payment Transfer
ms:assetid: 4ddcb34f-e08d-4509-b859-c13523654ec7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ665074(v=AX.60)
ms:contentKeyID: 49386656
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Lithuania
---

# (LTU) Generate a customer payment using Foreign Payment Transfer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The Lithuanian market began using LITAS, the unified electronic banking system, in 2005. LITAS is the unified file format used to export foreign customer payments from the company accounting system to the banking system.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Press CTRL+N to create a new journal, and enter the required details.

3.  Click **Lines**, and then create payment journal lines or select open transactions to settle.

4.  Enter the required details.

5.  In the **Method of payment** field, select the method of payment for the current payment.

6.  In the **Debit** field, enter the debit amount in the given currency.
    

    > [!NOTE]
    > <P>If sufficient funds are not available in the currency indicated in the payment order, the deficient amount must be converted from the selected currency.</P>



7.  Click the **Payment** tab.

8.  In the **Payment purpose** field, enter the purpose of the payment.

9.  In the **Payment priority** field, select the payment priority.

10. In the **Foreign bank fee** field, select the appropriate fee type.

11. Select the **Inform by telex** check box, if the payment must be announced by telex.

12. Select the **Inform by phone** check box, if the payment must be announced by phone.

13. Click **Functions** \> **Generate payments** to open the **Generate payments** form.

14. Click **Payment method,** and then in the **Method of payment** field, select the customer method of payment or click **Export format,** and then in the **Export format** field, select the format for export of the payments.

15. In the **Bank account** field, select the bank account number.

16. Check the **Show format dialog** checkbox to review the payment format before generating payments.

17. Click **Select** to specify details for the journal lines.

18. Click **Dialog,** and then in the **File name** field, select the file path and name.

19. Click **OK** to return to the **Generate payments** form.

20. In the **Generate payments** form, click **OK** to generate the payment transfer.

## See also

[(LTU) Customer payment journal lines (modified form)](https://technet.microsoft.com/en-us/library/jj665039\(v=ax.60\))

[(LTU) Generate a vendor payment using Foreign Payment Transfer](ltu-generate-a-vendor-payment-using-foreign-payment-transfer.md)

  


