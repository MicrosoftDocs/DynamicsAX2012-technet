---
title: Vendor portal administrator security role (VendVendorPortalAdministrator)
TOCTitle: Vendor portal administrator security role (VendVendorPortalAdministrator)
ms:assetid: 0548f644-2d08-4a51-a869-e38b4e40e236
ms:mtpsurl: https://technet.microsoft.com/library/Hh544037(v=AX.60)
ms:contentKeyID: 37823118
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Vendor portal administrator security role (VendVendorPortalAdministrator) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Vendor portal administrator security role represents an external user who has a vendor relationship with legal entities. This user is responsible for maintaining information about external parties who use the vendor portal. This user can also grant access to the vendor portal to external parties.

## Duties

By default, this security role is assigned the following duties in Microsoft Dynamics AX.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Duty name</strong></p></th>
<th><p><strong>Duty AOT name</strong></p></th>
<th><p><strong>Duty description</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Inquire into items for vendor master (Enterprise Portal)</p></td>
<td><p>VendInventTableVSSInquire</p></td>
<td><p>Respond to inquiries about items for vendor master in Enterprise Portal</p></td>
</tr>
<tr class="even">
<td><p>Inquire into purchase order to invoice progress (Enterprise Portal)</p></td>
<td><p>VendPurchaseToInvoiceVSSInquire</p></td>
<td><p>Respond to inquiries about the status of the purchase order to invoice process in Enterprise Portal</p></td>
</tr>
<tr class="odd">
<td><p>Inquire into request for quotation for vendor</p></td>
<td><p>PurchRFQVendorInquire</p></td>
<td><p>Inquire into the request for quotation for a vendor by using the vendor self-service portal</p></td>
</tr>
<tr class="even">
<td><p>Inquire into vendor master (Enterprise Portal)</p></td>
<td><p>VendVendorMasterVSSInquire</p></td>
<td><p>Respond to inquiries about vendor master data in Enterprise Portal</p></td>
</tr>
<tr class="odd">
<td><p>Maintain catalogs</p></td>
<td><p>CatProcurementCatalogMasterMaintain</p></td>
<td><p>Maintain all types of catalogs</p></td>
</tr>
<tr class="even">
<td><p>Maintain external vendor user requests</p></td>
<td><p>VendUserRequestExternalMaintain</p></td>
<td><p>Maintain and submit vendor user request for vendor self-service portal</p></td>
</tr>
<tr class="odd">
<td><p>Maintain vendor catalogs on vendor self-service portal</p></td>
<td><p>CatProcurementCatalogMasterVSSMaintain</p></td>
<td><p>Catalog maintenance</p></td>
</tr>
<tr class="even">
<td><p>Maintain vendor contact list</p></td>
<td><p>VendProfileContactListMaintain</p></td>
<td><p>Maintain vendor contact list on vendor portal</p></td>
</tr>
</tbody>
</table>

  


