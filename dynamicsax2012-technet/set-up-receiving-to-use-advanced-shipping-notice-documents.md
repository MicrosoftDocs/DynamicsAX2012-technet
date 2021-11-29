---
title: Set up receiving to use advanced shipping notice documents
TOCTitle: Set up receiving to use advanced shipping notice documents
ms:assetid: ff78e074-f6bc-4012-9ca8-ba738951fa8e
ms:mtpsurl: https://technet.microsoft.com/library/Dn553217(v=AX.60)
ms:contentKeyID: 62200197
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up receiving to use advanced shipping notice documents 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic applies to features in the <STRONG>Warehouse management</STRONG> module. It does not apply to features in the <A href="inventory-management.md">Inventory management</A> module.</P>



This topic describes how to set up Microsoft Dynamics AX 2012 so that you can automatically receive and import an advanced shipping notice (ASN) from your vendors. An ASN is a document in which a sender can provide information about a delivery. Typically, the information includes order details, product descriptions, packing structure, and carrier information. In **Warehouse management**, you can use the information in an ASN to streamline the receiving process. For example, you can capture some or all of the information in the ASN, and generate the put-away work and instructions by scanning the license plate when you receive it.

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
<td><p>Endpoints and data action policies</p></td>
<td><p>You must set up endpoint services and data action policies for ASNs in the Microsoft Dynamics AX Application Integration Framework (AIF) to automatically receive and import the ASN to create the load and the associated packing structure.</p></td>
</tr>
</tbody>
</table>


## Ensure that you can transform the file from the sender into the required format

To automate the receiving process by using an ASN, you must be able to import the information into Microsoft Dynamics AX. Typically, ASNs are provided in an XML format. However, other file formats are also used. Work with your supplier to determine the file format that they can provide, and then determine how to transform it into the XML format that Microsoft Dynamics AX requires. For example, the structure of the XML file can differ depending on the information that you want to capture. You can use an XSLT file to transform the XML file into the format that is required by Microsoft Dynamics AX.

The following example shows a structure for an XML file that can be imported through the AIF.

    <?xml version="1.0" encoding="UTF-8"?>
    <Envelope xmlns="https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
      <Header>
        <Action>http://tempuri.org/WHSShipmentASNService/create</Action>
        <Company>CEU</Company>
      </Header>
      <Body>
        <MessageParts xmlns="https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
          <WHSShipmentASN xmlns="https://schemas.microsoft.com/dynamics/2008/01/documents/WHSShipmentASN">
            <WHSShipmentTable class="entity">
              <ShipmentId>CEU-SHP000411-TST001</ShipmentId>
              <WHSUOMStructure class="entity">
                <LicensePlateId>ASN.TSTLP001</LicensePlateId>
                <Module>Purch</Module>
                <WHSASNItem class="entity">
                  <ItemId>000147_202</ItemId>
                  <PurchId>000411</PurchId>
                  <Qty>1</Qty>
                  <UOM>ea</UOM>
                  <InventDim class="entity">
                     <InventBatchId /> 
                     <InventSerialId /> 
                  </InventDim>
                </WHSASNItem>
              </WHSUOMStructure>
              <DirPartyPostalAddressView class="entity">
                <City/>
                <CountryRegionId/>
                <State/>
                <Street/>
                <ZipCode/>
              </DirPartyPostalAddressView>
            </WHSShipmentTable>
          </WHSShipmentASN>
        </MessageParts>
      </Body>
    </Envelope>

## Set up the AIF to automatically import inbound advanced shipping notices

To import ASNs on a schedule, you must configure an inbound integration port and a batch job. You use the AIF import process to import an ASN, which can either create a load for the inbound items or use an existing load. The packing structure of the inbound load is also created automatically.

There is one requirement for the inbound port that is specific to receiving an inbound ASN. You must expose the **WHSShipmentASNService.create** service operation. For an example of how to set up an inbound integration port, see [Walkthrough: Configuring an inbound integration port for Office Excel import](walkthrough-configuring-an-inbound-integration-port-for-office-excel-import.md).

## Set up warehouse management parameters for inbound advanced shipping notices

To set up warehouse management parameters for ASNs, follow these steps:

1.  Click **Warehouse management** \> **Setup** \> **Warehouse management parameters**.

2.  On the **General** tab, on the **Receiving exceptions** FastTab, in the **Code for missing items from ASN** field, select the work exception to use if an item that is listed in the ASN is missing from the load.

3.  To automatically generate the inbound load when a purchase order line is created or updated, on the **Automatically create at purchase order entry** tab, select the **Automatically create at purchase order entry** check box.

## Provide the supplier with the purchase order number

You must create a purchase order and provide your supplier with the purchase order information so that they can include the number in the ASN. If the ASN has been imported, you can then use the license plate ID that is listed in the ASN to receive the shipment and assign it to the purchase order. The load details and the associated packing structure are updated automatically.

## Set up a mobile device for license plate receiving

You can create a mobile device menu item that enables a worker to scan a license plate to receive an order based on the information in an advanced shipping notice. For more information, see Configure mobile devices for warehouse work.

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

  


