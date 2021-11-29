---
title: (JPN) Set up depreciation and depreciation methods
TOCTitle: (JPN) Set up depreciation and depreciation methods
ms:assetid: c8935f79-f46d-4fae-8ec4-851833bf349d
ms:mtpsurl: https://technet.microsoft.com/library/Dn408184(v=AX.60)
ms:contentKeyID: 56285049
author: Khairunj
ms.date: 12/03/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.AssetDepreciationProfile
- Forms.AssetGroup
- Forms.AssetParameters
- Forms.AssetGroupBookSetup
- Forms.AssetBookTable
- Forms.Currency
- Forms.AssetDepBookTable
- Forms.AssetGroupDepBookSetup
- Forms.AssetDepRate_JP
- MsDynAx060.Forms.AssetBookTable
- MsDynAx060.Forms.AssetDepreciationProfile
- MsDynAx060.Forms.AssetParameters
- MsDynAx060.Forms.AssetDepBookTable
- MsDynAx060.Forms.Currency
- MsDynAx060.Forms.AssetGroup
- MsDynAx060.Forms.AssetGroupBookSetup
- MsDynAx060.Forms.AssetGroupDepBookSetup
- depreciation method
- depreciation profile
- Equally divided
- MsDynAx060.Forms.AssetDepRate_JP
audience: Application User
ms.search.region: Japan
---

# (JPN) Set up depreciation and depreciation methods 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

To depreciate a fixed asset in Microsoft Dynamics AX, you can set up parameters, depreciation methods, and allowable limits for depreciation. You can specify the allowable limit for accumulated depreciation, which is the maximum amount of accumulated depreciation that can be deducted from the acquisition value of a fixed asset for its useful life.

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
<td><p><strong>Version</strong></p></td>
<td><p>Microsoft Dynamics AX 2012 with cumulative update 6 or later</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Japan</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup tasks</strong></p></td>
<td><ul>
<li><p>Ensure that you have set up basic fixed asset parameters, such as a default value model, reason codes, and number sequences, by using the <strong>Fixed assets parameters</strong> form. For more information, see <a href="set-up-fixed-assets-parameters.md">Set up Fixed assets parameters</a>.</p></li>
<li><p>Define a fixed asset group by using the <strong>Fixed asset groups</strong> form. For more information, see <a href="https://technet.microsoft.com/library/aa573347(v=ax.60)">Fixed asset groups (form)</a>.</p></li>
<li><p>Ensure that you have created a fixed asset record. For more information, see <a href="create-a-fixed-asset.md">Create a fixed asset</a>.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p><strong>Depreciation setup task</strong></p></td>
<td><p>Set up a depreciation book by using the <strong>Depreciation books</strong> form. For more information, see <a href="https://technet.microsoft.com/library/aa572416(v=ax.60)">Depreciation books (form)</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set up fixed asset parameters for calculating depreciation

Use the **Fixed assets parameters** form to enable the catch-up rule for depreciation, and to allow a manual change to the depreciation method that is applied to a fixed asset.

To set up the fixed asset parameters that are required for calculating depreciation, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Fixed assets parameters**.

2.  In the **Fixed assets parameters** form, in the **Set up fixed asset information** area, on the **Depreciation** FastTab, select the **Allow catch-up rule for depreciation** and **Allow the depreciation method to be manually changed** check boxes.

## 2\. Assign the fiscal calendar to a value model

Use the **Value models** form to assign the fiscal calendar to the value model of the fixed asset. The calendar period must cover the useful life of the fixed asset.

To assign the fiscal calendar to the value model, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Value models**.

2.  On the **Calendar** FastTab, click **New**.
    

    > [!NOTE]
    > <P>The <STRONG>Calendar</STRONG> FastTab is available only if you select a value model with a depreciation profile that is specifically used to depreciate fixed assets in Japan.</P>



3.  In the **From date** field, select the starting date of the period to calculate depreciation for.

4.  In the **Calendar** field, select the identification code of the fiscal year.

## 3\. Set up the depreciation rate schedule

Use the **Depreciation rates for fixed assets** form to set up a depreciation rate schedule that is based on the useful life and the depreciation profile of the fixed asset. When you depreciate a fixed asset, Microsoft Dynamics AX uses this depreciation rate schedule to calculate depreciation amounts for the asset. You can import a Microsoft Excel file that contains the depreciation rates to apply to fixed assets. The depreciation rates in the depreciation rate schedule are categorized based on the depreciation method that is assigned to each asset.

