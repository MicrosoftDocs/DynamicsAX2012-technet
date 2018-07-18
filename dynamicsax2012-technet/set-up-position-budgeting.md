---
title: Set up position budgeting
TOCTitle: Set up position budgeting
ms:assetid: a73e1b33-7076-47a6-b311-dcc7313a68fa
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn527699(v=AX.60)
ms:contentKeyID: 59626232
ms.date: 03/06/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.HcmBudgetPurposeType
- Forms.HcmPositionForecastCompensationGroup
- MsDynAx060.Forms.HcmBudgetPurposeType
- MsDynAx060.Forms.HcmPositionForecastCompensationGroup
- position budget
- position budgeting
---

# Set up position budgeting 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic describes the procedures that are required to set up position budgeting so that you can create and work with forecast positions.

To budget for new and existing positions in future budget cycles, you must consider all costs that are related to forecast positions. In Microsoft Dynamics AX 2012 R3 and later releases, these costs are called budget cost elements. Budget cost elements represent earnings, employer-paid benefits, taxes, or other expenditures for which an organization will budget for a forecast position. You can create as many budget cost elements as you want. After you create the budget cost elements that your organization requires, you can assign the budget cost elements to forecast positions.

If you have any problems when you set up position budgeting, see the frequently asked questions about how to configure position budgeting in [Position budgeting setup issues](position-budgeting-setup-issues.md).


> [!NOTE]
> <P>If you are using a version of Microsoft Dynamics AX 2012 R2 earlier than cumulative update 7 for Microsoft Dynamics AX 2012 R2, see <A href="https://technet.microsoft.com/en-us/library/jj680908(v=ax.60)">Budget purpose types (form)</A>.</P>



The following illustration shows the steps that are required to configure position budgeting. The numbers correspond to the procedures later in this topic.

![Configure position budgeting diagram](images/Dn527699.ConfigurePB(AX.60).gif "Configure position budgeting diagram")

## Prerequisites

The following table shows the prerequisites that must be in place before you start.

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
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3 or cumulative update 7 for Microsoft Dynamics AX 2012 R2 and later</p></td>
</tr>
</tbody>
</table>


## 1\. Create budget cost elements

Budget cost elements are specific costs that are associated with a position, such as 401(k) matching, cell phone allowances, base pay, and so on. Each budget cost element can be assigned to multiple positions and can include detailed information, such as the legal entity and the main account to use.


> [!NOTE]
> <P>If you are using a version of Microsoft Dynamics AX 2012 R2 before cumulative update 7, budget cost elements are called budget purpose types. For more information, see <A href="https://technet.microsoft.com/en-us/library/jj680908(v=ax.60)">Budget purpose types (form)</A>.</P>



To create a new budget cost element, follow these steps:

1.  Click **Human resources \> Setup \> Budget planning \> Budget cost elements**.

2.  Click **New**, and complete the following fields.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Budget cost element</strong></p></td>
    <td><p>The name of the budget cost element, such as Overtime or Dental plan A. You can’t change the name of the budget cost element after you save it. Therefore, consider all naming conventions before you save your changes to make sure that the name is unique and the budget cost element can be identified easily.</p>
    <div>

    > [!NOTE]
    > <P>All organizations should have at least one “Base pay” budget cost element. In addition, most have 401(k) elements, life insurance elements, car insurance elements, and many others.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Description</strong></p></td>
    <td><p>Enter additional information to help users if they are not sure which budget cost element to select when they assign budget cost elements to positions.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Budget cost type</strong></p></td>
    <td><p>Select the budget cost type that best describes the budget cost element:</p>
    <ul>
    <li><p><strong>Benefit</strong> – Select this option for benefit-related costs, such as Group dental.</p></li>
    <li><p><strong>Tax</strong> – Select this option for tax-related costs, such as FICA.</p></li>
    <li><p><strong>Other</strong> – This type is automatically assigned to all budget purpose types that were updated from Microsoft Dynamics AX 2012 R2. You can also assign this type to budget cost elements that are not accurately described by the other available budget cost types.</p></li>
    <li><p><strong>Earning</strong> – Earning budget cost elements are unique because they can be used as the cost basis for other budget cost elements. For example, if you create a Base pay cost element that has a budget type of <strong>Earning</strong>, you can create an Annual bonus cost element that is calculated by multiplying 10 percent of the Base pay value. If the base pay is 100,000, the bonus is 10,000. For more information about how to configure cost elements to use other cost elements as a calculation basis, see step 5.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


