---
title: About payment calendars
TOCTitle: About payment calendars
ms:assetid: b295a699-94fd-452a-b7f4-b709d35c6bff
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ677355(v=AX.60)
ms:contentKeyID: 49384130
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# About payment calendars 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes how to set up payment calendars in Accounts payable and Accounts receivable. You can use payment calendars, together with payment calendar rules, to make sure that payment due dates and the start date for grace periods for invoices are always set on business days.

When you set up a payment calendar, you can specify non-business days for countries and regions. You can also specify additional holidays at the state and province levels, or for any other purpose, such as non-banking days. When a payment is due or interest and fees are set to start on a non-business day, they will instead be due or start on the closest business date. The closest business date can be either before or after the original date, depending on the options that you select.


> [!NOTE]
> <P>If you will add holidays at the state and province level, the states and provinces must be defined for the country or region that is associated with the payment calendar.</P>



To start using payment calendars, you must create one or more payment calendar rules.

## Payment calendar rules

You can set up rules for all payment calendars, for all customers and vendors, or for specific payment calendars, customers, or vendors. Payment calendar rules determine which payment calendar will be used. After you create payment calendar rules, you can arrange the rules according to their priority.

You can create the following types of rules:

  - **Company location** – Use the primary address of your legal entity to determine the payment calendar to use. You can create only one company location rule. To create a company location rule, you must select a location calendar.

  - **Customer/vendor location** – Use the address information on the document, or the customer’s or vendor’s default bank account, to determine the payment calendar to use. You can specify the order in which you want the system to search sources for location information. You can create only one customer/vendor location rule, and it applies to all customers and vendors.

  - **Specific** – Use the method of payment and terms of payment that are specified on the document or journal as the criteria that determine the payment calendar to use. You can also use specific rules to create alternate rules for a company location rule or a customer/vendor location rule.
    
    For example, to create a specific rule that applies to only one customer, you must assign unique terms of payment to the customer. You can then use the terms of payment in a payment calendar rule. You must also ensure that the rule has a higher priority than the company location rule.

To start applying rules, select either **Next business day** or **Previous business day** in the **Due date update** field in the **Terms of payment** form.

## Payment calendars for interest calculations

You can also assign payment calendars to interest codes. If you define a payment calendar for an interest code, you can do the following:

  - Specify whether state or province holidays are applied, if the associated payment calendar supports these holidays based on the primary address of the customer.

  - Specify whether business days are considered when grace periods are calculated.

  - Specify whether interest calculation starts on the next business day or the previous business day when the due date is on a non-business day.

## See also

[Set up a payment calendar and payment calendar rules](set-up-a-payment-calendar-and-payment-calendar-rules.md)

[Payment calendar (form)](https://technet.microsoft.com/en-us/library/jj677409\(v=ax.60\))

[Payment calendar configuration - vendors and customers (form)](https://technet.microsoft.com/en-us/library/jj677400\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