To set up the depreciation rate schedule, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Schedules** \> **Depreciation rate schedule**.

2.  In the **Depreciation rates for fixed assets** form, click **New** to create a record.

3.  In the **Name** and **Description** fields, enter a name and a description for the depreciation rate schedule.

4.  On the **Overview** FastTab, click **New**.

5.  In the **Method** field, select the depreciation method to import a depreciation rate schedule for.

6.  Click **Import the depreciation rate from a Microsoft Excel file** to open the Excel file that contains the depreciation rates for fixed assets. You must publish the Excel file to Microsoft Dynamics AX to import the depreciation rates into the **Depreciation rates for fixed assets** form.
    

    > [!NOTE]
    > <P>If necessary, you can customize the depreciation rate schedule by manually changing the depreciation rates in the Excel file.</P>



7.  Close the Excel file to return to the **Depreciation rates for fixed assets** form. On the **Overview** FastTab, the depreciation rates are listed based on the type of depreciation that is applied to the fixed asset, as shown in the following table.

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
<td><p><strong>Method</strong></p></td>
<td><p>The depreciation method that the depreciation rate schedule is imported for. The imported depreciation rates are applied to fixed assets that use this depreciation method.</p></td>
</tr>
<tr class="even">
<td><p><strong>Service life</strong></p></td>
<td><p>The number of years that the fixed asset will be in service.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Depreciation rate</strong></p></td>
<td><p>The depreciation rate that is applied to the fixed asset.</p></td>
</tr>
<tr class="even">
<td><p><strong>Revised depreciation rate</strong></p></td>
<td><p>The depreciation rate that is used if the guaranteed minimum amount of depreciation is larger than the original depreciation amount.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Guaranteed depreciation rate</strong></p></td>
<td><p>The guaranteed minimum depreciation rate.</p></td>
</tr>
</tbody>
</table>


## 4\. Set up rounding parameters for fixed asset depreciation

Use the **Currencies** form to specify parameters to round down fractional depreciation amounts.

To set up the rounding parameters for fixed asset depreciation, follow these steps:

1.  Click **General ledger** \> **Setup** \> **Currency** \> **Currencies**.

2.  In the **Currencies** form, create or select a record for the Japanese yen (JPY). For more information, see [Create a currency code](create-a-currency-code.md).

3.  On the **Rounding rules** FastTab, in the **Fixed asset depreciation** field group, in the **Rounding rule** field, enter 1.

4.  In the **Rounding method** field, select **Downward**.

By specifying this rounding parameter, you ensure that fractional depreciation amounts are rounded down to the nearest whole currency unit.

## 5\. Set up a depreciation profile

Use the **Depreciation profiles** form to specify the depreciation methods, value models, and depreciation books to use to depreciate a fixed asset.

To set up the depreciation profile, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Depreciation** \> **Depreciation profiles**.

2.  In the **Depreciation profiles** form, create a depreciation profile. For more information, see [Set up depreciation profiles](set-up-depreciation-profiles.md).

3.  On the **General** FastTab, in the **Method** field, select one of the following options:
    
      - **Old straight line** – For assets that were placed into service prior to April 1, 2007
    
      - **New straight line** – For assets that were placed into service on or after April 1, 2007
    
      - **Old declining balance** – For assets that were placed into service prior to April 1, 2007
    
      - **250% new declining balance** – For assets that were placed into service prior to April 1, 2012
    
      - **200% new declining balance** – For assets that were placed into service on or after April 1, 2012
    
      - **Equally divided** – For assets for which the depreciation amounts are equally divided among all of the fiscal periods within the useful life of the fixed asset. The amounts are depreciated based on the period length that you specify in the **Number of years to equally divide depreciation amounts** field for the depreciation profile.
        
        This control is available only if Microsoft Dynamics AX 2012 R3 is installed.
    

    > [!NOTE]
    > <P>When you select one of these options, the <STRONG>Depreciation year</STRONG> field displays <STRONG>Fiscal</STRONG> by default.</P>



4.  In the **Period frequency** field, select a period that determines how often ledger accruals occur during the fiscal year.

