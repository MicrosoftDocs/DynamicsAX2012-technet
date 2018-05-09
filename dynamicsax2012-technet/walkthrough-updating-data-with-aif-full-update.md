---
title: 'Walkthrough: Updating Data with AIF (Full Update)'
TOCTitle: 'Walkthrough: Updating Data with AIF (Full Update)'
ms:assetid: 5b6e5199-c9cf-4f7c-b11b-185ee74b50df
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Cc598792(v=AX.60)
ms:contentKeyID: 35244390
ms.date: 04/17/2013
mtps_version: v=AX.60
dev_langs:
- xml
---

# Walkthrough: Updating Data with AIF (Full Update) 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Application Integration Framework (AIF) enables you to integrate your Microsoft Dynamics AX installation with external systems. This framework supports the ability to create, read, update, and delete data.

In this walkthrough, you will update a sales order using the file system transport. This topic describes how to configure AIF in addition to how to format the update message correctly.

This walkthrough illustrates the following tasks:

  - Create the directories for the file system adapter

  - Set up the AIF components that are required for the update:
    
      - Create an inbound integration port for the Sales Order service and add the update service operation
    
      - Configure the inbound port to use the file system adapter and the directories you created

  - Configure and start the AIF batch services

  - Read the sales order

  - Update the sales order

This walkthrough demonstrates a full update. This is also known as a "document-centric" update and one in which all the data being updated is assumed to be in the message. If a field in the message matches a field in the table, the table field is updated with the message value. If there is a field in the table that is not in the message, the table field is set or cleared according to the rules for the data type of the field.

You can identify a full update in one of two ways:

1.  The presence of the update action in the message header and no other update attributes in any of the records.

2.  The presence of the update action in the message header and the top record in the submitted data contains the replace action attribute.

For more information about full and partial updates, see [Updating Data With AIF](updating-data-with-aif.md).

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX

  - A developer license file

## Set Up the AIF Components

You must do some general setup to use AIF. In the following section you create directories for inbound and outbound files, and create and configure the inbound enhanced integration port that uses the file system adapter.

You must create an inbound and an outbound directory. The inbound directory is where the XML files that come into AIF are put. The outbound directory is where XML files produced by AIF are put. When the batch jobs are started, AIF polls the inbound directory for files.

### To create and configure a directory

1.  In Windows Explorer, create an inbound and an outbound directory.

2.  Name the directories **AIFin** and **AIFout**. For more information, see [Walkthrough: Exchanging documents by using the file system adapter](walkthrough-exchanging-documents-by-using-the-file-system-adapter.md).

The integration ports associate the file system adapter with the file system directories that you just created. You must create an inbound port that uses the AIFout directory for response messages. For more information, see [Managing integration ports](managing-integration-ports.md).

### To create the inbound port

1.  Open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  Click **New**.

3.  Name the new integration port AIFUpdateTest.

### To configure the inbound port

1.  In the **Adapter** list in the **Address** group, select **File system adapter**.

2.  In the **URI** list, click the arrow to browse to the folder that you created that is named **AIFIn**.

3.  Select **Response address** and repeat steps 1 and 2. This time, in the URI list, provide the path of the folder that you created that is named AIFOut.

4.  On the **Service contract customizations** FastTab, click **Service operations**.

5.  In the **Select service operations** form, select **SalesSalesOrderService.create** and **SalesSalesOrderService.read** in the **Remaining service operations** list. Click the left arrow to move the service operations to the **Selected service operations** list.

6.  Close the form.

7.  On the **Service contract customizations** FastTab, select **Customize documents** and then click **Data policies**.

8.  In the **Document data policies** form, click **Enable all**.

9.  Close the **Document data policies** form.

10. In the **Inbound ports** form, click **Activate** to enable the port.

## Configure and Start the AIF Batch Services

For asynchronous document exchanges, such as the one demonstrated in this scenario, you must configure an AIF batch job. This batch job periodically executes business logic through integration ports that are configured to use asynchronous adapters. If you have previously configured the AIF batch services, you can skip this section. For more information, see [Walkthrough: Exchanging documents by using the file system adapter](walkthrough-exchanging-documents-by-using-the-file-system-adapter.md).

### To create the batch job

1.  Open the **Batch job** form. Click **System** **administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

2.  Create a new batch job.