3.  By default, users can override cost element values for individual forecast positions. If you do not want users to change the value of a particular cost element, on the **General** tab, make sure that you set the **Forecast position override** field to **Do not allow cost changes**.

4.  Complete the fields on the **Cost calculation** tab. The information on this tab determines the currency value that is calculated for the budget cost element.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Add</strong></p></td>
    <td><p>Add a new line to the cost element. You can create multiple lines for each cost element.</p>
    <p>If you are changing a line and adding a new line to a budget cost element that is already assigned to forecast positions, click <strong>Update positions</strong> to update the existing lines on the forecast positions. To add the new line to the assigned forecast positions, copy the list of forecast positions in which the budget cost element is assigned when updating the positions and continue with the update process. After you have updated the positions, click <strong>Add to positions</strong> and select the positions that you copied. The new line will be added to the positions.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Legal entity</strong></p></td>
    <td><p>You must create at least one line for each legal entity that offers the cost element. If you do not create a line for a legal entity, the cost element is not available to forecast positions that are assigned to a budget planning process that uses the ledger for the legal entity.</p>
    <div>

    > [!NOTE]
    > <P>Each budget cost element can have multiple lines for the same legal entity, if the dates that are assigned to the lines do not overlap. For example, if you are creating a budget cost element for a 500.00 monthly car allowance that will increase to 550.00 next year for a particular legal entity, you would create two lines for the legal entity. One line would have an annual amount of 6,000.00 for one year and the other would have an annual amount of 6,600.00 for the following year.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Effective</strong></p>
    <p><strong>Expiration</strong></p></td>
    <td><p>If you enter multiple lines for the same legal entity, the date ranges can’t overlap, but gaps are permitted.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Main account</strong></p></td>
    <td><p>The main account is not required to save the budget cost element, but is required when users add the budget cost element to a forecast position.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Percent</strong></p></td>
    <td><p>If the cost element is percentage-based, enter the percentage, such as 3. You can create multiple lines for different percentages if you know that they will change. For example, if the PERS percentage will increase from 3 percent to 4 percent of base pay next year, enter 3 in the <strong>Percent</strong> field and set the expiration date to the end of the year. Then create a second line and enter 4 in the <strong>Percent</strong> field and set the effective date to the first day of the following year.</p>
    <p>You must assign a budget cost element as the calculation basis so the value can be determined. For more information, see step 5.</p>
    <div>

    > [!IMPORTANT]
    > <P>If you upgraded your data from Microsoft Dynamics AX 2012 R2, all budget purpose types that were calculated by using a percentage of the annual gross compensation are converted to fixed amounts. You must reconfigure these after the data upgrade is complete so that the amounts are calculated correctly.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Annual amount</strong></p></td>
    <td><p>If the cost element is a fixed amount, enter the annual figure in the <strong>Annual amount</strong> field. For example, enter 600.00 for a 50.00 monthly gym allowance.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Annual limit</strong></p></td>
    <td><p>This field is available only for budget cost elements that are calculated by using a percentage. It is typically used for certain taxes and retirement contributions. If you are setting up a percentage-based cost element and there is no annual limit, leave this field set to 0 (zero).</p>
    <p>This limit applies to each 365-day increment that is found between the starting and ending dates of the cost element. For example, if you enter a value of 3500.00 in the <strong>Annual limit</strong> field and the date range for the cost element spans two years, a limit of 7,000.00 will be enforced.</p></td>
    </tr>
    </tbody>
    </table>


5.  If you entered a percentage instead of an annual amount for any calculation line on the **Cost calculation** tab, follow these steps on the **Calculation basis** tab:
    
    1.  Click **Add**.
    
    2.  Select the budget cost element that the percentage is based on.
    
    3.  Repeat these steps until all the budget cost elements are listed.


