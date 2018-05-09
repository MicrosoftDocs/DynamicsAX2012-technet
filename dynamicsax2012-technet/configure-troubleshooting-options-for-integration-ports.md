---
title: Configure troubleshooting options for integration ports
TOCTitle: Configure troubleshooting options
ms:assetid: 2a274dc4-5a0b-4973-9c19-24c7412b4f2c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh202045(v=AX.60)
ms:contentKeyID: 35949277
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Configure troubleshooting options for integration ports 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic describes one step in the process for managing integration ports. For more information, see <A href="managing-integration-ports.md">Managing integration ports</A>.</P>



This topic describes how to configure troubleshooting settings in services and Application Integration Framework (AIF) by using either the **Inbound ports** form or the **Outbound ports** form. To open these forms, follow one of these steps.

  - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

  - Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

Use the **Troubleshooting** FastTab to specify settings that can help you diagnose issues in the configuration and operation of an integration port.

## Configure the logging mode

You can store copies of the XML code for documents that are exchanged by using AIF. You can then view these copies by using the **History** form.

In the **Logging mode** list, select the logging mode. The following options are available:

  - **Original document** – Select this option to store only the original document.

  - **All document versions** – Select this option to store a separate version of the document every time that the document is modified by a pipeline. When you select this option, you can use the **Document log** form to view details about each step in the processing of the document.
    

    > [!NOTE]
    > <P>Document versions are not logged for each integration-port-level transform. Document versions are logged only for pipeline components. For example, you can use an XSLT in a pipeline if you want to log the various document versions that are the result of transformations.</P>



  - **Message header only** – Select this option to store only the message header for each document.

  - **Logging disabled** – Select this option to turn logging off. When you select this option, no documents are entered in the document history. As a result, you cannot view correlation information.

## Configure error messaging

You can configure the integration port to provide information about errors by using the following check boxes:

  - **Include exceptions in fault** – Select this check box to specify that X++ and .NET Framework error messages from the service are included in fault messages. When you select this check box, the fault message includes detailed Infolog messages.

  - **Respond after error in asynchronous request** – For inbound integration ports, select this check box to specify that the port automatically sends error messages as responses in asynchronous scenarios.

## Next step

[Configure security for integration ports](configure-security-for-integration-ports.md)

