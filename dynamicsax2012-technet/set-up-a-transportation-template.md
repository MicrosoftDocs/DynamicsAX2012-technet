---
title: Set up a transportation template
TOCTitle: Set up a transportation template
ms:assetid: 7bd474cd-4fba-4389-b8d1-74a7de3ee7ac
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553174(v=AX.60)
ms:contentKeyID: 62200104
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TMSTransportationTemplate
- transportation template
- transportation templates
---

# Set up a transportation template 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



You can use transportation templates to override the general rating setup that is returned when you rate a shipping carrier. Templates enable you to identify specific charges that apply to the shipping carrier. If a transportation template is selected for a shipping carrier, the template charges will override the charges from the general rating setup that applies to the shipping carrier. For more information about the general rating setup, see [Set up rate masters](set-up-rate-masters.md). The template also overrides any charges that are set up for the shipping carrier in the **Override charges** form.

When you use a transportation template, you can specify that charges from a shipping carrier should correspond to charges for a customer or to a specific charge that will be applied in the rating of the shipment carrier.

## Set up a transportation template

To set up a transportation template, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Transportation template**.

2.  Click **New** to create a new transportation template.

3.  Enter an identification and a name for the transportation template.

4.  On the **Shipper** FastTab, specify the shipping carrier that should be associated with a specific charge. You can also specify if a carrier group, carrier service, or route plan should be associated with specific charges.

5.  On the **Customer** FastTab, specify the customer or customer details that will indicate if the rating setup that is returned for the shipping carrier should be ignored.

6.  Select the **Manual** check box to specify a specific charge for the shipment carrier.

7.  On the **Charges** FastTab, click **New** to create a charge for the shipment carrier. This charge is only available if, on the **Customer** FastTab, you have selected the **Manual** check box.

8.  Optional: On the **Additional information** FastTab, in the **Load template ID** field, select a load template to be associated with the charge. If any equipment is registered for the load template, it is displayed in the **Equipment** field.

## Select a transportation template

To make sure that a transportation template is considered when you rate a load in the **Rate route workbench** form, the transportation template must be selected.

To select a transportation template, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Rate route workbench**.

2.  On the **Rate criteria** tab, in the **Data** group, select the **Transportation template ID**.

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
<td><p>Click <strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Licensing</strong> &gt; <strong>License configuration</strong>. Expand the <strong>Trade</strong> license key, and select the <strong>Warehouse and Transportation management</strong> configuration key.</p></td>
</tr>
</tbody>
</table>


## See also

[Set up rate masters](set-up-rate-masters.md)

[Set up a load template](set-up-a-load-template.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

