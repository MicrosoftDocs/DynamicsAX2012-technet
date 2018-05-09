---
title: (JPN) Configure and calculate fixed asset depreciation
TOCTitle: (JPN) Configure and calculate fixed asset depreciation
ms:assetid: c6ea5abd-69bc-4767-81a0-249e9d2f1b71
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn473951(v=AX.60)
ms:contentKeyID: 59371905
ms.date: 12/03/2014
mtps_version: v=AX.60
---

# (JPN) Configure and calculate fixed asset depreciation 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

After you set up depreciation methods and allowable limits for depreciation, you can create a depreciation proposal that depreciates the asset and calculates the monthly depreciation expenses.


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 6 for AX 2012.</P>



To depreciate a fixed asset, you can change the fixed asset depreciation profile to one that uses a different depreciation method. You can then import a depreciation rate schedule to calculate the undepreciated balances and update the service life of the fixed asset.

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
<td><p>Related setup tasks</p></td>
<td><p>Set up basic fixed asset parameters, such as a default value model, reason codes, and number sequences, by using the <strong>Fixed assets parameters</strong> form. For more information, see <a href="set-up-fixed-assets-parameters.md">Set up Fixed assets parameters</a>.</p>
<p>Define a fixed asset group by using the <strong>Fixed asset groups</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa573347(v=ax.60)">Fixed asset groups (form)</a>.</p>
<p>Create a fixed asset record. For more information, see <a href="create-a-fixed-asset.md">Create a fixed asset</a>.</p></td>
</tr>
<tr class="even">
<td><p>Depreciation</p></td>
<td><p>Set up the following prerequisites:</p>
<ul>
<li><p>Enable the catch-up rule for depreciation</p></li>
<li><p>Allow manual changes to the depreciation method</p></li>
<li><p>Assign the fiscal calendar to a value model</p></li>
<li><p>Set up the depreciation rate schedule</p></li>
<li><p>Set up rounding parameters for fixed asset depreciation</p></li>
<li><p>Set up a depreciation profile</p></li>
<li><p>Set up allowable limits for accumulated depreciation</p></li>
</ul>
<p>For more information, see <a href="jpn-set-up-depreciation-and-depreciation-methods.md">(JPN) Set up depreciation and depreciation methods</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Depreciate a fixed asset

Use the **Depreciation proposal** form to create a depreciation proposal to depreciate a fixed asset. After you run the depreciation proposal, you can view the posted depreciation amounts and the planned depreciation amounts for the fixed asset.

To depreciate the fixed asset, follow these steps:

1.  Click **Fixed assets** \> **Journals** \> **Fixed assets**.

2.  In the **Fixed assets** form, select the fixed asset journal, and then click **Lines**.

