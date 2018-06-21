---
title: Set up interest rates for an interest code
TOCTitle: Set up interest rates for an interest code
ms:assetid: cbdda5aa-6baf-43fe-b08d-9030a2c42dd1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg213664(v=AX.60)
ms:contentKeyID: 36059345
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Set up interest rates for an interest code [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Interest codes contain settings that determine when interest is charged and how it is calculated on overdue accounts. You can set up a single interest code and apply it to multiple customer posting profiles, billing codes, or to specific invoice lines. When the interest code details are changed, all features that use the code will automatically implement the changes on new transactions. For each interest code, you can set up two types of rates:

  - Rates for interest earnings − These represent revenue that is earned by charging interest on invoices or interest notes.

  - Rates for interest payments − These represent a cost that is paid for interest on credit notes.

Both of these rate types can exist at the same time and in the same interest code.

Interest rates can be based on three calculation types:

  - Interest by percentage

  - Interest by amount

  - Interest by range, which results in a single percentage or amount

When an interest code is used to calculate interest, a separate interest note is created for each interest rate that is in effect during the time that the payment has exceeded the transaction due date.

## Set up interest rates based on percentages

You can set up interest rates that calculate a specified percentage. The same percentage applies to all currencies that are specified for the interest code.

This procedure explains how to set up interest rates for interest that you earn by charging interest. You use the **Earnings** tab in the **Interest** form to do this. To set up interest rates for interest that you pay, use the **Payments** tab, instead.

1.  Click **Accounts receivable** \> **Setup** \> **Collections** \> **Interest**.

2.  Select an interest code, or click **New** to create an interest code.

3.  Click the **Earnings** tab.

4.  In the **Calculate interest every** field, enter the rate of recurrence for the calculation and select the unit of time for the recurrence.
    
    For example, to set up an interest code that assesses 5 percent interest for every two months that the invoice payment exceeds the transaction due date, you would enter 2 in the **Calculate interest every** field and select **Month**.

5.  In the **Ledger posting debit** field, select the ledger account where the interest earnings will be posted.

6.  In the **Interest by range** field, select **None**.

7.  In the **Calculate interest based on** field, select **Percentage**.

8.  In the **Monthly interest %** field, enter the percentage value to use in the calculation.
    
    For example, to set up an interest code that assesses 5 percent interest for every two months that the invoice payment exceeds the transaction due date, you would enter 5 in this field.

9.  Click the **Add** button on the **Earnings** tab, and then select a currency code.
    

    > [!NOTE]
    > <P>When you first set up an interest code, the accounting currency code is selected in the <STRONG>Currency</STRONG> field. For more information about the <STRONG>Currency</STRONG> field, see <A href="https://technet.microsoft.com/en-us/library/aa574050(v=ax.60)">Interest setup (form)</A>.</P>



10. Optional: Enter interest amount limits in the **Minimum interest amount** and **Maximum interest amount** fields.

11. Specify values for the remaining fields.

12. To define interest terms for additional currencies, click **Add**, select a new code in the **Currency** field, and repeat steps 10 and 11.

## Set up interest rates based on amounts

You can set up interest rates that calculate a specified amount per currency. You must specify an interest amount for each currency that is specified for the interest code.

This procedure explains how to set up interest rates for interest that you earn by charging interest. You use the **Earnings** tab in the **Interest** form to do this. To set up interest rates for interest that you pay, use the **Payments** tab, instead.

1.  Click **Accounts receivable** \> **Setup** \> **Collections** \> **Interest**.

2.  Select an interest code, or click **New** to create an interest code.

3.  Click the **Earnings** tab.

4.  In the **Calculate interest every** field, enter the rate of recurrence for the calculation and select the unit of time for the recurrence.
    
    For example, to set up an interest code that assesses interest of 25.00 for every 20 days that the invoice payment exceeds the transaction due date, you would enter 20 in the **Calculate interest every** field and select **Day**.

5.  In the **Ledger posting debit** field, select the ledger account where the interest earnings will be posted.

6.  In the **Interest by range** field, select **None**.

7.  In the **Calculate interest based on** field, select **Amount**.

8.  Click the **Add** button on the **Earnings** tab, and then select a currency code.
    

    > [!NOTE]
    > <P>When you first set up an interest code, the accounting currency code is selected in the <STRONG>Currency</STRONG> field. For more information about the <STRONG>Currency</STRONG> field, see <A href="https://technet.microsoft.com/en-us/library/aa574050(v=ax.60)">Interest setup (form)</A>.</P>



9.  In the **Interest amount** field, enter the amount to use in the calculation.
    
    For example, to set up an interest code that assesses interest of 25.00 for every 20 days that the invoice payment exceeds the transaction due date, you would enter 25 in this field.

10. Optional: Enter interest amount limits in the **Minimum interest amount** and **Maximum interest amount** fields.

11. Specify values for the remaining fields.

12. To define interest terms for additional currencies, click **Add**, select a new code in the **Currency** field, and repeat steps 10 and 11.

## Set up interest rates based on ranges

You can set up interest rates that vary depending on the overdue amount, the number of days that the amount is late, or the number of months that the amount is late.

This procedure explains how to set up interest rates for interest that you earn by charging interest. You use the **Earnings** tab in the **Interest** form to do this. To set up interest rates for interest that you pay, use the **Payments** tab, instead.

1.  Click **Accounts receivable** \> **Setup** \> **Collections** \> **Interest**.

2.  Select an interest code, or click **New** to create an interest code.

3.  Click the **Earnings** tab.

4.  In the **Calculate interest every** field, enter the rate of recurrence for the calculation and select the unit of time for the recurrence.
    
    See the examples after this procedure for examples of value combinations that you might enter.

5.  In the **Ledger posting debit** field, select the ledger account where the interest earnings will be posted.

6.  In the **Interest by range** field, select the type of interval that is used in the **Customer interest range** form to determine the interest percentage or amount for the calculation.

7.  In the **Calculate interest based on** field, select whether to base the interest calculation on a percentage or amount.

8.  Click the **Add** button on the **Earnings** tab, and then select a currency code.
    

    > [!NOTE]
    > <P>When you first set up an interest code, the accounting currency code is selected in the <STRONG>Currency</STRONG> field. For more information about the <STRONG>Currency</STRONG> field, see <A href="https://technet.microsoft.com/en-us/library/aa574050(v=ax.60)">Interest setup (form)</A>.</P>



9.  Optional: Enter interest amount limits in the **Minimum interest amount** and **Maximum interest amount** fields.

10. Specify values for the remaining fields.

11. Click the **Ranges** button.
    

    > [!TIP]
    > <P>Conditions are displayed for the currency of the selected line. To view and edit conditions for other currencies, select the corresponding currency code in the left pane.</P>



12. In the **Interest value** field, enter a value in the active row.
    
    This number represents either a percentage or an amount, depending on the selection in the **Calculate interest based on** field in the **Interest** form.
    

    > [!NOTE]
    > <P>The default, and required, value in the first <STRONG>From value</STRONG> field is 0 (zero).</P>



13. To define additional ranges, click **New**, enter the next value in the **From value** field, and repeat step 12.
    

    > [!NOTE]
    > <P>Each time that you add a new row to a range, the previous interval ends with a value that is one less than the new value that is in the <STRONG>From value</STRONG> field.</P>



14. To define interest terms for additional currencies, close the **Customer interest range** form to return to the **Earnings** tab of the **Interest** form. Click **Add**, select a new code in the **Currency** field, and repeat steps 9 through 13.

## Example 1: Interest by range = Amount

You set up an interest code that assesses interest one time for every three months that the invoice payment exceeds the transaction due date. You want to base the calculation on a percentage interest value, according to stepped amount intervals. The interest value will be 1 percent for invoice amounts up to 1,000.00, 2 percent for amounts from 1,001.00 to 5,000.00, and 3 percent for amounts larger than 5,000.00.

You set up the interest code field values as follows.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field name</p></th>
<th><p>Field value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Interest code</strong></p></td>
<td><p>3M%ByAmt</p></td>
</tr>
<tr class="even">
<td><p><strong>Calculate interest every</strong></p></td>
<td><p>3/<strong>Month</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Interest by range</strong></p></td>
<td><p><strong>Amount</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Calculate interest based on</strong></p></td>
<td><p><strong>Percentage</strong></p></td>
</tr>
</tbody>
</table>


You set up the range information as follows.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>From value</strong></p></th>
<th><p><strong>Interest value</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0</p></td>
<td><p>1</p></td>
</tr>
<tr class="even">
<td><p>1,001</p></td>
<td><p>2</p></td>
</tr>
<tr class="odd">
<td><p>5,001</p></td>
<td><p>3</p></td>
</tr>
</tbody>
</table>


## Example 2: Interest by range = Days

You set up an interest code that assesses interest one time for every 15 days that the invoice payment exceeds the transaction due date. You want to base the calculation on an amount interest value, according to stepped day intervals. The interest value will be 10.00 per 15 days during the first 60 days, 15.00 per 15 days during days 61 to 90, and 20.00 per 15 days from day 91 and after.

You set up the interest code field values as follows.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field name</p></th>
<th><p>Field value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Interest code</strong></p></td>
<td><p>15DAmtXDay</p></td>
</tr>
<tr class="even">
<td><p><strong>Calculate interest every</strong></p></td>
<td><p>15/<strong>Day</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Interest by range</strong></p></td>
<td><p><strong>Days</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Calculate interest based on</strong></p></td>
<td><p><strong>Amount</strong></p></td>
</tr>
</tbody>
</table>


You set up the range information as follows.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>From value</strong></p></th>
<th><p><strong>Interest value</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0</p></td>
<td><p>10</p></td>
</tr>
<tr class="even">
<td><p>61</p></td>
<td><p>15</p></td>
</tr>
<tr class="odd">
<td><p>91</p></td>
<td><p>20</p></td>
</tr>
</tbody>
</table>


## Example 3: Interest by range = Months

You set up an interest code that assesses interest one time for every month that the invoice payment exceeds the transaction due date. You want to base the calculation on a percentage interest value, according to stepped month intervals. The interest value will be 1.5 percent per month for the first three overdue months, 2.0 percent per month for the second three months, and 2.5 percent per month for each month beyond the first six months.

You set up the interest code field values as follows.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Field name</p></th>
<th><p>Field value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Interest code</strong></p></td>
<td><p>1M%ByMth</p></td>
</tr>
<tr class="even">
<td><p><strong>Calculate interest every</strong></p></td>
<td><p>1/<strong>Month</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Interest by range</strong></p></td>
<td><p><strong>Months</strong></p></td>
</tr>
<tr class="even">
<td><p><strong>Calculate interest based on</strong></p></td>
<td><p><strong>Percentage</strong></p></td>
</tr>
</tbody>
</table>


You set up the range information as follows.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>From value</strong></p></th>
<th><p><strong>Interest value</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>0</p></td>
<td><p>1.5</p></td>
</tr>
<tr class="even">
<td><p>4</p></td>
<td><p>2</p></td>
</tr>
<tr class="odd">
<td><p>7</p></td>
<td><p>2.5</p></td>
</tr>
</tbody>
</table>


## See also

[Interest setup (form)](https://technet.microsoft.com/en-us/library/aa574050\(v=ax.60\))

[Calculate interest and create interest notes](calculate-interest-and-create-interest-notes.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

