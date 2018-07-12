---
title: (CHE) Set up LSV+ information for a bank account
TOCTitle: (CHE) Set up LSV+ information for a bank account
ms:assetid: 8da14aa9-b013-4876-8cbd-bc1496892996
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg242884(v=AX.60)
ms:contentKeyID: 36058505
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Switzerland
---

# (CHE) Set up LSV+ information for a bank account 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Bank accounts** form to set up Lastschriftenverfahren (LSV+) information for a bank account.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**. Double-click a bank account or click **Bank account** in the **New** group to open the **Bank accounts** form and create a new bank account. For more information, see [Bank accounts (form)](https://technet.microsoft.com/en-us/library/aa587660\(v=ax.60\)).

2.  Click the **General** FastTab, and then in the **Bank account** field, select a customer bank account.
    

    > [!NOTE]
    > <P>In the <STRONG>Routing number</STRONG> field, be sure to enter a Swiss bank clearing number.</P>



3.  Click the **Additional identification** FastTab. In the **IBAN** field, enter the international bank account number for your company.

4.  In the **Company ID** field, enter your LSV member identification number.

5.  In the **ESR** field, enter the Enzahlungsschein mit Referenznummer (ESR) membership number.

6.  In the **BESR ID number** field, enter the bank ESR number. This number is combined with the ESR membership number, customer account, and invoice number to create a unique ESR payment reference number for each line in the Swiss LSV payment export file.

7.  Click the **Currency management** FastTab.

8.  In the **Currency** field, select the currency code for **Swiss franc (CHF)** or **Euro (EUR)**.
    

    > [!NOTE]
    > <P>Be sure that the currency you select has the appropriate ISO currency code defined for it in the <STRONG>Currencies</STRONG> form.</P>



9.  Close the form to save your changes.

## See also

[(CHE) Set up a method of payment for LSV+ payment export files](che-set-up-a-method-of-payment-for-lsv-payment-export-files.md)

[(CHE) Set up a method of payment for ESR payment import files](che-set-up-a-method-of-payment-for-esr-payment-import-files.md)

[(CHE) Set up an LSV+ method of payment for a customer](che-set-up-an-lsv-method-of-payment-for-a-customer.md)

[(CHE) Create a payment proposal for LSV+ payments](che-create-a-payment-proposal-for-lsv-payments.md)

[(CHE) Create an LSV+ payment file](che-create-an-lsv-payment-file.md)

  


