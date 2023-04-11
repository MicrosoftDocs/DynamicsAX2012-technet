---
title: Work with forecast positions
TOCTitle: Work with forecast positions
ms:assetid: 13c1aad0-9829-49f8-b9e8-baa4d534c85e
ms:mtpsurl: https://technet.microsoft.com/library/Dn527691(v=AX.60)
ms:contentKeyID: 59626224
author: tonyafehr
ms.date: 03/06/2015
mtps_version: v=AX.60
f1_keywords:
- Forms.hcmpositionforecast
- Forms.hcmpositionmassupdate
- Forms.hcmpositionforecastlist
- Forms.HcmPositionCopy
- Forms.HcmPositionForecastAddPosition
- Forms.HcmPositionForecastNewPosition
- Forms.HcmPositionForecastAssignCostElement
- MsDynAx060.Forms.HcmPositionCopy
- MsDynAx060.Forms.hcmpositionforecast
- MsDynAx060.Forms.HcmPositionForecastNewPosition
- MsDynAx060.Forms.HcmPositionForecastAssignCostElement
- MsDynAx060.Forms.HcmPositionForecastAddPosition
- MsDynAx060.Forms.hcmpositionforecastlist
- MsDynAx060.Forms.hcmpositionmassupdate
- forecast position
- forecast positions
audience: Application User
ms.search.region: Global
---

# Work with forecast positions 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic explains how to add existing positions to a budget planning process and scenario, copy forecast positions that are already in the forecast, or create new positions for the next budget cycle. After you add a position to a forecast, you can add and change specific budget cost elements for the position so that the elements are accurate, or update multiple positions at the same time using the mass-update functionality.


> [!NOTE]
> <P>This topic includes information updated for Microsoft Dynamics AX 2012 R3 Cumulative Update 8 and the KB3043775 hotfix. If you are using a version of Microsoft Dynamics AX 2012 R2 earlier than cumulative update 7, see <A href="https://technet.microsoft.com/library/jj729760(v=ax.60)">Key tasks: Forecast positions</A>.</P>



The following illustration shows the steps that are required to create a position forecast. The numbers correspond to the procedures later in this topic.

![Work with forecast positions diagram](images/Dn527691.Work_with_forecast_positons(AX.60).gif "Work with forecast positions diagram")

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
<td><p>Related configuration tasks</p></td>
<td><p>Create budget cost elements and optionally create compensation groups if they will be used. For more information, see <a href="set-up-position-budgeting.md">Set up position budgeting</a>.</p></td>
</tr>
<tr class="even">
<td><p>Budget manager activities</p></td>
<td><p>The budget manager must create the budget planning processes and budget plan scenarios that you assign the positions to. For more information, see <a href="key-tasks-configure-budget-planning-and-set-up-budget-planning-processes.md">Key tasks: Configure budget planning and set up budget planning processes</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Version</p></td>
<td><p>Microsoft Dynamics AX 2012 R3 or cumulative update 7 or later for AX 2012 R2</p></td>
</tr>
</tbody>
</table>


## 1\. Add the initial positions to the forecast

Forecast positions are independent from Human resources positions so that they don’t affect current operations. To create one or more forecast positions, follow these steps:

1.  Click **Human resources** \> **Periodic** \> **Budget planning** \> **Forecast positions**.

