---
title: Document XML Generation
TOCTitle: Document XML Generation
ms:assetid: b0a11426-9ad7-46fa-8159-0a8b81df2264
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa856184(v=AX.60)
ms:contentKeyID: 35249736
ms.date: 11/26/2012
mtps_version: v=AX.60
dev_langs:
- xml
---

# Document XML Generation [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R2.</P>



This document describes how Application Integration Framework (AIF) serializes data into XML. In Microsoft Dynamics AX, data is exchanged using documents, and each document is represented by a document service class. When a document is exchanged, the XML data is contained in an envelope with a header that includes the message delivery information. The actual data is contained in the \<Body\> tags of the message.

When a document is serialized into XML, a table element is created for each table in the query. The table is denoted by the class="entity" attribute and value. Each table element contains a list of fields that is derived from all the properties of the corresponding internal Ax \<Table\> class for which a parm \<Field\> get/set method exists. Within each table element is a series of child table elements that represent the child data sources as defined in the query.

When the customer document is serialized into XML, it resembles the following XML which is the result of calling the read method on the CustCustomerService document service class. Blank fields in the table are not returned.

``` 
  <?xml version="1.0" encoding="UTF-8" ?> 
- <Envelope xmlns="http://schemas.microsoft.com/dynamics/2011/01/documents/Message">
- <Header>
   <MessageId>{93FE7B5F-99E6-45D6-BAA5-654699EFF0EA}</MessageId> 
   <Action>http://schemas.microsoft.com/dynamics/2008/01/services/CustomerService/read</Action> 
   <RequestMessageId>{E983D78F-0011-47B7-8716-F8B64D120EF6}</RequestMessageId> 
  </Header>
- <Body>
  - <MessageParts xmlns="http://schemas.microsoft.com/dynamics/2011/01/documents/Message">
  - <Customer xmlns="http://schemas.microsoft.com/dynamics/2008/01/documents/Customer">
      <DocPurpose>Original</DocPurpose> 
      <SenderId>DMO</SenderId> 
      <ValidAsOfDateTime>2012-04-19T19:42:40Z</ValidAsOfDateTime> 
      <ValidTimeStateType>AsOf</ValidTimeStateType> 
    - <CustTable class="entity">
        <_DocumentHash>261dcc95694f19ee9010b1866237b4a2</_DocumentHash> 
        <AccountNum>4503</AccountNum> 
        <AccountStatement>Always</AccountStatement> 
        <Blocked>No</Blocked> 
        <CashDisc>14D1%</CashDisc> 
        <CompanyType_MX>Blank</CompanyType_MX> 
        <CreditCardAddressVerification>None</CreditCardAddressVerification> 
        <CreditCardAddressVerificationLevel>Accept</CreditCardAddressVerificationLevel> 
        <CreditCardAddressVerificationVoid>No</CreditCardAddressVerificationVoid> 
        <CreditCardCVC>None</CreditCardCVC> 
        <Currency>USD</Currency> 
        <CustExcludeCollectionFee>No</CustExcludeCollectionFee> 
        <CustExcludeInterestCharges>No</CustExcludeInterestCharges> 
        <CustFinalUser_BR>No</CustFinalUser_BR> 
        <CustGroup>60</CustGroup> 
        <EInvoice>No</EInvoice> 
        <ExportSales_PL>No</ExportSales_PL> 
        <FedNonFedIndicator>None</FedNonFedIndicator> 
        <FiscalDocType_PL>Invoice</FiscalDocType_PL> 
        <ForecastDMPInclude>No</ForecastDMPInclude> 
        <ForeignResident_RU>No</ForeignResident_RU> 
        <GenerateIncomingFiscalDocument_BR>No</GenerateIncomingFiscalDocument_BR> 
        <GiroType>None</GiroType> 
        <GiroTypeAccountStatement>None</GiroTypeAccountStatement> 
        <GiroTypeCollectionletter>None</GiroTypeCollectionletter> 
        <GiroTypeFreeTextInvoice>None</GiroTypeFreeTextInvoice> 
        <GiroTypeInterestNote>None</GiroTypeInterestNote> 
        <GiroTypeProjInvoice>None</GiroTypeProjInvoice> 
        <ICMSContributor_BR>No</ICMSContributor_BR> 
        <InclTax>No</InclTax> 
        <InterCompanyAllowIndirectCreation>No</InterCompanyAllowIndirectCreation> 
        <InterCompanyAutoCreateOrders>No</InterCompanyAutoCreateOrders> 
        <InterCompanyDirectDelivery>No</InterCompanyDirectDelivery> 
        <InventProfileType_RU>NotSpecified</InventProfileType_RU> 
        <InvoiceAddress>InvoiceAccount</InvoiceAddress> 
        <InvoicePostingType_RU>Standard</InvoicePostingType_RU> 
        <IRS1099CIndicator>No</IRS1099CIndicator> 
        <MandatoryCreditLimit>No</MandatoryCreditLimit> 
        <MandatoryVatDate_PL>No</MandatoryVatDate_PL> 
        <OneTimeCustomer>No</OneTimeCustomer> 
        <PackageDepositExcempt_PL>No</PackageDepositExcempt_PL> 
        <Party>1310</Party> 
        <PaymTermId>D14</PaymTermId> 
        <PdsFreightAccrued>No</PdsFreightAccrued> 
        <RecId>5637144600</RecId> 
        <RecVersion>1</RecVersion> 
        <RFIDCaseTagging>No</RFIDCaseTagging> 
        <RFIDItemTagging>No</RFIDItemTagging> 
        <RFIDPalletTagging>No</RFIDPalletTagging> 
        <ServiceCodeOnDlvAddress_BR>No</ServiceCodeOnDlvAddress_BR> 
        <ShipCarrierBlindShipment>Yes</ShipCarrierBlindShipment> 
        <ShipCarrierFuelSurcharge>No</ShipCarrierFuelSurcharge> 
        <Suframa_BR>No</Suframa_BR> 
        <SuframaPISCOFINS_BR>No</SuframaPISCOFINS_BR> 
        <SyncEntityId>{00000000-0000-0000-0000-000000000000}</SyncEntityId> 
        <TaxWithholdCalculate_IN>No</TaxWithholdCalculate_IN> 
        <TaxWithholdCalculate_TH>No</TaxWithholdCalculate_TH> 
        <UnitedVATInvoice_LT>No</UnitedVATInvoice_LT> 
        <UseCashDisc>Normal</UseCashDisc> 
        <UsePurchRequest>No</UsePurchRequest> 
        <WebSalesOrderDisplay>WebEntered</WebSalesOrderDisplay> 
      - <DirParty xsi:type="AxdEntity_DirParty_DirOrganization" class="entity" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
          <LanguageId>En-us</LanguageId> 
           <Name>3 Company</Name> 
           <NameAlias>3</NameAlias> 
           <PartyNumber>1310</PartyNumber> 
           <RecId>5637145091</RecId> 
           <RecVersion>1</RecVersion> 
         - <DirPartyPostalAddressView class="entity">
             <Address>522 West 5th Street New York, NY 10032 US</Address> 
             <City>New York</City> 
             <CountryRegionId>US</CountryRegionId> 
             <County>New York</County> 
             <IsLocationOwner>Yes</IsLocationOwner> 
             <ISOcode>US</ISOcode> 
             <IsPrimary>Yes</IsPrimary> 
             <IsPrivate>No</IsPrivate> 
             <Location>5637146387</Location> 
             <Party>1310</Party> 
             <PartyLocation>5637145688</PartyLocation> 
             <RecId>5637145688</RecId> 
             <Roles>Invoice;Primary postal address</Roles> 
             <State>NY</State> 
             <Street>522 West 5th Street</Street> 
             <TimeZone xsi:nil="true" /> 
             <ValidFrom>2009-07-09T00:43:51Z</ValidFrom> 
             <ValidTo>2154-12-31T23:59:59Z</ValidTo> 
             <ZipCode>10032</ZipCode> 
             </DirPartyPostalAddressView>
             <ABC>None</ABC> 
           - <OrganizationName class="entity">
               <Name>3 Company</Name> 
               <RecId>5637144581</RecId> 
               <RecVersion>1</RecVersion> 
               <ValidFrom>2009-06-13T00:17:00Z</ValidFrom> 
               <ValidTo>2154-12-31T23:59:59Z</ValidTo> 
             </OrganizationName>
           </DirParty>
         </CustTable>
       </Customer>
     </MessageParts>
    </Body>
  </Envelope>
```

