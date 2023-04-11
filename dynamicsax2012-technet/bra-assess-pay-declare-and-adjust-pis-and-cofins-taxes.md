---
title: (BRA) Assess, pay, declare and adjust PIS and COFINS taxes
TOCTitle: (BRA) Assess, pay, declare and adjust PIS and COFINS taxes
ms:assetid: 6a268b67-d768-4e38-a531-8bbdd0f7e70f
ms:mtpsurl: https://technet.microsoft.com/library/Mt267600(v=AX.60)
ms:contentKeyID: 66250922
author: tfehr
ms.date: 07/07/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Assess, pay, declare and adjust PIS and COFINS taxes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


This topic explains how to determine the amount of PIS and COFINS tax to be paid per fiscal organization for a specific month. The difference between the PIS and COFINS tax amount collected on sales of goods and the PIS and COFINS tax amount paid on purchases of goods is calculated. If the net amount is results in a tax liability, you can enter a vendor invoice journal entry and pay the amount of PIS and COFINS tax that you owe to the tax authority.

PIS and COFINS tax assessment is generated separted per tax type and per fiscal organization. When the tax assessment is created, the process warns when booking periods are missing for fiscal stablishment that belongs to the fiscal organization

PIS and COFINS tax assessment are created from the booking period of root fiscal establishment. When is created from fiscal establishment other than root, the action is disabled

## Assess and pay PIS and COFINS tax assessment

1.  Click Fiscal books \> Common \> Booking period.

2.  Select a booking period of root fiscal establishment.

3.  On the Action Pane Assessment, click PIS-COFINS .

4.  On the PIS and COFINS list page, on the Action Pane New, click PIS and COFINS tax assessment, and then click OK.

5.  PIS and COFINS tax assessment is created in a separate records.
    

    > [!NOTE]
    > <P>Fiscal books &gt; Common &gt; Tax assessment &gt; PIS-COFINS &gt; New is also used to create PIS and COFINS tax assessment.</P>



6.  If the sum of the tax debt is larger than the sum of tax credits, there will be a debit balance (liability) to be paid to the tax authorities. You can view the amounts in the FactBoxes on the PIS or COFINS list page. Enter this amount in a vendor invoice journal entry for the tax authority. For more information, see [Enter vendor invoices in journals](enter-vendor-invoices-in-journals.md).

7.  To create and post an PIS or COFINS tax payment, follow these steps.
    
    1.  Click Tax payment \> Create from assessment.
    
    2.  Enter the Receita code.
    
    3.  Enter an Interest amount or Fine amount value if this is a late tax payment.
    
    4.  The Voucher field is populated when the Accounts payable payment is posted.
    
    5.  Enter a Description for the tax payment.
    
    6.  Select the Authority that will receive the tax payment and terms of payment.
    
    7.  Enter a Referenced process number value and select the agency.
    
    8.  Click Post to post the tax payment in Accounts payable.
    
    9.  You can view the tax transactions for PIS and COFINS tax payment by clicking Tax transactions on the form.
    
    10. You can view the Voucher after posting by clicking Voucher button.

8.  You can reverse the Voucher payment posted in Tax payment form.

9.  Click **Transactions**.

10. Select the tax payment transaction to reverse, and then click Reverse transaction.

11. Enter the Date of the reversal, and then click OK.

## Create initial credit balance

In PIS and COFINS tax assessment, the credit amount from current period or amount coming from other period must be detailed by period. Use the Credit Balance option to verify the current available credit amount and/or introduce the initial credit balance when you start to use for the first time the process of tax assessment.

This information and amounts are later on reported into SPED Contributions under records 1100 for PIS tax and 1500 for COFINS tax.

1.  In the PIS or COFINS tax assessment, click Credit Balance.

2.  Click New to register the initial credit balance.

3.  Select the **Month** and **Year**.

4.  Select the Origin of this credit amount.

5.  Enter the CNPJ if the credit amount was transferred from other legal entity.

