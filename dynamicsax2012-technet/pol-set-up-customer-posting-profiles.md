---
title: (POL) Set up customer posting profiles
TOCTitle: (POL) Set up customer posting profiles
ms:assetid: 4b7469f5-0e3c-44e4-9b40-671f33f62ce2
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678195(v=AX.60)
ms:contentKeyID: 49386918
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Poland
---

# (POL) Set up customer posting profiles 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up the profiles that control the posting of customer transactions to the general ledger in the **Customer posting profiles** form. In this form, you can also create a collection letter sequence and attach it to a customer's posting profile.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  In the **Customer posting profiles** form, press CTRL+N to create a posting profile, or select an existing posting profile. For more information, see [Customer posting profiles (form)](https://technet.microsoft.com/en-us/library/aa600572\(v=ax.60\)).

3.  On the **Table restrictions** tab, select the **Interest** check box to specify whether interest is calculated on the transaction.

4.  Select the **Collection letter** check box to specify whether to create collection letters for the posting profile.

5.  On the **Setup** tab, in the **Account code** field, select an account code to specify whether the posting profile applies to a single customer, a group of customers, or all customers.

6.  In the **Account/Group number** field, select the customer account number or group number associated with the posting profile.
    

    > [!NOTE]
    > <P>If you selected <STRONG>All</STRONG> in the <STRONG>Account code</STRONG> field, you cannot select a value in the <STRONG>Account/Group number</STRONG> field.</P>



7.  In the **Collection letter sequence** field, select the identification for the collection letter sequence associated with the posting profile.

8.  In the **Interest code** field, select the interest code to use to calculate interest.

9.  Press CTRL+S or close the form.

## See also

[Create collection letters](create-collection-letters.md)

[Set up a collection letter sequence](set-up-a-collection-letter-sequence.md)

[(POL) Set up interest codes](pol-set-up-interest-codes.md)

[(POL) Set up a number sequence code for the interest note and voucher](pol-set-up-a-number-sequence-code-for-the-interest-note-and-voucher.md)

[(POL) Set up the accounts receivable parameters to calculate interest](pol-set-up-the-accounts-receivable-parameters-to-calculate-interest.md)

[(POL) Post and print an interest note](pol-post-and-print-an-interest-note.md)

[(POL) Calculate tax interest and free-hand interest](pol-calculate-tax-interest-and-free-hand-interest.md)

[(POL) View the calculated interest](pol-view-the-calculated-interest.md)

[(POL) Accounts receivable parameters (modified form)](https://technet.microsoft.com/en-us/library/jj678183\(v=ax.60\))

  


