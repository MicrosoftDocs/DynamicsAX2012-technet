---
title: Create an electronic payment file for customers
TOCTitle: Create an electronic payment file for customers
ms:assetid: dffcf26c-fcbc-4047-84ab-c03511f6ce26
ms:mtpsurl: https://technet.microsoft.com/library/Gg243204(v=AX.60)
ms:contentKeyID: 36971934
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create an electronic payment file for customers 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The electronic payment files that you can create for customers can have many different formats. Consult your authorized partner to learn whether the format that your bank or payment processing service requires for payment files is available.

1.  Click **Accounts receivable** \> **Journals** \> **Payments** \> **Payment journal**.

2.  Select a journal, and then click **Lines**.

3.  Click **Functions** \> **Generate payments**. The **Generate payments** form is displayed.

4.  Select the **Export format** option, and then, in the **Export format** field, select a format for the export file.
    
    –or–
    
    Select the **Payment method** option, and then, in the **Method of payment** field, select a method of payment that uses the appropriate format for export files.
    

    > [!NOTE]
    > <P>For Canada, select <STRONG>RBC Pre-Authorized Debits [PADS] Service (CA)</STRONG> or <STRONG>HSBC Distribution Format (CA)</STRONG> as the export format for the method of payment.</P>



5.  Click **Dialog**.

6.  In the form that is displayed, enter the information that is required for the payment format.
    

    > [!NOTE]
    > <P>The fields that are displayed in this form depend on the payment format that was selected. For example, if you select the <STRONG>RBC Pre-Authorized Debits (PADS) Service (CA)</STRONG> format, you can select either CAD or USD as the currency that is used for the payments.</P>



7.  Click **OK**.

8.  In the **Generate payments** form, click **OK**.

## See also

[Set up a file format for a method of payment for customers](set-up-a-file-format-for-a-method-of-payment-for-customers.md)

[(CAN) Set up IAT ACH file parameters](can-set-up-iat-ach-file-parameters.md)

  