2.  Create, copy, or add the new position to the forecast. Note that if you use an existing position as the basis for a new position, the two positions are no longer linked after the new position is created.
    
    There are several ways to add positions to a budget forecast.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Option</p></th>
    <th><p>Description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Add existing positions</strong></p></td>
    <td><p>When positions are added to the forecast, the annual fixed compensation assigned to the worker on the date the worker is added will be used. along with any selected budget cost elements.</p>
    <p>To add positions that exist in the live environment to the forecast list, follow these steps:</p>
    <ol>
    <li><p>In the <strong>New</strong> group, select <strong>Forecast position</strong>.</p></li>
    <li><p>Click <strong>Add existing positions</strong>.</p></li>
    <li><p>Select the budget planning process to assign the positions to. For more information, see <a href="https://technet.microsoft.com/library/jj677441(v=ax.60)">Budget planning process (form)</a>.</p></li>
    <li><p>Select the budget plan scenario to assign the position to. For more information, see <a href="https://technet.microsoft.com/library/jj677418(v=ax.60)">Budget planning configuration (form)</a>.</p></li>
    <li><p>Optional: Select the <strong>Earnings budget cost element</strong> to use. If the worker does not have a fixed compensation plan assigned to them. This value is determined by the default annual amount from the budget cost setup.</p>
    <div class="alert">

    > [!NOTE]
    > <P>Only earning budget cost elements for the selected budget planning process are displayed.</P>


    </div></li>
    <li><p>Optional: Click <strong>Assign anniversary date</strong> to select how to mark the position’s anniversary date, for example to schedule wage increases.</p>
    <div class="alert">

    > [!WARNING]
    > <P>This control is available only if you have installed Microsoft Dynamics AX 2012 R3 with the following hotfix: KB3043775</P>


    </div></li>
    <li><p>Select the positions to add.</p></li>
    <li><p>Click <strong>OK</strong>. A message is displayed that confirms the positions were successfully added to the forecast.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The <STRONG>Forecast state</STRONG> field is set to <STRONG>Existing</STRONG> for positions that are created by using this method.</P>


    </div></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p><strong>Create new forecast position</strong></p></td>
    <td><p>To create a new forecast position that does not yet exist, follow these steps:</p>
    <ol>
    <li><p>In the <strong>New</strong> group, select <strong>Forecast position</strong>.</p></li>
    <li><p>Click <strong>Create new forecast position</strong>.</p></li>
    <li><p>Select the job that is associated with the position. The job is used to set the default job description, job title, and full-time equivalent (FTE) employment factor for the forecast position.</p></li>
    <li><p>Select the budget planning process to assign the position to. For more information, see <a href="https://technet.microsoft.com/library/jj677441(v=ax.60)">Budget planning process (form)</a>.</p></li>
    <li><p>Select the budget plan scenario to assign the position to. For more information, see <a href="https://technet.microsoft.com/library/jj677418(v=ax.60)">Budget planning configuration (form)</a>.</p></li>
    <li><p>Enter or accept the default activation date for the position.</p></li>
    <li><p>Optional: If known, enter the position retirement date.</p></li>
    <li><p>Click <strong>Create positions</strong>. The <strong>Forecast position</strong> form appears.</p>
    <p>On the <strong>General</strong> tab, the <strong>Forecast state</strong> field is set to <strong>Proposed</strong> for positions that are created by using this method.</p></li>
    <li><p>Optional: Enter or change any other details about the forecast position.</p></li>
    <li><p>Optional: On the <strong>Compensation</strong> tab, select a compensation group to add default cost elements and their values to the forecast position.</p></li>
    <li><p>Optional: On the <strong>Compensation</strong> tab, select a step and level to add a cost element for earnings.</p></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Copy the selected forecast position</strong></p></td>
    <td><p>To create one or more copies of the selected forecast position, follow these steps:</p>
    <ol>
    <li><p>Select the position to copy.</p></li>
    <li><p>In the <strong>New</strong> group, select <strong>Forecast position</strong>.</p></li>
    <li><p>Click <strong>Copy the selected forecast position</strong>.</p></li>
    <li><p>In the <strong>Number of copies</strong> field, enter the number of forecast positions to create. This number is in addition to the forecast position that is selected.</p></li>
    <li><p>Optional: Change the position duration, if it differs from the selected position.</p></li>
    <li><p>Select the <strong>Relationships</strong> and <strong>Financial dimensions</strong> check boxes to copy the information from the existing forecast position.</p></li>
    <li><p>Click <strong>Copy</strong>. A message is displayed that confirms that the positions were successfully added to the forecast.</p></li>
    </ol>
    <p>The <strong>Forecast state</strong> field is set to <strong>Proposed</strong> for positions that are created by using this method.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Copy to scenario</strong></p></td>
    <td><p>To copy a forecast position to a different budget planning scenario while retaining the same budget planning process, budget cost elements, position activation and retirement dates, full-time or part-time employment, and compensation group, follow these steps:</p>
    <ol>
    <li><p>Select one or more positions to copy.</p></li>
    <li><p>In the <strong>New</strong> group, select <strong>Copy to scenario</strong>.</p></li>
    <li><p>Select the <strong>Budget plan scenario</strong>.</p></li>
    <li><p>Click <strong>Create</strong>.</p></li>
    </ol>
    <p>A message will appear indicating the number of records that were updated successfully.</p></td>
    </tr>
    </tbody>
    </table>


