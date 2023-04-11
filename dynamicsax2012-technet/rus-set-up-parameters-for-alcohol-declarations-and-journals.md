---
title: (RUS) Set up parameters for alcohol declarations and journals
TOCTitle: (RUS) Set up parameters for alcohol declarations and journals
ms:assetid: efe47d6c-54f2-4825-acfb-e083862e52b0
ms:mtpsurl: https://technet.microsoft.com/library/Dn494962(v=AX.60)
ms:contentKeyID: 60513662
author: tonyafehr
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- Parameters
- Forms.InventLocation
- Forms.InventParameters
- Forms.EcoResProductPerCompanyListPage
- Russia
- Forms.Branches_RU
- Forms.InventProfile_RU
- Forms.AlcoholActivityKind_RU
- Forms.AlcoholLicenseRelTable_RU
- Forms.AlcoholProductionType_RU
- Forms.AlcoholLicenseTable_RU
- RU - 00126
- Alcohol declaration journal
- Russian federation
- RU - 00055
- Alcohol declaration
- alcoholic items
- movement of alcoholic items
- purchases of alcoholic items
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up parameters for alcohol declarations and journals 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use Microsoft Dynamics AX to set up and generate an alcohol declaration that contains information about the sales of alcoholic items, purchases of alcoholic items, and movement of alcoholic items between separate company divisions for each vendor type, customer type, or alcohol production type.

You can set up inventory profiles, inventory parameters, alcohol regulatory authorities, alcohol activity kinds, alcohol production types, alcohol declaration for items, and alcohol licenses for alcohol declarations and journals.

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
<td><p>Microsoft Dynamics AX 2012 R2 with cumulative update 7 or later</p></td>
</tr>
<tr class="even">
<td><p><strong>Country/region</strong></p></td>
<td><p>The primary address for the legal entity must be in the following countries/regions: Russia</p></td>
</tr>
<tr class="odd">
<td><p><strong>Related setup task</strong></p></td>
<td><p>Set up a unit of measure and a unit conversion for alcohol. For more information, see <a href="https://technet.microsoft.com/library/jj853235(v=ax.60)">(RUS) Units (modified form)</a> and <a href="https://technet.microsoft.com/library/hh209285(v=ax.60)">Unit conversions (form)</a>.</p></td>
</tr>
</tbody>
</table>


## 1\. Set up an inventory profile for an alcohol activity type

Use the **Inventory profiles** form to set up an inventory profile to track and report the movement of items and the accounting of on-hand inventory quantities for alcohol activity types.

To set up the inventory profile, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Dimensions** \> **Inventory profiles**.

2.  Click **New** to create a profile, and then enter the required details. For more information, see [(RUS) Set up an inventory profile](rus-set-up-an-inventory-profile.md).

3.  In the **Alcohol activity type** field, select **Retail** or **Wholesale**.

## 2\. Set up a number sequence for alcohol declarations and journals

Use the **Inventory and warehouse management parameters** form to set up a number sequence for alcohol declarations and journals.

To set up the number sequence, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

2.  Click **Number sequences**, and then in the **Number sequences** area, in the **Number sequence code** field, select the number sequence code for **The alcohol declaration journal number** reference.

## 3\. Set up an alcohol regulatory authority for a division

Use the **Separate divisions** form to set up a vendor account as an alcohol regulatory authority for a company division.

To set up the alcohol regulation authority, follow these steps:

1.  Click **Organization administration** \> **Setup** \> **Separate divisions**.

2.  Click **New** to create a record, and then enter the required details. For more information, see [(RUS) Set up a division for a company and associate it with a vendor](rus-set-up-a-division-for-a-company-and-associate-it-with-a-vendor.md).

3.  In the **Alcohol regulation authority** field, select the vendor to use as the regulatory authority.

## 4\. Optional: Assign a warehouse to a vendor that is associated with the separate company division

Use the **Warehouses** form to assign a warehouse to a vendor that is associated with the separate company division.

To assign the warehouse to a vendor, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Inventory breakdown** \> **Warehouses**.

2.  Select the **Warehouse** to assign to the vendor.

3.  In the **Vendor account** field, select the vendor account that is associated with the vendor.

## 5\. Set up an alcohol activity kind

Use the **Alcohol activity kinds** form to set up an activity kind for retail transactions that are associated with the sale of alcohol.

To set up the alcohol activity kind, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Alcohol declaration** \> **Alcohol activity kinds**.

2.  Click **New** to create a record.

3.  In the **Alcohol activity kind** and **Description** fields, enter the name and description of the activity kind.

## 6\. Set up an alcohol production type

Use the **Alcohol production types** form to set up an alcohol production type for alcohol sales.

To set up the alcohol production type, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Alcohol declaration** \> **Alcohol production types**.

2.  Click **New** to create a record.

3.  In the **Production type** field, enter the production type code.

4.  In the **Parent type** field, select the next highest hierarchical category for the production type that you specified in the **Production type** field.

