---
title: (POL) Update the VAT register information
TOCTitle: (POL) Update the VAT register information
ms:assetid: d97d9c3c-fe6b-422b-96d4-8cfe1db0957b
ms:mtpsurl: https://technet.microsoft.com/library/JJ711299(v=AX.60)
ms:contentKeyID: 49387118
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Update the VAT register information 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Polish tax law requires that companies report specific VAT information in their VAT registers. You can use the **Journal voucher** form to update the VAT register information from a tax line in another journal line when one of the fields is modified.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Journals** \> **General journal**. In the **General journal** form, on the **Overview** tab, select a journal, and the click **Lines**.

2.  In the **Account type** field, select the account type.

3.  In the **Account** field, select an account for the selected account type.

4.  In the **Debit** or **Credit** fields, enter the debit or credit amount.

5.  In the **Sales tax group** and **Item sales tax group** fields, select the tax groups.
    

    > [!NOTE]
    > <P>Do not select any tax groups for the <STRONG>Ledger</STRONG> account type. Instead, select only the sales tax code in the <STRONG>Sales tax code</STRONG> field.</P>



6.  On the **Invoice** tab, in the **Invoice** field, enter the invoice number.

7.  In the **Tax exempt number** field, select the tax exempt number of the customer or vendor account.

8.  In the **Document date** field, select the date of the document.

9.  In the **Date of VAT register** field, select the transaction date for VAT register period.

10. Save the line.
    

    > [!NOTE]
    > <P>For more information, see <A href="https://technet.microsoft.com/library/aa591466(v=ax.60)">Journal voucher - General journal (form)</A>.</P>



11. Press CTRL+ N to create the second line for the offset account with the same voucher number as the first line.

12. In the **Debit** or **Credit** fields, enter the debit or credit amount. Save the line.

13. Click **Yes** if you want to update the rest of lines with the VAT date from the first line. Otherwise, click **No**.

  


