---
title: (BRA) Assess, pay, declare, and adjust IPI taxes
TOCTitle: (BRA) Assess, pay, declare, and adjust IPI taxes
ms:assetid: 6569c8c1-eae1-425d-9c7f-33dffcd73a6f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn305870(v=AX.60)
ms:contentKeyID: 54912970
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.FBTaxAssessmentIPIListPage_BR
- MsDynAx060.Forms.FBTaxAssessmentIPIListPage_BR
---

# (BRA) Assess, pay, declare, and adjust IPI taxes [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic explains how to determine the amount of Imposto sobre Produtos Industrializados (IPI) tax to be paid per fiscal establishment for a specific month. The difference between the IPI tax amount collected on sales of goods and the IPI tax amount paid on purchases of goods is calculated. If the net amount is results in a tax liability, you can enter a vendor invoice journal entry and pay the amount of IPI tax that you owe to the tax authority.


> [!NOTE]
> <P>This topic applies only if KB 2839295 and KB 2850595 for Microsoft Dynamics AX 2012 R2 are installed, if cumulative update 6 or later for AX 2012 R2 is installed, or if AX 2012 R3 is installed.</P>



## Assess, pay, and declare IPI taxes

1.  Run IPI reports to determine whether there are any inconsistencies in IPI tax calculations. Follow these steps:
    
    1.  Click **Fiscal books** \> **Reports** \> **Incoming book 1A**. Select a fiscal establishment, enter the starting and ending dates, and then click **OK**. The Livro de Registro de Entrada report is printed.
    
    2.  Click **Fiscal books** \> **Reports** \> **Outgoing book 2A**. Select a fiscal establishment, enter the starting and ending dates, and then click **OK**. The Livro de Registro de Saída report is printed.

2.  Resolve inconsistencies that appear on the reports.

3.  Click **Fiscal books** \> **Common** \> **Booking period.**

4.  Select a booking period.

5.  On the **Action Pane**, click **IPI** and then select the month.

6.  On the **IPI** list page, on the **Action Pane**, click **IPI tax assessment**, and then click **OK**.

7.  On the **Action Pane**, click **Print** \> **IPI tax assessment book** to print the IPI assessment book (Resumo e Registro de Apuração de IPI) to verify the IPI amount collected and received from each fiscal document issued/received.

8.  If the sum of the tax debt is more than the sum of tax credits, there will be a debit balance (liability) to be paid to the tax authorities. You can view these amounts in the FactBoxes on the **IPI** list page. Enter this amount in a vendor invoice journal entry for the tax authority. For more information, see “Enter vendor invoices in journals” in the Application User Help.

9.  Register and settle the payment to the tax authority by using a payment journal or payment proposal. For more information, see “Select vendor invoices to pay and settle” in the Application User Help.

## Next step

[(BRA) Generate the SPED fiscal export file for a month](bra-generate-the-sped-fiscal-export-file-for-a-month.md)

## Adjust IPI tax assessments

1.  Click **Fiscal books** \> **Common** \> **Tax assessment** \> **IPI**. On the **Action Pane**, click **Adjustment**.

2.  In the **General tax adjust/benefit/incentive** form, click **New**.

3.  Select an adjustment code.

4.  Enter a complementary description.

5.  Enter the amount of the adjustment.

## See also

[(BRA) Assess, pay, declare, and adjust ICMS and ICMS-ST taxes](bra-assess-pay-declare-and-adjust-icms-and-icms-st-taxes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

