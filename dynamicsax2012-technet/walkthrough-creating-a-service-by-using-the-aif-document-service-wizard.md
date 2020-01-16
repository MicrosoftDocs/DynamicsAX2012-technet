---
title: 'Walkthrough: Creating a Service by Using the AIF Document Service Wizard'
TOCTitle: 'Walkthrough: Creating a Service by Using the AIF Document Service Wizard'
ms:assetid: 53aa8783-4a66-4687-b7dc-e7557137c71f
ms:mtpsurl: https://technet.microsoft.com/library/Cc589855(v=AX.60)
ms:contentKeyID: 35244327
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Creating a Service by Using the AIF Document Service Wizard 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This walkthrough covers how to create a document query, a new service, and a document schema when you want to create a document service that is not included with Application Integration Framework (AIF). After you have created a document service, you can use it from modules within Microsoft Dynamics AX and external applications. Document services enable you to create reusable business logic. For information about which services are included with AIF, see [Standard Document Services](standard-document-services.md).

In the following scenario, you want to send data to an external system for reporting. You may also want to receive information through AIF from an external accounting system and then create a journal entry and its associated lines. In this scenario, a journal and its entries are stored in the LedgerJournalTable and LedgerJournalTrans tables.


> [!NOTE]
> <P>In this walkthrough, you create a new service from a query that has the data source set to LedgerJournalTable and the LedgerJournalTrans tables. The general journal service is already included in AIF. Be careful when you name objects so that they do not conflict with the existing general journal service. The name of the included class is AxdLedgerGeneralJournal. The query name for the included document is also AxdLedgerGeneralJournal.</P>



The following illustration shows the relationship between the LedgerJournalTable table and the LedgerJournalTrans table (shown here with an abbreviated field list).

![Ledger Journal Tables](images/Cc589855.LedgerJournalTables(AX.60).gif "Ledger Journal Tables")

**The tables that contain journal entries.**

This walkthrough illustrates the following tasks:

  - Creating a document query

  - Creating the service

  - Generating the document schema

## Prerequisites

To complete this walkthrough, you need:

  - Microsoft Dynamics AX 2012

  - A developer license

## Creating a Document Query

You use the AIF Document Service Wizard to create a service from a document query. The first step is to create the document query. For more information about document queries, see [How to: Create a Document Query](how-to-create-a-document-query.md).

### To create a document query

1.  Press CTRL-D to open the AOT, right-click **Queries**, and then click **New Query**.

2.  Expand the node for the new query that is named something like **Query1**.

3.  In the AOT, right-click **Data Dictionary**, and then click **Open New Window**.

