---
title: (USA) Set up IAT ACH file parameters
TOCTitle: (USA) Set up IAT ACH file parameters
ms:assetid: 15d1aa39-0b7f-48ae-b44b-bbd42f32caf5
ms:mtpsurl: https://technet.microsoft.com/library/Hh242149(v=AX.60)
ms:contentKeyID: 36056066
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- parameters
- ACH
- IAT
- USA
audience: Application User
ms.search.region: USA
---

# (USA) Set up IAT ACH file parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The National Automated Clearing House Association (NACHA) and Office of Foreign Assets Control (OFAC) of the U.S Department of the Treasury have introduced a standard entry class code for International ACH Transactions (IAT). When you make payments to a vendor or refund a payment to a customer who is outside the United States, you must use this code in the transaction to denote the origin of the payment.

Complete the following tasks before you generate an IAT EFT file:

  - Set up information for your company in the **Legal entities** form. These details are used as the originator information when the IAT Electronic File Transmission (EFT) file is generated. For more information, see [Legal entities (form)](https://technet.microsoft.com/library/hh242860\(v=ax.60\)).

  - Set up bank account details, such as **Bank account**, **Routing number type**, **Routing number**, and **SWIFT code**, for your company in the **Bank accounts** form. For more information, see [Bank accounts (form)](https://technet.microsoft.com/library/aa587660\(v=ax.60\)) and .

  - Set up details for the vendor who receives the payment in the **Vendors** form. These details are used as the receiver or beneficiary information in the IAT EFT file. For more information, see [Create a vendor account](create-a-vendor-account.md).

  - Set up bank account details for the vendor in the **Vendor bank accounts** form. These details are used as the receiver Depository Financial Institution (DFI) information in the IAT EFT file. For more information, see [Vendor bank accounts (form)](https://technet.microsoft.com/library/aa589805\(v=ax.60\)).

  - Set up details for the customer who receives a refund in the **Customers** form. These details are used as the originator information in the IAT EFT file. For more information, see [Create a customer record](create-a-customer-record.md).

  - Set up bank account details for the customer in the **Customer bank accounts** form. These details are used as the originator DFI information in the IAT EFT files. For more information, see [Customer bank accounts (form)](https://technet.microsoft.com/library/aa575695\(v=ax.60\)).

## Set up a method of payment

Set up and assign a method of payment for a vendor or customer and select the **NACHA IAT (US)** file format as the export file format for the payment.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.
    
    –or–
    
    Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Press CTRL+N to create a new payment method. For more information, see [Set up a file format for a method of payment for vendors](set-up-a-file-format-for-a-method-of-payment-for-vendors.md) and [Set up a file format for a method of payment for customers](set-up-a-file-format-for-a-method-of-payment-for-customers.md).

3.  In the **Method of payment** field, enter an appropriate identifier, such as NACHA IAT.

4.  Click the **File formats** FastTab and in the **Export format** field, select **NACHA IAT (US)**.
    

    > [!NOTE]
    > <P>If the field list is empty, click <STRONG>Setup</STRONG>, and select <STRONG>NACHA IAT (US)</STRONG> from the available formats.</P>



5.  Close the form to save your changes.

## See also

[(USA) Create a payment journal and generate the IAT transmission file](usa-create-a-payment-journal-and-generate-the-iat-transmission-file.md)

  


