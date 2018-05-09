---
title: 'How to: Bypass Record Level Security in Outbound Documents'
TOCTitle: 'How to: Bypass Record Level Security in Outbound Documents'
ms:assetid: 4265fdc5-5c9d-4afb-8df4-13261e37ddcd
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa627307(v=AX.60)
ms:contentKeyID: 35242952
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Bypass Record Level Security in Outbound Documents 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

By default, record level security (RLS) is enabled for outbound documents. It may be necessary to bypass RLS in a document when the omission of data renders the document invalid, for example, in the sales invoice document. In this case, RLS is bypassed to create a valid document. The following standard documents bypass RLS by default when sent from Microsoft Dynamics AX:

  - Sales Invoice - AxdSalesInvoice

  - Advance Ship Notice - AxdASN

  - Purchase Requisition - AxdPurchaseRequisition

It is not possible to bypass RLS for all documents at the same time. Each outbound document exchange must be manually adjusted to bypass RLS for only that document. The following steps describe how RLS is bypassed in standard documents in Microsoft Dynamics AX. Use these guidelines to bypass RLS for your own documents.

## Send Electronically Method

Sending of documents can be initiated within Microsoft Dynamics AX either automatically or manually. A document is sent automatically when a posting occurs and AIF has been configured to send the posted information.

A document is sent manually through the **Send electronically** button. Typically, the **Send electronically** button calls the sendElectronically method on the base table. For more information about how to code a document to be sent manually, see [Walkthrough: Deploying the Document Service in an Outbound Exchange](walkthrough-deploying-the-document-service-in-an-outbound-exchange.md).

## Property Bag

A property bag is a collection of parameters that is sent by the table's sendElectronically method to AIF in the [AxdSendContext Class](https://technet.microsoft.com/en-us/library/gg804228\(v=ax.60\)). A property bag is passed unchanged from AIF to the Axd \<Document\> class that creates the outbound document.

A property bag is used for storing a series of properties that are relevant to the outbound document, such as if the document is an original or a copy. A property bag is also used to contain parameters. One of these parameters is used to determine whether RLS is bypassed; other parameters contain additional information that is pertinent at the time the document is sent.

The property that controls whether to bypass RLS is packed into a property bag, sent with the document, and then sent to the Axd \<Document\> class. The contents of the property bag are then unpacked and processed by the document class in the unpackPropertyBag method. For more information about security in Axd \<Document\> classes, see [Security in Axd\<Document\> and Ax\<Table\> Classes](security-in-axd-document-and-ax-table-classes.md).

## Bypass RLS for Outbound Documents

The following procedures explain how RLS is bypassed in the standard documents. Use these procedures to bypass RLS in your own documents.

### Bypass RLS in an Electronic Document

1.  In the AOT, navigate to the table associated with the document and open the sendElectronically method.

2.  Change the line of code axdSendContext.parmSecurity(true) to axdSendContext.parmSecurity(false). This directs AIF not to use RLS for the document.

3.  Save and compile the method.

The following table displays the tables that contain the sendElectronically method for the standard documents that bypass RLS.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Document</p></th>
<th><p>Class</p></th>
<th><p>Table</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Advance Ship Notice</p></td>
<td><p>AxdASN</p></td>
<td><p>CustPackingSlipJour</p></td>
</tr>
<tr class="even">
<td><p>Purchase Requisition</p></td>
<td><p>AxdPurchaseRequisition</p></td>
<td><p>VendPurchOrderJour</p></td>
</tr>
<tr class="odd">
<td><p>Sales Invoice</p></td>
<td><p>AxdSalesInvoice</p></td>
<td><p>CustInvoiceJour</p></td>
</tr>
</tbody>
</table>


## Use the Send Framework

The send framework is used when the recipient of a document cannot be determined from the context of the document. As a result, the sendElectronically method is neither created nor used on the main table that is associated with the document query.

When the send framework is used, the sendDocument or sendMultipleDocuments method is called from the Main method on the AxdSend \<Document\> class. The RLS settings must be edited in the Main method. The [AxdSendContext Class](https://technet.microsoft.com/en-us/library/gg804228\(v=ax.60\)) is passed as an argument to the sendDocument or sendMultipleDocuments methods.

Some documents that use the send framework require the [AxdSendContext Class](https://technet.microsoft.com/en-us/library/gg804228\(v=ax.60\)) to bypass RLS while others do not. The following table shows outbound documents that utilize the send framework.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Document</p></th>
<th><p>Document class</p></th>
<th><p><a href="https://technet.microsoft.com/en-us/library/gg804228(v=ax.60)">AxdSendContext Class</a> is called</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Price List</p></td>
<td><p>AxdSendPriceList</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Chart of Accounts</p></td>
<td><p>AxdSendChartofAccounts</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>Dimensions</p></td>
<td><p>AxdSendDimension</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>Exchange Rates</p></td>
<td><p>AxdSendExchangeRates</p></td>
<td><p>No</p></td>
</tr>
</tbody>
</table>


## Bypass RLS When AxdSendContext is Called

Use the following steps to bypass RLS if the send framework is already called with the AxdSendContext class or a class derived from it.

### To bypass RLS when AxdSendContext is called

1.  Open the Main method in the relevant AxdSend\<Document\> class.

2.  Add the line of code AxdSendContext.parmSecurity(false); before calling the sendDocument method or the sendMultipleDocuments method.

3.  Save and compile the method.

## Bypass RLS When AxdSendContext is Not Called

Use the following steps to bypass RLS if the send framework is called without the AxdSendContext class or a class derived from it.

### To bypass RLS when AxdSendContext is not called

1.  Open the Main method in the relevant AxdSend \<Document\> class.

2.  Create an AxdSendContext object in the AxdSend \<Document\> class.

3.  Add the line of code AxdSendContext.parmSecurity(false); before calling the sendDocument method or the sendMultipleDocuments method.

4.  Add the axdSendContext class as the last parameter to the sendDocument method or the sendMultipleDocuments method.

5.  Save and compile the method.


#### Example from AxdSendExchangeRates.Main

The following code shows you how to bypass RLS in the AxdSendExchangeRates class.

Static public void main (Args args)

{

AxdSendExchangeRates axdSendExchangeRates ;

AifConstraintList aifConstraintList;

AifConstraint aifConstraint;

;

axdSendExchangeRates = new AxdSendExchangeRates();

aifConstraintList = new AifConstraintList();

aifConstraint = new AifConstraint();

// The AxdSendContext object is created.

axdSendContext axdSendContext = new AxdSendContext() ;

aifConstraint.parmType(AifConstraintType::NoConstraint);

aifConstraintList.addConstraint(aifConstraint);

axdSendExchangeRates.parmShowDocPurpose(true) ;

axdSendExchangeRates.parmShowQuery(true);

// Call to axdSendContext class to bypass RLS

// before calling the sendMultipleDocuments method.

axdSendContext.parmSecurity(false);

axdSendExchangeRates.sendMultipleDocuments(

classnum axdExchangeRates),

AifSendMode::Async, aifConstraintList, axdSendContext);

}

## See also

[Record Level Security and Outbound Documents](record-level-security-and-outbound-documents.md)

[AxdSendContext Class](https://technet.microsoft.com/en-us/library/gg804228\(v=ax.60\))

