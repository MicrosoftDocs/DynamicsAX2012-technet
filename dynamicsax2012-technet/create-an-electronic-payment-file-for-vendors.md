---
title: Create an electronic payment file for vendors
TOCTitle: Create an electronic payment file for vendors
ms:assetid: cac647cf-c80e-4221-8c28-53774fbb9017
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213659(v=AX.60)
ms:contentKeyID: 36971932
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Create an electronic payment file for vendors 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The electronic payment files that you can create for vendors can have many different formats. Consult your authorized partner to learn whether the format that your bank or payment processing service requires for payment files is available.

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a journal, and then click **Lines**.

3.  Click **Functions** \> **Generate payments**. The **Generate payments** form is displayed.

4.  Select the **Export format** option, and then, in the **Export format** field, select a format for the export file.
    
    –or–
    
    Select the **Payment method** option, and then, in the **Method of payment** field, select a method of payment that uses the appropriate format for export files.
    

    > [!NOTE]
    > <P>For Canada, select <STRONG>RBC Payment Distribution Service (CA)</STRONG> or <STRONG>HSBC Distribution Format (CA)</STRONG> as the export format for the method of payment.</P>



5.  Click **Dialog**.

6.  In the form that is displayed, enter the information that is required for the payment format.
    

    > [!NOTE]
    > <P>The fields that are displayed in this form depend on the payment format that you selected. For example, if you select the <STRONG>RBC Payment Distribution Service (CA)</STRONG> format, you can select either CAD or USD as the currency that is used for the payments.</P>



7.  Click **OK**.

8.  In the **Generate payments** form, click **OK**.

## See also

[Set up a file format for a method of payment for vendors](set-up-a-file-format-for-a-method-of-payment-for-vendors.md)

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

[(CAN) Set up IAT ACH file parameters](can-set-up-iat-ach-file-parameters.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