3.  Add four tasks that use the following classes to the batch job: **AifGatewayReceiveService**, **AifGatewaySendService**, **AifInboundProcessingService**, and **AifOutboundProcessingService**.

4.  Set a recurrence interval for the batch job. For testing, it is convenient to set the interval to one minute.

5.  To start the batch job, change its status to **Waiting**.

## Read the Sales Order

The first step in updating a sales order is to read the sales order and return the current sales order data in the table to the client. This is necessary because the update operation uses concurrency control to determine whether the record you are trying to update has been changed in between the time the record was first read and the time the update is sent into AIF. Concurrency control is implemented by comparing a hash value or by comparing the RecId and RecVersion fields for each record being updated. For more information about concurrency, see [Concurrency When Updating Data](concurrency-when-updating-data.md).

To read the sales order, you must place a message specifying the entity key (ID) of the sales order you want to read in the inbound directory. AIF obtains this message from the inbound channel and puts a message that contains the corresponding sales order into the outbound channel.

### To read the sales order

1.  Create an XML file that contains the entity key of the sales order to be updated. The format of this message should resemble the following XML example. Notice that the \<Field\> and \<Value\> elements contain the name of the table field that contains the SalesId and the value of the SalesId. The \<Action\> element in the header is the only required header element and specifies the read action. AIF obtains the user credentials from the file itself.
    
    ``` xml
    <?xml version="1.0" encoding="utf-8"?>
    <Envelope xmlns="http://schemas.microsoft.com/dynamics/2011/
        01/documents/Message">
        <Header>
            <MessageId></MessageId>
            <Action>http://schemas.microsoft.com/dynamics/2011/
                01/services/SalesOrderService/read</Action>
            <ConversationId></ConversationId>
        </Header>
    <Body>
        <MessageParts xmlns="http://schemas.microsoft.com/dynamics/2011/
            01/documents/Message">
            <EntityKeyList xmlns="http://schemas.microsoft.com/dynamics/
            2006/02/documents/EntityKeyList">
                <EntityKey xmlns="http://schemas.microsoft.com/dynamics/
                    2006/02/documents/EntityKey">
                    <KeyData>
                        <KeyField>
                            <Field>SalesId</Field>
                            <Value>00016_036</Value>
                        </KeyField>
                    </KeyData>
                </EntityKey>
            </EntityKeyList>
        </MessageParts>
    </Body>
    </Envelope>
    ```
    

    > [!NOTE]
    > <P>This message is passed as a parameter to the SalesSalesOrderService.update service operation. Therefore, it must validate against the schema for the _&nbsp;entityKeyList parameter. For more information, see <A href="updating-data-with-aif.md">Updating Data With AIF</A>.</P>



2.  Place the message in the inbound directory. Depending on how often you configure the batch jobs to run, the services get this request message and then write the requested sales order into the outbound directory. The section Response Sales Order XML at the end of this topic provides an example of what the sales order returned by AIF resembles.

## Update the Sales Order

Now that you have read the sales order, you can make the necessary changes and send the data back to AIF to update the sales order in the table.

### To update the sales order

1.  Create an XML file that contains the sales order to be updated. The format of this message should resemble the XML in the section Update Sales Order XML at the end of this topic. The \<Action\> element in the header is the only required header element and specifies the update action. Notice that there are no RecId or RecVersion fields so this update uses the \_DocumentHash value for concurrency control.

2.  Put the message in the inbound directory. Depending on how often you configure the batch jobs to run, the services retrieve this request message and then update the sales order in Microsoft Dynamics AX.

## Response Sales Order XML

The following code is an example of what AIF returns when you request a sales order.

