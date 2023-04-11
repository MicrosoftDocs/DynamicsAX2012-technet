---
title: 'Walkthrough: Debugging AIF Service Operation Calls When Using File System Adapter'
TOCTitle: 'Walkthrough: Debugging AIF Service Operation Calls When Using File System Adapter'
ms:assetid: 0c8a2815-d09b-4f49-8f10-3683ea4cc669
ms:mtpsurl: https://technet.microsoft.com/library/JJ710372(v=AX.60)
ms:contentKeyID: 49384264
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Walkthrough: Debugging AIF Service Operation Calls When Using File System Adapter 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2_

AIF enables asynchronous document exchanges by processing XML messages that are stored as files. Debugging code in an asynchronous exchange requires the Microsoft Visual Studio debugger. You must first set up and configure the exchange by using an enhanced integration port. For more information about integration ports, the file system adapter, and messages in the Application Integration Framework (AIF), see [Integration ports](integration-ports.md), [Adapters](adapters.md), and [Messages and transforms in AIF](messages-and-transforms-in-aif.md) in the [Key concepts in AIF](key-concepts-in-aif.md) section of the documentation.


> [!NOTE]
> <P>You use Visual Studio to view the service class code that is compiled into Common Intermediate Language (CIL) when you debug the X++ service code in an asynchronous transfer that uses the file adapter. For more information, see <A href="https://technet.microsoft.com/library/gg860898(v=ax.60)">Debugging in Microsoft Dynamics AX 2012</A>.</P>



In this walkthrough you will complete the following tasks by using the create operation of the sales order service included with Microsoft Dynamics AX:

  - Set up the transfer environment that uses an enhanced inbound integration port, the file system adapter, the create operation of the sales order service, and folders that contain the inbound and outbound XML message files.

  - Save an XML file that contains a create message to process and copy it to the inbound file system folder.

  - In Visual Studio, set a breakpoint in one of the sales order service operation methods and attach the Visual Studio debugger to the Microsoft Dynamics AX server process.

  - In Microsoft Dynamics AX, create the job to run the methods in the AIF gateway and processing classes. These classes process messages in the folder associated with the inbound port.

  - Run the job and step into the service operation code in the Visual Studio debugger.