5.  In the **Depreciation rate schedule** field, select the name of the depreciation rate schedule that you created for the depreciation profile.
    

    > [!NOTE]
    > <P>In AX 2012 R3: This field is not available if you select <STRONG>Equally divided</STRONG> in the <STRONG>Method</STRONG> field.</P>



6.  In the **Number of years to equally divide depreciation amounts** field, enter the number of years to equally divide depreciation amounts for fixed assets that were placed into service before April 1, 2007.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Equally divided</STRONG>, <STRONG>Old straight line</STRONG>, or <STRONG>Old declining balance</STRONG> in the <STRONG>Method</STRONG> field.</P>



7.  For the **Equally split the depreciation amount (95% of acquisition cost)** field, mark the field if you want to equally split the depreciation amount for the last year, when the accumulated depreciation reaches 95% of the acquisition cost.
    

    > [!NOTE]
    > <P>This field is available only if you select <STRONG>Old straight line</STRONG> or <STRONG>Old declining balance</STRONG> in the <STRONG>Method</STRONG> field.</P>



After you set up the depreciation profile, you can create a value model by using the **Value models** form, and assign the depreciation profile to the value model. For more information, see [Set up value models](set-up-value-models.md) and [Value models (form)](https://technet.microsoft.com/library/aa590830\(v=ax.60\)).

You can also assign the depreciation profile to a depreciation book by using the **Depreciation books** form. For more information, see [Depreciation books (form)](https://technet.microsoft.com/library/aa572416\(v=ax.60\)).

## 6\. Set up allowable limits for accumulated depreciation

The allowable limit for accumulated depreciation is the maximum amount of depreciation that can be deducted per tax book from the acquisition value of a fixed asset for its entire useful life. The allowable limit is based on the depreciation method that you apply to the fixed asset, and whether the fixed asset is tangible or intangible.

To set up allowable limits for accumulated depreciation, follow these steps:

1.  Click **Fixed assets** \> **Setup** \> **Fixed asset groups**.

2.  Select the fixed asset group for the fixed asset that you want to depreciate, and then click **Value models**.

3.  In the **Fixed asset group/value model** form, select the value model for the fixed asset.

4.  In the **Allowable limit for accumulated depreciation** field, select **95% \* Acquisition cost**, and then close the form.

5.  Click **Fixed assets** \> **Setup** \> **Depreciation** \> **Depreciation books**.

6.  Select the depreciation book for the fixed asset, and then click **Fixed asset groups**.

7.  In the **Fixed asset group/depreciation book** form, select the fixed asset group that the fixed asset belongs to.

8.  In the **Allowable limit for accumulated depreciation** field, select **95% \* Acquisition cost**, and then close the form.

9.  Click **Fixed assets** \> **Setup** \> **Value models**.

10. On the **Depreciation** tab, in the **Allowable limit for accumulated depreciation** field, select **95% \* Acquisition cost**.

## Next step

[(JPN) Configure and calculate fixed asset depreciation](jpn-configure-and-calculate-fixed-asset-depreciation.md)

## Related tasks

[Fixed asset transaction types](fixed-asset-transaction-types.md)

[Basic setup of Fixed assets](basic-setup-of-fixed-assets.md)

[Fixed asset inquiries](fixed-asset-inquiries.md)

[Fixed asset posting and journals](fixed-asset-posting-and-journals.md)

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
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To set up depreciation and depreciation methods, you must be a member of a security role that includes the duties that are described in the following table:</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Enable fixed assets process</strong></p></td>
<td><p>AssetFixedAssetsProcessEnable</p></td>
<td><p>Enable the fixed asset process</p></td>
</tr>
<tr class="even">
<td><p><strong>Inquire into fixed asset policies</strong></p></td>
<td><p>AssetFixedAssetPoliciesInquire</p></td>
<td><p>Set up a depreciation profile</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To set up depreciation and depreciation methods, you must be a member of a security role that includes the privileges that are described in the following table:</p>
<div class="caption">

</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
<th><p>Procedure</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Maintain fixed assets depreciation profiles</strong></p></td>
<td><p>AssetDepreciationProfile</p></td>
<td><p>Maintain fixed assets depreciation profiles</p></td>
</tr>
<tr class="even">
<td><p><strong>View fixed assets depreciation profiles</strong></p></td>
<td><p>AssetDepreciationProfileView</p></td>
<td><p>View fixed assets depreciation profiles</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