``` xml
<?xml version="1.0" encoding="utf-8" ?> 
<Envelope xmlns="http://schemas.microsoft.com/dynamics/2011
    01/documents/Message">
    <Header>
        <MessageId>{2002A291-8AA4-4405-BC10-383C30376F76}</MessageId>
        <Action>http://schemas.microsoft.com/dynamics/
            2008/01/services/SalesOrderService/read</Action>
        <RequestMessageId>{13A5A1E4-D248-4361-B484-791AE121C952}
            </RequestMessageId> 
    </Header>
    <Body>
        <MessageParts xmlns="http://schemas.microsoft.com/dynamics/
            2011/01/documents/Message">
            <SalesOrder xmlns="http://schemas.microsoft.com/dynamics/
                2008/01/documents/SalesOrder">
                <DocPurpose>Original</DocPurpose>
                <SenderId>DAT</SenderId>
                <SalesTable class="entity">
                    <_DocumentHash>de321661b44419fc5052246e6274f726
                        </_DocumentHash>
                    <CaseTagging>No</CaseTagging>
                    <CashDisc>14D1%</CashDisc>
                    <CommissionGroup>CCG-OTH</CommissionGroup>
                    <CovStatus>1</CovStatus>
                    <CreditCardAuthorizationError>No
                        </CreditCardAuthorizationError>
                    <CurrencyCode>EUR</CurrencyCode>
                    <CustAccount>4005</CustAccount>
                    <CustGroup>40</CustGroup>
                    <Deadline>2002-03-31</Deadline>
                    <DeliveryAddress>St. Hallvard vei 1 N-0244 
                        Oslo Norway</DeliveryAddress>
                    <DeliveryCity>Oslo</DeliveryCity>
                    <DeliveryCountryRegionId>NO
                        </DeliveryCountryRegionId
                    <DeliveryDate>2002-03-01</DeliveryDate>
                    <DeliveryDateControlType>None
                        </DeliveryDateControlType>
                    <DeliveryName>Office Supplies Inc.</DeliveryName>
                    <DeliveryStreet>St. Hallvard vei 1</DeliveryStreet>
                    <DeliveryZipCode>N-0244</DeliveryZipCode>
                    <DlvMode>UPS</DlvMode>
                    <DocumentStatus>None</DocumentStatus>
                    <EInvoiceLineSpec>No</EInvoiceLineSpec>
                    <FreightSlipType>None</FreightSlipType>
                    <GiroType>None</GiroType>
                    <InclTax>No</InclTax>
                    <InterCompanyAllowIndirectCreation>No
                        </InterCompanyAllowIndirectCreation>
                    <InterCompanyAutoCreateOrders>No
                        </InterCompanyAutoCreateOrders>
                    <InterCompanyDirectDelivery>No
                        </InterCompanyDirectDelivery>
                    <InterCompanyDirectDeliveryOrig>No
                        </InterCompanyDirectDeliveryOrig>
                    <InterCompanyOrder>No</InterCompanyOrder>
                    <InvoiceAccount>4005</InvoiceAccount>
                    <ItemTagging>No</ItemTagging>
                    <LanguageId>En-us</LanguageId>
                    <Listcode>IncludeNot</Listcode>
                    <MarkupGroup>FR10</MarkupGroup>
                    <OneTimeCustomer>No</OneTimeCustomer>
                    <PalletTagging>No</PalletTagging>
                    <Payment>M15</Payment>
                    <PaymMode>CHEQUE</PaymMode>
                    <PostingProfile>Gen</PostingProfile>
                    <PurchOrderFormNum />
                    <RecId>5637144586</RecId>
                    <RecVersion>1</RecVersion>
                    <Reservation>None</Reservation>
                    <ReturnReplacementCreated>No
                        </ReturnReplacementCreated>
                    <ReturnStatus>None</ReturnStatus>
                    <SalesGroup>CSG-OTH</SalesGroup>
                    <SalesId>00016_036</SalesId>
                    <SalesName>Office Supplies Inc.</SalesName>
                    <SalesPoolId>DEF</SalesPoolId>
                    <SalesResponsible>MPO</SalesResponsible>
                    <SalesStatus>Backorder</SalesStatus>
                    <SalesTaker>TJO</SalesTaker>
                    <SalesType>Sales</SalesType>
                    <SettleVoucher>None</SettleVoucher>
                    <ShipCarrierBlindShipment>No
                        </ShipCarrierBlindShipment>
                    <ShipCarrierDlvType>Misc</ShipCarrierDlvType>
                    <ShipCarrierExpeditedShipment>No
                        </ShipCarrierExpeditedShipment>
                    <ShipCarrierFuelSurcharge>No
                        </ShipCarrierFuelSurcharge>
                    <ShipCarrierResidential>No</ShipCarrierResidential>
                    <ShippingDateConfirmed>2002-03-01
                        </ShippingDateConfirmed>
                    <ShippingDateRequested>2002-03-01
                        </ShippingDateRequested>
                    <totalBalance>3300.00</totalBalance>
                    <TotalCashDiscount>33.00</TotalCashDiscount>
                    <TotalInvoice>3300.00</TotalInvoice>
                        <SalesLine class="entity">
                            <Blocked>No</Blocked>
                            <CaseTagging>No</CaseTagging>
                            <Complete>No</Complete>
                            <ConfirmedDlv>2002-03-01</ConfirmedDlv>
                            <CurrencyCode>EUR</CurrencyCode>
                            <CustAccount>4005</CustAccount>
                            <CustGroup>40</CustGroup>
                            <DeliveryAddress>St. Hallvard vei 1 N-0244 
                                Oslo Norway</DeliveryAddress>
                            <DeliveryCity>Oslo</DeliveryCity>
                            <DeliveryCountryRegionId>NO
                                </DeliveryCountryRegionId>
                            <DeliveryDateControlType>None
                                </DeliveryDateControlType>
                            <DeliveryName>Office Supplies Inc.
                                </DeliveryName> 
                            <DeliveryStreet>St. Hallvard vei 1
                                </DeliveryStreet>
                            <DeliveryType>None</DeliveryType>
                            <DeliveryZipCode>N-0244</DeliveryZipCode>
                            <InventDimId>00001_060</InventDimId>
                            <InventRefType>None</InventRefType>
                            <InventTransId>00065_059</InventTransId>
                            <ItemId>OL-1500</ItemId>
                            <itemReplaced>No</itemReplaced>
                            <ItemTagging>No</ItemTagging>
                            <LineAmount>3300.00</LineAmount>
                            <LineNum>1.0000000000</LineNum>
                            <Name>Office Lamp 1500 2-tubes</Name>
                            <PalletTagging>No</PalletTagging>
                            <PriceUnit>1.00</PriceUnit>
                            <ProjCategoryId>Lamps</ProjCategoryId>
                            <QtyOrdered>200.00</QtyOrdered>
                            <RecId>5637144590</RecId>
                            <RecVersion>1</RecVersion>
                            <RemainInventPhysical>200.00
                                </RemainInventPhysical>
                            <RemainSalesPhysical>200.00
                                </RemainSalesPhysical>
                            <Reservation>None</Reservation>
                            <ReturnAllowReservation>No
                                </ReturnAllowReservation>
                            <ReturnStatus>None</ReturnStatus>
                            <SalesGroup>CSG-OTH</SalesGroup>
                            <SalesId>00016_036</SalesId>
                            <SalesPrice>16.50</SalesPrice>
                            <SalesQty>200.00</SalesQty>
                            <SalesStatus>Backorder</SalesStatus>
                            <SalesType>Sales</SalesType>
                            <SalesUnit>Pcs</SalesUnit>
                            <Scrap>No</Scrap>
                            <TaxAutogenerated>Yes</TaxAutogenerated>
                            <TaxItemGroup>full</TaxItemGroup>
                            <InventDim class="entity">
                                <inventDimId>00001_060</inventDimId>
                                <InventLocationId>GW</InventLocationId>
                                <InventSiteId>S1</InventSiteId>
                                <RecId>5637144576</RecId>
                                <RecVersion>1</RecVersion>
                            </InventDim>
                        </SalesLine>
                    </SalesTable>
            </SalesOrder>
        </MessageParts>
    </Body>
</Envelope>
```