## Serialization Strategy

The serialization from Microsoft Dynamics AX to XML is as follows:

  - The parm \<Field\> methods on the Axd \<Document\> class are serialized to add the sending company and the document purpose (original or copy) properties. These properties are stored at the document level and are not returned from the query.

  - Empty data is not serialized so table fields that have no values are excluded from the XML.

  - When the Axd \<Document\> class serializes data (generates XML from the database), the Ax \<Table\> classes are used to read data. If there are no Ax \<Table\> classes present, data is read directly from the tables.

  - When the Axd \<Document\> class deserializes XML (writes the data to the database), Ax \<Table\> classes are used to validate data, ensure referential integrity of data, set default fields, and ensure the business logic compliance of the inbound data.

  - The field list from the Axd \<Document\> query controls the fields that are included in the serialized XML. However, if the Ax \<Table\>class is present, only fields that have a corresponding parm \<Field\> method on the Ax \<Table\> class are serialized. Calculated fields (display fields) are always serialized.


> [!NOTE]
> <P>In Microsoft Dynamics AX 2012 R2, AIF includes support for optional replacement fields for a surrogate foreign key that has multiple replacement fields.&nbsp;In other words, a replacement field is optional if the referring surrogate foreign key field is specified as non-mandatory on the table.</P>
> <P>In previous versions of Microsoft Dynamics AX, AIF considered all surrogate foreign key replacement fields as mandatory.&nbsp; For outbound transfers, this meant that previous versions of Dynamics AX serialized each field when sending Axd documents. Therefore, in external clients written to use outbound document services in previous versions of Microsoft Dynamics AX, fields that were previously mandatory are now optional, and may be missing from the XML message.</P>



