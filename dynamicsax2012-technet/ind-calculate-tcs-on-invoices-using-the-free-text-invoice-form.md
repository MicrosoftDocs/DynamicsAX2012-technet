---
title: (IND) Calculate TCS on invoices using the Free text invoice form
TOCTitle: (IND) Calculate TCS on invoices using the Free text invoice form
ms:assetid: 88c279a9-12e4-440d-b2e8-1fd9a3b11968
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ678022(v=AX.60)
ms:contentKeyID: 49385983
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Calculate TCS on invoices using the Free text invoice form 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



Tax Collected at Source (TCS) is calculated on various types of sales transactions, and is the tax amount above the invoice amount that is collected by the seller of goods from the buyer.

If you attach a cash discount to an invoice, TCS is calculated before calculating the cash discount for the invoice.

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Create a free text invoice in the **Free text invoice** form and enter the required details.

3.  Click the **Invoice** tab. The nature of the assessee of the customer is displayed in the **Nature of assessee** field.
    

    > [!NOTE]
    > <P>TCS is calculated only if the <STRONG>Calculate withholding tax</STRONG> check box is selected for the customer on the <STRONG>Setup</STRONG> tab of the <STRONG>Customers</STRONG> form.</P>



4.  Click the **Invoice lines** tab to create invoice lines, and enter the required details.

5.  Click the **Tax information** tab. Under the **Company information** field group, the company name is displayed in the **Name** field. You can select the name of alternate addresses that are set up for the company in this field.
    

    > [!NOTE]
    > <P>Click <STRONG>Organization administration</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Organization</STRONG> &gt; <STRONG>Legal entities</STRONG>.</P>



6.  Click **Withholding tax** to open the **Temporary withholding tax transactions** form and view the tax details.

7.  Click **Threshold** to open the **Threshold** form, where you can view the threshold limit defined for the TCS tax component that is attached to a specific TCS tax code.

8.  Click **Designer** to open the **Formula designer** form, where you can view the formula that is defined for a specific TCS tax code.

9.  Close the **Temporary withholding tax transactions** form.

10. Post the free text invoice in the **Free text invoice** form.
    

    > [!NOTE]
    > <P>The TCS amount is posted to the payable account defined for each TCS tax code in the TCS group. Click <STRONG>General ledger</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Withholding tax</STRONG> &gt; <STRONG>Withholding tax codes</STRONG>.</P>



## See also

[(IND) Free text invoice (modified form)](https://technet.microsoft.com/en-us/library/jj664875\(v=ax.60\))

[(IND) Maintain sales tax transactions for Accounts receivable](ind-maintain-sales-tax-transactions-for-accounts-receivable.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