## Update Sales Order XML

The following code is an example of what the XML message should resemble when you submit data to update a sales order.

``` xml
<?xml version="1.0" encoding="utf-8"?>
<Envelope xmlns="http://schemas.microsoft.com/dynamics/
    2011/01/documents/Message">
    <Header>
        <MessageId></MessageId>
        <Action>http://schemas.microsoft.com/dynamics/
            2008/01/services/SalesOrderService/update</Action>
        <ConversationId></ConversationId>
    </Header>
    <Body>
        <MessageParts xmlns="http://schemas.microsoft.com/dynamics/
            2011/01/documents/Message">
            <EntityKeyList xmlns="http://schemas.microsoft.com/
                dynamics/2006/02/documents/EntityKeyList">
                <EntityKey xmlns="http://schemas.microsoft.com/
                    dynamics/2006/02/documents/EntityKey">
                    <KeyData>
                        <KeyField>
                            <Field>SalesId</Field>
                            <Value>00016_036</Value>
                        </KeyField>
                    </KeyData>
                </EntityKey>
            </EntityKeyList>
            <SalesOrder xmlns="http://schemas.microsoft.com/
                dynamics/2008/01/documents/SalesOrder">
                <DocPurpose>Original</DocPurpose>
                <SenderId>dat</SenderId>
                <SalesTable class="entity">
                     <_DocumentHash>820acb9d4e266e791f5069edd7bd3d39
                         </_DocumentHash> 
                     <CaseTagging>No</CaseTagging> 
                     <CashDisc>14D1%</CashDisc> 
                     <CommissionGroup>CCG-OTH</CommissionGroup> 
                     <ContactPersonId>00174_002</ContactPersonId> 
                     <CreditCardAuthorizationError>No
                         </CreditCardAuthorizationError> 
                     <CurrencyCode>EUR</CurrencyCode> 
                     <CustAccount>4005</CustAccount> 
                     <CustGroup>40</CustGroup> 
                     <Deadline>2002-03-30</Deadline> 
                     <DeliveryAddress>St. Hallvard vei 1 N-0244 
                         Oslo Norway</DeliveryAddress> 
                     <DeliveryCity>Oslo</DeliveryCity> 
                     <DeliveryCountryRegionId>NO
                         </DeliveryCountryRegionId> 
                     <DeliveryDate>2002-03-01</DeliveryDate> 
                     <DeliveryDateControlType>None
                         </DeliveryDateControlType> 
                     <DeliveryName>Office Supplies Inc.</DeliveryName> 
                     <DeliveryStreet>St. Hallvard vei 1
                         </DeliveryStreet> 
                     <DeliveryZipCode>N-0244</DeliveryZipCode> 
                     <DlvMode>UPS</DlvMode> 
                     <DocumentStatus>None</DocumentStatus> 
                     <EInvoiceLineSpec>No</EInvoiceLineSpec> 
                     <Email>test@test.test</Email> 
                     <FreightSlipType>None</FreightSlipType> 
                     <GiroType>None</GiroType>
                     <InclTax>No</InclTax>
                     <InterCompanyAllowIndirectCreation>No
                         </InterCompanyAllowIndirectCreation>
                     <InterCompanyAutoCreateOrders>No
                         </InterCompanyAutoCreateOrders>
                     <InterCompanyDirectDelivery>No
                         </InterCompanyDirectDelivery>
                     <InterCompanyDirectDeliveryOrig>No
                         </InterCompanyDirectDeliveryOrig>
                     <InterCompanyOrder>No</InterCompanyOrder>
                     <InvoiceAccount>4005</InvoiceAccount>
                     <ItemTagging>No</ItemTagging>
                     <LanguageId>En-us</LanguageId>
                     <Listcode>IncludeNot</Listcode>
                     <MarkupGroup>FR10</MarkupGroup>
                     <OneTimeCustomer>No</OneTimeCustomer>
                     <PalletTagging>No</PalletTagging>
                     <Payment>M15</Payment>
                     <PaymMode>CHEQUE</PaymMode>
                     <PostingProfile>Gen</PostingProfile>
                     <PurchOrderFormNum>00007_049</PurchOrderFormNum>
                     <Reservation>None</Reservation>
                     <ReturnReplacementCreated>No
                         </ReturnReplacementCreated>
                     <ReturnStatus>None</ReturnStatus>
                     <SalesGroup>CSG-OTH</SalesGroup>
                     <SalesId>00016_036</SalesId>
                     <SalesName>Office Supplies Inc.</SalesName>
                     <SalesPoolId>DEF</SalesPoolId>
                     <SalesResponsible>MPO</SalesResponsible>
                     <SalesStatus>Backorder</SalesStatus>
                     <SalesTaker>TJO</SalesTaker>
                     <SalesType>Sales</SalesType>
                     <SettleVoucher>None</SettleVoucher>
                     <ShipCarrierBlindShipment>No
                         </ShipCarrierBlindShipment>
                     <ShipCarrierDlvType>Misc</ShipCarrierDlvType>
                     <ShipCarrierExpeditedShipment>No
                         </ShipCarrierExpeditedShipment>
                     <ShipCarrierFuelSurcharge>No
                         </ShipCarrierFuelSurcharge>
                     <ShipCarrierResidential>No
                         </ShipCarrierResidential>
                     <ShippingDateConfirmed>2002-03-01
                         </ShippingDateConfirmed>
                     <ShippingDateRequested>2002-03-01
                         </ShippingDateRequested>
                     <totalBalance>3300.00</totalBalance>
                     <TotalCashDiscount>33.00</TotalCashDiscount>
                     <TotalInvoice>3300.00</TotalInvoice>
                     <URL>www.test.test</URL>
                     <SalesLine class="entity">
                     <Blocked>No</Blocked>
                     <CaseTagging>No</CaseTagging>
                     <Complete>No</Complete>
                     <ConfirmedDlv>2002-03-01</ConfirmedDlv>
                     <CurrencyCode>EUR</CurrencyCode>
                     <CustAccount>4005</CustAccount>
                     <CustGroup>40</CustGroup>
                     <DeliveryAddress>St. Hallvard vei 1 N-0244 
                         Oslo NO</DeliveryAddress>
                     <DeliveryCity>Oslo</DeliveryCity>
                     <DeliveryCountryRegionId>NO
                         </DeliveryCountryRegionId>
                     <DeliveryDateControlType>None
                         </DeliveryDateControlType>
                     <DeliveryName>Office Supplies Inc.</DeliveryName>
                     <DeliveryStreet>St. Hallvard vei 1
                         </DeliveryStreet>
                     <DeliveryType>None</DeliveryType>
                     <DeliveryZipCode>N-0244</DeliveryZipCode>
                     <InventDimId>00001_060</InventDimId>
                     <InventRefType>None</InventRefType>
                     <ItemId>OL-1500</ItemId>
                     <itemReplaced>No</itemReplaced>
                     <ItemTagging>No</ItemTagging>
                     <LineAmount>3300.00</LineAmount>
                     <LineNum>1.0000000000</LineNum>
                     <Name>Office Lamp 1500 2-tubes</Name>
                     <PalletTagging>No</PalletTagging>
                     <PriceUnit>1.00</PriceUnit>
                     <ProjCategoryId>Lamps</ProjCategoryId>
                     <QtyOrdered>200.00</QtyOrdered>
                     <RecId>5637144590</RecId>
                     <RecVersion>406348234</RecVersion>
                     <RemainInventPhysical>200.00
                         </RemainInventPhysical>
                     <RemainSalesPhysical>200.00</RemainSalesPhysical>
                     <Reservation>None</Reservation>
                     <ReturnAllowReservation>No
                         </ReturnAllowReservation>
                     <ReturnStatus>None</ReturnStatus>
                     <SalesGroup>CSG-OTH</SalesGroup>
                     <SalesId>00016_036</SalesId>
                     <SalesQty>200.00</SalesQty>
                     <SalesStatus>Backorder</SalesStatus>
                     <SalesType>Sales</SalesType>
                     <SalesUnit>Pcs</SalesUnit>
                     <Scrap>No</Scrap>
                     <ShipCarrierDlvType>Misc</ShipCarrierDlvType>
                     <ShippingDateConfirmed>2002-03-01
                         </ShippingDateConfirmed>
                     <ShippingDateRequested>2002-03-01
                         </ShippingDateRequested>
                     <StatTriangularDeal>No</StatTriangularDeal>
                     <TaxAutogenerated>Yes</TaxAutogenerated>
                     <TaxItemGroup>full</TaxItemGroup>
                     <InventDim class="entity">
                         <inventDimId>00001_060</inventDimId>
                         <InventLocationId>GW</InventLocationId>
                         <InventSiteId>S1</InventSiteId>
                         <RecId>5637144576</RecId>
                         <RecVersion>1</RecVersion>
                     </InventDim>
                     </SalesLine>
                </SalesTable>
            </SalesOrder>
        </MessageParts>
    </Body>
</Envelope>
```

## Next Steps

After you submit the message to update the sales order, you can check the status of the exchange in the **Queue manager** form. After AIF has processed the message, you can view it in the **History** form or troubleshoot any errors in the **Exceptions** form. For more information, see [Monitoring services and AIF](monitoring-services-and-aif.md).

## See also

[Updating Data With AIF](updating-data-with-aif.md)

[Concurrency When Updating Data](concurrency-when-updating-data.md)