3.  Optional: To view the forecast positions, click **Refresh** on the **Action Pane** of the **Forecast positions** list page.

4.  Open any position and enter additional information, or make any necessary changes. Note that the **Position generation date** field displays the date that the initial forecast position values were based on.
    

    > [!NOTE]
    > <P>Any changes that you make to the forecast position do not affect the job or position that the initial creation was based on.</P>



## 2\. Make changes to the forecast positions

To change an existing forecast position, follow these steps:

1.  Click **Human resources** \> **Periodic** \> **Budget planning** \> **Forecast positions**.

2.  Double-click the position to view the details.
    
    To filter the choices, press Ctrl+G. You can limit the search results to a specific field, such as **Department**.

3.  Click **Edit**.

4.  Complete the following fields on the **Budget planning** tab.
    
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
    <td><p><strong>Budget planning process</strong></p></td>
    <td><p>The budget planning process was assigned to the forecast position when it was created and can’t be changed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Budget plan scenario</strong></p></td>
    <td><p>The budget plan scenario was assigned to the forecast position when it was created and can’t be changed.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Full-time equivalent</strong></p></td>
    <td><p>If you change the <strong>Full-time equivalent</strong> value, a message bar appears that prompts you to recalculate the budget cost elements. When you recalculate, on the <strong>Budget cost elements</strong> tab, the <strong>Annual amount</strong> and <strong>Budget amount</strong> columns are updated. For example, if you reduce the <strong>Full-time equivalent</strong> value from 1.0 to .5 on a position that has a base pay calculation of 100,000, the new budget amount is 50,000.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Position generation date</strong></p></td>
    <td><p>This field displays the date that the initial forecast position values were based on. For example, if you create a forecast position on November 14, 2014, that is based on position values from June 30, 2014, the position generation date will be set to June 30, 2014. If you created the position by using the <strong>Create new forecast position</strong> option, this is the date when the forecast position was created.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Activation</strong></p>
    <p><strong>Retirement</strong></p></td>
    <td><p>If you change the <strong>Activation</strong> or <strong>Retirement</strong> date and the change affects the starting or ending date of one or more budget cost element lines, you are prompted to recalculate the costs. For example, the start date of the budget cost element is April 1, 2014. If you change the position activation date from January 1, 2014, to July 1, 2014, the budget cost element start date changes to July 1, 2014. This change affects the budgeted amount.</p>
    <div class="alert">

    > [!WARNING]
    > <P>If changing the activation or retirement date causes the starting or ending date of a budget cost element to occur outside of the position date range, the budget cost element line is removed. For example, if a budget cost line isn’t in effect until July 1, 2014, and you change the end date of the position from December 31, 2014, to June 30, 2014, the line is removed.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


