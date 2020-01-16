---
title: 'Example: Read Action'
TOCTitle: 'Example: Read Action'
ms:assetid: 7ef4a0ee-9263-484d-9f0a-09b09cecab13
ms:mtpsurl: https://technet.microsoft.com/library/Aa642551(v=AX.60)
ms:contentKeyID: 35246128
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- xml
---

# Example: Read Action 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes sample inbound and outbound messages for the read action in Application Integration Framework (AIF) document services. The read action retrieves records that have specific entity key values that you specify in the inbound message. All of the fields are returned for the selected records.

The service specified in the \<Action\> tag determines the \<entityName\> tag name that is used for each returned record in the outbound message. In this example, the \<entityName\> tag that is used is \<CustTable class=”entity”\>.

## Inbound Read Message Sample

The following inbound read message specifies one \<EntityKey\> tag. Therefore, at most one record can be returned in the outbound message from the target table. Records from child tables are also returned in the outbound message.

There are no XML tags that are specific to this inbound message. However, the value for the \<Field\> tag is specific to this message, and it must be compatible with the service that is listed in the \<Action\> tag. In other words, the \<Field\> tag must contain the string for a valid field in the target table referenced by the query used by the document service.

The read action in the following message requests that the customer record with the AccountNum value of 4507 be returned by AIF. Line breaks have been added to improve readability.

``` xml
<?xml version="1.0" encoding="utf-8"?>
<Envelope xmlns = "http://schemas.microsoft.com/
 dynamics/2011/01/documents/Message">

 <Header>
  <MessageId>{E983D78F-0011-47B7-8716-F8B64D120EF6}</MessageId>
  <Action>http://schemas.microsoft.com/dynamics/
   2008/01/services/CustomerService/read</Action>
 </Header>

 <Body>
  <MessageParts xmlns = "http://schemas.microsoft.com/
   dynamics/2011/01/documents/Message">
   <EntityKeyList xmlns = "http://schemas.microsoft.com/
    dynamics/2006/02/documents/EntityKeyList">
    <EntityKey xmlns = "http://schemas.microsoft.com/
     dynamics/2006/02/documents/EntityKey">
     <KeyData>
      <KeyField>
       <Field>AccountNum</Field>
       <Value>4507</Value>
      </KeyField>
     </KeyData>
    </EntityKey>
   </EntityKeyList>
  </MessageParts>
 </Body>
</Envelope>
```

## Corresponding Outbound Message

In an outbound message, the read action signifies that the read method on the document service class was called. The \<Body\> of this outbound message contains the data of the record being returned. The \<AccountNum\> value matches the \<Value\> value for the \<KeyField\> from the inbound message.

The \<DirParty\> tag indicates subsequent tags that contain information about the customer. This includes the postal address. For more information about the DirParty class and the global address book (GAB) framework, see [Global Address Framework](https://technet.microsoft.com/library/hh608233\(v=ax.60\)).

The following outbound message is generated from the previous inbound message.

``` xml
  <?xml version="1.0" encoding="UTF-8" ?> 
  <Envelope xmlns="http://schemas.microsoft.com/dynamics/2011/01/documents/Message">
  <Header>
   <MessageId>{93FE7B5F-99E6-45D6-BAA5-654699EFF0EA}</MessageId> 
   <Action>http://schemas.microsoft.com/dynamics/2008/01/services/CustomerService/read</Action> 
   <RequestMessageId>{E983D78F-0011-47B7-8716-F8B64D120EF6}</RequestMessageId> 
  </Header>
  <Body>
    <MessageParts xmlns="http://schemas.microsoft.com/dynamics/2011/01/documents/Message">
    <Customer xmlns="http://schemas.microsoft.com/dynamics/2008/01/documents/Customer">
      <DocPurpose>Original</DocPurpose> 
      <SenderId>DMO</SenderId> 
      <ValidAsOfDateTime>2012-04-19T19:42:40Z</ValidAsOfDateTime> 
      <ValidTimeStateType>AsOf</ValidTimeStateType> 
      <CustTable class="entity">
        <_DocumentHash>261dcc95694f19ee9010b1866237b4a2</_DocumentHash> 
        <AccountNum>4507</AccountNum> 
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
        <DirParty xsi:type="AxdEntity_DirParty_DirOrganization" class="entity" xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance">
          <LanguageId>En-us</LanguageId> 
           <Name>3 Company</Name> 
           <NameAlias>3</NameAlias> 
           <PartyNumber>1310</PartyNumber> 
           <RecId>5637145091</RecId> 
           <RecVersion>1</RecVersion> 
           <DirPartyPostalAddressView class="entity">
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
             <OrganizationName class="entity">
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
  </Envelope
```

## See also

[Document Class Service Operations](document-class-service-operations.md)

[AIF Messages](aif-messages.md)

[Message Header](message-header.md)

[Message Body](message-body.md)

