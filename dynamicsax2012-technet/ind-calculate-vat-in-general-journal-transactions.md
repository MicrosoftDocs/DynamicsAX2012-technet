---
title: (IND) Calculate VAT in general journal transactions
TOCTitle: (IND) Calculate VAT in general journal transactions
ms:assetid: 61e6809f-27cb-4b7c-aade-fafb5f2ccd75
ms:mtpsurl: https://technet.microsoft.com/library/JJ677858(v=AX.60)
ms:contentKeyID: 49385824
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate VAT in general journal transactions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can calculate the VAT for transactions that are entered in journals. For example, a journal is created for the sale of goods that costs INR 10,000 with the account combination of Customer (Dr) – Ledger (Cr).


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The item tax group is VAT at 10 percent, and the tax rate is 10 percent. When the journal is posted, the customer account is debited with an amount of INR 11,000. The ledger account for the transaction is credited with an amount of INR 10,000, and the VAT payable account is credited with an amount of INR 1000.

1.  Click **General ledger** \> **Journals** \> **General journal**.

2.  Create a new journal.

3.  Enter the required details.

4.  Click **Lines** to open the **Journal voucher** form.

5.  Enter the required details.

6.  Click the **Tax information** tab.

7.  Select the TIN for the legal entity in the **Tax Identification Number (TIN)** field.

8.  Select the goods type for the transaction in the **VAT goods type** field from the following options:
    
      - **Input**
    
      - **Capital goods**
    

    > [!NOTE]
    > <P>The deferment schedule can be created for the VAT amount in a transaction, only when the VAT goods type for the transaction is selected is <STRONG>Capital goods</STRONG>. For more information, see <A href="ind-calculate-vat-for-various-purchase-types.md">(IND) Calculate VAT for various purchase types</A> and <A href="ind-enter-vat-in-purchase-orders.md">(IND) Enter VAT in purchase orders</A>.</P>



9.  In the **Non-recoverable pct.** field, enter the nonrecoverable percentage of VAT for the transaction. Non recoverable goods are purchased goods that are used for the production or manufacturing of nontaxable goods.

10. Click **Sales tax** to view the calculated VAT amount and the other taxes applied to the transaction in the **Temporary sales tax transactions** form.

11. Click the **Adjustment** tab to adjust or modify the calculated VAT amount.

12. Click **Apply** to apply the adjustments made to the VAT amount.

13. Click **Formula designer** to view the formula defined for the item sales tax group.

14. Close the form to return to the **Journal voucher** form.

15. Post the journal.

16. In the **Journal voucher** form, click **Deferment schedule** to open the **Deferment schedule** form for the journal voucher line.
    

    > [!NOTE]
    > <P>The <STRONG>Deferment schedule</STRONG> button is activated only under the following conditions:</P>
    > <P>VAT goods type is Capital goods.</P>
    > <P>The calculated VAT amount is a positive amount.</P>
    > <P>The transaction is a purchase transaction.</P>



17. Click the **Deferment schedule** tab and select one of the following options in the **Allocation** field to determine the installment amount.
    
      - **Fixed quantity**
    
      - **Fixed amount**
    
      - **Total**

18. Select the time unit to claim the deferment amount in the **Payment per** field.

19. Enter the period range for the time unit in the **Change** field.

20. Enter the number of installments for tax payments in the **Number of deferment** field.

21. Enter the amount to be paid per installment in the **Amount currency** field.

22. Enter the minimum amount to be paid per installment in the **Minimum** field.

23. Click the **Installment** tab to modify the period and the values.

24. Click **Calculate** to view the changes in the deferment schedule.

25. Click **OK** to apply the changes and close the form.
    

    > [!NOTE]
    > <P>The <STRONG>OK</STRONG> button is activated only when the values in the <STRONG>VAT deferment amount</STRONG> field and the <STRONG>Installment amount in total</STRONG> field are equal. The deferment schedule for a posted transaction can be modified only once.</P>

    
    The deferment schedule cannot be modified if any of the deferment installment amounts is already transferred through the periodic process.

## See also

[(IND) Deferment schedule (form)](https://technet.microsoft.com/library/jj664609\(v=ax.60\))

  