5.  Complete the following fields on the **Compensation** tab.
    
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
    <td><p><strong>Compensation group</strong></p></td>
    <td><p>Optional: The compensation group determines the base earning cost element (rate), the date of the next scheduled increase, and the set of default budget cost elements that are added to the position.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you change the compensation group, the assigned budget cost elements are removed and are replaced by those that are assigned to the updated compensation group. All the line values are recalculated, based on the new base earnings amount.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><p><strong>Compensation level</strong></p></td>
    <td><p>Optional: The <strong>Compensation level</strong> determines the level and reference point that are used to determine the current compensation rate. This field is available only if a compensation group is selected.</p>
    <div class="alert">

    > [!NOTE]
    > <P>If you change the compensation level, you are prompted to update the base earnings.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Step</strong></p>
    <p><strong>Rate</strong></p></td>
    <td><p>These values are displayed for informational purposes and are determined by the compensation level.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Anniversary date</strong></p></td>
    <td><p>This value that you enter in this field is copied to the <strong>Scheduled increase date</strong> field when the <strong>Increase schedule</strong> field is set to <strong>Anniversary date</strong> in the <strong>Compensation groups</strong> form.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Scheduled increase date</strong></p></td>
    <td><p>This date is determined by the compensation group that is assigned to the position:</p>
    <ul>
    <li><p>If the <strong>Increase schedule</strong> field is set to <strong>Anniversary date</strong> in the <strong>Compensation groups</strong> form, this field is set to the date that was entered in the <strong>Anniversary date</strong> field for the budget cycle.</p></li>
    <li><p>If the <strong>Increase schedule</strong> field is set to <strong>Common date</strong> in the <strong>Compensation groups</strong> form, the value entered in the <strong>Date of increase</strong> field in the <strong>Compensation groups</strong> form is used for the budget cycle.</p></li>
    </ul></td>
    </tr>
    </tbody>
    </table>


6.  Complete the following fields on the **Budget cost elements** tab.
    

    > [!NOTE]
    > <P>If you change the value of an earning cost element, all dependent earning cost lines must be recalculated. For example, if you change the base pay amount from 90,000.00 to 100,000.00, and an annual bonus is set up to calculate at 10 percent of the base earnings line, the bonus changes from 9,000.00 to 10,000.00 after you recalculate.</P>

    
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
    <td><p><strong>Add</strong> (button)</p></td>
    <td><p>Click this button to manually add budget cost element lines to the position. The system uses the durations of the position, the budget cost element, the budget cycle of the budget planning process, and the FTE equivalent to calculate the budget amount values.</p>
    <div class="alert">

    > [!NOTE]
    > <P>When you select a compensation group, the default budget cost element lines are added for the time period of the duration of the position within the budget cycle. You can change these lines as needed.</P>


    </div></td>
    </tr>
    <tr class="even">
    <td><img src="images/Dn527691.Yellow_triangle(AX.60).gif" title="Yellow triangle" alt="Yellow triangle" /></td>
    <td><p>If an exclamation point icon with a triangle appears in the first column, you have changed a value that is now different from the value defined on the <strong>Budget cost elements</strong> form. This could be intentional – for example, if you’re overwriting a default amount – or it could be because the budget cost element was updated but this forecast position was not.</p></td>
    </tr>
    <tr class="odd">
    <td><img src="images/Dn527691.Redcirclewithslash(AX.60).gif" title="Red circle with slash" alt="Red circle with slash" /></td>
    <td><p>If a circle with a slash through it appears in the first column, the system administrator has indicated that the line values for this budget cost element can’t be changed.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Start date</strong></p>
    <p><strong>End date</strong></p></td>
    <td><p>When you change the starting or ending date of a cost element, you are prompted to recalculate the budget cost elements. The annual amount is prorated on daily basis using a factor of 365 days in a year to determine the new cost values.</p>
    <div class="alert">

    > [!NOTE]
    > <P>The starting and ending dates must fall within the effective and expiration dates of the cost element and the activation and retirement dates of the position. If there are duplicate budget cost lines, the date ranges can’t overlap.</P>


    </div>
    <div class="alert">

    > [!NOTE]
    > <P>By default in Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the Start date for the forecast position cost element becomes the Effective date of the budget plan line when the line is generated.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Percent</strong></p></td>
    <td><p>Percentage-based cost elements are determined by the earning budget cost elements that are assigned in the <strong>Budget cost element</strong> form. For example, the Medicare line might be determined by multiplying .0145 by the base pay, overtime pay, and bonus pay values. For more information, see <a href="set-up-position-budgeting.md">Set up position budgeting</a>. After this value is determined, the amount is multiplied by the number of days the cost element is valid for, and then divided by 365 days. The system also verifies that an annual limit has not been reached for the cost element.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Budget amount</strong></p></td>
    <td><p>For fixed-amount cost elements, the budget amount is calculated by taking the number of days the cost element line is valid for and dividing it by 365 days. The result then is multiplied by the annual amount.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Retain value</strong></p></td>
    <td><p>If you manually change any line values for a budget cost element, the <strong>Retain value</strong> column will be set to <strong>Yes</strong> to ensure that the line amount is not updated if the budget cost element is changed and the forecast positions are updated. You can change this field to <strong>No</strong> if you want the value to be updated if the cost element is changed in the <strong>Budget cost elements</strong> form.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Step</strong></p></td>
    <td><p>The step value that was used to determine the line amount.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Source</strong></p></td>
    <td><p>This field is ready-only and identifies how the line was created:</p>
    <ul>
    <li><p><strong>Manual</strong> – This line was entered manually by the user.</p></li>
    <li><p><strong>Original assignment</strong> – Compensation increases were applied using this line as the basis.</p></li>
    <li><p><strong>Rate change</strong> – This line was created when compensation increases were generated that included a rate change.</p></li>
    <li><p><strong>Step increase</strong> – This line was created when compensation increases were generated that included a change to the step value.</p>
    <div class="alert">

    > [!TIP]
    > <P>For more information about generating compensation increases, see “5. If required: Periodically update forecast positions with compensation increases” later in this topic.</P>


    </div></li>
    </ul></td>
    </tr>
    <tr class="even">
    <td><p><strong>Notes</strong></p></td>
    <td><p>This field stores any notes entered by the system. You can also manually enter any additional details about the budget cost line.</p></td>
    </tr>
    </tbody>
    </table>