4.  In the second AOT window, expand the **Tables** node and drag the LedgerJournalTable table onto the **Data Sources** node under the new query in the first window. By default, all of the fields in the data source are included in the query.
    
    For more information, see [How to: Create Queries by using the AOT](https://technet.microsoft.com/library/bb314753\(v=ax.60\)).

5.  Right-click the new data source, and then click **Properties**. In the **Properties** sheet, rename the query data source name from LedgerJournalTable\_1 to LedgerJournalTable.

6.  In the first AOT window, expand the **LedgerJournalTable** node. Drag the LedgerJournalTrans table onto the LedgerJournalTable **Data Sources** node.

7.  Right-click the new query and then click **Properties**. In the **Properties** sheet, rename the query data source table from LedgerJournalTrans\_1 to LedgerJournalTrans.

8.  Set the **JoinMode** property to **OuterJoin**.

9.  Right-click **Fields** in the **LedgerJournalTable** node and then click **Properties**. Set the **Dynamic** property to **Yes**. This setting makes sure that all fields are returned and is required when a table participates in an interitance relationship.

10. In the AOT, click the new query, and then in the **Properties** sheet, set the **Name** property to AxdLedgerJournal.
    

    > [!NOTE]
    > <P>As a best practice, the query name should always be the same as the document class name. This is especially true when you use the AIF Document Service Wizard to generate the service because it sets the document name to the name of the query by default.</P>



11. In the AOT, expand the **LedgerJournalTrans** data source node, right-click **Relations**, and then select **New Relation**. By default, a relation is created between the LedgerJournalTable.JournalNum field and the LedgerJournalTrans.JournalNum field. This is because the data type for the JournalNum field is based on the LedgerJournalId extended data type which has a relation to the LedgerJournalTable.

12. Expand **LedgerJournalTrans**, right-click **Fields**, and then click **Properties**.

13. Set the **Dynamic** property to **Yes**.

14. Right click the **LedgerJournalTrans** node and then click **Properties**.

15. Set the **FetchMode** property to **1:n**.

16. Press Ctrl+Shift+S to save the **AxdLedgerJournal** query.

## Creating a Service

You use the AIF Document Service Wizard to create the service, document class, Ax \<Table\> classes, and other service related artifacts. For more information, see [How to: Create a Service by Using the AIF Document Service Wizard](how-to-create-a-service-by-using-the-aif-document-service-wizard.md).

### To create a service by using the AIF Document Service Wizard

1.  In the Developer Workspace, click **Tools** \> **Application Integration Framework** \> **Create Document Service**. The **Welcome** screen appears.

2.  Click **Next**. In the **Select document parameters** screen, in the **Query** field, select the AxdLedgerJournal query. The default setting is the document name.

3.  Click **Next**. In the **Select code generation parameters** screen, the **Class names** default setting is based on the AxdLedgerJournal query selected.

4.  Select the **Read** and **Create** service operations that the service will expose. The AxdLedgerJournal class must support reading a single journal and its entries and creating a single journal and its entries. For more information, see [Document Class Service Operations](document-class-service-operations.md).

5.  Click **Next**. In the **Generate code** screen, you can review the artifacts that will be generated, and then click **Generate**.

6.  The **Completed** screen displays the artifacts that the wizard created. Click **Finish**.

## Generating a Document Schema

The document schema, or XSD, defines the structure and format of the XML that is serialized or deserialized by the document class. In AIF, the schema for each document is generated by iterating through the query associated with the document class. The document schema defines the XML rules for the document. For more information, see [Document Schema Rules](document-schema-rules.md).

When you use the AIF Document Service Wizard to create a service, it automatically creates an X++ job that you can run to generate the document schema. Use the following steps to generate the document schema for the service.

### To generate the document schema for the service

1.  Press Ctrl+Shift+P to open the **Projects** form.

2.  Expand the **Private** node, and then double-click the AxdLedgerJournal project. This project contains all of the objects created by the AIF Document Service Wizard that are related to the new service.

3.  Double-click the GenerateXSDSchema\_AxdLedgerJournal job to open it in the code editor.

4.  Press F5 to run the job. You will not see any message indicating the job has completed.

When you run this job, it creates a file that contains the schema for all of the fields in the document. The file location is c:\\XSDSchema\_AxdLedgerJournal.xml. Now that the service has been generated, your scenario may require that you [add custom business logic code](guidelines-for-adding-code-to-document-service-classes.md) to the document service classes. For simplicity, we will consider this service implementation completed.

## Next Steps

You can now use the document service you have created in an inbound or an outbound exchange. For more information about how to configure and code an outbound exchange using the file adapter, see [Walkthrough: Deploying the Document Service in an Outbound Exchange](walkthrough-deploying-the-document-service-in-an-outbound-exchange.md)

When using an inbound adapter-based exchange such as file system transfer or Message Queuing, you must run the AIF batch services so that the message is transferred to the gateway queue. The message is then transferred from the gateway queue, deserialized into an AxdLedgerJournal class, and then saved to the database by using the Ax \<Table\> classes. For more information about how to configure the AIF batch services for an inbound exchange, see [Configuring batch jobs and tasks for AIF](configuring-batch-jobs-and-tasks-for-aif.md) and [Walkthrough: Exchanging documents by using the file system adapter](walkthrough-exchanging-documents-by-using-the-file-system-adapter.md).

## See also

[How to: Create a Document Query](how-to-create-a-document-query.md)

[How to: Create a Service by Using the AIF Document Service Wizard](how-to-create-a-service-by-using-the-aif-document-service-wizard.md)

