---
title: Create charges codes
TOCTitle: Create charges codes
ms:assetid: a68a5c6b-5aeb-4544-9eef-01e6c5af6d3b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550275(v=AX.60)
ms:contentKeyID: 44081022
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create charges codes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you have to track sales amounts or purchase amounts in addition to line items, you can use charges codes. For example, you might pay freight and insurance on a purchase order, and these amounts might be itemized separately on the purchase order. You can specify whether these amounts are posted to expense accounts, or whether they are added to the cost of the items.

You can create charges codes for Accounts receivable and Accounts payable.

## Set up charges codes for Accounts receivable

1.  Click **Accounts receivable** \> **Setup** \> **Charges** \> **Charges code**.

2.  Click **New**. In the **Charges code** field, type a code for the charge.

3.  In the **Description** field, type a description of the charge.

4.  Optional: In the **Item sales tax group** field, select a sales tax group.

5.  On the **Posting** FastTab, specify how the charge is automatically debited and credited.

6.  If you selected **Ledger account** as the debit type or credit type, specify a posting type in the **Posting** fields, and specify the main account in the **Account** fields.

## Example

Your customer pays the charge. Therefore, the charge is added to the sales order totals. You set up the following posting information:

  - In the **Type** field in the **Debit** field group, select **Customer/Vendor** to add the invoice charge to the customer's account.

  - In the **Type** field in the **Credit** field group, select **Ledger account**. Then, in the **Account** field, select the main account for revenue from invoice charges.


> [!NOTE]
> <P>You can enter a different currency for the charge transaction if the debit type or credit type is either <STRONG>Ledger account</STRONG> or <STRONG>Item</STRONG> for the selected code.</P>
> <P>You can print the text for charges in the language that is assigned to the customer. Click <STRONG>Translations</STRONG> to specify text for the charges code in other languages.</P>



## Set up charges codes for Accounts payable

1.  Click **Accounts payable** \> **Setup** \> **Charges** \> **Charges code**.
    
    –or–
    
    Click **Procurement and sourcing** \> **Setup** \> **Charges** \> **Charges code**.

2.  Click **New**. In the **Charges code** field, type a code for the charge.

3.  In the **Description** field, type a description of the charge.

4.  Optional: In the **Item sales tax group** field, select a sales tax group.

5.  Optional: In the **Maximum amount** field, type the maximum amount that is allowed for this charges code.
    
    This field is used to validate charges for vendor invoices. You can enable the validation of charges in the **Accounts payable parameters** form. In the **Invoice validation** area, select the **Enable invoice matching validation** check box.
    

    > [!IMPORTANT]
    > <P>To validate charges for invoices, you must also create an instance of a policy rule type that is based on charges for the specific vendor invoice policy. For more information, see <A href="key-tasks-vendor-invoice-policies.md">Key tasks: Vendor invoice policies</A>.</P>



6.  On the **Posting** FastTab, specify how the charge is automatically debited and credited.

7.  If you selected **Ledger account** as the debit type or credit type, specify a posting type in the **Debit posting** and **Credit posting** fields, and specify the main account in the **Debit account** and **Credit account** fields.

8.  To enable the comparison of charges values for an invoice that contains the charges from the corresponding purchase order header or lines, select the **Compare purchase order and invoice values** check box.

## Example

You can record the charge as an expense as part of the total for the purchase order or vendor invoice. You set up the following posting information:

  - In the **Type** field in the **Credit** field group, select **Customer/Vendor** to add the invoice charge to the vendor's account.

  - In the **Type** field in the **Debit** field group, select **Ledger account**. Then, in the **Account** field, select the main account for expenses from invoice charges.

To add the unit charge to the item cost, you set up the following posting information:

  - In the **Type** field in the **Credit** field group, select **Customer/Vendor** to add the invoice charge to the vendor's account.

  - In the **Type** field in the **Debit** field group, select **Item** to add the charge to the item cost.


> [!NOTE]
> <P>You might want to use a currency other than the currency that is specified on the purchase order or invoice. You can enter a different currency if the debit type or credit type is either <STRONG>Ledger account</STRONG> or <STRONG>Item</STRONG> for the selected code.</P>
> <P>You can print the text for charges in the language that is assigned to the vendor. Click <STRONG>Translations</STRONG> to specify text for the charges code in other languages.</P>



## See also

[Set up shipping carriers](set-up-shipping-carriers.md)

[Charges totals details/Compare charges values (form)](https://technet.microsoft.com/en-us/library/hh242731\(v=ax.60\))

  


