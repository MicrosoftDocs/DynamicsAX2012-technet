---
title: About vendor request configuration
TOCTitle: About vendor request configuration
ms:assetid: 6114cc41-3f11-4297-85fe-4a148c0ec3e6
ms:mtpsurl: https://technet.microsoft.com/library/Hh209168(v=AX.60)
ms:contentKeyID: 36057640
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# About vendor request configuration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Workers in your company may want to purchase products from a vendor who is not approved to do business with your company. Or they may want to work with a vendor who is already approved to do business with your organization in another legal entity or procurement category. Workers can submit requests to add new vendors to the vendor master or extend existing vendors into additional legal entities or procurement categories. These requests are routed, via workflow, to an approver. If a request is approved, the vendor becomes a prospective vendor.

Prospective vendors are invited to complete and submit an application on the **Vendor registration** page in Enterprise Portal for Microsoft Dynamics AX. Information in the vendor profile includes company address information, contact information, other business-related information such as tax ID and DBA information, and banking details. After the vendor completes and submits the application, it is routed, via workflow, to an approver. Approvers can request additional information, if it is required. When all necessary information has been provided, the completed profile is evaluated. If it is approved, the vendor is added to the vendor master for the company.

When you define vendor request configurations, you are defining the appearance of the vendor request pages in Enterprise Portal and in other portals. Those portals include the Employee services portal, the Vendor portal, and the Unsolicited vendors portal.

**Vendor request prerequisites**

Before vendor requests can be submitted to workflow, the following configuration steps must be completed:

  - Number sequences for vendor requests must be set up in the **Procurement and sourcing parameters** form. For more information, see [Set up procurement and sourcing parameters](set-up-procurement-and-sourcing-parameters.md).

  - Workflows must be configured for new vendor add justifications and new vendor applications. For more information, see [Set up Procurement and sourcing workflows](set-up-procurement-and-sourcing-workflows.md).

  - Workflow must be configured for user requests. For more information, see [Set up Organization administration workflows](set-up-organization-administration-workflows.md).
    

    > [!IMPORTANT]
    > <P>If you do not configure workflow for user requests, the vendor request cannot move from the <STRONG>Request pending approval</STRONG> status to the <STRONG>Request pending complete</STRONG> status.</P>



  - Workflow must be enabled. For more information, see [Configuring the workflow system](configuring-the-workflow-system.md).

The following table defines the types of vendor requests that are available and the name and location of the corresponding pages in Enterprise Portal.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Request type</p></th>
<th><p>Definition</p></th>
<th><p>Page name</p></th>
<th><p>Page location</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Vendor add request</p></td>
<td><p>A request that an employee submits to add a new vendor to the vendor master for the employee’s legal entity. This request applies to vendors that are not approved to do business in any part of the organization.</p></td>
<td><p>New vendor request</p></td>
<td><p>Employee services portal</p></td>
</tr>
<tr class="even">
<td><p>Vendor add application</p></td>
<td><p>An application that a prospective vendor company submits in response to an invitation from the customer company.</p></td>
<td><p>Vendor registration page</p></td>
<td><p>Enterprise Portal</p></td>
</tr>
<tr class="odd">
<td><p>Vendor extension request</p></td>
<td><p>A request that an employee submits to add an existing vendor to one or more legal entities in the organization.</p></td>
<td><p>New extension request</p></td>
<td><p>Employee services portal</p></td>
</tr>
<tr class="even">
<td><p>Vendor extension application</p></td>
<td><p>An application that a vendor submits after the vendor is invited by the customer to expand their business opportunity with the organization.</p></td>
<td><p>Vendor registration page</p></td>
<td><p>Enterprise Portal</p>
<div class="alert">

> [!NOTE]
> <P>Although the vendor is already approved to business in a different legal entity in the organization, they are not a vendor in the legal entity that is identified in the vendor extension request. Therefore, the request does not appear in the Vendor portal. Instead, it appears in Enterprise Portal.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Vendor category request</p></td>
<td><p>A request that an employee submits to allow a vendor to do business in additional procurement categories.</p></td>
<td><p>Category request page</p></td>
<td><p>Employee services portal</p></td>
</tr>
<tr class="even">
<td><p>Vendor category confirmation</p></td>
<td><p>A confirmation that a vendor submits in response to an invitation to do business in additional procurement categories.</p></td>
<td><p>Vendor category confirmation page</p></td>
<td><p>Vendor portal</p></td>
</tr>
<tr class="odd">
<td><p>Vendor category application</p></td>
<td><p>A request that a vendor initiates to be approved for additional procurement categories.</p></td>
<td><p>Category request page</p></td>
<td><p>Vendor portal</p></td>
</tr>
<tr class="even">
<td><p>Vendor status change request</p></td>
<td><p>A request that an employee submits to change the hold status of a vendor.</p></td>
<td><p>Vendor status change request page</p></td>
<td><p>Employee services portal</p></td>
</tr>
<tr class="odd">
<td><p>Vendor profile</p></td>
<td><p>This request type defines the settings and fields that appear in the vendor profile on the Vendor portal, where active vendors can view and update their data. It is not triggered by any workflow activity.</p></td>
<td><p>Edit profile page</p></td>
<td><p>Vendor portal</p></td>
</tr>
<tr class="even">
<td><p>Unsolicited vendor registration</p></td>
<td><p>A request that a supplier in the broader marketplace submits to become a vendor for your organization.</p></td>
<td><p>Unsolicited vendor registration page</p></td>
<td><p>Unsolicited vendor portal</p></td>
</tr>
</tbody>
</table>


## See also

[Vendor request configurations (form)](https://technet.microsoft.com/library/hh209430\(v=ax.60\))

[Configuring Enterprise Portal for vendor requests](configuring-enterprise-portal-for-vendor-requests.md)

  


