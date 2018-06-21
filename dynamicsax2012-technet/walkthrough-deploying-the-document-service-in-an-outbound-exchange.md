---
title: 'Walkthrough: Deploying the Document Service in an Outbound Exchange'
TOCTitle: 'Walkthrough: Deploying the Document Service in an Outbound Exchange'
ms:assetid: 5f807796-8b0e-4903-a803-91c46eb3295c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh696875(v=AX.60)
ms:contentKeyID: 42517319
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Deploying the Document Service in an Outbound Exchange [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This walkthrough illustrates the following tasks:

  - Set up Application Integration Framework (AIF) components for an outbound exchange.

  - Code the outbound exchange.

  - Test the outbound exchange.

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX 2012

  - A developer license

  - The AxdLedgerJournal document service created in [Walkthrough: Creating a Service by Using the AIF Document Service Wizard](walkthrough-creating-a-service-by-using-the-aif-document-service-wizard.md).

## Setting Up Components for an Outbound Exchange

You create and configure an outbound integration port to deploy a document in an outbound exchange. In the following section you will create directories for inbound and outbound files, and create and configure an outbound enhanced integration port that uses the [file system adapter](adapters.md).

You must first create an outbound directory. Microsoft Dynamics AX puts the XML files that it creates in the outbound directory.

### To create and configure a directory

1.  In Windows Explorer, create an outbound directory.
    

    > [!IMPORTANT]
    > <P>Directories that are accessed by the file system adapter must grant appropriate access to the domain account under which the AOS runs. If the AOS runs under the NETWORK SERVICE account, you must grant permissions for that specific account. For example, granting full permissions to Everyone does not enable the file system adapter to access the files in the directory or network share accessed by the file system adapter if the AOS runs under the NETWORK SERVICE account.</P>
    > <P>We strongly recommend that you use a domain account or a managed service account in a production environment. Use the Network Service account only in development and testing environments. For more information, see <A href="create-service-accounts.md">Create service accounts</A>.</P>



2.  Name the directory **AIFout**. For more information, see [Walkthrough: Exchanging documents by using the file system adapter](walkthrough-exchanging-documents-by-using-the-file-system-adapter.md).

You must create a port for the outbound directory. You use an integration port to associate the file system adapter with the file system directory that you just created. For more information, see [Managing integration ports](managing-integration-ports.md).

### To create the outbound port

1.  Open the **Outbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

2.  Click **New**.

3.  Name the new integration port **LedgerJournalOut**.

### To configure the outbound port to use the file adapter

1.  In the **Adapter** list in the **Address** group, select **File system adapter**.

2.  In the **URI** list, click the arrow to browse to the folder that you created that is named AIFOut.

3.  On the **Service contract customizations** FastTab, click **Service operations**.

4.  In the **Select service operations** form, select **LedgerJournalService.read** in the **Remaining service operations** list. Click the left arrow to move the service operation to the **Selected service operations** list.

5.  Close the form.

6.  On the **Service contract customizations** FastTab, select **Customize documents** and then click **Data policies**.

7.  In the **Document data policies** form, click **Enable all**. The XPath field determines which entity is the source of the data element. In AxdLedgerJournal class, a data element can come from the document class itself, the LedgerJournalTable table, or the LedgerJournalTrans table.

8.  Close the **Document data policies** form.

9.  Expand the **Troubleshooting** FastTab, select **All document versions** for **Logging mode**.

10. In the **Outbound ports** form, click **Activate** to activate the port.

## Coding the Outbound Exchange

After a new document is created and you have configured the integration port for the data that will be sent in an outbound exchange, you must write code to initiate the document transfer. For this example, you will create a **Send electronically** button on the **General journal** form.

The first step in writing the code to send a document is to identify the form from which the exchange will be initiated. The following steps describe how to get the form class name for the **General journal** form.

### To identify the General journal form

1.  Navigate to the **General journal** form. Click **General Ledger** \> **Journals** \> **General journal**.

2.  Right-click a record in the **General journal** form, and then click **Personalize**.

3.  Click the **Information** tab in the **Personalization** form. The **Form name** field contains the name of the form, and in this case, it should be LedgerJournalTable form. Click the **Query** tab to see that the form table is the LedgerJournalTable table.

In this section, you will add a button to the **LedgerJournalTable** form to initiate the sending of the ledger journal document. The user can send the ledger journal as an original or a duplicate. To do this, the form must contain a MenuButton control with two MenuItemButton controls.

### To add a button

1.  In the AOT, expand the **Forms** node and then expand the **LedgerJournalTable** node.

2.  Expand **Designs**, expand **Design**, expand **ActionPane: ActionPane**, and then expand **ActionPaneTab: ActionPaneTab**.

3.  Right-click **ButtonGroup:ButtonGroup**, select **New control**, and then click **MenuButton**.
    

    > [!NOTE]
    > <P>The VendPurchOrderJournal form has the same button structure for sending a purchase order. You can use this form as a reference when you implement your own send button. On the <STRONG>VendPurchOrderJournal</STRONG> form, expand the <STRONG>Design</STRONG> node, expand <STRONG>Tab:Tab</STRONG>, expand <STRONG>TabPage:Overview</STRONG>, expand <STRONG>ActionPane:ActionPane</STRONG>, expand <STRONG>ActionPaneTab:ActionPanetab</STRONG>, expand <STRONG>ButtonGroup:OverviewButtonGroup</STRONG>, and then expand <STRONG>MenuButton:MenuSendXML</STRONG> to view the form controls.</P>



4.  Right-click the new MenuButton control, click **Properties**, and then set the following properties.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Name</p></td>
    <td><p>SendXMLMenu</p></td>
    </tr>
    <tr class="even">
    <td><p>Text</p></td>
    <td><p>Send Electronically</p></td>
    </tr>
    </tbody>
    </table>


5.  In the AOT, right-click the **MenuButton:SendXMLMenu** button control, point to **New control**, and then click **Button**. This button specifies that the user is sending an original message.
    
    Set the following properties on the new Button control.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Name</p></td>
    <td><p>SendXMLOriginal</p></td>
    </tr>
    <tr class="even">
    <td><p>Text</p></td>
    <td><p>Original</p></td>
    </tr>
    </tbody>
    </table>


6.  In the AOT, right-click the **MenuButton:SendXMLMenu** button control, point to **New control**, and then click **Button**. This button will specify that the user is sending a duplicate message.
    
    Set the following properties on the new Button control and save your changes.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Property</p></th>
    <th><p>Value</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Name</p></td>
    <td><p>SendXMLDuplicate</p></td>
    </tr>
    <tr class="even">
    <td><p>Text</p></td>
    <td><p>Duplicate</p></td>
    </tr>
    </tbody>
    </table>


When the user clicks the **Send electronically** button, the clicked event calls two methods from the LedgerJournalTable table:

  - canXMLBeSent

  - sendElectronically

These methods contain the code that sends the ledger journal document.

The canXMLBeSent method makes sure that an integration port has been configured for the selected document action. If there is no integration port configured, the code returns false. In this section you will add this method to the LedgerJournalTable table.

### To add the canXMLBeSent table method

1.  In the AOT, expand the **Data Dictionary** node, expand **Tables**, and then expand **LedgerJournalTable**.

2.  Right-click **Methods**, and then click **New method**.

3.  In the code editor, copy the following code into the new method.
    
        boolean canXMLBeSent()
        {
            boolean ret;
            AifActionId actionId;
            AifEndpointList endpointList;
            AifConstraint aifConstraint = new AifConstraint();
            AifConstraintList aifConstraintList = new AifConstraintList();
            ;
        
            actionId = 
                 AifSendService::getDefaultSendAction(classnum(LedgerJournalService), AifSendActionType::SendByKey);
        
            if(actionId)
            {
                aifConstraint.parmType(AifConstraintType::NoConstraint);
                aifConstraintList.addConstraint(aifConstraint);
        
                endpointList = AifSendService::getEligibleEndpoints(actionId, 
                    aifConstraintList);
                if(endpointList.getEndpointCount()>0)
                {
                    ret = true;
                }
            }
            return ret;
        }

The sendElectronically method gets the entity key for the selected journal, calls the method that retrieves the data, serializes that data into an XML message, and then sends the document to the gateway queue.

### To add code to the sendElectronically table method

1.  In the AOT, in the **LedgerJournalTable** table, right-click the **Methods** node, and then click **New method**.

2.  In the code editor, copy the following code into the new method.
    
        void sendElectronically(XMLDocPurpose _xMLDocPurpose, 
                                AifSendMode _aifSendMode = AifSendMode::Async)
        {
            AxdSendContext axdSendContext = AxdSendContext::construct();
            AifEntityKey aifEntityKey = AifEntityKey::construct();
            Map keyData;
            AifConstraintList aifConstraintList = new AifConstraintList();
            AifConstraint aifConstraint = new AifConstraint();
            ;
            keyData = SysDictTable::getKeyData(this);
        
            aifEntityKey.parmTableId(this.TableId);
            aifEntityKey.parmRecId(this.RecId);
            aifEntityKey.parmKeyDataMap(keyData);
        
            axdSendContext.parmXMLDocPurpose(_xMLDocPurpose);
            axdSendContext.parmSecurity(false);
        
            aifConstraint.parmType(AifConstraintType::NoConstraint) ;
            aifConstraintList.addConstraint(aifConstraint) ;
        
            AifSendService::submitDefault(
                classnum(LedgerJournalService),
                aifEntityKey,
                aifConstraintList,
                _aifSendMode,
                axdSendContext.pack());
        }


> [!NOTE]
> <P>Parallel processing distributes the processing of messages across one or more instances of Application Object Server (AOS). To enable parallel processing for outbound messages, you use two optional parameters, processingMode and conversationID, in the call to the <A href="https://technet.microsoft.com/en-us/library/gg742775(v=ax.60)">AifSendServicesubmitDefault()</A> method.</P>
> <P>The following example code illustrates the signature of the submitDefault method.</P>
> <UL>
> <LI><PRE><CODE>public static void submitDefault(     AifServiceClassId serviceClassId,     AifEntityKey entityKey,     AifConstraintList constraintList,     AifSendMode sendMode,    [AifPropertyBag propertyBag = connull(),     AifProcessingMode processingMode =  AifProcessingMode::Parallel,     AifConversationId conversationId = #NoConversationId ]  )</CODE></PRE></LI></UL>
> <P>You set a value for processingMode to indicate parallel or sequential processing. If no value is specified, AIF uses sequential processing. You set processingMode to AifProcessingMode::Parallel to indicate that messages can be moved from the AIF outbound processing queues to the AIF gateway queues in parallel. For sequential or first in first out (FIFO) processing, the default value AifProcessingMode::Sequential is used.</P>
> <P>In parallel processing mode, you specify a value for conversationId when you want AIF to process all messages that use the same conversationId in sequential FIFO order. In other words, all messages that have the same conversation ID are processed sequentially. The processing order for other messages that have different values for conversationId is not guaranteed.</P>
> <P>For more information, see <A href="sequential-and-parallel-processing-in-services-and-aif.md">Sequential and parallel processing in services and AIF</A>.</P>



In this section you will add code to the clicked events for the **SendXMLOriginal** and **SendXMLDuplicate** buttons.

### To add code to the button clicked events

1.  In the AOT, expand the **Forms** node and then expand the **LedgerJournalTable** form.

2.  Expand **Designs**, expand **Design**, expand **ActionPane: ActionPane**, and then expand **ActionPaneTab: ActionPaneTab**.

3.  Expand **ButtonGroup:ButtonGroup**, expand **MenuButton:SendXMLMenu**, and then expand **Button:SendXMLOriginal**.

4.  Right-click the **Methods** node, click **Override Method**, and then select **clicked**.

5.  In the code editor, enter the following code in the clicked event.
    
        void clicked()
        {
            LedgerJournalTable  ledgerJournalTableLocal;
            ;
        
            for (ledgerJournalTableLocal = LedgerJournalTable_ds.getFirst(true) 
                ? LedgerJournalTable_ds.getFirst(true) : LedgerJournalTable;
                ledgerJournalTableLocal;
                ledgerJournalTableLocal = LedgerJournalTable_ds.getNext())
         
            // Check to see if document can be sent.
            if (ledgerJournalTableLocal.canXMLBeSent())
            {
                // Send the document.
                ledgerJournalTableLocal.sendElectronically(XMLDocPurpose::Original);
             }
            else
            {
                warning (strfmt("@SYS72175"));
                // TODO Add a ledger journal specific error message to the 
                // label file.
                // warning (strfmt("@SYSnnnnn",ledgerJournalTableLocal.JournalNum));
            }
        }

6.  Repeat steps 1 through 3 for the **MenuItemButton:SendXMLDuplicate** control.

7.  In the clicked event of the **MenutItemButton:SendXMLDuplicate** button control, change XMLDocPurpose::Original to XMLDocPurpose::Duplicate.

## Testing the Outbound Exchange

For AIF to begin sending and receiving documents for adapter-based exchanges, the services that move documents through the queues must be running as batch jobs within Microsoft Dynamics AX. For more information, see [Configuring batch jobs and tasks for AIF](configuring-batch-jobs-and-tasks-for-aif.md).

### To create the batch job

1.  Open the **Batch job** form. Click **System administration** \> **Inquiries** \> **Batch jobs** \> **Batch jobs**.

2.  Create a new batch job and enter a name. For more information, see [Create a batch job](create-a-batch-job.md).

3.  Click **View tasks**. On the **Batch tasks** form, press CTRL+N to add a row, and then enter a **Task description** and select the **Company account**.

4.  Add four tasks that use the following classes to the batch job: **AifGatewayReceiveService**, **AifGatewaySendService**, **AifInboundProcessingService**, and **AifOutboundProcessingService**.

5.  On the **Batch job** form, set a recurrence interval for the batch job. For testing, it is convenient to set the interval to one minute.

6.  To start the batch job, change its status to **Waiting**.

### To test sending the document

1.  Open the **General journal** form. Click **General ledger** \> **Journals** \> **General journal**.

2.  Click one of the journal lines, and then click the **Send electronically** button. Click **Original** to send the original document.
    
    The selected ledger journal and its lines are serialized into XML with header information and sent to the gateway queue. When the AIF batch services run, the message will be selected from the gateway queue and sent to the **AIFout** directory that you created earlier.

## See also

[Walkthrough: Exchanging documents by using the file system adapter](walkthrough-exchanging-documents-by-using-the-file-system-adapter.md)

[Example of Outbound XML Message](example-of-outbound-xml-message.md)

