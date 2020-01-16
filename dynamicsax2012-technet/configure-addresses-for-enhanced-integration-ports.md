---
title: Configure addresses for enhanced integration ports
TOCTitle: Configure addresses
ms:assetid: 4178fdd6-6e80-47b0-a281-99f8d7564989
ms:mtpsurl: https://technet.microsoft.com/library/Hh202051(v=AX.60)
ms:contentKeyID: 35949285
author: Khairunj
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Configure addresses for enhanced integration ports 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic describes one step in the process for managing integration ports. For more information, see <A href="managing-integration-ports.md">Managing integration ports</A>.</P>



This topic describes how to configure addresses in either the **Inbound ports** form or the **Outbound ports** form. To open these forms, follow one of these steps.

  - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

  - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

In Microsoft Dynamics AX 2012 services and Application Integration Framework (AIF), enhanced integration ports use adapters to enable Microsoft Dynamics AX to communicate by using various transport protocols. For an overview of adapters and descriptions of the types of adapters that are included with Microsoft Dynamics AX 2012, see [Adapters](adapters.md). The addresses of integration ports are defined by the adapters that you select and the Uniform Resource Identifiers (URIs) of the adapters. Inbound integration ports have an inbound address that is used for inbound messages, and they can also have a response address that is used for outbound messages. Outbound integration ports have only an outbound address that is used for outbound messages.

## Register adapters

An adapter must be registered before it can be used. Adapters that are included with Microsoft Dynamics AX are automatically registered during installation. Whenever a new adapter is added to the Application Object Tree (AOT), you must register the adapter to make it available in the configuration forms for enhanced integration ports. If you do not have to register adapters, go to the next section.

To register adapters, follow these steps.

1.  Click **System administration** \> **Setup** \> **Checklists** \> **Initialization checklist**.

2.  Expand the **Initialize system** node.

3.  Click **Set up Application Integration Framework**.

Adapters, basic ports, and services are registered. This operation can take some time to be completed.

## Select adapters

After adapters have been registered, you must select the adapters that you want to use for integration.

  - In the **Address** group or the **Response address** group, click the arrow in the **Adapter** field, and then select an adapter in the list.

You can select the appropriate adapter for your connection when you configure an enhanced integration port.

For example, in an outbound scenario, the chart of accounts is sent from Microsoft Dynamics AX to two external systems. The first system is configured to receive messages by checking for files in a specific file system directory. For this system, the integration port uses the file system adapter. The second system is configured to receive messages by using Message Queuing, which is also known as MSMQ. For this system, the integration port uses the MSMQ adapter.

In this outbound scenario, both messages are first put in the gateway queue in Microsoft Dynamics AX. To start and stop processing in the queues, you use the Microsoft Dynamics AX batch job feature. When a batch job starts, it retrieves messages from the queue. The batch job sends the first message to the first system by using the appropriate file system directory. The batch job also sends the second message to the appropriate MSMQ queue for the second system. For more information about batch jobs, see [Configuring batch jobs and tasks for AIF](configuring-batch-jobs-and-tasks-for-aif.md).

An example of an inbound scenario is the creation of a sales order. For an inbound integration port, you can provide a response address where AIF sends the results of processing an inbound message. For example, when an inbound message creates a sales order, a response message contains the sales order ID of the new sales order, if the inbound message is completed successfully. Responses can also contain error information. To provide a response address, select the check box in the **Response address** group. For an inbound integration port, you can select the same adapter type or different adapter types for inbound messages and responses.

## Specify URIs

Before you can configure an adapter, you must specify its URI. The format of the URI varies, depending on the type of adapter that you selected:

  - If the adapter type is **File system adapter**, and the address is an inbound address, the URI is the file system path of the directory where the port retrieves documents. If the address is an outbound or response address, the URI is the file system path of the directory where the port saves documents. To select a directory, click the arrow in the **URI** field, and then browse to a folder. Make sure that the service account for Application Object Server (AOS) has the appropriate read or write permissions for the directory.
    

    > [!NOTE]
    > <P>When you submit multiple documents to a port that uses the file system adapter, the documents are processed in order, based on the file names. To control the order in which documents are processed, use file names that include a sequencing scheme, such as "PO_0001" and "PO_0002".</P>



  - If the adapter type is **NetTcp**, the URI is automatically provided by Microsoft Dynamics AX, based on the port name. You can view the URI after you save the port configuration by, for example, pressing CTRL+S.

  - If the adapter type is **MSMQ**, the URI is based on the queue that you select. To select a queue, click the arrow in the **URI** field, and then select a queue in the list. The server must be configured to provide Message Queuing services, and queues must be defined before they can be used by the integration port. For more information about how to set up message queues, see [Deploy Message Queuing for AIF](deploy-message-queuing-for-aif.md).

  - If the adapter type is **HTTP**, the URI is the Internet address of a website that you added by using the **Web sites** form. To select a website, click the arrow in the **URI** field. Then, in the **Select Web site** form, click the arrow in the **Web site** field, and then select a website in the list. For more information about how to set up a website, see [Install web services on IIS](install-web-services-on-iis.md).

## Configure adapters

After you specify the URI of the adapter that you selected, you can configure the adapter.

  - In the **Address** group or the **Response address** group, click **Configure**. In Microsoft Dynamics AX 2012 R2, click **Configure AOS** for adapter types other than **NetTcp**. To make the **Configure AOS** button visible, you must save the port settings by, for example, pressing CTRL+S.
    
    One of the following configuration forms opens:
    
      - For the file system adapter, the **File system adapter configuration** form opens. We recommend that you specify a Microsoft Dynamics AX user account that is used as the default message owner when file ownership cannot be resolved deterministically. For example, User Account Control (UAC) is enabled in Windows, and files are created by an administrator account. For these files, the **Owner** attribute in the file properties is set to the Windows **Administrators** group. Similarly, for files that are created from a process that runs on a network service, the owner is set to **NT AUTHORITY\\NETWORK SERVICE**.
    
      - For adapters that are based on Windows Communication Foundation (WCF), the **WCF configuration** form opens. The types of adapters that are based on WCF include **NetTcp**, **HTTP**, and **MSMQ**. The **WCF configuration** form contains the WCF Configuration Editor tool, SvcConfigEditor.exe, if the tool is installed. The WCF Configuration Editor tool is installed as a component of some versions of the Windows SDK and by Microsoft Visual Studio 2010. This tool provides a graphical user interface (GUI) that you can use to create and modify configuration settings for WCF services. For more information about the WCF Configuration Editor tool, see [Configuration Editor Tool](https://go.microsoft.com/fwlink/?linkid=215021) on the MSDN website.
        
        If the WCF Configuration Editor tool is not installed, the WCF configuration file opens in Notepad. You can change the WCF configuration information by modifying the XML code in Notepad. Then save the file. For more information about how to modify XML code in WCF configuration files, see [Configuring Services Using Configuration Files](https://go.microsoft.com/fwlink/?linkid=215024) on the MSDN website.

## Next step

[Configure processing options](configure-processing-options.md)