## Data Serialization

When a document class serializes data into XML, the field data types are dependent on the primitive data type of the fields in Microsoft Dynamics AX.

### String

The String field is serialized unchanged except for characters that are used as markup delimiters. These are converted to the corresponding XML entities as shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Source character</p></th>
<th><p>Output entity</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>&lt;</p></td>
<td><p>&amp;lt;</p></td>
</tr>
<tr class="even">
<td><p>&gt;</p></td>
<td><p>&amp;gt;</p></td>
</tr>
<tr class="odd">
<td><p>&amp;</p></td>
<td><p>&amp;amp;</p></td>
</tr>
<tr class="even">
<td><p>'</p></td>
<td><p>&amp;apos;</p></td>
</tr>
<tr class="odd">
<td><p>&quot;</p></td>
<td><p>&amp;quot;</p></td>
</tr>
</tbody>
</table>


### Integer

The Integer field value is converted to a string and serialized. If the field is based on an extended data type that derives from timeOfDay, createdTime, or modifiedTime, the field represents a time value and is serialized using the rules described for DateTime.

### Int64

The Int64 field value is converted to a string and serialized.

### Real

The Real field value is converted to a string and serialized based on the following rules:

  - Minimum length of 1

  - Decimal separator is a period

  - No thousands separator

  - Number of decimals defaults to 2

### Date

The Date field value is converted to a string and serialized based on the following rules:

  - Format is YYYY-MM-DD

  - Day always contains 2 digits

  - Month always contains 2 digits

  - Year, month, and day are separated by a hyphen

### DateTime

  - The DateTime field value is converted to a string and serialized based on the following rules:

  - Format is HH:MM:SS

  - Hours, minutes, and seconds are separated by a colon

  - Time is represented by 24 hours

### Enum

The Enum field values are converted to a string that contains the Name property of the corresponding enum value. For example, if the query returns a field based on the NoYes enum and the value of the field is "1," then the resulting XML element will contain "Yes."

``` xml
<TaxJournalTrans class="entity">
    <EUROTriangulation>Yes</EUROTriangulation> 
</TaxJournalTrans>
```

### GUID

The GUID field value is converted to a string and serialized.

### Container

When a container is serialized to XML, the field values are serialized based on their data types as described earlier. Container values are not serialized if they are one of the following types:

  - Record

  - Class

  - UserType

  - AnyType

#### Rstring and VarString

The Rstring and VarString field values are serialized unchanged except for characters that are used as markup delimiters. These are converted to the corresponding XML entities, as shown in the following table.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Source character</p></th>
<th><p>Output entity</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>&lt;</p></td>
<td><p>&amp;lt;</p></td>
</tr>
<tr class="even">
<td><p>&gt;</p></td>
<td><p>&amp;gt;</p></td>
</tr>
<tr class="odd">
<td><p>&amp;</p></td>
<td><p>&amp;amp;</p></td>
</tr>
<tr class="even">
<td><p>'</p></td>
<td><p>&amp;apos;</p></td>
</tr>
<tr class="odd">
<td><p>&quot;</p></td>
<td><p>&amp;quot;</p></td>
</tr>
</tbody>
</table>


#### BLOB

A BLOB field value is serialized as a stream of Base64 encoded binary data.

## See also

[Document Schemas](document-schemas.md)

[Document Schema Rules](document-schema-rules.md)

[How to: Generate a Document Schema](how-to-generate-a-document-schema.md)

[Messages and transforms in AIF](messages-and-transforms-in-aif.md)

