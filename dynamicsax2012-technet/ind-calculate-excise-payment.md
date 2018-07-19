---
title: (IND) Calculate excise payment
TOCTitle: (IND) Calculate excise payment
ms:assetid: d25eeb65-3710-4b7b-aa18-db5b4f1ff409
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664941(v=AX.60)
ms:contentKeyID: 49386270
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate excise payment 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can adjust the tax amounts according to the setoff rule in the **Tax adjustment** form. Select only the excise-related voucher transactions to consider for the settlement process for that period in the **Transactions** form.

The adjusted tax amount is the amount that is left after setting off the amounts among the various tax components according to the setoff rule. For more information, see [(IND) Tax setoff rule (form)](https://technet.microsoft.com/en-us/library/jj677818\(v=ax.60\)).


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**.

2.  Select the tax registration group to run the excise settlement process in the **Tax registration group** field, and select the tax registration number in the **Tax registration number** field.

3.  Select the period for the excise settlement process in the **Settlement period** field.

4.  Enter the starting date in the **Date** field. All the excise transactions for the settlement period starting from this date will be considered for the settlement process.

5.  Click **Tax adjustment** to open the **Tax adjustment** form and verify the tax setoff rule that is applied to the tax components.

6.  Click **Transactions** to open the **Transactions** form to view the transactions that are posted to the recoverable account and the payable account for the tax component.

7.  Select the transactions to be updated and click the **Update** button. The tax amounts are recalculated for the transactions that you select using the **Mark** check box, and the recalculated tax amounts are updated and displayed in the **Tax adjustment** form.

8.  Click **Adjustments** in the **Tax adjustment** form to open the **Adjustment** form.

9.  View the total of the amounts from the **Recoverable amount** field and the **Adjustment** field of the **Tax adjustment** form in the **Recoverable amount in total** field. When you transfer the excise recoverable amount, you can transfer the amount only to the extent that is available in the **Recoverable amount in total** field.

10. Press CTRL+N to create a new line.

11. Select the tax component to transfer the tax amount to in the **To tax component** field.

12. Enter the amount to transfer in the **Transfer amount** field. You can transfer the amount up to the extent displayed in the **Recoverable amount in total** field.

13. Click **Transfer** to recalculate and adjust the tax amounts between the tax components and close the **Adjustment** form. You can view the adjusted tax amounts in the **Tax adjustment** form, based on the adjustment made.
    

    > [!NOTE]
    > <P>You can transfer the excise recoverable amount from the recoverable account of one excise tax component to the recoverable account of another excise tax component to adjust the tax amounts. When an adjustment amount is transferred, the <STRONG>Update</STRONG> button in the <STRONG>Transactions</STRONG> form is not available.</P>



14. Specify the date that the tax report must be generated for in the **Transaction date** field in the **Sales tax payment** form.

15. Select the type of the excise transaction in the **Sales tax payment version** field.

16. Select the excise register in the **Priority RG register** field from the following options:
    
      - **RG23A**
    
      - **RG23C**
    

    > [!NOTE]
    > <P>Using the excise recoverable amount for the settlement of excise will be based on the excise register that you select in the <STRONG>Priority RG register</STRONG> field.</P>



17. Select the **Post to interim PLA** check box to post the deficit balance amount to the interim PLA. If the payable amount is more than the recoverable amount, and if the balance that is available in the PLA for any tax component is insufficient when you run the settlement process, you must select the **Post to interim PLA** check box to transfer the required balance amount to the interim Personal Ledger Account.

18. Select the **Update** check box. The balance amount is posted to the **Interim PLA** account only if you select this check box.

19. Click **OK** to save the settings and close the form. The tax components that have insufficient balances will be posted to interim Personal Ledger Account.
    

    > [!NOTE]
    > <P>The value in the <STRONG>Adjustment</STRONG> field of the <STRONG>Tax adjustment</STRONG> form is posted to the tax adjustment settlement account that is set up in the <STRONG>System accounts</STRONG> form (Click <STRONG>General ledger</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>Posting</STRONG> &gt; <STRONG>Accounts for automatic transactions</STRONG>.).</P>



20. You can verify the adjusted tax amount to pay to the excise authority for the tax settlement period in the **Tax adjustment** form.

## See also

[(IND) Excise registers inquiries](ind-excise-registers-inquiries.md)

[(IND) Tax adjustment (form)](https://technet.microsoft.com/en-us/library/jj664843\(v=ax.60\))

  


