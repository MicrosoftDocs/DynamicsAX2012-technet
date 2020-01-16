---
title: Example of Outbound XML Message
TOCTitle: Example of Outbound XML Message
ms:assetid: ab56d274-e0d1-4d6d-8365-4114395b7059
ms:mtpsurl: https://technet.microsoft.com/library/Bb530211(v=AX.60)
ms:contentKeyID: 35249616
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- xml
---

# Example of Outbound XML Message 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

When Application Integration Framework (AIF) sends a document out of Microsoft Dynamics AX, the result can be an XML message that is transferred by using the outbound integration port. For example, when you use the file system adapter on an outbound integration port to send an AxdLedgerJournal document, the system creates an XML file in the outbound directory that you created. Depending on the fields that you have enabled for the document on the outbound port, the final XML message could resemble the following example.

``` xml
<?xml version="1.0" encoding="UTF-8" ?> 
<Envelope xmlns="http://schemas.microsoft.com/dynamics/2011/01/
    documents/Message">
    <Header>
        <MessageId>{55240EEC-0057-4B82-A144-89F107A26F80}</MessageId> 
        <Action>http://schemas.microsoft.com/dynamics/2008/01/services/LedgerJournalService/read</Action> 
        <RequestMessageId>{7947E0F8-B07D-4344-8632-571C46129A54}<RequestMessageId /> 
    </Header>
    <Body>
        <MessageParts xmlns="http://schemas.microsoft.com/dynamics/2011/01/documents/Message">
        <LedgerJournal xmlns="http://schemas.microsoft.com/dynamics/2008/01/documents/LedgerJournal">
            <DocPurpose>Original</DocPurpose>
            <SenderId>DAT</SenderId>
            <LedgerJournalTable class="entity">
              <_DocumentHash>d4753aeeff82274cfc769cf8124b4d5a</_DocumentHash>
               <RecId>5637144633</RecId>
               <RecVersion>1</RecVersion>
                <Name>Day1</Name> 
                <JournalNum>000043_003</JournalNum> 
                <JournalType>Daily</JournalType> 
                <LedgerJournalTrans class="entity">
                     <AccountType>Ledger</AccountType> 
                </LedgerJournalTrans>
            </LedgerJournalTable>
        </LedgerJournal>
    </Body>
</Envelope>
```

## See also

[Walkthrough: Deploying the Document Service in an Outbound Exchange](walkthrough-deploying-the-document-service-in-an-outbound-exchange.md)

[Managing integration ports](managing-integration-ports.md)

[Configure processing options](configure-processing-options.md)

