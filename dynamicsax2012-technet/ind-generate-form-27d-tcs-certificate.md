---
title: (IND) Generate Form 27D TCS certificate
TOCTitle: (IND) Generate Form 27D TCS certificate
ms:assetid: 6ef35429-ddb1-4ad0-a05b-8249f0338293
ms:mtpsurl: https://technet.microsoft.com/library/JJ677921(v=AX.60)
ms:contentKeyID: 49385891
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Generate Form 27D TCS certificate 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The collectors of tax at source are required to issue Form 27D certificates for TCS transactions that are posted to payable accounts defined for TCS tax codes.

The following are the prerequisites to generate the Form 27D certificate:

  - Provisional receipt numbers must be entered for all statements generated for the period in the **Provisional receipt numbers** form.

  - The required number of certificates must be created for the withholding tax component group in the **Certificates** form.

You can generate only one certificate per customer for a specific period. If additional TCS transactions have been posted for the period, you can generate an additional certificate for a customer for a period. In this case, the certificate is only generated for the additional TCS transactions.

After you generate Form 27D certificates for customers, the certificate status changes from **Created** to **Issued** in the **Certificates** form. You also can generate duplicate certificates by using the **TCS certificate - Form 27D**.

The Form 27D certificate displays the following information:

  - Specific information about the person collecting the tax and the buyer/licensee or lessee/person who is awarded the contract.

  - TAN and PAN details about the collector and PAN details of the buyer/licensee or lessee/person who is awarded the contract.

  - Details of payment, tax collection, and deposition of tax into a Central government account.


> [!NOTE]
> <P>If the TCS transaction is reversed using a credit note, only the net amount will be displayed for the transaction in the certificate.</P>



1.  Click Click **General ledger** \> **Reports** \> **India** \> **TCS** \> **TCS certificate**.

2.  Select the TAN to issue the certificate for in the **Tax account number (TAN)** field.

3.  Select the withholding tax component group to issue the certificate for in the **Withholding tax component group** field.

4.  Enter the starting date and the ending date of the period interval to issue the certificate for.

5.  Select the customer account range to issue the certificate for in the **Customer account** field.

6.  Enter the full name and designation of the person who is responsible for TCS collection in the **Full name** and **Designation** fields.

7.  Enter the printing date for the certificate in the **Printing date** field.

8.  Click **OK** to generate the certificate.

## See also

[(IND) Generate 27EQ quarterly statement for TCS](ind-generate-27eq-quarterly-statement-for-tcs.md)

  