3.  In the **Journal voucher** form, enter the required details for the voucher. For more information, see [Journal voucher - Fixed assets (form)](https://technet.microsoft.com/en-us/library/aa620564\(v=ax.60\)).

4.  Click **Proposals** \> **Depreciation proposal**.

5.  In the **Depreciation proposal** form, in the **To date** field, enter the ending date of the period to create the depreciation profile for.
    

    > [!NOTE]
    > <P>If required, you can select the <STRONG>Summarize depreciation</STRONG> check box to summarize the details of monthly depreciation amounts in one journal line.</P>



6.  Click **OK** to generate the depreciation proposal and close the form.

You can use the **Fixed asset balances** form to view the depreciation amounts that are posted. For more information, see [Fixed asset balances (form)](https://technet.microsoft.com/en-us/library/aa589217\(v=ax.60\)).

If you want to view the planned depreciation amounts for the fixed asset value model, you can do so in the **Profile** form. You can also view a timetable for planned depreciation if you specified the number of years to use to equally divide depreciation amounts in the **Number of years to equally divide depreciation amounts** field in the **Depreciation profiles** form.

For more information about the fields that are available in the **Profile** form, see [Fixed asset profile (form)](https://technet.microsoft.com/en-us/library/aa583543\(v=ax.60\)), and the following table:

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
<td><p><strong>Beginning balance of accumulated depreciation</strong></p></td>
<td><p>The beginning balance of the accumulated depreciation from the start of the fiscal period for the selected date.</p></td>
</tr>
<tr class="even">
<td><p><strong>YTD value of accumulated depreciation</strong></p></td>
<td><p>The sum of the depreciation expenses that are incurred from the beginning of the year for the selected date.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Period</strong></p></td>
<td><p>The name of the fiscal period.</p></td>
</tr>
<tr class="even">
<td><p><strong>From date</strong></p></td>
<td><p>The starting date of the period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>To date</strong></p></td>
<td><p>The ending date of the period.</p></td>
</tr>
<tr class="even">
<td><p><strong>Number of months</strong></p></td>
<td><p>The number of months in the selected period.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Number of remaining months</strong></p></td>
<td><p>The number of months that remain for depreciation in the selected period.</p></td>
</tr>
</tbody>
</table>


## 2\. Change the depreciation profile for a fixed asset

Use the **Change fixed asset depreciation profile** form to change a fixed asset depreciation profile. You can change the depreciation profile to one that uses a different depreciation method to depreciate the asset.

If necessary, you can also use this form to specify whether to update the service life of the fixed asset. The service life of the asset is updated depending on the change of depreciation method that is applied to the fixed asset.

The following table shows the depreciation method changes that are allowed:

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Starting depreciation method</p></th>
<th><p>Allowed depreciation method change</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Old straight line</p></td>
<td><p>Old declining balance</p></td>
</tr>
<tr class="even">
<td><p>Old declining balance</p></td>
<td><p>Old straight line</p></td>
</tr>
<tr class="odd">
<td><p>New straight line</p></td>
<td><p>250% declining balance</p>
<p>–or–</p>
<p>200% declining balance</p></td>
</tr>
<tr class="even">
<td><p>250% declining balance</p></td>
<td><p>200% declining balance</p>
<p>–or–</p>
<p>New straight line</p></td>
</tr>
<tr class="odd">
<td><p>200% declining balance</p></td>
<td><p>250% declining balance</p>
<p>–or–</p>
<p>New straight line</p></td>
</tr>
</tbody>
</table>


To change the depreciation profile for a fixed asset, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Value models**.

2.  Select a value model that is assigned to the fixed asset, and then click **Fixed asset groups**.

3.  In the **Fixed asset group/value model** form, click **Change the fixed asset depreciation profile**.

4.  In the **Change fixed asset depreciation profile** form, in the **To depreciation profile** field, select the depreciation profile that uses the depreciation method that you want to change to.

5.  In the **Start date** field, enter the date from which the depreciation profile is effective.

6.  Select the **Use equally-divided formula** check box to divide depreciation amounts equally.
    

    > [!NOTE]
    > <P>This field is available only if you are changing from a depreciation profile that uses the <STRONG>Old declining balance</STRONG> depreciation method to a depreciation profile that uses the <STRONG>Old straight line</STRONG> depreciation method.</P>



7.  In the **Number of years for equally-divided formula** field, enter the number of years that the remaining depreciation amounts should be equally spread across.

8.  Select the **Update service life** check box to automatically update the service life of the fixed asset.
    

    > [!NOTE]
    > <P>This check box is available only if the <STRONG>Use equally-divided formula</STRONG> check box is not selected and if you are performing the following changes to depreciation methods:</P>
    > <UL>
    > <LI>
    > <P><STRONG>Old declining balance</STRONG> to <STRONG>Old straight line</STRONG></P>
    > <LI>
    > <P><STRONG>250% declining balance</STRONG> to <STRONG>New straight line</STRONG></P>
    > <LI>
    > <P><STRONG>200% declining balance</STRONG> to <STRONG>New straight line</STRONG></P>
    > <LI>
    > <P><STRONG>250% declining balance</STRONG> to <STRONG>200% declining balance</STRONG></P></LI></UL>



9.  Select the **Always allow the depreciation method to be changed** check box to allow a depreciation method change even when the accumulated depreciation is more than 95 percent of the acquisition cost and the equally divided formula is used to recalculate the depreciation amounts when you run the depreciation proposal.

10. Click **Apply** to recalculate the depreciation amounts and service life by using the depreciation method from the depreciation profile that you selected in the **To depreciation profile** field.

For more information about the fields on the **Change fixed asset depreciation profile** form, refer to the following table:

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
<td><p><strong>From depreciation profile</strong></p></td>
<td><p>The depreciation profile that is currently used to depreciate the fixed asset.</p></td>
</tr>
<tr class="even">
<td><p><strong>Selected depreciation profile</strong></p></td>
<td><p>The depreciation profile that is displayed in the <strong>From depreciation profile</strong> field.</p></td>
</tr>
<tr class="odd">
<td><p><strong>End date</strong></p></td>
<td><p>The ending date of the period during which the depreciation profile is effective.</p></td>
</tr>
<tr class="even">
<td><p><strong>Net book value</strong></p></td>
<td><p>The net book value of the fixed asset as of the depreciation profile switch date.</p>
<div class="alert">

> [!NOTE]
> <P>When this field was stored, it does not change automatically any more. Under unusual use cases when a transaction is posted on a date before the <STRONG>Start date</STRONG>, this field will still not change. The workaround is to calculate the new correct net book value and update the field manually. For this scenario, regardless of whether the user has updated this field on the form, future calculations will always consider the newly posted transaction.</P>


</div></td>
</tr>
</tbody>
</table>


## 3\. Import a depreciation rate schedule to recalculate depreciation balances and update the service life

After you change the depreciation method for the fixed asset, you can use the **Undepreciated balance schedule for fixed assets** form and the **Years passed schedule for fixed assets** form to import depreciation rate schedules. This depreciation rate schedule is used to recalculate depreciation balances and to update the service life of the fixed asset. You can import a Microsoft Excel file that contains the calculation rates for depreciation balances and the updated service life of the fixed asset. You can determine which of these forms to use depending on the depreciation method change that you apply to the fixed asset.

The following table provides details about the forms and the scenarios in which they can be used to import the depreciation rate schedule:

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Form name
  </p> </th>
    <th> <p>
   
	 Change of depreciation method
  </p> </th>
  </tr>
  <tr>
    <td rowspan="3"> <p> <strong>Undepreciated balance schedule for fixed assets</strong> </p> </td>
    <td> <p> <strong>Old declining balance</strong> to <strong>Old straight line</strong> </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>250% declining balance</strong> to <strong>New straight line</strong> </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>200% declining balance</strong> to <strong>New straight line</strong> </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Years passed schedule for fixed assets</strong> </p> </td>
    <td> <p> <strong>250% declining balance</strong> to <strong>200% declining balance</strong> </p> </td>
  </tr>
</table>


To import a depreciation rate schedule by using the **Undepreciated balance schedule for fixed assets** form, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Schedules** \> **Undepreciated balance schedules**.

2.  Click **New** to create a record to import the depreciation rate schedule.

3.  In the **Name** field, enter a name for the imported depreciation schedule.

4.  In the **From method** field and **To method** field, select the starting and ending depreciation methods that are applied to the fixed asset. The undepreciated balances and service life of the fixed assets to which this change of depreciation profile is assigned are updated based on the depreciation rate schedule that you import.

5.  Click **Import from Microsoft Excel** to open the Excel file that contains the depreciation rates for the fixed assets. You must publish the Excel file to Microsoft Dynamics AX to import the depreciation rates into the **Undepreciated balance schedule for fixed assets** form.

6.  On the **Overview** FastTab, you can view the details about the depreciation rate schedule in the following fields:
    
      - **Service life** – The service life of the fixed asset in years.
    
      - **Upper limit** – The maximum depreciation rate for the fixed asset.
    
      - **Lower limit** – The minimum depreciation rate for the fixed asset.
    
      - **Years passed** – The number of years that have passed before the depreciation method is changed.

You can follow steps 2 through 6 in this procedure to import the depreciation rate schedule by using the **Years passed schedule for fixed assets** form. Click **Fixed assets** \> **Setup** \> **Schedules** \> **Years passed schedules** to open the **Years passed schedule for fixed assets** form.

## 4\. View or change the start date of 5 year equally divided depreciation

In the fiscal years after 2008, when the accumulated depreciation for a fixed asset with old straight line or old declining balance methods reaches 95% of the acquisition cost, the net book value of the fixed asset is permitted to be depreciated to 1 Yen in 5 years with equal amount for each of the 5 years. The 5 years of equal amount depreciation is referred to as **the 5 year mode**. The entering of the 5 year mode has been built-in to the depreciation logic of Microsoft Dynamics AX. When you migrate fixed assets into Microsoft Dynamics AX, you must manually enter the start date for any fixed assets that are already in the 5 year mode.

To view or update the start date of the 5 year mode, follow these steps:

1.  Click **Fixed assets** \> **Common** \> **Fixed assets** \> **Fixed assets**.

2.  Select the fixed asset to view or update.

3.  Click **Value models** or **Depreciation books** and then expand the **Depreciation** tab.

4.  View or update the **Start date off the 5 year equally divided method** field.

## Related tasks

[Fixed asset transaction types](fixed-asset-transaction-types.md)

[Basic setup of Fixed assets](basic-setup-of-fixed-assets.md)

[Fixed asset inquiries](fixed-asset-inquiries.md)

[Fixed asset posting and journals](fixed-asset-posting-and-journals.md)

[(JPN) Fixed asset depreciation](jpn-fixed-asset-depreciation.md)

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
<td><p>Ensure that the <strong>Asset</strong> configuration key is available under the <strong>Data Dictionary</strong> &gt; <strong>Configuration Keys</strong> node in the Application Object Tree.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>To perform this task, you must be a member of the <strong>SYSADMIN</strong> security role.</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