## Prerequisites

  - The Microsoft Dynamics AX Application Explorer must be installed. For more information, see [Install Visual Studio Tools](install-visual-studio-tools.md).

  - The Microsoft Dynamics AX debugger must be installed. For more information, see [Install developer tools](install-developer-tools.md).

  - Microsoft Dynamics AX Services must be initialized. For more information, see [Customize service contracts](customize-service-contracts.md).

  - The AOS must be configured for debugging. For more information, see [Debugging in Microsoft Dynamics AX 2012](https://technet.microsoft.com/library/gg860898\(v=ax.60\)).

  - To use the Visual Studio debugger with Microsoft Dynamics AX services, you must be logged on with a user ID that is a member of the Windows Administrators group on the computer. This user ID must also be added to Microsoft Dynamics AX with the appropriate permissions to create a sales order.

  - You must be logged on to the system where the AOS is running.

  - If you are using services and AIF for the first time after you install Microsoft Dynamics AX, you must register the services and adapters included with Microsoft Dynamics AX.
    
    ### To register services in Microsoft Dynamics AX
    
    1.  Click **System administration** \> **Setup** \> **Checklists** \> **Initialization checklist**.
    
    2.  Expand the **Initialize system** node and then click **Set up Application Integration Framework**. This operation can take some time to be completed.

## Set Up the File System Transfer Environment

You must create a folder for inbound messages and a folder for outbound response messages when you use the file system adapter. To set up the file system transfer environment you use the Microsoft Dynamics AX client to create and configure an inbound integration port that uses the two folders.

### To create the folders and set up the inbound integration port

1.  To enable the document exchange using the file system adapter, create the following two folders.
    
      - A folder to contain the source document for the request. Name this folder **AIFIn**. This is the folder from which AIF retrieves the original sales order document as an XML message.
    
      - A folder to receive the AIF response message. Name this folder **AIFOut**.
    

    > [!IMPORTANT]
    > <P>You must set the permissions on these folders so that the account that the AOS runs under has read and write access to the files in the folders.</P>

    

    > [!TIP]
    > <P>AIF deletes the source document for the request after it has been processed. To save a copy of the message you submitted, you can create a new folder named AifinArchives to store a copy of the request message before you submit it.</P>



2.  Create the inbound integration port.
    
    ### To create and configure the inbound integration port
    
    1.  Open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.
    
    2.  Click **New**.
    
    3.  Enter testSOcreateFileSystem for the name of the port. Enter a description for the port.
    
    4.  In the **Address** group, select **File system adapter**.
    
    5.  To select a directory, click the arrow in the **URI** field, and then browse to the **AifIn** folder that you created. Make sure that your AOS service account has the appropriate read or write permissions for the directory.
    
    6.  Click **Configure** and then click **Use default owner for administrator’s group**. Select your Microsoft Dynamics AX user account as the default message owner.
    
    7.  Select **Response address**. Click the arrow in the **URI** field, and then browse to the **AifOut** folder that you created.
    
    8.  On the **Service contract customizations** FastTab, select **Expose service operations** and then click **Service operations** to open the **Select service operations** form.
    
    9.  Select the **SalesSalesOrderService.create** service operation from the right-hand list, and then click the left arrow to move the operation to the **Selected service operations** list.
    
    10. Close the form.

3.  Click **Activate** on the **Inbound ports** form to enable the **testSOcreateFileSystem** port.

## Prepare the Inbound XML Message

The following example XML file contains a message that causes AIF to call the SalesOrderService.Create method with the information to create one record in the SalesOrder table and a related record in the SalesLine table.

### To prepare the inbound XML message

1.  Copy the following XML code into an empty Notepad document.
    
        <?xml version="1.0" encoding="utf-8" ?>
        <Envelope xmlns="https://schemas.microsoft.com/dynamics/2011/01/documents/Message">
        <Header>
          <Action>https://schemas.microsoft.com/dynamics/2008/01/services/SalesOrderService/create</Action>
        </Header>
          <Body>
            <MessageParts>
              <SalesOrder xmlns="https://schemas.microsoft.com/dynamics/2008/01/documents/SalesOrder">
                <SalesTable class="entity">
                  <CustAccount>2124</CustAccount>
                  <DeliveryDate>2011-10-11</DeliveryDate>
                  <PurchOrderFormNum>PO</PurchOrderFormNum>
                  <ReceiptDateRequested>2011-11-11</ReceiptDateRequested>
                  <SalesLine class="entity">
                    <ItemId>1604</ItemId>
                    <SalesQty>18</SalesQty>
                    <SalesUnit>Pcs</SalesUnit>
                  </SalesLine>
                </SalesTable>
              </SalesOrder>
            </MessageParts>
          </Body>
        </Envelope>
    

    > [!NOTE]
    > <P>No message ID is specified in the example XML message. AIF supplies a unique message ID every time that you submit the message. If you want to match an exception with a particular message, you may specify a message ID in the header section using the &lt;MessageID&gt; tag. For more information about tags in the message header, see <A href="message-header.md">Message Header</A>.</P>



2.  Replace the values in the document by using valid values for your Microsoft Dynamics AX environment. For example, you will probably have to replace the values for \<CustAccount\> and \<ItemId\>. You can see the values in the system when you open the **Sales order** form.
    
    Note that this message creates a sales order in the default company and partition for the calling user. The calling user for exchanges that use the file system adapter is the owner of the XML file in the AifIn folder.

3.  Save the file. Name the file TestSOcreate.xml.

4.  Copy the file into the AifIn folder.
    

    > [!TIP]
    > <P>Save a copy of the file in the AifinArchives folder.</P>



5.  If you did not configure the file system adapter to use a default message owner on the **Inbound ports** form, you must set the owner of the file to be a Microsoft Dynamics AX user, which is known to AIF as the calling user.
    
    ### To set the owner of the file
    
    1.  In Windows Explorer, right-click the file name and then click **Properties**.
    
    2.  Click **Security** and then click **Advanced**.
    
    3.  Click **Owner** and then click **Advanced**.
    
    4.  Click **Edit** and then select a Windows account that is also an Microsoft Dynamics AX user. AIF recognizes this user as the calling user when the system processes the XML message.
    
    5.  Click **Ok**.

## Set a Breakpoint in the Service Operation

You use Visual Studio to set a breakpoint in the prepareForSave method in the create service operation in the AxdSalesOrder class.

### To set a breakpoint in the prepareForSave method

1.  In Visual Studio click **View** and then click **Application Explorer**. If Application Explorer is not visible, you must install Visual Studio Tools. For more information, see [Install Visual Studio Tools](install-visual-studio-tools.md).

2.  In the **Classes** node, open **AxdSalesOrder**.

3.  Right-click **prepareForSave** and then click **View code**.

4.  Set a breakpoint on a line of code.

5.  Click **Debug** and then click **Attach to Process**.

6.  Select **Show processes from all users** and **Show processes in all sessions**.

7.  Select **AX32Serv.exe** and then click **Attach**. The debugging windows appear in Visual Studio. It may take some time to load the symbols. Progress messages appear at the bottom of the Visual Studio window.
    

    > [!IMPORTANT]
    > <P>You must be logged into the computer where the AOS is running, and you must have configured the AOS for debugging. For more information, see <A href="https://technet.microsoft.com/library/gg860898(v=ax.60)">Debugging in Microsoft Dynamics AX 2012</A>.</P>



## Create and Run the Job to Process the Inbound XML Message

For asynchronous exchanges, you create a job to execute the AIF code that receives the inbound message and sends the response.

### To create and run the job in the AOT

1.  Create a new job in the **Jobs** node in the **AOT**.

2.  Copy the following code and paste it into the code editor window:
    
        static void AifProcessingClasses(Args _args)
        {
         AifGatewayReceiveService receive = new AifGatewayReceiveService();
         AifInboundProcessingService inbound = new AifinboundProcessingService();
         AifOutboundProcessingService outbound = new AifOutboundProcessingService();
         AifGatewaySendService send = new AifGatewaySendService();
        
        receive.run();
        inbound.run();
        outbound.run();
        send.run();
        }

3.  Click **Go** or press F5 to run the job.
    
    The Visual Studio debugger opens and you can examine the code at the breakpoint.
    

    > [!TIP]
    > <P>You may have to point Visual Studio to the X++ source files (.xpp files) for debugging. These files are created when you enable debugging on the AOS server computer. Depending on your installation, the X++ source files may reside in a directory path similar to the following:</P>
    > <UL>
    > <LI>
    > <P>C:\Program Files\Microsoft Dynamics AX\60\Server\MicrosoftDynamicsAX\bin\XppIL\source</P></LI></UL>

    
    For more information about how to create X++ source files for debugging, see [How to: Enable the Debugger](https://technet.microsoft.com/library/aa569665\(v=ax.60\)).

