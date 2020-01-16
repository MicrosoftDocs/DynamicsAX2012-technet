---
title: Set up elimination rules for transactions
TOCTitle: Set up elimination rules for transactions
ms:assetid: 333f2971-d689-499f-9e9a-0a0844e48a09
ms:mtpsurl: https://technet.microsoft.com/library/Gg231040(v=AX.60)
ms:contentKeyID: 36676382
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- rules
- elimination
- elimination transactions
- elimination rules
audience: Application User
ms.search.region: Global
---

# Set up elimination rules for transactions 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Although elimination rules can be created in any legal entity, to use elimination rules, you must set them up in a consolidation legal entity. A warning will be displayed if you open the **Ledger elimination rule** form, and the **Use for financial elimination process** option in the **Legal entities** form is not selected.


> [!NOTE]
> <P>We recommend that you use Management Reporter for Microsoft Dynamics ERP to combine the financial results for multiple legal entities in a consolidated format. Management Reporter lets you create consolidated financial reports across legal entities, use Microsoft Excel to import consolidation data from other sources, and translate amounts into any number of reporting currencies without having to run the consolidation process in Microsoft Dynamics AX.</P>
> <P>For more information about how to consolidate transactions by using Management Reporter, see <A href="https://go.microsoft.com/fwlink/?linkid=389548">Financial consolidations and currency translation</A>.</P>



Elimination rules are stored on a per-legal entity basis and must be unique in the legal entity that they are saved for.

You must specify an existing elimination legal entity in which the elimination journal will be created. The list will include all legal entities that you have access to. You can enter an elimination journal name that has a journal type of **Elimination** for processing.

## Create an elimination rule

1.  Click **General ledger** \> **Setup** \> **Posting** \> **Ledger elimination rule**.

2.  Click **New** to create a rule.

3.  Enter an identifier and a description for the elimination rule.

4.  In the **Destination company** field, select the legal entity where the elimination journal will be created.

5.  Enter or select the effective and expiration dates for the elimination rule.

6.  Select the **Active** check box to activate the elimination rule.

7.  In the **Name** field, select a journal name.

8.  Click **Lines** to create elimination rule lines.

## Create elimination rule lines

1.  Click **General ledger** \> **Setup** \> **Posting** \> **Ledger elimination rule**. Click **Lines**.

2.  Click **New** to create a line.

3.  Select the elimination method.
    
      - If you select **Net change**, go to step 4.
    
      - If you select **Fixed amount**, go to step 5.

4.  If the elimination method is **Net change**, enter or select information in the following fields.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field or button</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Source account</strong></p></td>
    <td><p>Select the account to retrieve the amount from.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Account specification</strong></p></td>
    <td><p>Select which account the transaction will be posted to for the destination legal entity.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Destination account</strong></p></td>
    <td><p>If you selected <strong>User specified</strong> in the <strong>Account specification</strong> field, select a destination account that will be used instead of the source account.</p>
    <p>If you selected <strong>Source</strong> in the <strong>Account specification</strong> field, the respective account that is defined in the source will be used during the allocation process.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Dimension specification</strong></p></td>
    <td><p>Select the dimension for the destination legal entity that the transaction will be posted to.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Source dimensions</strong> button</p></td>
    <td><p>Select the dimensions to retrieve the amount from.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Destination dimensions</strong> button</p></td>
    <td><p>If you selected <strong>User specified</strong> in the <strong>Dimension specification</strong> field, select the dimensions to associate to the elimination rule.</p>
    <p>If you selected <strong>Source</strong> in the <strong>Dimension specification</strong> field, the dimensions that are defined in the source will be used during the elimination process.</p></td>
    </tr>
    </tbody>
    </table>


5.  If the elimination method is **Fixed amount**, enter or select information in the following fields.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field or button</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Destination account</strong></p></td>
    <td><p>Select the account that the transaction will be posted to.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Fixed amount</strong></p></td>
    <td><p>Enter the debit amount for the destination account or dimension.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Destination dimensions</strong> button</p></td>
    <td><p>Select the dimensions to associate to the elimination rule.</p></td>
    </tr>
    </tbody>
    </table>


## See also

[Elimination rules for transactions](elimination-rules-for-transactions.md)

  


