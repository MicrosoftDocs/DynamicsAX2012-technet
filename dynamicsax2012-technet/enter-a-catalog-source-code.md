---
title: Enter a catalog source code
TOCTitle: Enter a catalog source code
ms:assetid: a3850d0c-0453-4fa3-ab26-ca8b8dcdd09d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn497808(v=AX.60)
ms:contentKeyID: 62200126
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- source code
- catalog code
- Forms.MCRSourceIdTargetLookup
- MsDynAx060.Forms.MCRSourceIdTargetLookup
audience: Application User
ms.search.region: Global
---

# Enter a catalog source code 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

If a customer orders from a call center catalog that includes a source code, you should enter the source code in the sales order as described in this topic. The sales that are associated with that catalog can then be tracked and analyzed.

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
<td><p><a href="set-up-catalog-source-codes.md">Set up catalog source codes</a></p>
<p><a href="set-up-a-call-center.md">Set up a call center</a></p>
<div class="alert">

> [!IMPORTANT]
> <P>During call center setup, you must do the following to enable source code functionality:</P>
> <UL>
> <LI>
> <P>Add the user who will create the sales order to the list of users for the call center channel.</P>
> <LI>
> <P>Select the <STRONG>Enable directed selling</STRONG> check box in the call center settings.</P></LI></UL>


</div></td>
</tr>
</tbody>
</table>


## Enter a catalog source code in a sales order

To enter a source code in a sales order, follow these steps.

1.  Click **Call center** \> **Common** \> **All sales orders**. Enter customer information to create a new sales order.

2.  Ask the customer for the source code that is printed on the catalog. On the **Sales order header** FastTab, in the **Source** field, select the code from the list.
    

    > [!NOTE]
    > <P>If the code has expired or has not yet been activated, it does not appear in the list.</P>



3.  Continue to create the sales order as usual.


> [!NOTE]
> <P>The call center parameters can be set up so that <STRONG>Source</STRONG> is a required field. For more information, see <A href="configuring-parameters-and-initial-settings-call-center.md">Configuring parameters and initial settings (Call center)</A>.</P>




> [!NOTE]
> <P>If free products are included in the catalog that is associated with the source code, those products are added to the order automatically when the source code is entered. For more information, see <A href="create-call-center-catalogs.md">Create call center catalogs</A>.</P>



## Next step

After you have created sales orders that include a source code, you can analyze the sales data for the source code. For more information, see [Analyze source code data](analyze-source-code-data.md).

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
<td><p><strong>Retail Headquarters</strong> configuration key</p>
<p><strong>Call center</strong> configuration key</p>
<p><strong>Source code</strong> configuration key</p></td>
</tr>
<tr class="even">
<td><p><strong>Security roles</strong></p></td>
<td><p>Sales clerk</p></td>
</tr>
</tbody>
</table>


## See also

[Create call center catalogs](create-call-center-catalogs.md)

[Set up catalog source codes](set-up-catalog-source-codes.md)

[Working with call center catalogs](working-with-call-center-catalogs.md)

[Configuring parameters and initial settings (Call center)](configuring-parameters-and-initial-settings-call-center.md)

  


