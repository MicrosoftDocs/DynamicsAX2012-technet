---
title: Set up a transportation tender
TOCTitle: Set up a transportation tender
ms:assetid: 6f7edf8d-b8a3-4c2e-906a-43f3d953d21d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553168(v=AX.60)
ms:contentKeyID: 62200089
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TMSTransportationTender
- transportation tender
- tender
- tenders
- transportation tenders
---

# Set up a transportation tender [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Transportation management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



A transportation tender is a shipping document that has an assignment for a load, a route, or part of a route. You can use this document to keep track of the dates and rates that are approved between the customer and a shipping carrier.

## Set up a transportation tender

You can create a transportation tender from a route, a route segment, or from a load on a route segment. You can also create and update these documents in the **Transportation tenders** form. The following steps describe how to complete the setup in the **Transportation tenders** form. For an overview of additional setup options, see the “Create or update transportation tenders from a route, route segment, or load” section later in this topic.

To set up a transportation tender, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Transportation tenders**.

2.  In the **Filter by** field, select one of the following options to indicate the type of assignment that is requested.
    
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
    <td><p><strong>Load</strong></p></td>
    <td><p>The pickup of a specific load.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Route</strong></p></td>
    <td><p>A load to be transported using a route.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Route segment</strong></p></td>
    <td><p>A load to be transported using part of a route.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Route segment for a load</strong></p></td>
    <td><p>A specific load to be transported using part of a route.</p></td>
    </tr>
    </tbody>
    </table>


3.  Click **New** to create a new transportation tender. The tender document automatically displays an ID in the **Transportation order** field.

4.  In the **Reference ID** field, select a unique ID for the load. The loads are filtered according to your selection in the **Filter by** field.

5.  On the **General** tab, in the **Shipping carrier** field, select the shipping carrier that should pick up the load.

6.  In the **Carrier service** field, select a service that is offered by the carrier.

7.  Enter the remaining information in the **Shipping** field group.

8.  In the **Rates** field group, enter the date and rate request for the carrier. The **Requested pickup date and time** and the **Requested rates** fields are for the customer request. If the carrier wants to update the information before confirmation, this information must be entered in the **Confirmed pickup date and time** and the **Confirmed rates** fields. You can view the exchange of information between the customer and the carrier on the **History** FastTab.

## Update a transportation tender

To update a transportation tender, follow these steps:

1.  Click **Transportation management** \> **Inquiries** \> **Transportation tenders**.

2.  Click **Update**, and then select one of the following options.
    
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
    <td><p><strong>Submit</strong></p></td>
    <td><p>The customer sends or communicates the agreement to the shipping carrier.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Confirm</strong></p></td>
    <td><p>The shipping carrier either confirms the agreement without changes or updates the <strong>Confirmed pickup date and time</strong> and the <strong>Confirmed rates</strong> fields with new information.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Deny</strong></p></td>
    <td><p>If the customer cannot accept the updated information, the document is sent back to the shipping carrier.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Accept</strong></p></td>
    <td><p>When the customer agrees with the information, the document can be accepted.</p></td>
    </tr>
    </tbody>
    </table>


## Create or update transportation tenders from a route, route segment, or load

To create or update transportation tenders from a route, route segment, or load, follow these steps:

1.  To create or update the type of assignment in a transportation tender, open one of the following forms.
    
      - To create a transportation tender from a route - Click **Transportation management** \> **Inquiries** \> **Routes**. Click **Create transportation tender**.
    
      - To create a transportation tender from a route segment - Click **Transportation management** \> **Inquiries** \> **Routes**. Select a segment on the **Segment** tab, and then click **Create transportation tender**.
    
      - To create a transportation tender from a load - Click **Transportation management** \> **Common** \> **Loads** \> **All loads**. On the **Action pane**, select the **Transportation** tab and, in the **Transportation tenders** group, click **Create transportation tender**.

2.  Create or update the transportation tender.

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

