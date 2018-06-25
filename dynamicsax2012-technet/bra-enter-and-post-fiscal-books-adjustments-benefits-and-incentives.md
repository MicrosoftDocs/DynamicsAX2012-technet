---
title: (BRA) Enter and post fiscal books adjustments, benefits, and incentives
TOCTitle: (BRA) Enter and post fiscal books adjustments, benefits, and incentives
ms:assetid: 7ca1b157-f9a4-4b67-a26b-3e06082b3cff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn600276(v=AX.60)
ms:contentKeyID: 62200239
ms.date: 07/08/2015
mtps_version: v=AX.60
f1_keywords:
- ICMS
- forms.LedgerJournalTable
- fiscal books
- ICMS-ST
---

# (BRA) Enter and post fiscal books adjustments, benefits, and incentives [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create and post tax adjustment transactions and reverse posted tax adjustment transactions.

## Enter PIS and COFINS tax adjustment transactions

To enter and post tax adjustment transactions, follow these steps.

1.  Click **Fiscal books** \> **Journals** \> **General tax adjustment** \> **benefit** \> **incentive**.

2.  Click **New** to create a tax adjustment transaction

3.  In the **Name** field, select the journal name, which was created in the Journal names form. For more information, see Journal names setup (form).

4.  On the **Setup** tab, in the **Fiscal establishment ID** and **Tax type** fields, select the default fiscal establishment ID and the tax type.

5.  Click **Lines** to enter the tax adjustment transactions.

6.  In the **Journal lines** form, enter the date.

7.  Select the fiscal establishment ID.

8.  In the **Tax type** field, select the type of tax.

9.  Select the **adjustment code**, which was set up in the PIS and COFINS adjustment codes table form. For more information, see [(BRA) Set up adjustment codes for PIS and COFINS taxes](bra-set-up-adjustment-codes-for-pis-and-cofins-taxes.md).

10. Enter a description and the amount of the tax adjustment.

11. On the **Tax detail** group select the Taxation code.

12. Enter the Base amount.

13. Enter the percentage of PIS or COFINS in the Tax value.

14. Enter Complementary description in **Other details** group.

15. In the **Posting** field group, select the account and offset account. These accounts are selected in the **PIS or COFINS adjustment codes table** form.

16. Click **Validate** to confirm the information.

17. Click **Post** to post the tax adjustment transaction.

18. Repeat steps 2 through 16 to create additional tax adjustment transactions.

Additional information is required in the Other details group when the adjustment code type is Credit transfers, Cumulative deduction or Non cumulative deduction.

1.  Enter the CNPJ of company that is transferring the credit amount.

2.  Enter the Assessment period where the credit amount transferred was originated.

3.  Enter the percentage of credit in **Transferred credit percentage** field.

4.  Select the Credit base source.

## Enter Fixed asset credit appropriation transaction

To enter and register the fixed asset credit appropriation transactions, follow these steps.

1.  Click **Fiscal books** \> **Journals** \> **General tax adjustment** \> **benefit** \> **incentive**.

2.  Click **New** to create a tax adjustment transaction.

