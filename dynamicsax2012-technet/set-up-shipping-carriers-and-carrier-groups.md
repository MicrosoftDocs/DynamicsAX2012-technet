---
title: Set up shipping carriers and carrier groups
TOCTitle: Set up shipping carriers and carrier groups
ms:assetid: 2b1174c1-8b0c-45b0-b27e-e4cfffc256b8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn553155(v=AX.60)
ms:contentKeyID: 62200048
ms.date: 11/13/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.TMSCarrier
- Forms.TMSCarrierGroup
- MsDynAx060.Forms.TMSCarrier
- MsDynAx060.Forms.TMSCarrierGroup
- carrier group
- carrier rate
- carrier service
- rate shopping
- route plan
- mode of shipment
- shipping carrier
- transportation tender
audience: Application User
ms.search.region: Global
---

# Set up shipping carriers and carrier groups 


_**Applies To:** Microsoft Dynamics AX 2012 R3_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up a shipping carrier and define details such as service, shipment mode, transportation tender, transportation constraints, and shipping rate. A transportation coordinator can then assign a shipping carrier to an inbound or outbound load based on one of the following criteria:

  - Least expensive carrier rate

  - Rate shopping

  - Route plan

  - Mode of shipment

  - Transportation tender

You can group shipping carriers by using a specific carrier service as a carrier group, and then set up a sequence in which the carrier group will be rated.

## Set up a shipping carrier

Use the **Shipping carrier** form to set up a carrier service, mode of shipment, transportation tender, and rating profile for the shipping carrier.

1.  Click **Transportation management** \> **Setup** \> **General** \> **Shipping carrier**.

2.  Click **New** to create a new shipping carrier.

3.  On the **Overview** FastTab, specify the shipping carrier details by using the fields described in the following table.
    
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
    <td><p><strong>Shipping carrier</strong></p></td>
    <td><p>Enter a unique identifier (ID) for the shipping carrier.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Use carrier</strong></p></td>
    <td><p>Select this check box to use the specified shipping carrier for shipment.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Mode</strong></p></td>
    <td><p>Select the ID for the shipment mode.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Vendor</strong></p></td>
    <td><p>Select the vendor account to which you want to assign the shipping carrier.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>SCAC</strong></p></td>
    <td><p>Enter an ID for the Standard Carrier Alpha Code (SCAC).</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Activate carrier rating</strong></p></td>
    <td><p>Select this check box to enable automatic rating for the shipping carrier.</p></td>
    </tr>
    </tbody>
    </table>


4.  Optional: In the **Transportation tenders** field, select one of the following methods for updating the details of transportation tender:
    
      - **Manual** – Manually update the transportation tender details by using the **Transportation tenders** form.
    
      - **EDI** – Automatically update the transportation tender details by using an Electronic Data Interchange (EDI) in the **Transportation tenders** form.

5.  Optional: In the **Pro number sequence** field, select a number sequence that is associated with a generic engine. For more information, see [Set up transportation management engines](set-up-transportation-management-engines.md).
    

    > [!NOTE]
    > <P>To configure number sequences, use the <STRONG>Number sequence</STRONG> window. Click <STRONG>Transportation management</STRONG> &gt; <STRONG>Setup</STRONG> &gt; <STRONG>General</STRONG> &gt; <STRONG>Number sequence</STRONG>.</P>



6.  On the **Service** FastTab, click **New**. Enter the carrier service details by using the fields described in the following table.
    
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
    <td><p><strong>Carrier service</strong></p></td>
    <td><p>Enter a unique ID for the carrier service.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Transportation method</strong></p></td>
    <td><p>Select the ID for the transportation method.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>External code</strong></p></td>
    <td><p>Enter an external code for the shipping carrier.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Billing group ID</strong></p></td>
    <td><p>Select the ID for the billing group.</p></td>
    </tr>
    </tbody>
    </table>


7.  Optional: In the **Load template ID** field, select the ID for the load template.

8.  On the **Address** FastTab, click **New**, and then enter the address and purpose of the shipping carrier.

9.  On the **Rating profile** FastTab, click **New**. Set up the details of the rating profile, such as rate engine, rate master, transit time engine, and carrier fuel index. Or more information, see [Set up a rating profile](set-up-a-rating-profile.md).

10. Click **Carrier fuel index**. Set up the fuel surcharges for the shipping carrier based on the transaction time, price per gallon (PPG), and currency of the country/region. For more information, see [Set up accessorial charges for a shipping carrier](set-up-accessorial-charges-for-a-shipping-carrier.md).

11. Click **Carrier accessorial charges**. Set up the accessorial charges for the shipping carrier.

12. Optional: Click **Accessorial assignments**. Configure other accessorial charges and define the criteria and rating calculations for the shipping carrier.

13. Click **Constraints**. Set up any restrictions or individual settings for the specified item, shipping carrier, or shipment.
    

    > [!NOTE]
    > <P>If you are running Microsoft Dynamics AX 2012 R3 Cumulative Update 8, constraints for the shipping carrier are specified only through the items and shipments.</P>



14. Click **Rate master**. Set up a rate base for the shipping carrier. For more information, see [Set up rate masters](set-up-rate-masters.md).

15. Click **Transit time engine**. Set up the transit time for the shipping carrier. For more information, see [Set up transportation management engines](set-up-transportation-management-engines.md).

## Set up a carrier group

Use the **Carrier group** form to group the shipping carriers with their corresponding shipping services.

1.  Click **Transportation management** \> **Setup** \> **General** \> **Carrier group**.

2.  Click **New**. In the **Carrier group** field, enter an ID for the carrier group.

3.  On the **Details** FastTab, click **New**, and then select the IDs for the shipping carrier and the carrier service.

4.  In the **Preference sequence** field, enter a sequence number for the shipping carrier. This number will be used for rating the carrier group.

## Next step

After you set up the shipping group and the carrier group, you can continue with setting up a route for the shipment. For more information, see [Set up a route plan and routing guide for freight transportation](set-up-a-route-plan-and-routing-guide-for-freight-transportation.md).

## Related tasks

[Set up a route plan and routing guide for freight transportation](set-up-a-route-plan-and-routing-guide-for-freight-transportation.md)

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

  


