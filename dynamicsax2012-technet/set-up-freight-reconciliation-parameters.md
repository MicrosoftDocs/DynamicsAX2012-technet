---
title: Set up freight reconciliation parameters
TOCTitle: Set up freight reconciliation parameters
ms:assetid: c1345cb5-f568-4810-92d8-b651edfecdde
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553197(v=AX.60)
ms:contentKeyID: 62200151
ms.date: 11/21/2014
mtps_version: v=AX.60
f1_keywords:
- reconciliation
- Forms.TMSFreightBillType
- Forms.TMSFreightBillTypeAssignment
- Forms.TMSFreightMatchReason
- MsDynAx060.Forms.TMSFreightBillType
- MsDynAx060.Forms.TMSFreightBillTypeAssignment
- MsDynAx060.Forms.TMSFreightMatchReason
- freight bill type
- freight bill type assignment
- freight reconciliation
- reconciliation reason
- unmatched freight bills
audience: Application User
ms.search.region: Global
---

# Set up freight reconciliation parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic explains how to set up freight bill types, freight bill type assignments, and reconciliation reasons for the freight reconciliation process. After you’ve set up these parameters, you can match freight bills that are generated in Microsoft Dynamics AX with invoices that are received from shipping carriers. You can use either an automatic or a manual process for freight reconciliation.

Use the following procedures to set up the parameters for automatic or manual freight reconciliation.

## Set up a freight bill type

Use the **Freight bill type** form to configure the engine assembly and engine type used during the automatic reconciliation process. You can also configure freight bill type descriptions, which determine the data fields that are used for matching. For example, in the **Description** field, you can select **Shipping carrier** and then use the **Match required** field to specify whether matching is required for a particular outbound load with the status **Shipped**.

To set up a freight bill type, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Freight reconciliation** \> **Freight bill type**.

2.  Click **New** to create a freight bill type.

3.  In the **Freight bill type** field, enter a unique identifier (ID) for the freight bill type.

4.  In the **Engine type** field, enter the type of the engine. For example, the engine could be a mileage engine, a generic engine, or a zone engine.

5.  In the **Engine assembly** field, enter a description for the engine assembly. For example, enter Microsoft.Dynamics.Ax.Tms.dll as the engine assembly code.

6.  On the **Details** FastTab, click **New** to create the details that indicate how freight bill records are used for matching.

7.  The **Sequence** field shows the sequence in which the freight bill type to be processed is displayed. You can modify the sequence, if you need to.

8.  In the **Description** field, select the item that you want to reconcile against.

9.  In the **Match required** field, select either **Yes** or **No** to indicate if the reconciliation criterion must be matched during the freight reconciliation process.
    

    > [!NOTE]
    > <P>You can use this setting to specify how records with empty fields should be treated. Select <STRONG>No</STRONG> to include&nbsp;these records or <STRONG>Yes</STRONG> to exclude them.</P>



## Set up a freight bill type assignment

Use the **Freight bill type assignments** form to set up the criteria for assigning a particular freight bill type to freight bill detail and invoice lines on a freight bill.

To set up a freight bill type assignment, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Freight reconciliation** \> **Freight bill type assignments**.

2.  Create a new freight bill type assignment.

3.  In the **Direction** field, select the direction of the load.

4.  In the **Mode** field, select the mode of transportation for the freight. To set up additional transportation modes, see [Set up a transportation mode and method for a shipping carrier](set-up-a-transportation-mode-and-method-for-a-shipping-carrier.md).

5.  In the **Shipping carrier** field, select a shipping carrier. To set up additional shipping carriers, see [Set up shipping carriers and carrier groups](set-up-shipping-carriers-and-carrier-groups.md).

6.  Optional: In the **Site** and **Warehouse** fields, select the site and warehouse for the freight.

7.  In the **Freight bill type** field, select the freight bill type to assign to the freight bill detail line and the invoice line.

## Set up a reason code for freight reconciliation

Use the **Reconciliation reasons** form to set up reason codes for unmatched freight bills. If an invoice amount does not match the related freight bill, you can use these reason codes to reconcile the different amounts.

To set up a reason code, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Freight reconciliation** \> **Reconciliation reasons**.

2.  Create a new reconciliation reason.

3.  Enter a name and a description for the reconciliation reason.

4.  Optional: Select the **Debit account** that is used to pay the reconciled amount to the freight vendor.

5.  Optional: Select the **Credit account** that is used to post to the general ledger account. You can only select a value in this field if the **Pay the freight vendor** check box is not selected.

6.  Optional: Select the **Pay the freight vendor** check box to pay the reconciled amount to the vendor.
    
    If you select a debit account and the **Pay the freight vendor** check box is not selected, you must specify a ledger account in the account field for the non-payment of freight.
    
    If you select a credit account, the following processes will be used during financial posting for reconciliation:
    
      - If the **Pay the freight vendor** check box is selected, the credit is posted against the freight vendor to create a payable account.
    
      - If the **Pay the freight vendor** check box is not selected, the ledger account is taken from the reason code.

7.  Optional: Select the **Override accounts** check box to override the charges that are posted to the debit account type that is specified in the **Charges code** form for the original sale order line or purchase order line. The charges are posted to the accounts specified in the **Reconciliation reasons** form.
    
    If you select a debit account, the following processes will be used during financial posting for reconciliation:
    
      - If the **Override accounts** check box is selected, the debit account that is specified for the reconciliation reason code is used as the account in the vendor invoice journal for reconciled amounts.
    
      - If the **Override accounts** check box is not selected, the ledger account that is specified for the debit account type in the **Charges code** form is used for posting a vendor account or customer account.

## Related tasks

[Set up an audit master for freight reconciliation](set-up-an-audit-master-for-freight-reconciliation.md)

## Technical information for system administrators

If you don't have access to the pages that are used to complete this task, contact your system administrator and provide the information that is shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Category</p></th>
<th><p>Prerequisite</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Configuration keys</strong></p></td>
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>

  


