---
title: 'Walkthrough: Reading a Customer by Using the File System Adapter'
TOCTitle: 'Walkthrough: Reading a Customer by Using the File System Adapter'
ms:assetid: 8ddda9b4-58a9-4811-bdf6-15e3f6a9c55e
ms:mtpsurl: https://technet.microsoft.com/library/JJ710376(v=AX.60)
ms:contentKeyID: 49384268
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Walkthrough: Reading a Customer by Using the File System Adapter 


_**Applies To:** Microsoft Dynamics AX 2012 R2_

The customer document service is one of the standard document services included with Microsoft Dynamics AX. It enables external systems to read, create, update, and delete customers in the Microsoft Dynamics AX database. This walkthrough illustrates reading a customer by using an enhanced integration port to pass Application Integration Framework (AIF) messages by using the file system adapter.

The customer document is defined by using XML that is included in the body of an AIF message. The AIF message also includes a header that specifies the service operation and the optional call context parameters. The read request passes in an entity key that uniquely identifies a customer in Microsoft Dynamics AX. The XML that is returned from a read request for the customer document service shows the data and structure of the AxdCustomer query. In the AOT, you can view the **AxdCustomer** query that underlies the customer document service.


> [!NOTE]
> <P>You can use the method illustrated in this walkthrough to pass a read request message for any document service included with Microsoft Dynamics AX. The data returned in the body of the XML response message shows the structure of the data returned by the Axd query for the document.</P>



This walkthrough includes the following tasks:

  - Creating an XML file that contains the read request and optional parameters to specify partition and company.

  - Creating the file system directories for the message files.

  - Creating and configuring an enhanced inbound integration port.

  - Creating the AIF batch jobs that initiate the transfer.

  - Viewing the output XML file that contains the message returned from Microsoft Dynamics AX.

  - Monitoring and troubleshooting the transfer.

## Prerequisites

To complete this walkthrough, you need the following prerequisites:

  - Microsoft Dynamics AX must be installed with a developer license.

  - A valid customer record must exist in your Microsoft Dynamics AX implementation.

  - The customer service must be registered. For information about how to register services, see [Customize service contracts](customize-service-contracts.md).

## Creating the XML Message for a Read Request

### To create the XML for a customer read request

1.  In a Microsoft Dynamics AX client, note the customer account number for a valid customer account number in your installation.

2.  Copy the following XML into an empty Notepad document.
    
        <?xml version="1.0" encoding="utf-8"?>
        <Envelope xmlns = "https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
         <Header>
          <MessageId>{2983D78F-0011-47B7-8716-F8B64D120EF6}</MessageId>
          <Action>https://schemas.microsoft.com/dynamics/2008/01/services/CustomerService/read</Action>
         </Header>
         <Body>
          <MessageParts >
           <EntityKeyList xmlns = "https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKeyList">
            <EntityKey xmlns = "https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey">
             <KeyData>
              <KeyField>
               <Field>AccountNum</Field>
               <Value>VALID-CUSTOMER-ACCOUNT-NUMBER</Value>
              </KeyField>
             </KeyData>
            </EntityKey>
           </EntityKeyList>
          </MessageParts>
         </Body>
        </Envelope>

3.  Replace the text VALID-CUSTOMER-ACCOUNT-NUMBER with a valid customer account number from step 1.

4.  The XML code includes an optional element titled \<MessageId\>, which contains a GUID that uniquely identifies the message. You can use the GUID to track and debug the message. If you do not provide a GUID, AIF generates one.

## Example XML for Customer Read Request That Specifies Partition and Company

