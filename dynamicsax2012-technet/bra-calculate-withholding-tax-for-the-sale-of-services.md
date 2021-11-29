---
title: (BRA) Calculate withholding tax for the sale of services
TOCTitle: (BRA) Calculate withholding tax for the sale of services
ms:assetid: a1e62480-cbc8-49bd-92b1-81a3b5769b43
ms:mtpsurl: https://technet.microsoft.com/library/Dn126105(v=AX.60)
ms:contentKeyID: 52075263
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BR - 00034
audience: Application User
ms.search.region: Brazil
---

# (BRA) Calculate withholding tax for the sale of services 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Use the **Journal voucher** form to enter and post payments that you receive from customers for the sale of items or services. When you post a customer payment journal, the withholding tax group that is set up for the customer is used to calculate the withholding tax on the transaction.


> [!NOTE]
> <P>To indicate that a customer is liable to pay withholding tax, you must select the <STRONG>Calculate withholding tax</STRONG> check box, and select a withholding tax group for the customer. For more information, see <A href="bra-set-up-a-withholding-tax-group-and-attach-it-to-a-customer-or-vendor.md">(BRA) Set up a withholding tax group and attach it to a customer or vendor</A>.</P>



Use the following procedures to calculate the withholding tax transactions when you can receive services by using the settlement process.

## Set up withholding tax for services

1.  Click **Product information management** \> **Common** \> **Released products**. Select a product and then click **Edit**.

2.  On the **Purchase** FastTab, select the **Calculate withholding tax** check box to enable the calculation of withholding tax for a service.

3.  In the **Item withholding tax group** field, select the item withholding tax group that is created for Program de Integração Social (PIS), Contribuição para Financiamento da Seguridade Social (COFINS), or Contribuição Social sobre Lucro Líquido (CSLL).

## Calculate a sales order

1.  Click **Sales and marketing** \> **Common** \> **Sales orders** \> **All sales orders**. To open an existing sales order, double-click the sales order. To create a new sales order, on the **Action Pane**, on the **Sales order** tab, click **Sales order**.
    
    –or–

2.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**. To open an existing sales order, double-click the sales order. To create a new sales order, on the **Action Pane**, on the **Sales order** tab, click **Sales order**.

3.  In the **Create sales order** form, select a customer account that is updated with the withholding tax setup. For more information, see [Create or edit a sales order](create-or-edit-a-sales-order.md).

4.  In the **Sales order lines** grid, click **Add line** or press CTRL+N to create a new sales order line. Select the service that is updated with the withholding tax details in the **Released product details** field.
    

    > [!NOTE]
    > <P>On the <STRONG>Line details</STRONG> FastTab, click the <STRONG>Setup</STRONG> tab to view the <STRONG>Withholding tax group</STRONG> and <STRONG>Item withholding tax group</STRONG> fields, which are selected for a service.</P>



5.  On the **Sell** tab, in the **Generate** group, click **Confirm** to confirm the sales order.

6.  On the **Invoice** tab, click **Invoice** to post the customer invoice. For more information, see [(BRA) Sales posting (modified form)](https://technet.microsoft.com/library/jj853383\(v=ax.60\)) and [Key tasks: Customer invoices](key-tasks-customer-invoices.md).

## Calculate withholding tax for service sales

1.  Click **Accounts payable** \> **Journals** \> **Payments** \> **Payment journal**. Create a payment journal, and then click **Lines** to open the **Journal voucher** form.

2.  In the **Account** field select the customer account that is updated with the withholding tax for services. The **Withholding tax group** field is updated with the withholding tax group that is assigned to the customer in the **Customers** form. For more information, see [(BRA) Journal voucher - Customer payment journal (modified form)](https://technet.microsoft.com/library/jj933499\(v=ax.60\)).

3.  Click **Functions** \> **Settlement**

4.  Select the **Mark** check box for each transaction that you want to settle. The withholding tax amount for those transactions is calculated and displayed on the **Withholding tax** tab.

5.  Click **OK** to close the form.

6.  In the **Journal voucher** form, in the **Tax withhold edit status** field, one of the following statuses is displayed for the payment journal line:
    
      - **Not applicable** – The withholding tax codes with a **Percentage of gross amount in month** origin do not apply to any invoice lines of the selected invoice in payment journal line.
    
      - **Opened** – The withholding tax code with a **Percentage of gross amount in month** origin applies to any invoice line of the selected invoice in the payment journal line, and the invoice is not considered in the calculation of the withholding tax for other invoices. The payment journal line that is set to **Opened** is available for editing.
    
      - **Closed** – The withholding tax code with a **Percentage of gross amount in month** origin applies to any invoice line of the selected invoice in the payment journal line, and the invoice is considered in the calculation of the withholding tax for other invoices. The payment journal line that is set to **Closed** is not available for editing.

7.  In the **Offset account type** field, select **Bank**.

8.  Click **Post** \> **Post** to post the customer payment journal.

## See also

[Reverse settlements](reverse-settlements.md)

[(BRA) Reverse a check or Bordero payment](bra-reverse-a-check-or-bordero-payment.md)

  