## 3\. If required: Add individual budget cost elements

You can assign individual budget cost elements to multiple forecast positions instead of assigning them to a compensation group or manually adding them individually to each forecast position.

To add a cost element to forecast positions, follow these steps:

1.  Click **Human resources** \> **Setup** \> **Budget planning** \> **Budget cost elements**.

2.  Select the budget cost element to assign positions to. On the action strip, click **Add to positions**.

3.  In the **Add budget cost elements** form, select the forecast positions to add the budget cost element. You can press Ctrl+G to filter the list of forecast positions.

4.  Click **Add** to move the forecast positions to the lower grid.

5.  Verify that you selected the appropriate positions, and then click **Assign**. A message appears that indicates the number of positions that were updated and the forecast positions that were not updated, if applicable.

## 4\. If required: Periodically update forecast positions with cost element changes

It is often necessary to update a cost element after it is assigned to a position, such as when a cost element is finalized or if a tax rate changes. When this happens, you must update the positions that use the cost element so that they reflect the updated costs. Although you can do this for each individual position, it might be more efficient to use the **Update positions** functionality to make the change for all the positions at the same time.

To update forecast positions, follow these steps:

1.  Click **Human resources** \> **Setup** \> **Budget planning** \> **Budget cost elements**.

2.  Select the budget cost element and make any necessary changes.

3.  Optional: On the **Cost calculation** tab, click **Change dates**. Change the effective or expiration dates and then click **OK** to automatically update all forecast positions that have the cost element assigned.
    

    > [!NOTE]
    > <P>By default in AX 2012 R3 CU8, the Start date for the forecast position cost element becomes the Effective date of the budget plan line when the line is generated.</P>



4.  On the action strip, click **Update positions**.

5.  In the **Update positions with cost element changes** form, the forecast positions that have the cost element assigned are displayed. Select the forecast positions to update, and then click **Add** to move them to the lower grid.
    
    You can press Ctrl+G to filter the list of forecast positions.