3.  In the **Name** field, select the journal name, which was created in the **Journal names** form. For more information, see [Journal names setup (form)](https://technet.microsoft.com/en-us/library/aa552517\(v=ax.60\)).

4.  On the **Setup** tab, in the **Fiscal establishment ID** and **Tax type** fields, select the default fiscal establishment ID and the tax type.

5.  Click **Lines** to enter the tax adjustment transactions.

6.  In the **Journal lines** form, enter the date.

7.  Select the fiscal establishment ID.

8.  Click **Functions** \> **Create PIS and COFINS asset credit transactions**.

9.  Select the Fiscal organization.

10. Enter the date.

11. Select the adjustment code that represents the credit appropriation in PIS asset credit adjustment code. The adjustment type is **Asset credit appropriation**.

12. Select the adjustment code that represents the credit appropriation in COFINS asset credit adjustment code. The adjustment type is **Asset credit appropriation**.

13. Automatically two lines are created, one for PIS and other for COFINS with the total amount of appropriate credit calculated in Fiscal books \> Tax assessment \> PIS-COFINS \> Asset credit appropriation.

14. Select the Credit base source, automatically is assigned to **Assets**.

15. In the **Posting** field group, select the account and offset account. These accounts are selected in the **PIS or COFINS adjustment codes table** form.

16. Click **Validate** to confirm the information.

17. Click **Post** to post the tax adjustment transaction.

## Enter and post tax adjustment transactions


> [!NOTE]
> <P>The <STRONG>Ledger integration is active</STRONG> option must be selected in the <STRONG>Ledger integration</STRONG> form before you can post or reverse tax adjustment transactions.</P>



To enter and post tax adjustment transactions, follow these steps:

1.  Run ICMS reports to determine whether there are any inconsistencies in ICMS tax calculations, and then enter and post tax adjustment transactions.
    
    To run the reports and enter and post tax adjustment transactions, follow these steps:
    
      - Click **Fiscal books** \> **Reports** \> **Incoming book**. Select a fiscal establishment, enter the starting and ending date, and then click **OK**. The Livro de Registro de Entrada report is printed.
    
      - Click **Fiscal books** \> **Reports** \> **Incoming book**. Select a fiscal establishment, enter the starting and ending date, and then click **OK**. The Livro de Registro de Saída report is printed.

2.  Click **Fiscal books** \> **Journals** \> **General tax adjustment/benefit/incentive**.

3.  Click **New** to create a tax adjustment transaction.

4.  In the **Name** field, select the journal name, which was created in the **Journal names** form. For more information, see [Journal names setup (form)](https://technet.microsoft.com/en-us/library/aa552517\(v=ax.60\)).

5.  On the **Setup** tab, in the **Fiscal establishment ID** and **Tax type** fields, select the default fiscal establishment ID and the tax type.

6.  Click **Lines** to enter the tax adjustment transactions.

7.  In the **Journal lines** form, enter the date.

8.  Select the fiscal establishment ID.

9.  In the **Tax type** field, select the type of tax.

10. Select the state that the fiscal establishment is located in.

11. In the **Adjustment type** field, select the type of adjustment transaction.

12. Select the adjustment code, which was set up in the **ICMS and ICMS-ST adjustment codes table** form. For more information, see [(BRA) Set up adjustment codes to use to adjust ICMS tax on fiscal documents](bra-set-up-adjustment-codes-to-use-to-adjust-icms-tax-on-fiscal-documents.md).

13. Enter a description and the amount of the tax adjustment.

14. In the **Posting** field group, select the account and offset account. These accounts are selected in the **ICMS and ICMS-ST adjustment codes table** form.

15. Click **Validate** to confirm the information.

16. Click **Post** to post the tax adjustment transaction.

17. Repeat steps 2 through 16 to create additional tax adjustment transactions.

## Register fiscal document adjustment transactions

To register tax adjustment transactions for fiscal documents, follow these steps:

1.  Click **Fiscal books** \> **Journals** \> **General tax adjustment/benefit/incentive**.

2.  Click **New** to create a tax adjustment transaction.

3.  In the **Name** field, select the journal name, which was created in the **Journal names** form. For more information, see [Journal names setup (form)](https://technet.microsoft.com/en-us/library/aa552517\(v=ax.60\)).

4.  On the **Setup** tab, in the **Fiscal establishment ID** and **Tax type** fields, select the default fiscal establishment ID and the tax type.

5.  Click **Lines**.

6.  In the **Adjustment type** field, select **Fiscal document**.

7.  Select the adjustment code.

8.  In the **Observation code** field, select the observation code for the fiscal document adjustment transaction.

9.  Enter the base amount and ICMS percentage.

10. Click **Functions** \> **Fiscal document**.

11. Select the related fiscal document on the **Customer** or **Vendor** tab.

12. Click **Close** to add the related fiscal document to the journal lines.

13. Click **Post** \> **Post** to post the journal to the general ledger.

## Reverse tax adjustment transactions

To reverse a posted tax adjustment transaction, follow these steps:

1.  Click **Fiscal books** \> **Journals** \> **General tax adjustment/benefit/incentive**.

2.  In the **Show** field, select **Posted**.

3.  Select the posted tax adjustment transaction to reverse.

4.  Click **Lines**.

5.  In the **Journal lines** form, click **Reverse**.

## See also

[(BRA) Set up adjustment codes for PIS and COFINS taxes](bra-set-up-adjustment-codes-for-pis-and-cofins-taxes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

