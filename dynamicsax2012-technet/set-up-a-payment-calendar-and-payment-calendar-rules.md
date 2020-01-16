---
title: Set up a payment calendar and payment calendar rules
TOCTitle: Set up a payment calendar and payment calendar rules
ms:assetid: 0bdd2f18-f71b-41d7-bfac-c2b854cdb709
ms:mtpsurl: https://technet.microsoft.com/library/JJ677322(v=AX.60)
ms:contentKeyID: 49384095
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a payment calendar and payment calendar rules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This procedure describes how to set up a payment calendar, and how to specify dates that are non-business days, such as public holidays. For more information about payment calendars, see [About payment calendars](about-payment-calendars.md).

## Set up a payment calendar

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Payment calendar**.
    
    –or–
    
    Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment calendar**.

2.  Click **New**.

3.  In the **Payment calendar** field, enter the name of the payment calendar.

4.  To create a calendar for a specific country or region, select the **Location calendar** check box. Then, select the country or region in the **Country/region** field.

5.  In the **Standard business week** field group, select the business days in a standard work week.

6.  In the **Display days for calendar year** field, enter the fiscal year to create the payment calendar for.

7.  To specify exception dates for the calendar year, click **Add**. In the **Date** field, select the date.

8.  In the **Type** field, specify whether the exception date is a business day or a holiday. For more information, see [Payment calendar (form)](https://technet.microsoft.com/library/jj677409\(v=ax.60\)).

## Configure payment calendar rules

After you set up payment calendars, you can set up rules that determine the payment calendar that will be used to calculate due dates for customer and vendor payments, or to calculate grace periods. For more information about these rules, see [About payment calendars](about-payment-calendars.md).

1.  Click **Accounts payable** \> **Setup** \> **Payment** \> **Payment calendar configuration - vendors**.
    
    –or–
    
    Click **Accounts receivable** \> **Setup** \> **Payment** \> **Payment calendar configuration – customers**.

2.  Click **New**.

3.  In the **Rule name** field that is displayed, enter an identifier for the rule.

4.  In the **Rule type** field, select one of the following types:
    
      - **Specific** – Create a payment calendar rule for a specific combination of the method of payment and terms of payment. When you select this type of rule, the **Method of payment** and **Terms of payment** fields are displayed. You can use all combinations or a specific combination of the method of payment and terms of payment for the rule.
    
      - **Customer/vendor location** – Create a payment calendar rule for a specific country or region. When you select this type of rule, the **Customer - location** or **Vendor location** field group is displayed. Location information will be retrieved from the documents in the order in which you arrange the documents in the list that is displayed. You can click **Move up** and **Move down** to arrange the documents.
    
      - **Company location** – Create a payment calendar rule for the primary address that is specified for the legal entity.

5.  Click **Create rule**.

6.  In the **Define rules** area, select **Active** to use the rule for the selected payment calendars. The rule becomes active when you close the form.

7.  In the **Prioritize rules** area, select the rule, and then click **Move up** or **Move down** to move the rule up or down in the list.

8.  If you are setting up a payment calendar rule for a country or region, in the **Select calendars** area, select the check box for each calendar that you want the rule to apply to.

## See also

[Payment calendar (form)](https://technet.microsoft.com/library/jj677409\(v=ax.60\))

[Payment calendar configuration - vendors and customers (form)](https://technet.microsoft.com/library/jj677400\(v=ax.60\))

  


