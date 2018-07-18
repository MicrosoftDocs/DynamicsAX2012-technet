---
title: (IND) Calculate sales tax settlements
TOCTitle: (IND) Calculate sales tax settlements
ms:assetid: 20095e8f-ea77-4b78-9ff4-c387ffb5af49
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664545(v=AX.60)
ms:contentKeyID: 49385624
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: India
---

# (IND) Calculate sales tax settlements 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Before you submit a tax settlement to the tax authorities for a financial year, you must complete the periodic sales tax payment process to make the necessary tax adjustments. You can view the amount that is recoverable and payable for the specified period.


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



1.  Click **General ledger** \> **Periodic** \> **Sales tax payments** \> **Sales tax payments**.

2.  Select the sales tax registration group to process the settlement for.
    

    > [!NOTE]
    > <P>You can click <STRONG>Tax registration group</STRONG> to view the sales tax registration groups that have been set up.</P>



3.  Select the sales tax registration number to process the settlement for in the **Registration number** field.

4.  Select the settlement period to process the settlement for in the **Settlement period** field.

5.  Select the date to identify the settlement period in the **Date** field. All the transactions that are based on the settlement period are considered for the settlement process.

6.  Select the version of the sales tax report to be settled in the **Sales tax payment version** field.

7.  Click **Tax adjustment** to open the **Tax adjustment** form to view the details of the tax components in the specified tax registration group.

8.  In the **Tax adjustment** form, click **Transactions** to open the **Transactions** form to view the sales tax transactions that are posted for the tax component.
    
    The total recoverable amount for the sales tax component is displayed in the **Recoverable amount in total** field and the total amount that is payable for the sales tax component is displayed in the **Payable amount in total** field.

9.  Clear the **Marked** check box for the transactions that you do not want to settle.

10. Click **Update** to update the selected transactions with the recalculated value that is based on the tax setoff rules. If you close the form without clicking **Update**, the changes will not be saved and the settled transactions will not be listed in the **Transactions** form when the subsequent settlements are processed.
    

    > [!NOTE]
    > <P>The values are recalculated, based on the tax setoff rules if the <STRONG>Marked</STRONG> check box is cleared for specific transactions.</P>



11. Close the **Transactions** form.

12. In the **Tax adjustment** form, click **Adjustments** to open the **Adjustment** form to adjust the tax amount.
    

    > [!NOTE]
    > <P>You can view the sales tax settlement period after you complete the sales tax payment periodic process in the <STRONG>Tax adjustment</STRONG> form. For more information, see "Adjustment (form)" in the Applications and Business Processes Help.</P>



13. Select the tax component to transfer the specified amount to in the **To tax component** field.

14. Enter the recoverable amount to be transferred to the tax component in the **Transfer amount** field.
    

    > [!NOTE]
    > <P>The tax amount can be transferred only to the extent of the amount that is available in the <STRONG>Recoverable amount in total</STRONG> field.</P>

    
    You can view the total adjusted recoverable amount in the **Recoverable amount in total** field. This is the sum of amounts in the **Recoverable amount** field and the **Adjustment** field for the sales tax component in the **Tax adjustment** form.

15. Click **Transfer** to transfer the specified amount from the tax component to a different tax component.

16. Close the **Adjustment** form.
    

    > [!NOTE]
    > <P>If you make any adjustments and do not click <STRONG>Transfer</STRONG>, the changes will not be saved when you close the <STRONG>Adjustment</STRONG> form.</P>



17. Click **OK** in the **Tax adjustment** form to close the form and save the changes.
    

    > [!NOTE]
    > <P>The values in the <STRONG>Adjustment</STRONG> field are posted to the Tax adjustment – Settlement account based on the tax component. When the <STRONG>Tax adjustment</STRONG> form is reopened, the last record that is saved is displayed.</P>



18. Select the sales tax payment version in the **Sales tax payment version** field.

19. Select the **Update** check box on the **Sales tax payment** form to update the details for the tax adjustment and settlement.

20. Click **OK** to start the sales tax settlement process and generate the sales tax payment report. The tax settlement amount is posted to the vendor account. The voucher entries are generated and posted to the vendor authority based on the tax component.
    
    You can view the tax payment details, such as the sales tax code, the tax type, the tax registration number, the tax component for the tax registration number, the original amount, and the sales tax amount on the **Sales tax payment** report.

## See also

[(IND) Tax adjustment (form)](https://technet.microsoft.com/en-us/library/jj664843\(v=ax.60\))

[(IND) Transactions (form)](https://technet.microsoft.com/en-us/library/jj664764\(v=ax.60\))

[(IND) Sales tax payment (modified form)](https://technet.microsoft.com/en-us/library/jj664427\(v=ax.60\))

  


