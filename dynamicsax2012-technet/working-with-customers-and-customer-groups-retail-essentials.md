---
title: Working with customers and customer groups (Retail essentials)
TOCTitle: Working with customers and customer groups (Retail essentials)
ms:assetid: 5bd24cb8-bf7b-463f-b91b-a0369336753d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn736886(v=AX.60)
ms:contentKeyID: 62200364
ms.date: 12/17/2014
mtps_version: v=AX.60
f1_keywords:
- MsDynAx060.Forms.CustTableListPage
- MsDynAx060.Forms.DirPartyQuickCreateForm
---

# Working with customers and customer groups (Retail essentials) 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to create customer records and customer groups in Retail essentials. You can create groups that share characteristics such as payment terms and the length of time that is typically required for payments to be received after an invoice is due. You can then assign these groups to customers.


> [!NOTE]
> <P>In Retail essentials, the forms that you use to complete these tasks might include a subset of the controls that are available for other configurations of Retail. If another topic about these forms describes controls that you don't see, it may be because you’re using Retail essentials.</P>



## Create a customer record

Use this procedure to create a customer record in Retail essentials.

1.  Click **Retail essentials** \> **Customers** \> **All customers**. On the **Action Pane**, on the **Customer account** tab, in the **Customer account** group, click **Customer account**.

2.  In the **Customer** form, in the **Record type** field, select whether the customer is an organization or a person.

3.  If the customer already has a record, select the customer’s name. If the customer does not have an existing record, enter the customer’s name.

4.  Select the customer group and currency code that apply to the customer.

5.  Select the appropriate payment, delivery, and tax information for the customer.

6.  Select the country/region and the postal code where the customer is located, and enter any other address and contact information.

7.  Click **Customer account** to add more information to the customer record, or click **Customer account** to close the customer record. You can add more information to the record later.
    
    If you save the information that you entered and open the customer record to add more details, see [Customers (form)](https://technet.microsoft.com/en-us/library/aa590606\(v=ax.60\)) for more information.

## Create a customer group

Use this procedure to create one or more customer groups.

1.  Click **Retail essentials** \> **Customers** \> **Customer groups**.

2.  Click **New**. In the **Customer group** field, enter a unique identifier for the customer group.

3.  In the **Description** field, enter a short description of the customer group.

4.  In the **Terms of payment** field, select the terms of payment that apply to customers who are assigned to the selected customer group. Terms of payment are used to manage your customer accounts. We strongly recommend that you select terms of payments for customer groups.
    
    For more information, see [Terms of payment (form)](https://technet.microsoft.com/en-us/library/aa588427\(v=ax.60\)).

5.  In the **Settle period** field, select the standard interval between the due date for payments from customers in the selected customer group and the date on which the payments are received in your legal entity’s bank account. The due date is defined by the terms of payment. The settle period is used for liquidity calculations that are based on the cash flow forecast.

6.  Select the sales tax group the customer group, and then select the **Prices include sales tax** check box if appropriate.

## See also

[Create sales orders and customer invoices (Retail essentials)](create-sales-orders-and-customer-invoices-retail-essentials.md)

[Create or modify quotations (Retail essentials)](create-or-modify-quotations-retail-essentials.md)

  


