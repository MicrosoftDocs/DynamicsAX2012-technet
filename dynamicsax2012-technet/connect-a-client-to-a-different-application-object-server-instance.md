---
title: Connect a client to a different Application Object Server instance
TOCTitle: Connect a client to a different Application Object Server instance
ms:assetid: d1489765-b203-4348-b884-34647443857a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa569658(v=AX.60)
ms:contentKeyID: 35132898
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Connect a client to a different Application Object Server instance 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can connect a Microsoft Dynamics AX 32-bit client or a .NET Business Connector client to a different Application Object Server (AOS) instance by using the Microsoft Dynamics AX 2012 Configuration utility.

## Connect to a different AOS instance

1.  Open the configuration utility. (Click **Start** \> **Control Panel** \> **Administrative Tools** \> **Microsoft Dynamics AX 2012 Configuration**.)

2.  In the **Configuration Target** list, click the client that you want to modify.

3.  In the **Configuration** list, click the configuration that you want to modify.
    

    > [!IMPORTANT]
    > <P>You cannot change the <STRONG>Original (installed configuration)</STRONG> configuration. Instead, create a new configuration by using the <STRONG>Manage</STRONG> button. For more information, see <A href="manage-a-client-configuration.md">Manage a client configuration</A>.</P>



4.  On the **Connection** tab, in the **Available Application Object Server instances** list, click the AOS instance that you want to connect to, and then click the **Up** button until the AOS instance is first in the list.
    

    > [!NOTE]
    > <P>Microsoft Dynamics AX clients connect to the first AOS instance in the list, unless that instance is not available. If the first AOS instance is not available, the client connects to the next instance in the list.</P>



5.  Click **OK**.

## Add an instance to the list of available AOS instances

1.  On the **Connection** tab, click **Add**.

2.  In the **Server name** box, enter the name of the computer that is running the AOS instance that you want to connect to.

3.  (Optional) In the **Instance name** box, enter the name of the AOS instance.

4.  (Optional) In the **TCP/IP port** and **WSDL port** boxes, enter the ports that the AOS instance is running on. If you do not enter port values, the system uses the default ports, or TCP/IP port 2712 and WSDL port 8101. Click **OK**.

## See also

[Manage client startup settings](manage-client-startup-settings.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

