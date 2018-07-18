---
title: (RUS) Set up bank accounts
TOCTitle: (RUS) Set up bank accounts
ms:assetid: 77e70933-5225-4533-a1ad-bf894ae458d5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678375(v=AX.60)
ms:contentKeyID: 49387605
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up bank accounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You must register the bank accounts for the company.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  On the **Overview** tab, press CTRL+N to create a new line.

3.  In the **Bank account** field, enter the bank account code.

4.  In the **Bank groups** field, select the bank group code for the bank. The **Bank name**, **BIC**, and **Corr. bank account** fields are completed based on the selected bank group code.

5.  In the **Bank account number** field, enter the bank account number.

6.  In the **Ledger account** field, select the account that will be shown on vouchers for the specified bank account.

7.  In the **Currency** field, select the currency code.

8.  On the **General** tab, in the **SWIFT code** field, enter the payment code in the SWIFT system.

9.  On the **Setup** tab, select the **More currencies** check box if the account conducts operations with various currencies.

10. In the **Payment order template** field, in the **Payment order in currency** field group, specify the path to the Microsoft Office Word template used to create and print a payment order in currency.
    

    > [!NOTE]
    > <P>The template folder must be set up in the <STRONG>Report Folder</STRONG> field on the <STRONG>Other</STRONG> tab in the <STRONG>Company information</STRONG> form.</P>



11. In the **Payment order template** field, in the **Purchase order for currency** field group, select the path to the template used to create and print a purchase order for funds in currency.

12. In the **P/O numeration** field, select the code for the document numbering series for the account.

13. On the **Address** and **Contact information** tabs, view and modify the address and contact information for the bank account. If a bank is selected in the **Bank groups** field for which the address and contact details are entered automatically, these address values are retrieved from the corresponding fields in the **Banks** table.

14. Press CTRL+S or close the form.

  


