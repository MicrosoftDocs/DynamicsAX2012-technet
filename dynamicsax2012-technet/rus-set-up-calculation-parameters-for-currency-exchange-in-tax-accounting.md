---
title: (RUS) Set up calculation parameters for currency exchange in tax accounting
TOCTitle: (RUS) Set up calculation parameters for currency exchange in tax accounting
ms:assetid: 9d812638-4788-4ad3-90c8-dc8d9d1414f3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ879296(v=AX.60)
ms:contentKeyID: 50639115
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (RUS) Set up calculation parameters for currency exchange in tax accounting [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Currency revaluation accounts** form to set up calculation parameters for currency exchange in tax accounting.

1.  Click **General ledger** \> **Setup** \> **General ledger parameters**.

2.  In the **Calculation method** field, select a method to calculate currency exchange differences, from the following options:
    
      - **Standard** – The exchange adjustment is calculated as the difference between the invoice value on the day the invoice is posted and the day the invoice payment is made. If the invoices are revalued in an earlier accounting period, the exchange adjustment amounts are reversed.
    
      - **Incremental** – The exchange adjustment is calculated based on incremental rates. An incremental rate is the difference between the exchange rate on the date when the invoices are last revalued and the exchange rate on the date of the current revaluation.
    
      - **Period grand total** – For invoices that are posted and paid in the same accounting period, the exchange rate is calculated by using the difference between the rates on the invoice date and the payment date. For the next accounting period, the exchange rate is calculated by using the difference between the exchange rates on the date when the invoices are last revalued in the previous accounting period and the exchange date on the current voucher. You cannot reverse transactions by overvaluing in previous periods.

3.  Close the form.

4.  Click **General ledger** \> **Setup** \> **Currency** \> **Currency parameters**.

5.  Select a currency, and then select the **Activate parameters** check box to activate revaluation parameters for the selected currency.

6.  On the **General** FastTab, select the **Amount difference in tax accounting** check box to use the selected currency in the calculation of the amount difference in tax accounting.

7.  Click the **Sales/customers** FastTab.
    

    > [!NOTE]
    > <P>This tab is available only if you select <STRONG>Incremental</STRONG> or <STRONG>Period grand total</STRONG> in the <STRONG>Calculation method</STRONG> field in the <STRONG>General ledger parameters</STRONG> form.</P>



8.  In the **Customer posting** grid, in the **Main account** field, select the account that the amount difference from settled transactions is posted to.

9.  In the **Customer tax dimension** field group, in the **Expense code** field, select the expense code. If the amount difference that results when the transactions are settled is a loss, this expense code is used to post the amount difference to the appropriate register.

10. In the **Revenue code** field, select a revenue code. If the amount difference that results when the transactions are settled is a profit, this revenue code is used to post the amount difference to the appropriate register.

11. Click the **Purchases/Vendors** FastTab.
    

    > [!NOTE]
    > <P>This tab is available only if you select <STRONG>Incremental</STRONG> or <STRONG>Period grand total</STRONG> in the <STRONG>Calculation method</STRONG> field in the <STRONG>General ledger parameters</STRONG> form.</P>



12. In the **Vendor posting** grid, in the **Main account** field, select the account that the amount difference from settled transactions is posted to.

13. In the **Vendor tax dimension** field group, in the **Expense code** field, select an expense code. If the amount difference that results when the transactions are settled is a loss, this expense code is used to post the amount difference to the appropriate register.

14. In the **Revenue code** field, select a revenue code. If the amount difference that results when the transactions are settled is a profit, this revenue code is used to post the amount difference to the appropriate register.

## See also

[(EEUR) General ledger parameters (modified form)](https://technet.microsoft.com/en-us/library/jj710686\(v=ax.60\))

[(RUS) About tax liabilities and asset calculation registers](rus-about-tax-liabilities-and-asset-calculation-registers.md)

[(RUS) Currency revaluation accounts (modified form)](https://technet.microsoft.com/en-us/library/jj852149\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