5.  In the **Name** field, enter the name of the production type.

6.  In the **Beer** field, select **Yes** or **No** to indicate whether the sale of beer is licensed.

## 7\. Set up alcohol declaration information for an alcoholic item

Use the **Released product details** and **Inventory and warehouse management parameters** forms to set up alcohol declaration information for an alcoholic item.

To set up alcohol declaration information, follow these steps:

1.  Click **Product information management** \> **Common** \> **Released products**.

2.  Double-click the alcoholic item record.

3.  On the **Manage inventory** FastTab, in the **Unit** field, enter the unit type that is used to measure the item.

4.  On the **Alcohol declaration** FastTab, in the **Production type** field, select the production type code for the item.

5.  In the **Manufacturer (Importer)** field, select the vendor that is identified as the manufacturer or importer of the item.

6.  In the **Alcohol concentration (%)** field, enter the percentage of alcohol that is contained in the item, and then close the form.

7.  Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**.

8.  Select the **Include alcohol concentration** check box to indicate that the percentage of alcohol that is contained in the item is considered in the calculation of alcohol production volume.

9.  In the **Unit** field, select the unit to use to calculate alcohol production.

## 8\. Set up an alcohol license and assign it to a customer, a vendor, or a legal entity

Use the **Alcohol licenses** form to set up an alcohol license. You can then use the **Customers**, **Vendors**, or **Legal entities** forms to assign the license to a customer, a vendor, or a legal entity.

To set up the alcohol license, follow these steps:

1.  Click **Inventory management** \> **Setup** \> **Alcohol declaration** \> **Alcohol licenses**.

2.  Press CTRL+N to create a record, and then enter the series, number, issue date, expiration date, alcohol activity type, alcohol activity kind, and production type for the alcohol license.
    
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
    <td><p><strong>Series</strong></p></td>
    <td><p>Enter the series number of the license.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Number</strong></p></td>
    <td><p>Enter the license number.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Issue date</strong></p></td>
    <td><p>Enter the date when the license was issued.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Expiration date</strong></p></td>
    <td><p>Enter the expiration date of the license.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Issued by</strong></p></td>
    <td><p>Enter the regulatory authority that issued the license.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Alcohol activity type</strong></p></td>
    <td><p>Select <strong>Retail</strong> or <strong>Wholesale</strong>.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Alcohol activity kind</strong></p></td>
    <td><p>Select the activity kind for the license.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Production type</strong></p></td>
    <td><p>Select the production type code for the license.</p></td>
    </tr>
    </tbody>
    </table>


To assign the alcohol license to a customer, a vendor, or a legal entity, follow these steps:

1.  Click **Accounts receivable** \> **Common** \> **Customers** \> **All customers**. Select a customer, and then on the **Action pane**, in the **Registration** action group, click **Alcohol licenses**.
    
    –or–
    
    Click **Accounts payable** \> **Common** \> **Vendors** \> **All vendors**. Select a vendor, and then on the **Action pane**, in the **Registration** action group, click **Alcohol licenses**.
    
    –or–
    
    Click **Organization administration** \> **Setup** \> **Organization** \> **Legal entities**. In the Left pane, select a legal entity, and then click **Alcohol licenses**.

2.  In the **Alcohol license** field, select the alcohol license to assign to the customer, the vendor, or the legal entity.

## Next step

You have finished setting up parameters for alcohol declarations and journals. You can now generate alcohol declarations and journals. For more information, see [(RUS) Generate alcohol declarations and journals](rus-generate-alcohol-declarations-and-journals.md).

## Related tasks

[(RUS) Set up and generate an electronic document for an alcohol declaration](rus-set-up-and-generate-an-electronic-document-for-an-alcohol-declaration.md)

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
<td><p>Ensure that you select the <strong>Trade</strong> (LogisticsBasic) configuration key.</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles and duties</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the duties that are described in the following table.</p>
<div class="caption">
</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Duty</p></th>
<th><p>Name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Enable alcohol declaration process</strong></p></td>
<td><p>AlcoholDeclarationProcessEnable_RU</p></td>
</tr>
<tr class="even">
<td><p><strong>Inquire into alcohol declaration data</strong></p></td>
<td><p>AlcoholDeclarationDataInquire_RU</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
<tr class="odd">
<td><p><strong>Security roles and privileges</strong></p></td>
<td><p>To perform this task, you must be a member of a security role that includes the privileges that are described in the following table.</p>
<div class="caption">

</div>
<div class="tableSection">
<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Privilege</p></th>
<th><p>Name</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Maintain alcohol declaration data</strong></p></td>
<td><p>AlcoholDeclarationMaintain_RU</p></td>
</tr>
<tr class="even">
<td><p><strong>View alcohol declaration data</strong></p></td>
<td><p>AlcoholDeclarationView_RU</p></td>
</tr>
</tbody>
</table>

</div></td>
</tr>
</tbody>
</table>

  