> [!NOTE]
> <P>All of the earning cost elements that you list on this tab are multiplied by the <STRONG>Percent</STRONG> field value on the <STRONG>Cost calculation</STRONG> tab to determine the value of the cost element that you are creating. For example, suppose you are creating a Medicare cost element and you list Base pay, Overtime pay, and Bonus pay on this tab. If you entered 1.45 in the <STRONG>Percent</STRONG> field on the <STRONG>Cost calculation</STRONG> tab, the system calculates 1.45 percent of each value to determine the Medicare tax estimate for forecast positions.</P>



## 2\. Optional: Create compensation groups

Although you can assign individual budget cost elements to forecast positions, it might be more efficient to group budget cost elements for positions that receive similar pay and benefits. For example, you could create a compensation group named Admin that has the following budget cost elements assigned to it: 401(k), medical, dental, and Social Security tax.


> [!NOTE]
> <P>You can assign a compensation group to a forecast position on the <STRONG>Compensation</STRONG> tab of the forecast position. After you assign a compensation group to a forecast position, you can make any specific adjustments to the forecast position.</P>



To create a compensation group, follow these steps:

1.  Click **Human resources** \> **Setup** \> **Budget planning** \> **Compensation groups**.

2.  Click **New**.

3.  Enter a name for the compensation group. This is often the name of the group of positions that have the same compensation plan, such as Admin.

4.  Enter a description, such as Hourly administrative assistant, to help users make the appropriate selection when they assign compensation groups to positions.

5.  On the **General** tab, specify the following information.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Field group</p></th>
    <th><p>Field descriptions</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Annual conversion rules</strong></p></td>
    <td><p>These field values determine the compensation amount for positions that are assigned to the compensation group:</p>
    <ul>
    <li><p><strong>Compensation basis</strong> – Select whether positions in this compensation group are paid on an hourly basis, or if they are paid a salary.</p></li>
    <li><p><strong>Annual regular hours</strong> – If you selected <strong>Hourly wage</strong> in the previous field, enter the number of regularly paid hours that positions in this group are expected to have each year. This value is used to convert hourly wages to an annual salary amount that can be used to calculate values for budget cost elements.</p></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Compensation details</strong></p></td>
    <td><p>These fields provide information about when increases are awarded to positions that are assigned to the compensation group:</p>
    <ul>
    <li><p><strong>Increase schedule</strong> – Select whether increases occur on the same common date for positions in the compensation group, or if increases are awarded based on the worker’s anniversary date. This field determines the <strong>Scheduled increase date</strong> value for forecast positions that are assigned to this group. This field is for information only.</p></li>
    <li><p><strong>Date of increase</strong> – If you selected <strong>Common date</strong> in the previous field, enter the date that positions in this compensation group will receive an increase. This field is for information only.</p></li>
    <li><p><strong>Earning cost element</strong> – Select the budget cost element that defines the base compensation, such as Base pay. Only budget cost elements for which the <strong>Budget cost type</strong> field is set to <strong>Earning</strong> are displayed.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


6.  On the **Compensation rate tables** tab, you can assign all current and future compensation grids to the compensation group. To add a version of a compensation grid, follow these steps:
    
    1.  Click **Add**.
        

        > [!NOTE]
        > <P>If you haven’t created compensation grids for budget planning, see “3. Create compensation grids for compensation tables” section later in this topic.</P>

    
    2.  Enter the effective and expiration date of the compensation grid.
    
    3.  For reference purposes, enter a description of the compensation grid version, such as Machinists 2015 rates.
    
    4.  Repeat these steps until you have listed all the versions of the compensation grid.
        

        > [!TIP]
        > <P>If you have to change an existing compensation grid, select the grid and then click <STRONG>Maintain compensation grid</STRONG>. To update any positions that are assigned to the compensation group for a budget plan and budget plan scenario, click <STRONG>Update position rates</STRONG>.</P>



