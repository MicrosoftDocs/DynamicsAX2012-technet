---
title: Set up address and contact information purposes
TOCTitle: Set up address and contact information purposes
ms:assetid: d2cc4e3f-cb49-45e9-9135-2b06c0590067
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731964(v=AX.60)
ms:contentKeyID: 35132906
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up address and contact information purposes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX, you can assign one or more purposes to a postal address record or a contact information record. A purpose describes how a particular address record or contact information record is used. The following table shows an example of the list of addresses for a customer, and the purposes that are assigned to each postal address.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Postal address</p></th>
<th><p><strong>Address purpose</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Eislebener Street/67</p>
<p>12345 Berlin</p>
<p>Germany</p></td>
<td><p><strong>Primary</strong>, <strong>Delivery</strong>, <strong>RemitTo</strong></p></td>
</tr>
<tr class="even">
<td><p>Thierschstrasse 12</p>
<p>56789 Munich</p>
<p>Germany</p></td>
<td><p><strong>Delivery</strong>, <strong>Service</strong></p></td>
</tr>
<tr class="odd">
<td><p>An der Budesstrasse 123</p>
<p>34567 Neu-Isenburg/Frankfurt</p>
<p>Germany</p></td>
<td><p><strong>One time</strong></p></td>
</tr>
</tbody>
</table>


For example, if a customer record contains a postal address for each of the customer's four locations, you can assign a purpose to each postal address. The purpose can help you track where deliveries must be sent, where services are needed, or where mail is sent by using the postal service.

## Predefined purposes

Microsoft Dynamics AX includes several predefined purposes. You can also create your own purposes to meet the requirements of your organization. The following table describes the purposes that are included in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Purpose</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Invoice</strong></p></td>
<td><p>The address to which you send invoices.</p></td>
</tr>
<tr class="even">
<td><p><strong>Delivery</strong></p></td>
<td><p>The address to which products are delivered.</p></td>
</tr>
<tr class="odd">
<td><p><strong>SWIFT</strong></p></td>
<td><p>The address that is used for money transfers by international banks.</p></td>
</tr>
<tr class="even">
<td><p><strong>Payment</strong></p></td>
<td><p>The address to which you send payments.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Service</strong></p></td>
<td><p>The address that is used for service calls.</p></td>
</tr>
<tr class="even">
<td><p><strong>Home</strong></p></td>
<td><p>The address that is used for the party's home.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Other</strong></p></td>
<td><p>The address that is used for another type of location that is not defined in this list.</p></td>
</tr>
<tr class="even">
<td><p><strong>Business</strong></p></td>
<td><p>The address that is used for the party's business.</p></td>
</tr>
<tr class="odd">
<td><p><strong>RemitTo</strong></p></td>
<td><p>The address to which you send the payment when a check is issued to a vendor.</p></td>
</tr>
<tr class="even">
<td><p><strong>Third party shipping</strong></p></td>
<td><p>The address that is used when the customer is billed for freight by a shipping carrier.</p></td>
</tr>
<tr class="odd">
<td><p><strong>Statement</strong></p></td>
<td><p>The address that is used when internal or external statements are generated, or when customer statements are exported to Microsoft Excel by using the <strong>Collections</strong> form.</p></td>
</tr>
<tr class="even">
<td><p><strong>Fixed asset</strong></p></td>
<td><p>The address that is used for a fixed asset.</p></td>
</tr>
<tr class="odd">
<td><p><strong>One time</strong></p></td>
<td><p>An address that is used only one time, and that does not have to be stored with the party record.</p>
<p>You can mark an address as one time only when you are adding an address in a transaction, such as a sales order.</p></td>
</tr>
<tr class="even">
<td><p><strong>Recruit</strong></p></td>
<td><p>The address that is used to for a recruit or a prospective worker.</p></td>
</tr>
</tbody>
</table>


## Assign a purpose to an address or contact

1.  Click **Organization administration** \> **Setup** \> **Global address book** \> **Address and contact information purpose**.

2.  In the list, select whether each purpose applies to an address record, a contact information record, or both.

3.  To add a new purpose, click **New**, and then enter the name of the purpose and a brief description. Then select the **Postal address** or **Contact information** check box to specify whether the purpose is used for address records or contact information records.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

