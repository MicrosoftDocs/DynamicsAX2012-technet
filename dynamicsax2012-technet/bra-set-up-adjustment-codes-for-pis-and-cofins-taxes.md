---
title: (BRA) Set up adjustment codes for PIS and COFINS taxes
TOCTitle: (BRA) Set up adjustment codes for PIS and COFINS taxes
ms:assetid: 9f5fa725-dd22-4b08-a3ce-abc5a6aa97b1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Mt267601(v=AX.60)
ms:contentKeyID: 66250921
ms.date: 07/07/2015
mtps_version: v=AX.60
---

# (BRA) Set up adjustment codes for PIS and COFINS taxes [AX 2012]


In a Sistema Publico de Escrituração Digital (SPED) Contributions the users are available to introduce specific adjustment transactions to adjust the credit or debit of PIS and COFINS amounts that are reported into the records M220, M225, M620, M625, M110, M115, M510 and M515. Before you can adjust PIS and COFINS taxes, you must specify the adjustment codes that are determined by the Brazilian government depending on the adjustment criteria and type of adjustment transaction. This topic explains how to set up adjustment codes to be applied PIS and COFINS taxes. You do this by using the PIS and COFINS adjustment codes table form. For information about how to enter PIS and COFINS tax adjustment transactions, see [(BRA) Enter and post fiscal books adjustments, benefits, and incentives](bra-enter-and-post-fiscal-books-adjustments-benefits-and-incentives.md).

## Set up adjustment code for PIS and COFINS taxes

To set up the adjustment code table 4.2.8 and 4.3.8 defined by the government follow these steps.

1.  Click **Fiscal books** \> **Setup** \> **Tax adjustment codes** \> **PIS and COFINS adjustment code table**.

2.  Click **New** and enter an adjustment code in the Identification field and a description of the adjustment code.

3.  Select a **tax type**.

4.  Select the **adjustment type** from the following options:
    
      - Debit increase
    
      - Debit decrease
    
      - Credit increase
    
      - Credit decrease
    
      - Cumulative deduction
    
      - Non Cumulative deduction
    
      - Credit transfer – This adjustment type is used to register credit amount that has been transferred from other companies.
    
      - Asset credit appropriation – This adjustment is used to register the credit amount coming from fixed assets.

5.  Enter the SPED **adjustment code**. This option is not available when you selected the adjustment type **Asset credit appropriation**.
    

    > [!NOTE]
    > <P>This information is enabled when you selected the adjustment types: Debit increase/decrease and Credit increase/decrease because these type of adjustment code are reported in the records mentioned above.</P>



6.  Select the **Transfer event** code. This option is available when the Adjustment type selected is Credit Transfer.

7.  In the **Valid from** and **Valid to** fields, enter the first and last dates that the adjustment codes are applicable.

8.  On the **Payment** FastTab, select the **Other debit** check box if you want to create an additional tax adjustment payment that is not included in the periodic payment.

9.  Enter the **Receita code** assigned for this individual tax payment.

10. On the **Posting** FastTab, in the **Company accounts** field, select the legal entity where the tax adjustment transactions will be posted.

11. In the **Sales tax code** field, select the tax code that will be used to select the accounts receivable or accounts payable account. The account that is selected depends on whether the tax adjustment is a debit or credit. For more information, see [Set up and use sales tax codes](set-up-and-use-sales-tax-codes.md).

12. Select the **Main account** that will be used to post the revenue or expense part of the adjustment transaction.

## See also

[(BRA) Enter and post fiscal books adjustments, benefits, and incentives](bra-enter-and-post-fiscal-books-adjustments-benefits-and-incentives.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

