---
title: Set up bank reconciliation matching rules
TOCTitle: Set up bank reconciliation matching rules
ms:assetid: ebaf0bb3-0e99-4138-846a-872469aa093a
ms:mtpsurl: https://technet.microsoft.com/library/JJ729761(v=AX.60)
ms:contentKeyID: 49564927
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up bank reconciliation matching rules 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can set up reconciliation matching rules and reconciliation matching rule sets to help the bank reconciliation process. Reconciliation matching rules are a set of criteria that are used to filter bank statement lines and bank document lines during the reconciliation process. You can set up more than one matching rule and create a reconciliation matching rule set in the **Reconciliation matching rule sets** form. Use the **Reconciliation matching rules** form to set up the reconciliation matching rules.


> [!NOTE]
> <P>Bank reconciliation matching rules are used if you are reconciling an electronic bank statement using advance bank reconciliation.</P>



  - In the **Reconciliation matching rules** form, you can select which actions and selection criteria are used when the matching rule is run.

  - In the **Actions** group, select which action will be taken when the matching rule is run during the reconciliation process.
    

    > [!NOTE]
    > <P>The option that you select will determine which fields are displayed.</P>

    
      - **Match with bank document** – Create criteria to specify how the bank documents and bank statement lines are matched when the matching rule is run from the **Bank reconciliation worksheet**. The transaction lines are selected according to the additional criteria set up on the FastTabs.
    
      - **Clear reversal statement lines** – Create criteria to specify how reversal statement lines should be removed from the **Bank reconciliation worksheet** form when the matching rule is run. This option is used when the bank makes a mistake and there are two bank statement lines listed in the imported bank statement and the lines must be reconciled.
    
      - **Mark new transactions** –Create criteria to specify how new transactions should be marked on the **Bank reconciliation worksheet** when the matching rule is run.
    

    > [!NOTE]
    > <P>Different selection criteria options are available, depending on which option that you select in the <STRONG>Actions</STRONG> group.</P>



  - The selection criteria that are available to set up when **Match with bank document** action is selected include the following:
    
      - **Step 1: Find statement lines** – Indicates which bank statement lines will be selected from the **Bank reconciliation worksheet** form by adding the selection fields.
    
      - **Step 2: Find bank documents** - Indicates which bank documents are selected for bank reconciliation by selecting basic criteria.

  - The selection criteria that are available to be set up when the **Clear reversal statement lines** action is selected include the following:
    
      - **Step 1: Find reversal statement lines** – Add selection criteria to select reversal bank statement lines.
        
        For example, to select only checks, select the **Bank transaction code** in the **Field** field, select the **+** in the **Operator** field, and then enter **Checks** in the **Value** field.
    
      - **Step 2: Find original statement lines** – You can add selection criteria to match bank document line to bank statement lines.
    
      - **Step 3: Find bank documents** – You can add selection criteria to match bank document lines to bank statement lines. Select the **Search bank documents** check box to search bank document transactions for the selected bank statement transaction.

  - The selection criteria that are available to be set up when the **Mark new transactions** action is selected include the following:
    
      - **Step 1: Find statement lines** – Indicates which bank statement lines will be selected from the **Bank reconciliation worksheet** form by adding the selection fields.
    
      - **Step 2: Do not include bank documents** – You can add selection criteria to search bank document lines based on criteria, a statement line will be marked as a new transaction if no bank document is found. Select the **Search bank documents** check box to search bank document transactions for the selected bank statement transaction during the reconciliation process.

## Example

Suppose that you want to create a reconciliation matching rule that will match payments.

1.  Click **Cash and bank management** \> **Setup** \> **Bank reconciliation** \> **Reconciliation matching rules**.

2.  Select **New** and enter a name in the **Matching rule** field and a description in the **Name** field.

3.  In the **Actions** group, select the **Match with bank document** action.

4.  On the **Step 1: Find statement lines** FastTab, click **Add** to create a new line.

5.  In the **Field** field, select **Bank transaction code**.

6.  In the **Operator** field, select **=**.

7.  In the **Value** field, enter **PMT**.

8.  To create matching criteria for bank documents, on the **Step 2: Find bank documents** FastTab, you can select options in the **Basic criteria** group.
    
    These options include the following:
    
      - **Check difference of amount** – Select this check box and enter .01 to indicate that you will accept a penny different between the bank document amount and the bank statement amount.
    
      - **Check difference of days** – Select this check box and enter 5 to indicate there can be five days difference between the bank document line date and the bank statement line date.

9.  In the **Additional criteria** group, in the **Field** field, select **Bank transaction type**.

10. In the **Operator** field, select **=**.

11. In the **Value** field, enter a value that is equal to the customer payment transaction type in the **Bank transaction types** form.

12. Click **Activate** to activate the reconciliation matching rule.

## See also

[Bank reconciliation worksheet (form)](https://technet.microsoft.com/library/jj729766\(v=ax.60\))

[Reconciliation matching rules (form)](https://technet.microsoft.com/library/jj729773\(v=ax.60\))

  