The following example illustrates a read request for the customer who has entity key (AccountNum) of 4503.

    <?xml version="1.0" encoding="utf-8"?>
    <Envelope xmlns = "https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
     <Header>
      <MessageId>{2983D78F-0011-47B7-8716-F8B64D120EF6}</MessageId>
      <Action>https://schemas.microsoft.com/dynamics/2008/01/services/CustomerService/read</Action>
       <PartitionKey>MyPartition</PartitionKey>
       <Company>MyCompany</Company>
     </Header>
     <Body>
      <MessageParts >
       <EntityKeyList xmlns = "https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKeyList">
        <EntityKey xmlns = "https://schemas.microsoft.com/dynamics/2006/02/documents/EntityKey">
         <KeyData>
          <KeyField>
           <Field>AccountNum</Field>
           <Value>4503</Value>
          </KeyField>
         </KeyData>
        </EntityKey>
       </EntityKeyList>
      </MessageParts>
     </Body>
    </Envelope>


> [!NOTE]
> <P>The PartitionKey and the Company have been specified in the message header as an illustration. Replace the text MyPartition and MyCompany with valid values for your installation. If you do not specify these optional parameters, AIF uses the default partition and the company for the calling user. For more information about tags you can use in the message header, see <A href="message-header.md">Message Header</A>.</P>



## Creating the File System Directories for the Message Files

AIF reads and writes XML files from folders that you specify on **the Inbound ports** form. First, you must create the folders on the system.

### To create the file system directories

1.  Create a folder to hold the source XML document for the request. Name the folder AifIn.

2.  Make a copy of the XML message file that you created and move it into the folder AifIn. This file is deleted after it is read by AIF.

3.  Create a folder to receive the response XML document from AIF. Name the folder AifOut.


> [!IMPORTANT]
> <P>The account that the AOS is running under must have read and write permissions to the AifIn and AifOut folders.</P>



## Creating and Configuring the Enhanced Inbound Integration Port

To send the service request and receive the response, you must create and configure a new inbound integration port to use the file system adapter. This port is the endpoint for the asynchronous exchange of XML files.

### To create a new enhanced inbound integration port

1.  Open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  Click **New**.

3.  Name the new integration port TestCustRead.

### To select and configure the file system adapter and its addresses

1.  In the **Adapter** list in the **Address** group, select **File system adapter**.

2.  In the **URI** list, click the arrow to browse to the folder that you created that is named AifIn.

3.  Select the **Response address** check box and repeat steps 1 and 2. This time, in the **URI** list, provide the path of the folder that you created that is named AifOut.

### To select the service operation

1.  On the **Service contract customizations** FastTab, click **Service operations**.

2.  In the **Select service operations** form, select **CustCustomerService.read** in the **Remaining service operations** list. Click the left arrow to move the service operation to the **Selected service operations** list.

3.  Close the **Select service operations** form.

### To set the options for troubleshooting

1.  On the **Troubleshooting** FastTab, select **Original document** in the **Logging mode** list. You can then view these copies by using the **History** form.

2.  Select **Include exceptions in fault** to specify that X++ and the .NET Framework error messages from the service are included in fault messages.

3.  Select **Respond after error in asynchronous request** to specify that the port automatically sends error messages as responses.

## Configuring Optional Restrictions on Port Access

To restrict your read requests to a particular company or partition, set the following options on the **Security** FastTab.

  - **Restrict to partition:** – By default, the integration port processes all documents, regardless of the partition key that is specified in the document's XML. To limit the use of the integration port to a specific partition, select the partition. For each partition, the list shows the partition key and name.
    

    > [!NOTE]
    > <P>This control is available only if Microsoft Dynamics AX 2012 R2 is installed.</P>



  - **Restrict to company** – By default, the integration port processes all documents, regardless of the company ID that is specified in the document's XML. To limit the use of the integration port to a specific company, select the name of the company.
    
    In Microsoft Dynamics AX 2012 R2, you must select a partition before you can select a company.

## Activating the port

### To enable the port

1.  On the **Inbound** ports form, click **Activate**. This process may take several minutes.

2.  Close the form.

## Configuring and Starting the AIF Batch Job Tasks

To send the service request and receive the response, you must create, configure, and start the AIF batch tasks in a batch job.

