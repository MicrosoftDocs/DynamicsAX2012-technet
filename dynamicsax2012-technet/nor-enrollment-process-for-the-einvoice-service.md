---
title: (NOR) Enrollment process for the eInvoice service
TOCTitle: (NOR) Enrollment process for the eInvoice service
ms:assetid: 765a86ad-b433-4140-8885-e711f67c9bb3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg212977(v=AX.60)
ms:contentKeyID: 36058189
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (NOR) Enrollment process for the eInvoice service 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The enrollment file contains information about customers who have requested the eInvoice service, have requested to cancel the eInvoice service, or a combination of both.

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **eInvoice enrollment and answer**.

2.  Click the **Functions** \> **Import enrollment** option to open the **Load diskette with payments** form.

3.  In the **Load diskette with payments** form, select the method of payment to import the enrollment file, and then click **OK** to open the **BBS import eInvoice** form.

4.  Select the enrollment file in the **File name** field. Click **OK** to import the file and copy the customer information from the file to the **eInvoice enrollment and answer** form.
    

    > [!NOTE]
    > <P>Under the <STRONG>Transfer</STRONG> field group, select the <STRONG>Transfer</STRONG> check box to update the customer address information that is received from the eInvoice reference.</P>



5.  Validate the customer information to approve or reject the customer enrollment request for the eInvoice service. Select the return status for the enrollment request in the **Return status** field.

6.  If the eInvoice reference matches the customer number, click **Status** \> **OK=Yes**.
    

    > [!NOTE]
    > <P>If the eInvoice reference does not match the customer number, click the <STRONG>Functions</STRONG> &gt; <STRONG>Customer account</STRONG> option to select a customer number.</P>



7.  If the customer information is incorrect, select **Rejected** as the new status, and then select an error code in the **Error code** field.

8.  Click **Functions** \> **Export answer** to send the response for the enrollment request.

9.  Click **Status** \> **Sent=Yes**.

10. Import the confirmation file that is received from Bankenes Betalingssentral (BBS) for customer enrollment for the eInvoice service. Post the enrollment to start the eInvoice service for the customer. The **New status** field is set to a status of **Active**.

## See also

[(NOR) Set up the layout for an eInvoice](nor-set-up-the-layout-for-an-einvoice.md)

[(NOR) Set up error codes for eInvoices](nor-set-up-error-codes-for-einvoices.md)

[(NOR) Set up the OCR method of payment](nor-set-up-the-ocr-method-of-payment.md)

[(NOR) Set up the types of payment mode change for eInvoices](nor-set-up-the-types-of-payment-mode-change-for-einvoices.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

