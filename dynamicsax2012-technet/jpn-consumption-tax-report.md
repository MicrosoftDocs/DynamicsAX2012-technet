---
title: (JPN) Consumption tax report
TOCTitle: (JPN) Consumption tax report
ms:assetid: 340a1f92-75f2-4a15-b8fe-49e96309bcd4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ711028(v=AX.60)
ms:contentKeyID: 49386439
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (JPN) Consumption tax report 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic has not been fully updated for Microsoft Dynamics AX 2012 R2.</P>



The Japanese taxation authority requires that all businesses file a consumption tax report that consists of an official consumption tax form and a worksheet. You can use the **Consumption tax report** form to view or enter tax calculation details and additional information about taxes.

1.  Click **General ledger** \> **Reports** \> **External** \> **Japanese sales tax report**.

2.  Enter the required details and click **OK** to open the **Consumption tax calculation sheet** form.
    

    > [!NOTE]
    > <P>For more information, see <A href="jpn-create-a-calculation-worksheet-and-print-the-consumption-tax-reports.md">(JPN) Create a calculation worksheet and print the consumption tax reports</A>.</P>



3.  Click **Functions** \> **Finalize** to finalize the calculations in the **Consumption tax calculation sheet** form.

4.  Click **Functions** \> **Consumption tax report** to open the **Consumption tax report** form.
    
    The fields on the **Header** tab, **Tax calculation** tab, and **Additional information** tab in the **Consumption tax report** form are explained below.
    
      - The details of the tax office name and the place of tax payment are displayed in the **Taxation office name** and **Place of tax payment** fields.
    
      - The name of the company and the name of the company representative are displayed in the **Company name**, **Company representative**, and **Accounting personnel** fields.
    
      - The period of tax calculation is displayed in the **From date** and **To date** fields for final sales tax reports.
    
      - The dates for interim sales tax reports are displayed in the **From date for mid term declaration** and **To date for mid term declaration** fields.

5.  Verify that the base amount to be taxed is displayed in the **Item 1** field.

6.  View or enter the consumption tax amount in the **Item 2** field.

7.  Verify that the adjustment amount of excessive tax deduction is displayed in the **Item 3** field.

8.  Verify that the qualified purchasing tax deduction amount is displayed in the **Item 4** field.

9.  Verify that the reimbursement tax amount is displayed in the **Item 5** field.

10. Verify that the tax amount for the uncollectible bad debt amount is displayed in the **Item 6** field.
    
    The subtotal of tax deducted in the **Item 7** field is the sum of the amounts in the **Item 4**, **Item 5**, and **Item 6** fields.

11. Verify that the tax refund amounts due to insufficient amount of tax deductions are displayed in the **Item 8** field.

12. Verify that the netted tax amount is displayed in the **Item 9** field.

13. Enter the interim tax amount in the **Item 10** field.
    
      - The tax payment amount in the **Item 11** field is the difference of the netted tax amount and the interim tax amount. The amount is displayed if the netted tax amount is greater than the interim tax amount.
    
      - The tax refund amount against the interim tax payment is displayed in the **Item 12** field. The amount is displayed if the interim tax amount is greater than the netted tax amount.

14. The previously declared tax amount is displayed in the **Item 13** field.

15. Enter the netted tax payment amount in the **Item 14** field.

16. Verify that the disposed amount of taxable assets is displayed in the **Item 15** field.

17. Verify that the disposed amount of assets is displayed in the **Item 16** field.

## View additional information about taxes

1.  On the **Additional information** tab, select the **Installment basis** check box to apply the installment basis.

2.  Select the **Deferred payment basis** check box to apply deferred payment.

3.  Select the **Percentage of completion basis** check box to apply the percentage of completion basis.

4.  Select the **Cash basis accounting** check box to apply the cash basis accounting.

5.  Select the **Exceptional tax calculation treatment** check box to apply the exceptional tax calculation treatment.

6.  Select the **Individual method** check box for the individual method of tax calculation.

7.  Select the **Lump sum method** check box for the lump sum method of tax calculation.

8.  Select the **Fully deductable** check box if the tax amount is fully deductible.
    

    > [!NOTE]
    > <P>The taxable base amount is displayed in the <STRONG>Taxable base amount</STRONG> field. The consumption tax amount is displayed in the <STRONG>Consumption tax amount</STRONG> field.</P>



9.  Enter the amount in the **Taxable sales amount of benchmark period** field.

10. Select the bank account in the **Bank information** field if **Bank** is selected for the refund payment method.

11. Enter the comments for the report in the **Comments** field.

12. Enter the name of the tax accountant in the **Name of the tax accountant** field.

13. Select the **Document submitted law No.30** check box if the document is submitted.

14. Select the **Document submitted law No.33-2** check box if the document is submitted.

15. Click **Functions** to select the following options:
    
      - **Update amount** – Calculate the amounts on the basis of the data entered.
    
      - **Finalize** – Finalize the report after the data is confirmed.
    
      - **Print reports** – Print the calculation sheet and consumption tax reports. This option is available after you select the **Finalize** option.

## Verify the tax amounts

1.  Verify that the amount of tax refunded due to an insufficient amount of tax deduction is displayed in the **Item 17** field.

2.  Verify that the netted tax amount, tax refund amount, and tax payment amount are displayed in the **Item 18**, **Item 19**, and **Item 20** fields.

3.  Enter the amount in the interim tax payment amount (local) in the **Item 21** field.

4.  Verify that the amounts in the tax payment amount (local) and the tax refund amount against the interim tax payment amount (local) are displayed in the **Item 22** and **Item 23** fields.

5.  View or enter the amount in the previously declared tax amount (local) in the **Item 24** field when the report is an Amendment Final or Amendment Interim tax declaration, which amends a Final or Interim tax declaration that was previously submitted.

6.  Enter the amount in the netted tax payment amount (local) in the **Item 25** field.

7.  Verify that the calculated amount for the consumption tax and local consumption tax total amount (payment/refund) is displayed in the **Item 26** field.

## See also

[(JPN) Consumption tax working sheet (form)](https://technet.microsoft.com/en-us/library/jj710998\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

