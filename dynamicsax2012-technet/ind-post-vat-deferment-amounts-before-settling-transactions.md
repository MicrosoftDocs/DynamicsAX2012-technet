---
title: (IND) Post VAT deferment amounts before settling transactions
TOCTitle: (IND) Post VAT deferment amounts before settling transactions
ms:assetid: 522048da-9ed5-47dc-bd3c-3a1395682cc5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664695(v=AX.60)
ms:contentKeyID: 49385777
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (IND) Post VAT deferment amounts before settling transactions [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



You must post the VAT deferment amount from the VAT deferred account to the VAT recoverable account before settling amounts to the tax authorities. You can process the VAT deferment amounts only for the same tax ledger posting group, for a Tax Identification Number (TIN), for a particular tax settlement period, and for a given period range.


> [!NOTE]
> <P>This process is sometimes referred to as the presettlement process.</P>



1.  Click **General ledger** \> **Periodic** \> **India** \> **VAT deferment**.

2.  Select the TIN of the company in the **Tax Identification Number (TIN)** field.

3.  Select the settlement period to run the presettlement for in the **Tax settlement period** field.

4.  Enter the starting date in the **From date** field to run the presettlement process for transactions for a specific period.

5.  Enter a transaction date to post the voucher for the specific period in the **Transaction date** field.

6.  Click **Show data** to view the following details for the selected settlement period for the date range:
    
      - The starting date of the settlement period starting date.
    
      - The ending date of the settlement period.
    
      - The opening balance for the period.
    
      - The total recoverable value for the period.
    
      - The amount transferred to the recoverable account.
    
      - The closing balance for the period.

7.  Click **Deferment lines** to open the **VAT deferment transactions** form.

8.  Click the **Overview** tab and view the details of the posted VAT transactions.
    

    > [!NOTE]
    > <P>The <STRONG>Mark</STRONG> check box is selected for the transactions that are selected for transfer.</P>



9.  View the amount transferred to the VAT recoverable account in the **Transfer amount** field.

10. Click **Post** to post the value in the **Transfer** field from the VAT deferment account to the VAT recoverable account, and to generate a voucher.

## See also

[(IND) VAT deferment balance (form)](https://technet.microsoft.com/en-us/library/jj664626\(v=ax.60\))

[(IND) View VAT deferment transactions](ind-view-vat-deferment-transactions.md)

[(IND) VAT deferment transactions (form)](https://technet.microsoft.com/en-us/library/jj710922\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

