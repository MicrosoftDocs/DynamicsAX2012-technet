---
title: (BRA) Set up interest and fines for customer payments
TOCTitle: (BRA) Set up interest and fines for customer payments
ms:assetid: ed1b025e-57db-4c41-93cf-025885e10069
ms:mtpsurl: https://technet.microsoft.com/library/JJ680912(v=AX.60)
ms:contentKeyID: 49624337
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BR - 00036
audience: Application User
ms.search.region: Brazil
---

# (BRA) Set up interest and fines for customer payments 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You must set up accounts for financial interest and fines, default codes for interest and fines, and interest codes and fines codes for customers, sales orders, and free text invoices. You must also define the holidays or non-business days in a financial year that are not considered when interest and fines are calculated.

## Set up a payment calendar and payment calendar rules

1.  Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment calendar**.

2.  Click **New**.

3.  In the **Payment calendar** field, enter the name of the payment calendar.

4.  To create a calendar for a specific country or region, select the **Location calendar** check box. Then select the country or region in the **Country/region** field.

5.  In the **Standard business week** field group, select the business days in a standard work week.

6.  In the **Display days for calendar year** field, enter the fiscal year to create the payment calendar for.

7.  To specify exception dates for the calendar year, click **Add**. In the **Date** field, select the date.

8.  In the **Type** field, specify whether the exception date is a business day or a holiday. For more information, see [Payment calendar (form)](https://technet.microsoft.com/library/jj677409\(v=ax.60\)).

9.  To specify exception dates for a state or province, click the **State/province holidays** button, and then enter the information in the **State/province holidays** form.
    

    > [!TIP]
    > <P>To also specify exception dates for cities, click <STRONG>City holidays</STRONG> in the <STRONG>State/province holidays</STRONG> form.</P>



10. Next, set up rules for the payment calendar. Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment calendar configuration – customers**.

11. Click **New**.

12. In the **Rule name** field that is displayed, enter an identifier for the rule.

13. In the **Rule type** field, select one of the following types:
    
      - **Specific** – Create a payment calendar rule for a specific combination of the method of payment and terms of payment. When you select this type of rule, the **Method of payment** and **Terms of payment** fields are displayed. You can use all combinations or a specific combination of the method of payment and terms of payment for the rule.
    
      - **Customer/vendor location** – Create a payment calendar rule for a specific country or region. When you select this type of rule, the **Customer - location** field group is displayed. Location information is retrieved from the documents in the order in which you arrange the documents in the list that is displayed. You can click **Move up** and **Move down** to arrange the documents.
    
      - **Company location** – Create a payment calendar rule for the primary address that is specified for the legal entity.

14. Click **Create rule**.

15. In the **Define rules** area, select **Active** to use the rule for the selected payment calendars. The rule becomes active when you close the form.

16. In the **Prioritize rules** area, select the rule, and then click **Move up** or **Move down** to move the rule up or down in the list.

17. If you are setting up a payment calendar rule for a country or region, in the **Select calendars** area, select the check box for each calendar to apply the rule to.

## Set up accounts for financial interest and fines

1.  Click **Accounts receivable** \> **Setup** \> **Customer posting profiles**.

2.  Select the posting profile.

3.  On the **Setup** FastTab, select the account code.

4.  In the **Financial interest** and **Fine** fields, select the ledger accounts to post the interest and fine amounts to for the customer account or the group.

## Set up interest codes for customers

You can set up interest codes to automatically calculate interest on overdue payments that are made by customers. The interest that is calculated for a customer is based on the rates and terms that are defined for the interest code.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Interest codes**.

2.  In the **Interest code** field, enter an identifier for the interest code.

3.  On the **Setup** FastTab, enter information in the following fields:
    
      - **Interest %** – Enter the interest percentage for the interest code.
    
      - **Interest calculation per** – Enter the number of days or months that the interest calculations are applied. The value in this field is based on the selection in the **Day/Mth** field.
    
      - **Day/Mth** – Select the unit of time that interest calculations are applied.
    
      - **Days** – Enter the number of grace days before the interest code is applied. The interest is calculated after the specified number of grace days from the payment due date.

## Set up fine codes for customers

You can set up fine codes to automatically calculate fines on delayed payments made by customers. A fine is calculated for a customer, based on the rates and terms that are defined for the fine code.

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Fine codes**.

2.  In the **Fine code** field, enter an identifier for the fine code.

3.  In the **Days** field, enter the number of grace days before the fine code is applied. The fine is calculated after the specified number of grace days from the payment due date.

4.  In the **Fine %** field, enter the fine percentage.

## Specify default codes for interest and fines for customers

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select a customer account. On the **Action Pane**, click **Edit**.

2.  In the **Customers** form, click the **Payment** FastTab. In the **Interest code** and **Fine code** fields, select the default codes for interest and fines for the customer.

## Specify interest codes and fine codes for sales orders

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Select the sales order. On the **Action Pane**, click **Edit**.

3.  In the **Sales order** form, click the **Price and discount** FastTab. In the **Interest code** and **Fine code** fields, select the codes for interest and fines. The interest and fines are calculated on the sales invoice if the payment is delayed.

## Define interest codes and fine codes for free text invoices

1.  Click **Accounts receivable** \> **Common** \> **Free text invoices** \> **All free text invoices**.

2.  Select the free text invoice, and then click **Edit**.

3.  Click the **Payment** FastTab. In the **Interest code** and **Fine code** fields, select the codes for interest and fines..

## See also

[About payment calendars](about-payment-calendars.md)

[Payment calendar (form)](https://technet.microsoft.com/library/jj677409\(v=ax.60\))

[Payment calendar configuration - vendors and customers (form)](https://technet.microsoft.com/library/jj677400\(v=ax.60\))

  