6.  Verify that you selected the appropriate positions, and then click **Update**. A message appears that indicates the number of positions that were updated and the forecast positions that were not updated, if applicable.
    

    > [!NOTE]
    > <P>If the <STRONG>Retain value</STRONG> field is set to <STRONG>Yes</STRONG> for a budget cost line and there is a percentage change, the amount will not be updated, but the <STRONG>Effective</STRONG>, <STRONG>Expiration</STRONG>, and <STRONG>Main account</STRONG> fields will be updated if they were changed.</P>



## 5\. If required: Periodically update forecast positions with compensation increases

It is often necessary to update the compensation for forecast positions after they are added to a forecast, such as when there is a rate increase, or if a worker receives a scheduled raise. Although you can do this for each individual forecast position, it is usually more efficient to use the **Generate increases** functionality so that you can update multiple positions at the same time.


> [!TIP]
> <P>This feature is also helpful for comparing different scenarios that have the same forecast position assigned to them. For example, if you change the values in a compensation grid, you can select the positions in one budget plan scenario to apply them without updating the other budget plan scenarios that the forecast positions are assigned to.</P>



When you generate increases, positions are updated as follows:

  - A new earning line is added to the forecast position. This will be the compensation group's default budget cost element and the start date of the line will be the scheduled increase date.

  - The end date of the current step and level earning budget cost element will be set to the day before the scheduled increase.

  - The earning line will be deleted and replaced with a new line if the increase earnings cost element already exists, unless the **Retain value** field is set to **Yes**.

  - A new earning line will be created with the same step value if the forecast position is at the highest step. This allows you to make manual increases to the line, if applicable.

  - Multiple increase lines are created for each year if the budget cycle contains more than one calendar year.

To update forecast positions, follow these steps:

1.  Click **Human resources** \> **Periodic** \> **Budget planning** \> **Forecast positions**.

2.  On the **Action Pane**, click **Generate increases**.

3.  Click **Yes** when you are prompted to confirm the generation process. A message will appear indicating the number of positions that received raises.

## 6\. Optional: Update multiple forecast positions with the same value, at the same time

To update the position information for multiple forecast positions at the same time, use the following steps.


> [!NOTE]
> <P>This procedure does not apply to compensation changes. For information about how to update compensation for multiple forecast positions, see <A href="set-up-position-budgeting.md">Set up position budgeting</A>.</P>



1.  Click **Human resources** \> **Periodic** \> **Budget planning** \> **Forecast positions**.

2.  Select the positions to update.

3.  On the **Action Pane**, in the **Maintain** group, click **Mass update**.

4.  Select the check box next to each field to update. You might have to expand the tab to see all the fields.
    
    The **Financial dimensions** tab is available only if all the selected forecast positions are assigned to the same legal entity.

5.  Select or enter the new value.

6.  Click **Update**. A message appears that confirms the update was successful.

## Next step

The budget manager will generate a budget plan that has the forecast positions, or the budget plan preparer can select the forecast positions to include in the budget plan. For more information, see [Generate budget plan from forecast positions (form)](https://technet.microsoft.com/library/jj677428\(v=ax.60\)) or [Select forecast positions (form)](https://technet.microsoft.com/library/jj677436\(v=ax.60\)).

## Related tasks

[Set up position budgeting](set-up-position-budgeting.md)

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
<td><p><strong>Compensation and benefits manager</strong></p>
<p><strong>Budget manager</strong></p>
<p><strong>Human resource assistant</strong></p></td>
</tr>
</tbody>
</table>


## See also

[Forecast positions by budget plan report (BudgetPlanHCMReport)](forecast-positions-by-budget-plan-report-budgetplanhcmreport.md)

[Budget plan scenarios report (BudgetPlanScenariosReport)](budget-plan-scenarios-report-budgetplanscenariosreport.md)

[Budget plan account totals report (BudgetPlanDimensionFocusTotalReport)](budget-plan-account-totals-report-budgetplandimensionfocustotalreport.md)

  


