---
title: (IND) Generate 26Q or 27Q quarterly statements for TDS
TOCTitle: (IND) Generate 26Q or 27Q quarterly statements for TDS
ms:assetid: 05b0a41e-c523-4677-ad86-3c7b4cd4a97d
ms:mtpsurl: https://technet.microsoft.com/library/JJ664451(v=AX.60)
ms:contentKeyID: 49385531
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- (IND)
- india
- 26q
- 27q
- Generate 26Q
- generate 27Q
- generate quarterly statements
- quarterly statements
- TDS
audience: Application User
ms.search.region: India
---

# (IND) Generate 26Q or 27Q quarterly statements for TDS 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

The deductors of tax at source can use the following two quarterly statements for Tax Deducted at Source (TDS):

  - **Form 26Q** – Quarterly statement of TDS generated for all payments other than salaries for residents.

  - **Form 27Q** – Quarterly statement of TDS generated for interest, dividend, or any other amount payable for nonresidents.

Form 26Q and Form 27Q statements display the following information:

  - TAN, PAN, assessment year, and details about statements that were previously filed.

  - Specific information about the deductor of tax at source. For more information, see [(IND) Key tasks: Tax information for legal entities](ind-key-tasks-tax-information-for-legal-entities.md).

  - Information about the person who is responsible for deducting taxes.

  - Details of taxes that are deducted and paid to the credit of Central Government.

  - Annexure with details of amounts paid and tax deducted from the deductees.

  - Verification section.

Form 26Q statement is generated for transactions with a **Resident** status, and Form 27Q is generated for transactions with a **Non-resident** status. The status is attached to the withholding tax component group. To view the status, open the **Withholding tax component groups** form. Click **General ledger** \> **Setup** \> **Withholding tax** \> **India** \> **Withholding tax component groups**.

The statements are generated for TDS transactions that are posted to payable accounts that are defined for TDS tax codes.

The following prerequisites are required to generate Form 26Q statements:

  - In the **Tax information** area of the **Legal entities** form, enter the Permanent Account Number (PAN) and withholding tax information.

  - In the **Withholding tax component groups** form, enter the section codes for all withholding tax component groups associated with TDS transactions that are posted for the period.

  - In the **Withholding tax codes** form, set up the reporting codes for the withholding tax components that are used for the TDS transactions that are posted for the period.

  - Enter the challan details for all TDS transactions that are posted for the period. For more information, see [(IND) Challan information (form)](https://technet.microsoft.com/library/jj677847\(v=ax.60\)).

## To generate 26Q or 27Q quarterly statements

1.  Click **General ledger** \> **Reports** \> **India** \> **TDS** \> **TDS statement**.

2.  Select the **Statement filed earlier** check box if the TDS statement has already been filed for the quarter. Enter the provisional receipt number of the TDS statement that was filed earlier in the **Provisional receipt number** field to generate a correction report.

3.  Select the Tax Account Number (TAN) to generate the TDS statement for.

4.  In the **Statement** field, select the type of TDS quarterly statement to be generated.

5.  Specify the ending date of the period that the TDS statement is generated for.
    
    The quarter that the TDS statement is to be generated is displayed in the **Period end** field.

6.  Enter the name and designation of the person who is responsible for TDS deduction for the quarter.

7.  Enter the date when you print the TDS statement.

8.  Select the **Generate file** check box to generate an electronic file (e-file) for the TDS statement that is generated for the quarter.
    
    If you are generating a correction statement or the statement was already filed for the quarter, select the **Generate corrected e-file** check box to generate an electronic file for the correction statement.

9.  Specify the name and location to save the e-file or correction e-file to.

10. Click **OK** to generate the TDS statement.
    

    > [!NOTE]
    > <P>If the TDS transaction is reversed using a credit note, only the net amount is displayed for the transaction in the annexure.</P>



## See also

[(IND) Withholding tax component groups (form)](https://technet.microsoft.com/library/jj678017\(v=ax.60\))

[(IND) Withholding tax reporting codes (form)](https://technet.microsoft.com/library/jj664934\(v=ax.60\))

  


