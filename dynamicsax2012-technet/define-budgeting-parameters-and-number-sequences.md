---
title: Define Budgeting parameters and number sequences
TOCTitle: Define Budgeting parameters and number sequences
ms:assetid: ff5559b1-295e-4cc0-b034-2eb61f286890
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227593(v=AX.60)
ms:contentKeyID: 36060131
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- budget appropriations
- budgeting number sequences
- number sequenes for budgeting
- budget journal
- budget parameters
- use rules for budget transfers
- revenue budget options
- parameters for budgeting
---

# Define Budgeting parameters and number sequences [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the **Budget parameters** form to enable budget transfers, and to specify options for revenue budgets and subledger budget transfers. You can also select the budget journal for budget appropriations and set up number sequences for Budgeting.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>



## In Microsoft Dynamics AX 2012 R3 and earlier

Use the following steps to define budgeting parameters and number sequences in AX 2012 R3 and earlier versions.

1.  Click **Budgeting** \> **Setup** \> **Budgeting parameters**.

2.  Select a period allocation key for cash flow forecasts. The allocation key determines how the amount for a budget account entry is allocated in a cash flow forecast. For more information, see [Period allocation categories (form)](https://technet.microsoft.com/en-us/library/aa582352\(v=ax.60\)).

3.  Select the **Use rules for budget transfers** check box to enable budget transfers.

4.  Select revenue budget options. You can allow or prevent updates if a budget register entry causes a revenue budget to go below 0 (zero). Alternatively, you can display warnings in this situation. You can also select a different time period for budget balances to aggregate for warnings or to prevent updates.

5.  Select whether to process budget register entries when they are transferred from project, fixed assets, demand forecast, or supply forecast budgets to general ledger budgets.

6.  If **Enable budget appropriation** is selected in the **General ledger parameters** form, select a budget journal to use for budget appropriations. This budget journal must have a journal type of **Budget** in the **Journal names** form. For more information, see [Journal names (form) (Project)](https://technet.microsoft.com/en-us/library/aa617509\(v=ax.60\)).
    

    > [!NOTE]
    > <P>Before you can select <STRONG>Enable budget appropriation</STRONG>, you must select <STRONG>Use posting definitions</STRONG> in the <STRONG>General ledger parameters</STRONG> form. You must also create posting definitions and transaction posting definitions. Then, when you enter a budget register entry for an account or financial dimension combination that is used in the match criteria of the posting definition, a voucher is created in the general ledger for the generated entry from the posting definition. The generated entry uses the journal number from the selected budget journal.</P>



7.  Click **Number sequences**, and then select number sequence codes:
    
      - Select a code for the **Budget register entries** reference.
    
      - Select a code for the **Commitments** reference.
        

        > [!NOTE]
        > <P>This control is available only if the following conditions are met:</P>
        > <UL>
        > <LI>
        > <P>The <STRONG>Public Sector</STRONG> configuration key is selected.</P>
        > <LI>
        > <P>The <STRONG>French regulatory</STRONG> configuration subkey is selected.</P>
        > <LI>
        > <P>In cumulative update 7 for Microsoft Dynamics AX 2012, the <STRONG>Use French public sector accounting rules</STRONG> check box is selected in the <STRONG>Budget parameters</STRONG> form.</P>
        > <LI>
        > <P>In versions of Microsoft Dynamics AX 2012 earlier than CU7, only the <STRONG>Public Sector</STRONG> configuration key must be selected, but the primary address of the legal entity must be in France.</P></LI></UL>

    
      - Select a code for the **Budget plans** reference.
        

        > [!NOTE]
        > <P>This control is available only if Microsoft Dynamics AX 2012 R2 or AX 2012 R3 is installed.</P>



You can also create new number sequences by using the **Number sequences** form. For more information about number sequences, see [Number sequences (form)](https://technet.microsoft.com/en-us/library/hh209531\(v=ax.60\)).

## In Microsoft Dynamics AX 2012 R3 Cumulative Update 8 with hotfix KB3047235

 If you are in the public sector and are using general budget reservations, see also [Set up general budget reservation rules and reservation types (Public sector)](set-up-general-budget-reservation-rules-and-reservation-types-public-sector.md).


> [!NOTE]
> <P>General budget reservations are available only if the <STRONG>Public Sector</STRONG> configuration key is selected and if Microsoft Dynamics AX 2012 R3 Cumulative Update 8 is installed with the following hotfix: KB3047235</P>



Use the following steps to define budgeting parameters and number sequences.

1.  Click **Budgeting** \> **Setup** \> **Budgeting parameters**.

2.  Select a period allocation key for cash flow forecasts. The allocation key determines how the amount for a budget account entry is allocated in a cash flow forecast. For more information, see [Period allocation categories (form)](https://technet.microsoft.com/en-us/library/aa582352\(v=ax.60\)).

3.  Select the **Use rules for budget transfers** check box to enable budget transfers.

4.  Select revenue budget options. You can allow or prevent updates if a budget register entry causes a revenue budget to go below 0 (zero). Alternatively, you can display warnings in this situation. You can also select a different time period for budget balances to aggregate for warnings or to prevent updates.

5.  Select whether to process budget register entries when they are transferred to general ledger budgets from project, fixed assets, demand forecast, or supply forecast budgets.

6.  If **Enable budget appropriation** is selected in the **General ledger parameters** form, select a budget journal to use for budget appropriations. This budget journal must have a journal type of **Budget** in the **Journal names** form. For more information, see [Journal names (form) (Project)](https://technet.microsoft.com/en-us/library/aa617509\(v=ax.60\)).
    

    > [!NOTE]
    > <P>Before you can select <STRONG>Enable budget appropriation</STRONG>, you must select <STRONG>Use posting definitions</STRONG> in the <STRONG>General ledger parameters</STRONG> form. You must also create posting definitions and transaction posting definitions. Then, when you enter a budget register entry for an account or financial dimension combination that is used in the match criteria of the posting definition, a voucher is created in the general ledger for the generated entry from the posting definition. The generated entry uses the journal number from the selected budget journal.</P>



7.  Under **Regulatory**, in the **Regulatory document type for your region** list, select the correct document type for your region.
    

    > [!NOTE]
    > <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



8.  Click **Number sequences**, and then select number sequence codes:
    
      - Select a code for the **Budget register entries** reference.
    
      - Select a code for the **General budget reservations** reference.
        

        > [!NOTE]
        > <P>This control is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>

    
      - Select a code for the **Commitments** reference.
        

        > [!NOTE]
        > <P>This control is available only if the following conditions are true:</P>
        > <UL>
        > <LI>
        > <P>The <STRONG>Public Sector</STRONG> configuration key is selected.</P>
        > <LI>
        > <P>The <STRONG>French regulatory</STRONG> configuration subkey is selected.</P>
        > <LI>
        > <P>The <STRONG>Commitments (France)</STRONG> regulatory document type is selected in the <STRONG>Budget parameters</STRONG> form.</P></LI></UL>

    
      - Select a code for the **Budget plans** reference.
    
    You can also create new number sequences by using the **Number sequences** form. For more information about number sequences, see [Number sequences (form)](https://technet.microsoft.com/en-us/library/hh209531\(v=ax.60\)).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

