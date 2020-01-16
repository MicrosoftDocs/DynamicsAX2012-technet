---
title: Example of Inbound XML Message
TOCTitle: Example of Inbound XML Message
ms:assetid: c1aed2aa-b605-4185-9d13-b6379781fa3d
ms:mtpsurl: https://technet.microsoft.com/library/Bb530212(v=AX.60)
ms:contentKeyID: 35250096
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
dev_langs:
- html
---

# Example of Inbound XML Message 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To create ledger journal entries in Application Integration Framework (AIF), the data is sent in the form of an XML message. This message is received by the inbound port in Microsoft Dynamics AX and is deserialized into a class. For example, an inbound message specifying the create service operation on the LedgerJournalService is used to create an instance of the AxdLedgerJournal class. The inbound message contains the data to be created: the parent ledger journal record and one or more child ledger journal transaction records. The format of the data varies depending on the business requirements for journal transactions.

## Validating the XML

The inbound XML is validated against the XSD for the document class by the framework. For more information about document class schemas, see [Document Schema Rules](document-schema-rules.md) and [How to: Generate a Document Schema](how-to-generate-a-document-schema.md).

The XML must also validate against the schema for the inbound port for the action that is called. Invalid messages are indicated in the [exception logs](monitoring-services-and-aif.md). In this case the action is create and this is implemented in the document class method createLedgerJournal. This schema varies depending on the fields that are enabled on the port for the document. To view this schema, follow these steps.

### To view the schema

1.  Open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  Select the inbound port and then click **Deactivate** to enable access to the configuration options.

3.  On the **Service contract customizations** FastTab, click **Data policies** to open the **Data policies** form. For more information, see [Customize service contracts](customize-service-contracts.md).

4.  Select the **LedgerJournal** document, and then click **View schema**. Save the schema for the **LedgerJournal** document.
    
    Click **View imported schemas** and then save the shared-types schema to the same folder.

5.  To view sample XML for the schema, open the LedgerJournal schema with Visual Studio. In the **Schema Explorer**, right-click on the root node and then click **Generate Sample XML**.

## The Inbound Message Format

The inbound XML message in the AxdLedgerJournal scenario should resemble the following XML code. Notice how the whole message is wrapped in an envelope and contains header information about the message unique identifier and the action that the document service performs. The body of the message contains the ledger journal record and a ledger journal transaction record that you generated. For more information about messages, see [AIF Messages](aif-messages.md).

You can create the inbound message by using Notepad to add the tags for the message header and body. Add the message header information between the \<Header\> and \</Header\> tags. The only required tag is the \<Action\> tag. It is a best practice to include a Message ID. For more information about the values of the tags in the message header, see [Message Header](message-header.md).

The message body contains the XML generated from the document schema. The following example shows the inbound message XML with a message header and body.

``` html
<?xml version="1.0" encoding="utf-8" ?> 
<Envelope xmlns = "https://schemas.microsoft.com/dynamics/2008/01/
    documents/Message">
    <Header>
        <MessageId>{5603D03A-4380-404D-9F27-738BE0FEA13E}</MessageId>
        <Action>http://tempuri.org/LedgerJournalService/create</Action>
    </Header>
    <Body>
        <MessageParts xmlns = "https://schemas.microsoft.com/dynamics/2008/01/
        documents/Message">
        <LedgerJournal xmlns = "https://schemas.microsoft.com/dynamics/2008/01/
        documents/LedgerJournal">
        <LedgerJournalTable class="entity">
            <CurrencyCode>USD</CurrencyCode>
            <JournalName>Day1</JournalName>
            <JournalTotalCredit>50</JournalTotalCredit>
            <JournalTotalDebit>50</JournalTotalDebit>
            <JournalType>Daily</JournalType>
            <Name>Daily Journal 1</Name>
            <VoucherSeries>Ledger_3</VoucherSeries>
        <LedgerJournalTrans class="entity">        
            <AccountType>Ledger</AccountType>
            <AmountCurDebit>50</AmountCurDebit>
            <CurrencyCode>USD</CurrencyCode>
            <DocumentDate>2007-05-28</DocumentDate>
            <Invoice>00003</Invoice>
            <OffsetAccount>12020</OffsetAccount>
            <OffsetAccountType>Ledger</OffsetAccountType>
            <TransDate>2007-05-28</TransDate>
            <Txt>AxLedgerJournal inbound test trans 1</Txt>
        </LedgerJournalTrans>      
        </LedgerJournalTable>  
        </LedgerJournal>
        </MessageParts>
    </Body>
</Envelope>
```

For another example of an inbound XML message, see [Walkthrough: Exchanging documents by using the file system adapter](walkthrough-exchanging-documents-by-using-the-file-system-adapter.md).

## See also

[Walkthrough: Creating a Service by Using the AIF Document Service Wizard](walkthrough-creating-a-service-by-using-the-aif-document-service-wizard.md)

[Messages and transforms in AIF](messages-and-transforms-in-aif.md)