7.  On the **Budget cost elements** tab, follow these steps to assign the default budget cost elements to the group. You can change these for individual positions if there are exceptions.
    
    1.  Click **Add**.
    
    2.  Select a budget cost element to add to the group. You can assign the same cost element to a group only one time.
    
    3.  Repeat these steps until you have listed all the cost elements that positions assigned to this group typically receive.
        

        > [!TIP]
        > <P>You can’t change the cost element values in this form. If the cost element isn’t accurate for this group, you must create a new one or change the existing one in the <STRONG>Budget cost elements</STRONG> form as described in the “1. Create budget cost elements” section earlier in this topic.</P>



## 3\. If required: Create compensation grids for compensation tables

If your organization has standard compensation tables that are referenced to determine worker pay when positions are forecasted, you must create and assign step tables of currency values. You can use these tables as a basis for compensation calculations. If you haven’t created a reference point setup that you can use for this grid, you must exit this area and create it before you set up the grid. For more information, see [Reference point setups (form)](https://technet.microsoft.com/en-us/library/hh803014\(v=ax.60\)).


> [!NOTE]
> <P>The grids that you use for position budgeting are based on the grids that have already been created for active positions. However, any changes that you make in the position forecasting and budgeting areas do not affect live compensation calculations.</P>



To create a compensation grid, follow these steps:

1.  Click **Human resources** \> **Setup** \> **Budget planning** \> **Compensation groups**..

2.  In the **Compensation rate tables** FastTab, click **Add**.

3.  Enter an effective date and an expiration date. This date range cannot overlap with a date range for the same compensation group.

4.  (Optional) Type a description.

5.  Press Ctrl+S to save the record.

6.  Click **Maintain compensation groups**.

7.  In the **Set up compensation** form, do one of the following tasks:
    
      - If you don’t have an existing compensation grid that you want to use as a starting point for the grid, select **Set up a new compensation grid** and select the reference setup to use in the grid. All existing reference point setups that have the **Type** field set to **Step** are listed.
        

        > [!TIP]
        > <P>The reference setup that you select determines the columns that appear in the compensation grid.</P>

    
      - If a compensation grid already exists that is the same or very similar to the one that you are creating, select **Create a new compensation grid from an existing grid** and select the grid to copy in the **Copy from grid** field.

8.  Select the first level to use in the grid and enter the appropriate currency values for each step and level combination. These can be hourly or annual figures, depending on the **Compensation basis** setting for the compensation group.

9.  Optional: You can, at any time, specify amount or percentage wage increases for multiple forecast positions at a time, as follows.
    

    > [!NOTE]
    > <P>This is only available with Microsoft Dynamics AX 2012 R3 with the following hotfix: KB3043775.</P>

    
    1.  In the Action strip, click **Mass change**.
    
    2.  In the dialog box that appears, select the adjustment type and value that you want. This can be a positive or negative value. Click **OK**.
    
    3.  Click **Close** in the **Mass change** form.

10. Click **New** to add more levels to the grid and enter the appropriate currency values for each combination until the grid is finished.


> [!NOTE]
> <P>If you have selected a compensation group and a compensation level for a forecast position, one or more new budget cost lines are added to the forecast position. This budget cost line uses the label that you selected in the <STRONG>Earning cost element</STRONG> field for the compensation group. The amount is calculated differently, depending on the compensation basis that you selected:</P>
> <UL>
> <LI>
> <P>If you selected <STRONG>Annual salary</STRONG> in the <STRONG>Compensation basis</STRONG> field of the compensation group, the annual amount is copied from the compensation grid by using the level and step to determine the amount.</P>
> <LI>
> <P>If you selected <STRONG>Hourly wage</STRONG> in the <STRONG>Compensation basis</STRONG> field of the compensation group, the annual amount is determined by using the level and step value, multiplied by the <STRONG>Annual regular hours</STRONG> value that is specified for the compensation group.</P></LI></UL>



## Next step

For more information, see [Work with forecast positions](work-with-forecast-positions.md).

## Related tasks

[Position budgeting setup issues](position-budgeting-setup-issues.md) (FAQ)

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
<td><p><strong>Budget planning configuration key</strong> (LedgerAdv2BudgetPlanning)</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p><strong>Budget clerk</strong> (compensation groups only)</p>
<p><strong>Compensation and benefits manager</strong></p>
<p><strong>Budget manager</strong></p>
<p><strong>Human resource assistant</strong></p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

