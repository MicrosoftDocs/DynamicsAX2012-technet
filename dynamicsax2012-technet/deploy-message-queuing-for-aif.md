---
title: Deploy Message Queuing for AIF
TOCTitle: Deploy Message Queuing for AIF
ms:assetid: 1e5a2329-3f18-40cc-ad10-3d2f1530f6c7
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa834340(v=AX.60)
ms:contentKeyID: 36687857
ms.date: 03/26/2014
mtps_version: v=AX.60
---

# Deploy Message Queuing for AIF 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The MSMQ adapter for Microsoft Message Queuing is included with Microsoft Dynamics AX.


> [!IMPORTANT]
> <P>Whenever the word "queue" is used in this topic, it refers to a Message Queuing queue, not the AIF gateway queue.</P>



To send documents by using Message Queuing, you must install it on a computer on the network and create at least one public queue.

To receive documents by using Message Queuing, you must install Message Queuing and create at least one queue on a computer that has Application Object Server (AOS) installed, and that has been configured to run Application Integration Framework (AIF) batch jobs. For more information about these batch jobs, see [Configuring batch jobs and tasks for AIF](configuring-batch-jobs-and-tasks-for-aif.md).

## Limitations of Message Queuing

Messages processed by the MSMQ adapter have a size limit of 4 megabytes (MB). For this reason, we do not recommend using Message Queuing to import data in bulk, such as by using the AIF batched-message schema. For more information about batched messages, see [Processing batched messages in AIF](processing-batched-messages-in-aif.md).

By default, AIF does not handle dead-letter queue notifications or poison message events.

## About signed messages

Microsoft Dynamics AX requires that incoming messages be signed. If you need to send signed messages from Microsoft Dynamics AX, such as to other Microsoft Dynamics AX installations, you must run the AOS service under an Active Directory domain account. By default, the AOS service runs under the Network Service account. When AOS is running under the Network Service account, it cannot send signed messages because the Network Service account is not in Active Directory. For more information about AOS account configuration, see [Install an Application Object Server (AOS) instance](install-an-application-object-server-aos-instance.md).

## Installing Message Queuing

Any computer that communicates through Message Queuing, including computers that run AOS, must have Message Queuing installed.

Windows servers must have the Application Server role added. For application servers, select the following options:

  - **Incoming Remote Transactions**

  - **Outgoing Remote Transactions**

For information about how to install Message Queuing, see [Install Message Queuing](http://go.microsoft.com/fwlink/?linkid=223865) on the TechNet website. Be sure to select the following options:

  - **Message Queuing Server**

  - **Directory Service Integration**

  - **HTTP Support**

For Microsoft Dynamics AX AIF scenarios, Message Queuing must be installed in Domain mode, which connects to the Active Directory service. Do not install Message Queuing in Workgroup mode on computers that exchange messages through AIF by using the MSMQ adapter. For more information about MSMQ modes, see [Information about Workgroup mode and about Domain mode in Microsoft Message Queuing](http://go.microsoft.com/fwlink/?linkid=223873) and [How to determine if MSMQ 2.0 is installed in Workgroup or Directory mode](http://go.microsoft.com/fwlink/?linkid=223874).

## Configure the Distributed Transaction Coordinator

The Distributed Transaction Coordinator (MSDTC) service coordinates transactions in Message Queuing queues. You must start and configure MSDTC on servers that use Message Queuing with AIF.

1.  Click **Start** and then type "component services" to open the **Computer Management** window.

2.  In the console tree, expand **Component Services** and then expand the tree until you open **Distributed Transaction Coordinator**.

3.  Right-click **Local DTC**, and then click **Properties**.

4.  On the **Security** tab, select the following check boxes:
    
      - **Network DTC Access**
    
      - **Allow Remote Clients**
    
      - **Allow Inbound**
    
      - **No Authentication Required**
    
      - **Enable XA Transactions**

## Set the security mode

To enable remote communication with queues, you must configure the MSMQ adapter's security mode. This mode is not configured by default. In the configuration file for the MSMQ adapter, the \<security\> element of the \<binding\> element that has the "MsmqIntegrationSendBinding" attribute must be configured as follows:

    <binding name="MsmqIntegrationSendBinding">
      <security mode="Transport">
        <transport msmqAuthenticationMode="WindowsDomain" msmqProtectionLevel="Sign"/>
      </security>
    </binding>

If you have installed the WCF Configuration Editor tool, you can change these settings by using the tool. These settings are available on the **Security** tab for the **MsmqIntegrationSendBinding** settings. For information about the WCF Configuration Editor tool, see [Configure addresses for enhanced integration ports](configure-addresses-for-enhanced-integration-ports.md).

## Creating a queue

For information about how to create a queue, see [Create Queues](http://go.microsoft.com/fwlink/?linkid=223867) on the TechNet website.

For most scenarios, you should select the **Transactional** check box when you create a queue. For scenarios that require prioritization of messages, do not select **Transactional** (see [Deploy Message Queuing for AIF](deploy-message-queuing-for-aif.md)).

Any queue that is used for receiving messages must be located on the same computer as the AOS that is configured to run the AIF batch jobs.

## Configure a queue for sending or receiving documents

AIF requires all inbound messages to be authenticated. When using Message Queuing, authenticated messages are passed to AIF through authenticated or unauthenticated queues. AIF does not provide authentication for outbound messages. Therefore, you must configure outbound queues to be unauthenticated.

1.  Open Computer Management.

2.  In the console tree, right-click the queue that you created, and then click **Properties**.

3.  If you are configuring an inbound queue, on the **General** tab, select **Authenticated**. If you are configuring an outbound queue, clear **Authenticated**.

4.  On the **Security** tab, set the appropriate permissions.
    
      - Be sure that an administrator has the Full Control permission for each queue. Otherwise, you might become locked out of the queue and unable to make changes.
    
      - By default, "Everyone" and "Anonymous Logon" users can send messages to any newly created queue. Only the creator of the queue and an administrator can receive messages from the queues.
    
      - For inbound queues, select **Full Control** for the AOS account, which is the domain account or Network Service account that is associated with the AOS instance. For AIF users, only grant permissions for **Send Message**, **Get Properties**, and **Get Permissions**. For more information about how to configure port users and trusted intermediaries in AIF, see [Configure security for integration ports](configure-security-for-integration-ports.md).
    
      - For outbound queues, set the permissions to select **Allow** on **Send Message**, **Get Properties**, and **Get Permissions** for the Anonymous Logon user. Select **Allow** on **Receive Message** and **Peek Message** for integration port users only.
    
      - If the inbound Message Queuing queue is not on the same computer as AOS, then two additional entries must be added to the permissions list. First, add the account for the AOS computer, for example, domain-name\\computer-name$, and select **Allow** on **Peek Message** and **Receive Message**. Second, grant the **Peek Message** and **Receive Message** permissions for the Anonymous Logon user.

5.  Close the dialog boxes.

6.  Log off and then log back on to the computer.

## Enabling prioritization of messages

To enable prioritization of messages when using Message Queuing:

  - Use only non-transactional queues. Transactional queues do not support message prioritization.

  - In the configuration file for the MSMQ adapter, or by using the WCF Configuration Editor tool, specify **False** for the **ExactlyOnce** setting for the relevant MSMQ integration bindings.

## See also

[Configure addresses for enhanced integration ports](configure-addresses-for-enhanced-integration-ports.md)

  


