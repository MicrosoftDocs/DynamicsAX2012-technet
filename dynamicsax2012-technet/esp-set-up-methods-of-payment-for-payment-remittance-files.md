---
title: (ESP) Set up methods of payment for payment remittance files
TOCTitle: (ESP) Set up methods of payment for payment remittance files
ms:assetid: 71c08dcb-3c1d-4cba-8837-3dfa86097097
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg231842(v=AX.60)
ms:contentKeyID: 36058070
ms.date: 05/27/2014
mtps_version: v=AX.60
f1_keywords:
- methods of payment
- VendPaymMode
- remittance
---

# (ESP) Set up methods of payment for payment remittance files [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can set up remittance formats, Single European Payment Area (SEPA) credit transfers, or SEPA direct debit file formats as methods of payments to generate vendor and customer remittance files.

## Vendors

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Select a method of payment or press CTRL+N to create a method of payment, and enter an appropriate identifier in the **Method of payment** field.

3.  Enter other information, as needed, for the method of payment.

4.  Click the **File formats** FastTab. In the **Remittance format** field, select **Remittance Format 34 AEB(ES)** or **SEPACreditTransfer** .
    

    > [!NOTE]
    > <P>If the field list is empty, click <STRONG>Setup</STRONG>, and select from the available formats.</P>



## Customers

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Select a method of payment or press CTRL+N to create a method of payment, and enter an appropriate identifier in the **Method of payment** field.

3.  Specify values in the **Period** and **Payment type** fields.

4.  Enter other information, as needed, for the method of payment.

5.  On the **General** FastTab, select the **Require mandate** check box to enable the SEPA format for the selected payment type.
    
    This field is available only when you select **Electronic payment** in the **Payment type** field.

6.  Click the **File formats** FastTab. In the **Remittance format** field, select **Remittance Format 19,32 & 58 AEB(ES)**.
    

    > [!NOTE]
    > <P>If the field list is empty, click <STRONG>Setup</STRONG>, and select from the available formats.</P>



## See also

[(ESP) Generate a vendor payment remittance file](esp-generate-a-vendor-payment-remittance-file.md)

[(ESP) Generate a customer payment remittance file](esp-generate-a-customer-payment-remittance-file.md)

[Print copies of payments as non-negotiable checks](print-copies-of-payments-as-non-negotiable-checks.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

