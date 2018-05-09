---
title: Set up a rating profile
TOCTitle: Set up a rating profile
ms:assetid: 4a3ed5e8-3e85-4da0-94fd-72bb69cbc0e4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553162(v=AX.60)
ms:contentKeyID: 62524892
ms.date: 06/25/2014
mtps_version: v=AX.60
---

# Set up a rating profile 


_**Applies To:** Microsoft Dynamics AX 2012 R3_

This topic provides an overview of how to use a rating profile to determine whether the shipping carrier’s rate matches the customer’s requirements. A rating profile is used to associate the shipping carrier with a rate master. The rate master defines the rate base assignment and the rate base. The rate base determines the rate of the carrier.

A rating profile is unique for a shipping carrier. You can set up a rating profile using a generic setup form which has an overview of all existing rating profiles. You can also set up the rating profile directly from the shipping carrier. The information that you set up for the rating profile is the same, regardless of how you access the setup.

## Create a rating profile using a setup form

To create a rating profile using a setup form, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **Rating** \> **Rating profile**.

2.  Click **New** to create a new rating profile.

3.  Enter a unique identifier (ID) and description for the rating profile.

4.  Select a shipping carrier, site, and warehouse.

5.  Select the rate engine and rate master that you want to use for the rating profile. You can use the rate master to define a rate base type and a rate base. For more information, see [Set up rate masters](set-up-rate-masters.md).

6.  Select the transit engine and carrier fuel index for the rating profile.

7.  Select the effective start and end times for the rating profile.

## Create a rating profile using a shipping carrier

To create a rating profile using a shipping carrier, follow these steps:

1.  Click **Transportation management** \> **Setup** \> **General** \> **Shipping carrier**.

2.  Select a shipping carrier.

3.  On the **Rating profile** FastTab, click **New** to create a rating profile. The fields on this FastTab correspond to the fields in the **Rating profile** form. For more information, see the “Create a rating profile using a setup form” section earlier in this topic.

## Related tasks

[Set up transportation management engines](set-up-transportation-management-engines.md)

[Set up accessorial charges for a shipping carrier](set-up-accessorial-charges-for-a-shipping-carrier.md)

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

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