### To create and configure the AIF batch job

1.  Open the **Batch job** form. Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

2.  Click **New** to create a new batch job.

3.  Enter a name for the new job.

4.  Click **View tasks** and add tasks that use the following four classes to the job on the **Batch tasks** form.
    
      - **AifGatewayReceiveService**
    
      - **AifGatewaySendService**
    
      - **AifInboundProcessingService**
    
      - **AifOutboundProcessingService**

5.  Click **Recurrence** and set a recurrence interval for the batch job on the **Recurrence** form. For testing, it is convenient to set the interval to one minute.

6.  Set the recurrence to **No end date**. You control the operation of the batch job by setting its status.

### To start and stop the AIF batch job

1.  On the **Batch jobs** form, click **Function** and then click **View status**.

2.  To start the batch job, set the status to **Waiting**.

3.  To stop the batch job, set the status to **Withhold**.

## Viewing the Output XML Message

When AIF reads the input XML message that contains the read request, it deletes the file from the AifIn folder. After AIF has processed the request, it writes a response XML file to the AifOut folder.

### To view the output XML message

1.  Watch the AifOut folder. After several minutes, AIF saves a response file to this folder.

2.  Open the file to view the customer record for the AccountNum you requested. The following example output file illustrates a typical customer record.

The following example shows an XML response file for a customer read request:

``` 
  <?xml version="1.0" encoding="UTF-8" ?> 
- <Envelope xmlns="https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
- <Header>
   <MessageId>{93FE7B5F-99E6-45D6-BAA5-654699EFF0EA}</MessageId> 
   <Action>https://schemas.microsoft.com/dynamics/2008/01/services/CustomerService/read</Action> 
   <RequestMessageId>{E983D78F-0011-47B7-8716-F8B64D120EF6}</RequestMessageId> 
  </Header>
- <Body>
  - <MessageParts xmlns="https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
  - <Customer xmlns="https://schemas.microsoft.com/dynamics/2008/01/documents/Customer">
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

## Monitoring and Troubleshooting the Transfer

If your input XML file does not disappear from the AifIn folder, or if the output XML file does not appear in the AifOut folder, an exception may have occurred. You can view information about exceptions by viewing the exception log. You may be able to view information about the message history on the **History** form.

The following list includes some other troubleshooting information:

  - Directories that are accessed by the file system adapter must grant appropriate access to the domain account under which the AOS runs. If the AOS runs under the NETWORK SERVICE account, you must grant permissions for that specific account. For example, granting full permissions to **Everyone** does not enable the file system adapter to access the files if the AOS runs under the NETWORK SERVICE account.
    

    > [!IMPORTANT]
    > <P>We strongly recommend that you use a domain account or a managed service account in a production environment. Use the Network Service account only in development and testing environments. For more information, see <A href="create-service-accounts.md">Create service accounts</A>.</P>



  - Each part of the XML request file is validated against the appropriate schema. The schemas are installed on the server tier of your Microsoft Dynamics AX installation. For more information, see [Messages and transforms in AIF](messages-and-transforms-in-aif.md).

  - For more information about how to troubleshoot, see [Troubleshoot services and AIF](troubleshoot-services-and-aif.md).

### To view the exception log

1.  Open the **Exceptions** form. Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **Exceptions**.

2.  On the **Overview** tab, select an exception record.

3.  **General** tab to view additional details about the exception.

4.  Click **Exception help** to see more information about the exception, if more information is available.

### To view the message history

1.  Click **System administration** \> **Inquiries** \> **Services and Application Integration Framework** \> **History**.

2.  In the **Display by** field, filter the display by selecting **Message**.

3.  Observe the following information about the message: the port, service operation, message ID, company accounts ID, and date and time that the message was created.

## Next Steps

You can use the output XML file as a template if you want to update a record. For more information, see [Updating Data With AIF](updating-data-with-aif.md) and [Document Class Service Operations](document-class-service-operations.md).

