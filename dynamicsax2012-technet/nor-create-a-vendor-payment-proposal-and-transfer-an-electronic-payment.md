---
title: (NOR) Create a vendor payment proposal and transfer an electronic payment
TOCTitle: (NOR) Create a vendor payment proposal and transfer an electronic payment
ms:assetid: 3a94aa32-fa89-494b-a304-13e6ac99b02b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231146(v=AX.60)
ms:contentKeyID: 36056643
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Norway
---

# (NOR) Create a vendor payment proposal and transfer an electronic payment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use this procedure to create vendor invoices, generate vendor payments, and transfer the vendor payments electronically. You can create a payment proposal and generate a payment file that is to be sent to the bank for approval by using the bank's software. After the bank receives the file, the bank will pay the specified invoices and charge your account. The bank sends a return file and indicates whether a payment line is approved or rejected. You can then import the returned file and verify the payment file details. You can also modify the details in the payment file, and then resend the file to the bank for approval.

You can create a separate journal with a corresponding number series for payment proposals, and then create another journal with a different voucher number series for importing and posting payments. These voucher number series should be different from other voucher number series. In certain cases, a vendor might owe you money, or you might owe money to a customer. If a vendor owes you money, you can use the OCR import file format for vendors to generate the payment file.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Create a payment journal, and then click **Lines**.

3.  Click the **Overview** tab, and then click **Payment proposal** \> **Create payment proposal** to create a new payment proposal.

4.  In the **Proposal type** field, select **Per due date**, and then enter the other required details in the form.

5.  Click **OK** to save the details. You can view all the transactions in the **Edit payment proposal** form, based on the criteria from the **Vendor payment proposal** form. Delete any transactions that should not be included in the payment.

6.  In the **Edit payment proposal** form, click **Transfer** to transfer the proposal lines to the **Journal voucher** form in the payment journal.

7.  Click **Functions** \> **Generate payments**. In the **Export format** field, select **Telepay 2.01**.

8.  In the **Generate payments** form, click **Dialog**. In the **File name** field, enter the file name and path to save the payment file that is sent to the bank.
    

    > [!NOTE]
    > <P>When the file is created, the status of the payments is updated as <STRONG>Sent</STRONG> in the <STRONG>Journal voucher</STRONG> form.</P>



9.  Close the form.

10. Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment transfer**.

11. Click **Return file - vendor** to import the return file.

12. In the **Method of payment** field, select the method of payment that has the **Telepay 2.01** return format, and then click **OK**.
    

    > [!NOTE]
    > <P>After the return file is imported, the status of the payment in the <STRONG>Payment status</STRONG> field changes to <STRONG>Approved</STRONG> or <STRONG>Rejected</STRONG>. The status of the payment lines is updated in the <STRONG>Payment journal</STRONG> form.</P>



13. Close the form.

14. Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Modify the details in the payment file, and then resend the file to the bank.

15. Click **Post** \> **Post** to validate and post the approved payment lines in the journal.

## See also

[Vendor payment proposal (class form)](https://technet.microsoft.com/en-us/library/aa554537\(v=ax.60\))

  