6.  Select the Credit type.

7.  In the **Previous periods** group, introduce the related amounts.
    
      - Initial credit balance
    
      - Credit deducted in the previous period if applicable
    
      - Credit reimbursed in the previous period if applicable
    
      - Credit compensated in the previous period if applicable

8.  Click **Recalculate** to update the amounts registered.

9.  In the **Current period** group, the assessment process will update all related amounts based on Tax assessment summary located in the right pane of the **Tax assessment** form.

## Create initial withholding balance

In PIS and COFINS tax assessment, the withholding amount from previous and current periods must be detailed by period. Use the Withholding balance option to verify the current available withholding amounts and/or introduce the initial withholding balance when you start to use for the first time the process of tax assessment.

This information and amounts are later on reported into SPED Contributions under records 1300 for PIS tax and 1700 for COFINS tax.

1.  In the PIS or COFINS tax assessment, click **Withholding Balance**.

2.  Click New to register the initial credit balance.

3.  Select the Month and Year.

4.  Select the Customer contribution type.

5.  Select the Assessment regimen.

6.  Enter the Total amount and the deducted amount on the period if applicable.

7.  Enter the Refunded and Compensation amount if applicable.

8.  Withholding balance is calculated based on the previous amounts registered.

9.  Click **Recalculate** button to update the current information.

## View tax assessment transactions

After you create a PIS and COFINS tax assessment, you can View all information that was included into the tax assessment process.You can view a list of adjustments, withholding, Non-fiscal operations, tax transactions and voucher payments.

1.  Click **Adjustment** to view the details of tax adjustment transactions posted into the tax assessment process. You can also view the details of related voucher or canceled voucher for the tax adjustment.

2.  Click **Fiscal documents** to view the details of fiscal document posted that belongs to this tax assessment process.

3.  Click **Non-fiscal documents** to view the details of non-fiscal operations posted that belongs to this tax assessment process.

4.  Click **Withholding taxes** to view the details of withholding tax transactions that applies to the tax assessment process.

5.  Click **Tax transactions** to view the details of tax transactions that belongs to the tax assessment process. You can also see the voucher that originates this tax transactions
    

    > [!NOTE]
    > <P>Tax transactions with CST = 49 and 99 are classified as Informative because there are not part of taxes to collect/recover and they are not considered as revenue as well.</P>



6.  Click **Voucher** to view the details of posted transaction generated when the tax assessment was finalized.

The following information describes how to complete closing procedures of tax assessment. You are not required to complete all of the following steps.

1.  Click Fiscal books \> Common \> Booking period \> Sync to synchronize all fiscal documents, non-fiscal operation and withholding taxes transactions that has not been transferred into the Fiscal books module. See [(BRA) Create a new booking period](bra-create-a-new-booking-period.md).

2.  Verify that all transactions have been transferred. **Fiscal books** \> **Common** \> **Booking period** \> **Fiscal documents** and select **Not booked** in Show display option, to verify that there are not pending fiscal documents to be transferred.

3.  Verify the PIS and/or COFINS tax assessment information. You can check the Tax assessment Summary, Credit balance and other relevant information available in the form.

4.  Process the tax payment if applicable (debit balance). **Fiscal books** \> **Common** \> **Tax assessment** \> **PIS-COFINS** \>**Tax payment**. Verify the Total amount posted in the Tax assessment summary.

5.  Click **Finalize**, to close the PIS and/or COFINS tax assessment.

6.  Click **Voucher** to see the voucher transactions generated by the Finalize process. Voucher is generated when there is debit balance or credit balance.

7.  After to complete the above steps you can generate the SPED Contributions tax statement.

8.  Click **Tax statement** \> **EFD Contributions** \> **Validate**, to validate the related information or **Execute** to generate the text file.

## See also

[(BRA) Brazilian parameters (form)](https://technet.microsoft.com/library/jj822920\(v=ax.60\))

[(BRA) About calculation of taxes](bra-about-calculation-of-taxes.md)

  


