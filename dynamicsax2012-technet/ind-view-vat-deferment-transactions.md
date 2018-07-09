---
title: (IND) View VAT deferment transactions
TOCTitle: (IND) View VAT deferment transactions
ms:assetid: 20f6f7ee-4b31-483c-88bb-f488398bc4c6
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664547(v=AX.60)
ms:contentKeyID: 49385626
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) View VAT deferment transactions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can view value added tax (VAT) deferment transactions separately for a Tax Identification Number (TIN) for a specific tax settlement period.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Inquiries** \> **Tax** \> **India posted tax** \> **VAT** \> **VAT deferment**.

2.  Select the query to modify in the **Select query** field.

3.  Select the Tax Identification number (TIN) of the company to query the VAT deferment transactions for in the **Tax Identification Number (TIN)** field.

4.  Select the tax settlement period to query the VAT deferment transactions for in the **Tax settlement period** field.

5.  Select the period range within the selected tax settlement period in the **From date** field and the **To date** field.

6.  Select the **Header note** check box to enter a header note for the inquiry and enter the text to display as the header note in the **Header note** field.

7.  Select the **Footer note** check box to enter the footer note for the inquiry and enter the text to display as the footer note in the **Footer note** field.
    

    > [!NOTE]
    > <P>The text that you enter in the <STRONG>Header note</STRONG> field and the <STRONG>Footer note</STRONG> field is displayed as the header and footer text in the <STRONG>VAT deferment balance</STRONG> form.</P>



8.  Click **Modify...** to edit, save, or delete the current query.

9.  Click **OK** and open the **VAT deferment balance** form, where you can view the information based on the details entered in the **VAT deferment inquiry** form. For more information, see [(IND) VAT deferment balance (form)](https://technet.microsoft.com/en-us/library/jj664626\(v=ax.60\)).

10. Click **Voucher** in the **VAT deferment balance** form to view the ledger transactions for the deferment amount that has been transferred from the deferred account to the recoverable account.

11. Click **Deferment lines** in the **VAT deferment balance** form to open the **VAT deferment transactions** form, where you can view the details of the posted deferred transaction.

12. Click the **Overview** tab and view the VAT deferment transaction details.

13. In the **VAT deferment transactions** form, click **Deferment installment** to open the **Deferment installment** form, where you can view the updated deferment installment for the selected line. For more information, see [(IND) Deferment installment (form)](https://technet.microsoft.com/en-us/library/jj710942\(v=ax.60\)).

## See also

[(IND) Setting up Value Added Tax (VAT)](ind-setting-up-value-added-tax-vat.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

