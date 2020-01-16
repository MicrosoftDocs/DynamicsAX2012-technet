---
title: Create alert rules
TOCTitle: Create alert rules
ms:assetid: 4b00add8-f1d3-43e7-929d-ff7e523eec8c
ms:mtpsurl: https://technet.microsoft.com/library/Aa497014(v=AX.60)
ms:contentKeyID: 46687541
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create alert rules 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create alert rules from any form in Microsoft Dynamics AX, or from the **Manage alert rules** form.

If the form that contains the data that you want to monitor is open, you can also right-click an item on the form, and then select **Create alert rule** on the **Command** menu.

## Create a rule in a form

1.  Open the form that contains the data to monitor.

2.  Right-click the field for which you want to set up an alert rule, or right-click anywhere in the form, and then click **Create alert rule**.
    
    –or–
    
    On the **Command** menu, click **Create alert rule**.

3.  In the **Create alert rule** form, in the **Field** list, select the field to monitor.

4.  In the **Event** list, select the type of event.

5.  In the **Alert me for** section, select an option.
    
    For more information, see [About alert rules](about-alert-rules.md).

6.  If you want the alert rule to become inactive on a specific date, in the **Alert me until** section, select an end date.
    
    For more information, see [About alert rules](about-alert-rules.md).

7.  In the **Subject** field, accept the default subject heading for the email message, or enter a new subject. The text is used as the subject heading for the email message that you receive when an alert is triggered.

8.  In the **Message** field, enter an optional message. The text is used as the message that you receive when an alert is triggered.

9.  Click **OK** to save the settings and create the alert rule.

## Example: Create an alert rule for postponement of a delivery date

1.  Click **Accounts payable** \> **Common** \> **Purchase orders** \> **All purchase orders**.

2.  Double-click a purchase order.

3.  In the **Purchase order** form, expand the **Purchase order header** tab.

4.  Right-click the **Delivery date** field, and then select **Create an alert rule**.

5.  In the **Create alert rule** form, in the **Event** list, select **has been postponed**.

When you close the **Create alert rule** form, your rule appears in the **Manage alert rules** form.

## Example: Create an alert rule for new sales orders

1.  Click **Accounts receivable** \> **Common** \> **Sales orders** \> **All sales orders**.

2.  Right-click a sales order, and then select **Create an alert rule**.

3.  In the **Create alert rule** form, in the **Event** field, select **Record has been created**.

When you close the **Create alert rule** form, your rule appears in the **Manage alert rules** form.

## Create a rule by using the Manage alert rule form

When you create an alert rule in a form, the **Manage alert rules** form also opens. You can then create additional alerts for the same form.

For more information, see [Manage alert rules](manage-alert-rules.md).

  - In the **Manage alert rules** form, click **Create alert rule**, and then click the form name that appears on the submenu.

## Create a rule by using a template

If you base your alert rules on a predefined template, you do not have to set up all the details of each alert rule.

1.  On the **File** menu, click **Tools**, and then select **Manage alert rules**.

2.  Click **Create alert rule**, and then click **From template** or press CTRL+N. A list of all the company-specific templates that are available is displayed.

3.  Select the template to use, and then click **OK**.

4.  In the **Manage alert rules** form, on the **General** tab, in the **Alert me for** and **Alert me with** sections, select the appropriate options.

## See also

[About alert rules](about-alert-rules.md)

[About creating alert rules](about-creating-alert-rules.md)

  


