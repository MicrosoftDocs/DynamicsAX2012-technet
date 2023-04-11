---
title: (BRA) Assess, pay, declare, and adjust ICMS and ICMS-ST taxes
TOCTitle: (BRA) Assess, pay, declare, and adjust ICMS and ICMS-ST taxes
ms:assetid: 6348f356-84a4-43a5-84ac-203627f491c3
ms:mtpsurl: https://technet.microsoft.com/library/Dn305871(v=AX.60)
ms:contentKeyID: 54912971
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.FBTaxAssessmentICMSListPage_BR
- Forms.FBTaxAssessmentICMSSTListPage_BR
- MsDynAx060.Forms.FBTaxAssessmentICMSListPage_BR
- MsDynAx060.Forms.FBTaxAssessmentICMSSTListPage_BR
audience: Application User
ms.search.region: Brazil
---

# (BRA) Assess, pay, declare, and adjust ICMS and ICMS-ST taxes 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to determine the amount of Imposto sobre Circulação de Mercadorias e Serviços (ICMS) tax to be paid per fiscal establishment for a specific month. This topic also explains how to generate the ICMS tax payment that allows the registration and posting of the ICMS tax payment with fiscal-related information. The difference between the ICMS tax amount collected on sales of goods and the ICMS tax amount paid on purchases of goods is calculated. If the net amount gives you a tax liability, you can enter a vendor invoice journal entry and pay the amount of ICMS tax that you owe to the tax authority.


> [!NOTE]
> <P>The procedure for completing this task has changed for Microsoft Dynamics AX 2012 R3. For information that is specific to Microsoft Dynamics AX 2012 R3, see the section later in this topic.</P>



## Assess, pay, and declare ICMS taxes

1.  Run ICMS reports to determine whether there are any inconsistencies in ICMS tax calculations. Follow these steps:
    
    1.  Click **Fiscal books** \> **Reports** \> **Incoming book**. Select a fiscal establishment, enter the starting and ending date, and then click **OK**. The Livro de Registro de Entrada report is printed.
    
    2.  Click **Fiscal books** \> **Reports** \> **Incoming book**. Select a fiscal establishment, enter the starting and ending date, and then click **OK**. The Livro de Registro de Saída report is printed.

2.  Resolve any inconsistencies that appear on the reports.

3.  Click **Fiscal books** \> **Common** \> **Booking period**.

4.  Select a booking period.

5.  On the **Action Pane**, click **ICMS**, and then select the month.

6.  On the **ICMS** list page, on the **Action Pane**, click **ICMS tax assessment**, and then click **OK**.

7.  On the **Action Pane**, click **Print** \> **ICMS tax assessment book** to print the ICMS assessment book (Registro de Apuração de ICMS modelo P9). This report shows the monthly total accounting values and tax values for ICMS on incoming and outgoing fiscal documents for goods and services.

8.  If the sum of the tax debt is larger than the sum of tax credits, there will be a debit balance (liability) to be paid to the tax authorities. You can view the amounts in the FactBoxes on the **ICMS** list page. Enter this amount in a vendor invoice journal entry for the tax authority. For more information, see “Enter vendor invoices in journals” in the Application User Help.

9.  To create and post an ICMS tax payment, follow these steps:
    
    1.  Click **Fiscal books** \> **Common** \> **Tax assessment** \> **ICMS**.. Select an ICMS tax assessment. In the **New** group, click **ICMS tax assessment**.
    
    2.  Click **Create from assessment** to create the ICMS tax payment from the ICMS tax assessment.
        
        \-or-
        
        Click **Other debit** to create a tax payment for a specific tax adjustment transaction.
        
        This creates record E116 for the ICMS tax payment and record E250 for the ICMS-ST tax payment of SPED fiscal obligation. The **Payment type** field is populated depending on whether the tax payment was created from a tax assessment or from other debits.
    
    3.  Enter the values in the **ICMS to pay code** and **Receita code** fields for the tax payment.
    
    4.  Enter an **Interest amount** or **Fine amount** value if this is a late tax payment.
        
        The **Voucher** field is populated when the Accounts payable payment is posted.
    
    5.  Enter a description for the tax payment.
    
    6.  Select the authority that will receive the tax payment and terms of payment.
    
    7.  Enter a **Referenced process number** value and select the agency.
    
    8.  Click **Post** to post the tax payment in Accounts payable.
        
        You can view the tax transactions for an ICMS tax payment by clicking **Tax transactions** on the **ICMS** list page.

## Reverse payments

1.  Click **Fiscal books** \> **Common** \> **Tax assessment** \> **ICMS**.

2.  On the **Action pane**, click **Tax payment**.

3.  In the **Tax payment** form, click **Transactions**.

4.  Select the tax payment transaction to reverse, and then click **Reverse transaction**.

5.  Enter the date of the reversal, and then click **OK**.

## Next step

[(BRA) Generate the SPED fiscal export file for a month](bra-generate-the-sped-fiscal-export-file-for-a-month.md)

## Adjust ICMS tax assessments

To change the tax amount for a specific ICMS or ICMS tributary substitution (ICMS-ST) tax assessment, you can enter an adjustment.

1.  Click **Fiscal books** \> **Common** \> **Tax assessment** \> **ICMS**. On the **Action Pane**, click **Adjustment**.

2.  In the **General tax adjust/benefit/incentive** form, click **New**.

3.  Select an adjustment code.

4.  Enter a complementary description.

5.  If necessary, select the **Tax difference** check box.

6.  Enter the amount of the adjustment.

## Adjust ICMS-ST tax assessments

1.  Click **Fiscal books** \> **Common** \> **Tax assessment** \> **ICMS**. On the **Action Pane**, click **Adjustment**.

2.  In the **General tax adjust/benefit/incentive** form, click **New**.

3.  Select an adjustment code.

4.  Enter a complementary description.

5.  Enter the amount of the adjustment.

## View retail Z report

When ICMS taxes are assessed, the taxable amount of the Z reports are considered and classified during the assessment process. You can view the retail Z reports of fiscal receipts and related fiscal receipts.

1.  Click **Fiscal books** \> **Common** \> **Booking period**. On the **Action Pane**, click **Z reports**.

2.  In the **Z reports** form, you can verify taxable amounts and other fiscal information.

3.  Click **Fiscal receipts** to open the **Fiscal receipts** form.

4.  View the taxable information about the related fiscal receipts.

## View ECF daily operations report

When ICMS taxes are assessed, the taxable amount of the Z reports are considered and classified during the assessment process. View all Z reports for a specific day for all fiscal printers located in the fiscal establishment.

A sequence number is generated for each report when the booking period is synchronized.

1.  Click **Fiscal books** \> **Common** \> **Booking period**. On the **Action Pane**, click **ECF daily operations report**.

2.  In the **ECF daily operations report** form, you can verify Z report amounts for a specific date or date range.

3.  You can set up the **Next ECF daily operation report number** value in the **Fiscal establishments** form. Click **Organization administration** \> **Setup** \> **Brazil** \> **Fiscal establishments**. On the **Retail** FastTab, in the **Next ECF Daily Operation Report Number** field, enter the next report number.

## See also

[(BRA) Assess, pay, declare, and adjust IPI taxes](bra-assess-pay-declare-and-adjust-ipi-taxes.md)

  


