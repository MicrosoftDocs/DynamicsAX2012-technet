---
title: About cash discounts
TOCTitle: About cash discounts
ms:assetid: 3fdf236c-0d8b-49b9-9e2d-6ec3645cc976
ms:mtpsurl: https://technet.microsoft.com/library/Aa496945(v=AX.60)
ms:contentKeyID: 36056710
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- discounts
- discount
- early
audience: Application User
ms.search.region: Global
---

# About cash discounts 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Cash discounts can be set up for both customers and vendors and can apply to both sales orders and purchase orders. Customers obtain a cash discount when they pay their invoices in a specified period of time, and the legal entity can also obtain cash discounts from vendors.

You create the cash discounts, which can apply to either customers or vendors, in the **Cash discounts** form. You can also define, by using the **Next discount code** field, a series of cash discounts that succeed each other as the invoice due date approaches. For more information, see “Example: Series of cash discounts” later in this topic.

If the invoice, credit transaction (either a payment or a credit note), or both use a currency other than the accounting currency of the legal entity that you are logged on to, the exchange rate for cash discounts is based on the date of the payment or credit note. If the invoice and credit document are entered in different legal entities, and if the accounting currencies for the legal entities differ, the exchange rate is taken from the legal entity of the invoice, as of the date of the credit document. For more information, see “Example: Exchange rates for cash discounts” later in this topic.

If an invoice is settled in time to obtain a cash discount, the cash discount is automatically posted to a cash discount ledger account according to the following account priority:

1.  The main account that is specified in the **Alternative cash discount account** field in the customer **Settle open transactions** form or the vendor **Settle open transactions** form.

2.  The main account that is specified in the **Customer cash discount** field or the **Vendor cash discount** field of the ledger posting group that is assigned to the sales tax code of the invoice. Set up ledger posting groups in the **Ledger posting groups** form and assign them to sales tax codes in the **Sales tax codes** form.

3.  The main posting account in either the **Main account for customer discounts** field or the **Main account for vendor discounts** field for the cash discount code of the customer or vendor that is on the settled invoice.

4.  The appropriate automatic account for cash discounts for customers or vendors, as defined in the **Accounts for automatic transactions** form.


> [!NOTE]
> <P>If the <STRONG>Public sector</STRONG> configuration key is selected, you can post cash discounts to the account or accounts that are specified on the invoice line. For more information, see the information about the <STRONG>Discount offset accounts</STRONG> field in <A href="https://technet.microsoft.com/library/aa596348(v=ax.60)">Accounts payable parameters (form)</A> and <A href="https://technet.microsoft.com/library/aa590275(v=ax.60)">Cash discounts (form)</A>.</P>



## Example: Series of cash discounts

Click **Accounts payable** \> **Setup** \> **Payment** \> **Cash discounts**.

–or–

Click **Accounts receivable** \> **Setup** \> **Payment** \> **Cash discounts**.

Set up three cash discount codes as follows:

  - Code 5D10% – A cash discount of 10% when the amount is paid within 5 days.

  - Code 10D5% – A cash discount of 5% when the amount is paid within 10 days.

  - Code 14D2% – A cash discount of 2% when the amount is paid within 14 days.

In the **Next discount code** field:

  - For the 5D10% code, select 10D5%.

  - For the 10D5% code, select 14D2%.

  - For the 14D2% code, leave the **Next discount code** field blank.

The three cash discounts succeed each other as the payment approaches the due date, and only one cash discount is granted when the invoice is paid.

## Example: Exchange rates for cash discounts

Your legal entity’s accounting currency is EUR and the following exchange rates are specified for USD:

  - February 1 = 110

  - March 1 = 80

An invoice for 1000 USD with cash discount terms of 20D2% is posted on February 15. The accounting currency amount of the invoice is 1100 EUR.

A payment for 980 USD is settled with the invoice on March 1. The cash discount amount is 20 USD. The accounting currency amount of the payment is 784 EUR. The accounting currency amount of the cash discount is calculated by using the exchange rate as of March 1: 20 \* 80 / 100 = 16 EUR.


> [!NOTE]
> <P>If the <STRONG>Calculate cash discounts for partial payments</STRONG> check box is selected in the <STRONG>Accounts receivable parameters</STRONG> or <STRONG>Accounts payable parameters</STRONG> forms, the exchange rate that is in effect on the date of each partial payment is used.</P>



## See also

[About partial customer payments](about-partial-customer-payments.md)

[About partial vendor payments](about-partial-vendor-payments.md)

[Cash discounts (form)](https://technet.microsoft.com/library/aa590275\(v=ax.60\))

[Settle open transactions - customer (form)](https://technet.microsoft.com/library/aa558602\(v=ax.60\))

[Settle open transactions - vendor (form)](https://technet.microsoft.com/library/aa619609\(v=ax.60\))

  


