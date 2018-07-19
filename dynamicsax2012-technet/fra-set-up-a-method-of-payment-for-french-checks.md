---
title: (FRA) Set up a method of payment for French checks
TOCTitle: (FRA) Set up a method of payment for French checks
ms:assetid: eac726c5-f65f-48de-be3c-3519f1402b6a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg243247(v=AX.60)
ms:contentKeyID: 36059856
ms.date: 04/25/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: France
---

# (FRA) Set up a method of payment for French checks 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The French check format includes a check letter that you can print along with a check. The check letter lists all of the payments that are associated with the current check. You can print checks for general ledger accounts to pay for bills from one-time vendors.

## Set up a method of payment for French checks

Use the **Methods of payment - vendors** form to set up a method of payment for French checks.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Methods of payment**.

2.  Click **New** or press CTRL+N to create a method of payment. In the **Method of payment** field, enter an identification code for the method of payment, such as Check.

3.  Enter additional information for the method of payment, if required. For more information, see [Methods of payment - vendors (form)](https://technet.microsoft.com/en-us/library/aa618565\(v=ax.60\)).

4.  On the **File formats** FastTab, in the **Export format** field, select **Check**.
    

    > [!NOTE]
    > <P>If the <STRONG>Check</STRONG> format is not available in the <STRONG>Export format</STRONG> field, click <STRONG>Setup</STRONG> to open the <STRONG>File formats for methods of payment</STRONG> form. On the <STRONG>Export</STRONG> tab, move <STRONG>Check</STRONG> from the <STRONG>Available</STRONG> list to the <STRONG>Selected</STRONG> list. Close the form.</P>



## Set up the check and payment letter format for French checks

Use the **Check layout** form to set up the French check and payment letter format for a bank account.

1.  Click **Cash and bank management** \> **Common** \> **Bank accounts**.

2.  Select or create a bank account. For more information, see [Bank accounts (form)](https://technet.microsoft.com/en-us/library/aa587660\(v=ax.60\)).

3.  In the **Bank accounts** form, on the **Set up** tab, click **Check** to open the **Check layout** form.

4.  In the **Check form** field, select **French check format** to print the checks in the French check format. When you print the checks, they display on the screen by default.

5.  Update additional information, if required. For more information, see [Set up the check layout for a bank account](set-up-the-check-layout-for-a-bank-account.md).

6.  On the **Notes** tab, in the **Header** field, enter the text that will appear in the header of the French check letter. The body of the check letter will include a list of transactions that are paid by the check.

7.  In the **Footer** field, enter the text that will appear in the footer of the check letter.

You can click **Print test** in the **Check layout** form to open the **Check layout - print test** form. Specify the parameters, such as the check format, and then click **OK** to print a test copy of the check layout on plain paper.

## See also

[Check layout (form)](https://technet.microsoft.com/en-us/library/aa576973\(v=ax.60\))

  


