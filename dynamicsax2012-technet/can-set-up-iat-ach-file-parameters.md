---
title: (CAN) Set up IAT ACH file parameters
TOCTitle: (CAN) Set up IAT ACH file parameters
ms:assetid: 8884b9a0-aafc-4ebf-9746-10c7d5a24743
ms:mtpsurl: https://technet.microsoft.com/library/Gg242852(v=AX.60)
ms:contentKeyID: 36058446
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Canada
---

# (CAN) Set up IAT ACH file parameters 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can transfer funds in Canadian dollars (CAD) or U.S. dollars (USD) through the Royal Bank of Canada Payment Distribution Service. Use the **RBC Payment Distribution Service (CA)** or **RBC Pre-Authorized Debits (PADS) Service (CA)** export format for the method of payment, and then select either **CAD** or **USD** as the currency when you generate payments. This format complies with the Royal Bank of Canada Standard 152 Payment Distribution Service format.

To comply with the National Automated Clearing House Association (NACHA) operating rules, the RBC electronic funds transfer (EFT) format now includes new address records for both the originator of the payment and the customer or recipient of the payment. If the payment transaction originates from or is transmitted to a financial agency outside the territorial jurisdiction of the United States, it is classified as an International ACH Transaction (IAT) by the RBC. You must complete the following tasks before you generate an IAT Automatic Clearing House (ACH) file:

  - In the **Legal entities** form, set up information for the originator. The originator is the company that makes a payment to a vendor or refunds a transaction to a customer. These details are used as the originator information when the IAT ACH file is generated.

  - In the **Bank accounts** form, set up bank account details for the originator of the payment.

  - In the **Vendors** form, set up the details for the vendor that receives the payment. These details are used as the receiver or beneficiary information when the IAT ACH file is generated.

  - In the **Vendor bank accounts** form, set up bank account details for your vendors. These details are used as the receiver depository financial institution (DFI) information when the IAT ACH file is generated.

  - In the **Customers** form, set up details for customers who receive refunds. These details are used as the receiver or beneficiary information when the IAT ACH file is generated.

  - In the **Customer bank accounts** form, set up bank account details for your customers. These details are used as the receiver DFI information when the IAT ACH file is generated.

## Set up a method of payment for vendor payments

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Create a new method of payment. In the **Method of payment** field, enter an appropriate identifier, such as RBC\_AP.

3.  Enter other information for the method of payment, as needed.

4.  Click the **File formats** FastTab. In the **Export format** field, select **RBC Payment Distribution Service (CA)**.
    

    > [!NOTE]
    > <P>If the <STRONG>Export format</STRONG> field list is empty, click <STRONG>Setup</STRONG>, and then select one of the available formats.</P>



5.  Close the form.

## Set up a method of payment for customer payments

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Create a new method of payment. In the **Method of payment** field, enter an appropriate identifier, such as RBC\_AR.

3.  Enter other information for the method of payment, as needed.

4.  Click the **File formats** FastTab, and then in the **Export format** field, select **RBC Pre-Authorized Debits (PADS) Service (CA)**.
    

    > [!NOTE]
    > <P>If the <STRONG>Export format</STRONG> field list is empty, click <STRONG>Setup</STRONG>, and then select one of the available formats.</P>



5.  Close the form.

## See also

[Create an electronic payment file for vendors](create-an-electronic-payment-file-for-vendors.md)

[Create an electronic payment file for customers](create-an-electronic-payment-file-for-customers.md)

[Methods of payment - vendors (form)](https://technet.microsoft.com/library/aa618565\(v=ax.60\))

  


