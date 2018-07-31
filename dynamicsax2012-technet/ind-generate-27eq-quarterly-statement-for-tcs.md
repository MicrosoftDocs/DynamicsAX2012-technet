---
title: (IND) Generate 27EQ quarterly statement for TCS
TOCTitle: (IND) Generate 27EQ quarterly statement for TCS
ms:assetid: 0504f685-72ef-442f-aa34-8a7a0acec57e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ664439(v=AX.60)
ms:contentKeyID: 49385529
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- 27EQ
- Generate 27EQ
- Generate quarterly statement
- india
- quarterly statement
- TCS
audience: Application User
ms.search.region: India
---

# (IND) Generate 27EQ quarterly statement for TCS 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The collectors of tax at source can use the 27EQ statement to report Tax Collected at Source (TCS) information to government authorities. The following prerequisites are required to generate Form 27EQ statements:

  - In the **Tax information** area of the **Legal entities** form, enter the Permanent Account Number (PAN) and withholding tax information. For more information, see [(IND) Key tasks: Tax information for legal entities](ind-key-tasks-tax-information-for-legal-entities.md).

  - In the **Withholding tax component groups** form, enter the section codes for all withholding tax component groups that are associated with the Tax Collected at Source (TCS) transactions posted for the period.

  - In the **Withholding tax codes** form, set up the reporting codes for the withholding tax components that are used for the TCS transactions posted for the period.

  - Enter the challan details for all TCS transactions that are posted for the period. For more information, see [(IND) Challan information (form)](https://technet.microsoft.com/en-us/library/jj677847\(v=ax.60\)).

## Generate the 27EQ quarterly statement

1.  Click **General ledger** \> **Reports** \> **India** \> **TCS** \> **TCS statement**.

2.  Select the **Statement filed earlier** check box if the TCS statement has already been filed for the quarter. Enter the provisional receipt number of the TCS statement that has been filed earlier in the **Provisional receipt number** field to generate a correction report.

3.  Select the Tax Account Number (TAN) to generate the TCS statement for.

4.  Specify the ending date of the period that the TCS statement is generated for.
    
    The quarter when the TCS statement is to be generated is displayed in the **Period end** field.

5.  Enter the name and designation of the person who is responsible for TCS collection for the quarter.

6.  Enter the date when you print the TCS statement.

7.  Select the **Generate file** check box to generate an electronic file (e-file) for the TCS statement that is generated for the quarter.
    
    If you are generating a correction statement or the statement has already been filed for the quarter, select the **Generate corrected e-file** check box to generate an electronic file for the correction statement.

8.  Specify the name and location to save the e-file or correction e-file to.

9.  Click **OK** to generate the TCS statement.

## See also

[(IND) Setting up Tax Collected at Source (TCS)](ind-setting-up-tax-collected-at-source-tcs.md)

[(IND) Legal entities (modified form)](https://technet.microsoft.com/en-us/library/jj664569\(v=ax.60\))

  


