---
title: Sales Order Document Service
TOCTitle: Sales Order Document Service
ms:assetid: 753b1a89-0689-48a5-8eb8-484b56c7d18b
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc967401(v=AX.60)
ms:contentKeyID: 35245957
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Sales Order Document Service [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Microsoft Dynamics AX sales order service enables external systems to read, create, update, and delete sales orders. You can configure the sales order service on an inbound or an outbound port to expose the following service operations:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service Operation</p></th>
<th><p>Input</p></th>
<th><p>Entity Key Returned</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>create</p></td>
<td><p>Values in the AxdSalesOrder object</p></td>
<td><p>Value for SalesTable.SalesID</p></td>
</tr>
<tr class="even">
<td><p>delete</p></td>
<td><p>Value for SalesTable.SalesID</p></td>
<td><p>Nothing is returned.</p></td>
</tr>
<tr class="odd">
<td><p>find</p></td>
<td><p>Values for the AifQueryCriteria object</p></td>
<td><p>AxdSalesOrder document object</p></td>
</tr>
<tr class="even">
<td><p>findKeys</p></td>
<td><p>Values in the AifQueryCriteria object</p></td>
<td><p>Value for SalesTable.SalesID</p></td>
</tr>
<tr class="odd">
<td><p>read</p></td>
<td><p>Value for SalesTable.SalesID</p></td>
<td><p>AxdSalesOrder document object</p></td>
</tr>
<tr class="even">
<td><p>update</p></td>
<td><p>Value for SalesTable.SalesID</p></td>
<td><p>Nothing is returned.</p></td>
</tr>
<tr class="odd">
<td><p>getKeys</p></td>
<td><p>Values in the AifDocumentPaging object</p></td>
<td><p>Value for SalesTable.SalesID</p></td>
</tr>
<tr class="even">
<td><p>getChangedKeys</p></td>
<td><p>Values in the AifDocumentPaging object</p></td>
<td><p>Value for SalesTable.SalesID</p></td>
</tr>
</tbody>
</table>


For more information about document service operations, see [Document Class Service Operations](document-class-service-operations.md).

## AIF Parameter Settings

You configure Application Integration Framework (AIF) parameter settings for the sales order service and the related free text invoice and picking list services on the **Accounts receivable parameters** form. To view this form, click **Accounts receivable** \> **Setup** \> **Parameters** and then click **AIF**.

The following sections describe the AIF parameter settings for sales order documents.

### Sales Order - Order Type

Select the default location (journal or sales order) of inbound sales order documents.

### Sales Order - Calculate Multiline Discount

Select this check box to calculate and apply the multiline discount for sales orders when creating or updating sales orders by using an AIF service.

### Sales Order - Calculate Total Discount

Select this check box to calculate and apply the total discount for sales orders when creating or updating sales orders by using an AIF service.

### Parameter Settings for Receiving Notes

Only documents of type **Note** can be included with sales orders.

The setting for the type of document is global for all integration ports. To set document management parameters for an organization, click **Organization administration** \> **Setup** \> **Document management** \> **Document management parameters** and then click **AIF**.

The following sections describe the AIF parameter settings for inbound documents, including sales order documents.

#### General – Document Type

Select the document type for notes in incoming electronic documents. For sales orders, this type must be **Note**.


> [!NOTE]
> <P>The information in this field is maintained in the <STRONG>Document types</STRONG> form. For more information, see <A href="about-print-management-document-types-and-modules.md">About print management document types and modules</A>.</P>



#### Document file service – Submit document files to workflow

Select this check box if the web service document files should be submitted to workflow for routing to appropriate parties.

## Related Classes

The following objects are associated with the sales order service.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Object</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Service class</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg841238(v=ax.60)">SalesSalesOrderService Class</a></p></td>
</tr>
<tr class="even">
<td><p>External service name</p></td>
<td><p>SalesOrderService</p></td>
</tr>
<tr class="odd">
<td><p>Axd &lt;Document&gt; class</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg837236(v=ax.60)">AxdSalesOrder Class</a></p></td>
</tr>
<tr class="even">
<td><p>Ax &lt;Table&gt; classes</p></td>
<td><p><a href="https://technet.microsoft.com/en-us/library/gg919878(v=ax.60)">AxSalesTable Class</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/gg903928(v=ax.60)">AxSalesLine Class</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/gg846010(v=ax.60)">AxInventDim Class</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/gg836142(v=ax.60)">AxDocuRef Class</a></p>
<p><a href="https://technet.microsoft.com/en-us/library/gg887599(v=ax.60)">AxMarkupTrans Class</a></p></td>
</tr>
<tr class="odd">
<td><p>Query</p></td>
<td><p>AxdSalesOrder</p></td>
</tr>
</tbody>
</table>


## Restrictions

If you call the create method and try to create a sales order with the same SalesTable.CustAccount and SalesTable.PurchOrderFormNum values as another sales order, a new sales order is automatically created that has an order type (field SalesTable.SalesType) of Journal.

### Document Limitations

Only inbound sales orders of type Sales Order and Journal are valid. The sales order document structure does not support the following types of sales orders:

  - Returned items

  - Item requirements

  - Subscription orders

  - Blanket orders

  - Project orders

## Document Data Sources

### Note Field Handling

The following relations between the DocuRef table and other tables must be respected when you integrate sales order documents.

#### Adding Notes to the Inbound Sales Order Header

DocuRef.RefRecId = SalesTable.RecId

DocuRef.RefTableId = SalesTable.TableId

DocuRef.RefCompanyID = SalesTable.DataAreaId

DocuRef.Restriction = "Internal"

CustFormLetterDocuments.DocuOnPurchOrder = "Header" or "All"

Only notes of type Note are valid on inbound sales order documents. If the sales order document contains notes of any other type, then the value in the **Document management parameters** form is used.

#### Adding Notes to the Inbound Sales Order Lines

DocuRef.RefRecId = SalesLine.RecId

DocuRef.RefTableId = SalesLine.TableId

DocuRef.RefCompanyID = SalesLine.DataAreaId

DocuRef.TypeId = CustFormLetterDocuments.DocuTypePackingSlip

DocuRef.Restriction = "Internal"

CustFormLetterDocuments.DocuOnPurchOrder = "Lines" or "All"

Only notes of type **Note** are valid on inbound sales order documents. If the sales order document contains notes of any other type, then the value in the **Document management parameters** form is used.

### Required Fields

For a sales order document to be a valid business document, the following fields must contain a valid value. Validation of the required fields is performed by the business logic in the Ax \<Table\> classes.

  - SalesTable.CustAccount

  - SalesTable.DeliveryDate (defaults to today's date)
    

    > [!NOTE]
    > <P>If the delivery date control configuration key (SalesDeliveryDateControl) is enabled, then you must set the value for SalesTable.ReceiptDateRequested instead of SalesTable.DeliveryDate. For more information about the delivery date control configuration key, see <A href="delivery-date-control-configuration-key-salesdeliverydatecontrol.md">Delivery date control configuration key (SalesDeliveryDateControl)</A>.</P>



  - SalesTable.PurchOrderFormNum

  - Item line (there must be at least one item line)
    
      - SalesLine.ItemId
    
      - SalesLine.QtyOrdered
    
      - SalesLine.SalesUnit

The MarkupTrans.MarkupCode field is mandatory if miscellaneous changes are added to the sales order.

## Security Settings

The sales order document supports role-based security as implemented by AIF. For more information, see [About role-based security in services and AIF](about-role-based-security-in-services-and-aif.md).

### Sales Order ID

The sales order ID follows the same restrictions and rules that apply for manually created sales orders. Typically, the sales order ID should not be supplied in the inbound XML document. However, AIF can accept a sales order ID directly from an XML document if the sales order number sequence in Microsoft Dynamics AX is set up to accept manual sales order ID entries.

If the sales order number sequence is set up to use a default number sequence and an inbound XML document contains a sales order ID value, the entire document will be rejected.

## See also

[Standard Document Services](standard-document-services.md)

