---
title: Set up rules for fraud alerts
TOCTitle: Set up rules for fraud alerts
ms:assetid: f5fda8c6-8c6a-4da6-9b8f-1b7df9b4e625
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn631663(v=AX.60)
ms:contentKeyID: 62381662
ms.date: 05/28/2014
mtps_version: v=AX.60
---

# Set up rules for fraud alerts [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to set up rules to alert customer service representatives of potentially fraudulent information when orders are processed. You can define specific codes to use to automatically or manually put suspicious orders on hold.

## Prerequisite: Enable fraud checking

Before you set up and use fraud checking rules, you must enable fraud checking and define the basic fraud checking values.

1.  Click **Call center** \> **Setup** \> **Call center parameters**.

2.  In the **Call center parameters** form, in the left pane, click **Holds**.

3.  On the **Fraud** FastTab, select the **Fraud check** check box to enable fraud checking.

4.  In the **Manual fraud hold code** and **Fraud hold code** fields, select the codes that will be shown if an order is placed on fraud hold either manually or automatically.

5.  Enter the minimum scores allowed in the next fields, and in the **Fraud comment type** field, select the comment type that will be used when a customer or a customer order is manually put on hold.

## Define variables, conditions, and rules for fraud alerts

Before you create a rule, you must create the variables and conditions that define who the rule applies to and when the rule should be applied. For example, you want to create a rule to require that when customer 1202 places an order that is worth1,000.00 or more, the sales order must be put on hold until the customer payment can be verified.

In this example, the variables are customer 1202 and order total 1,000.00. The conditions are that when customer 1202 places an order that is equal to or more than 1,000.00, the sales order will be placed on hold until the customer payment is verified.

Use the procedures in this section to set up the variables, conditions, and rules that will be applied to fraud alerts.

## Set up fraud variables

Use this procedure to set up variables for fraud rules.

1.  Click **Call center** \> **Setup** \> **Fraud** \> **Variables**.

2.  In the **Variables** form, click **New**, and enter a name.

3.  Enter a brief description of the field variable.

4.  In the **Variable table** field, select the table that contains the field variable.
    
    For the example above, you would select **CustTable**, because that is the table that contains the customer ID field.

5.  In the **Field** field, select the field whose value will be used as the variable.
    
    For the example above, you would select **AccountNum**, because that is the field that contains customer ID.

6.  Repeat steps 2 through 5 to add more variables.

## Set up fraud conditions

Use this procedure to set up fraud conditions.

1.  Click **Call center** \> **Setup** \> **Fraud** \> **Conditions**.

2.  In the **Conditions** form, click **New** to create a new condition.

3.  Enter the name and a brief description of the condition and then select the table that the condition is based on.
    
    For the example above, you would select the **CustTable** table.

4.  On the **Fields** FastTab, click **Add** to add fields and field information to the condition.

5.  In the **Field type** field, select the method type or table field and then, in the **Field** field, select the field whose value will be used in the condition.

6.  In the **Value type** field, select whether a variable or value will be used in the condition, and then select an operand for the condition.

7.  In the **Value** field, select the value condition of the field.
    
    For example, to specify that a condition applies to customer 1202, you enter the following values for the condition:
    
      - **Field type** – **Table field**
    
      - **Field** – **AcctNum**
    
      - **Value type** – **Value**
    
      - **Operand** – **=**
    
      - **Value** – **1202**

## Set up fraud rules

Use this procedure to define a fraud rule that uses the variables and conditions that you created in the previous procedures.

1.  Click **Call center** \> **Setup** \> **Fraud** \> **Rules**.

2.  In the **Rules** form, click **New** to create a new rule, and enter a name and brief description of the rule.

3.  On the **General** FastTab, enter the fraud score for the rule, and select whether the rule should be applied to an entire order or individual order lines for a customer.

4.  Select the **Active** check box to activate the rule.

5.  On the **Conditions** FastTab, click **New** to add a condition, and select a condition from the list.
    
    Repeat this step to add conditions as needed for the rule.

6.  Click **Test rule**.

## Set up fraud types

Use this procedure to set up fraud type records for information that is known to be fraudulent, including phone numbers, email addresses, and ZIP/postal codes.

1.  Click **Call center** \> **Setup** \> **Fraud** \> **Static fraud data**.

2.  In the **Static fraud data** form, click **New**.

3.  In the **Fraud type** field, select the type of fraud, and then in the **Value** field, enter a description or exact text of the fraud type.
    
    For example, if you selected **Email** in the **Fraud type** field, you would enter a known fraudulent email address.

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
<td><p><strong>Trade agreements</strong> configuration key</p>
<p><strong>Margin alert</strong> configuration key (if you use margin alerts)</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales manager (to enable fraud alerts)</p>
<p>Sales clerk (to create sales orders)</p></td>
</tr>
</tbody>
</table>


## See also

[Configuring parameters and initial settings (Call center)](configuring-parameters-and-initial-settings-call-center.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

