---
title: 'How to: Create a Basic Inbound Integration Port'
TOCTitle: 'How to: Create a Basic Inbound Integration Port'
ms:assetid: b127d90f-9402-4755-9df9-a660eb73d2bb
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh496439(v=AX.60)
ms:contentKeyID: 37072021
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Create a Basic Inbound Integration Port [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic shows you how to create a basic inbound integration port for a service. Use a basic port to test the operation of a custom service that does not require any data processing or exposure to the Internet.

### To create a basic inbound port

1.  Open the Application Object Tree (AOT).

2.  Right-click the **Service Groups** node, and then click **New Service Group**.

3.  Right-click the new service group, and then click **Properties**. Set the **Name** property to **TestBasicPortServiceGroup**. Click **Save**.

4.  Right-click **TestBasicPortServiceGroup**, and then click **Open New Window**. Drag one of the custom services from the **Services** node onto **TestBasicPortServiceGroup**.

5.  Right-click **TestBasicPortServiceGroup**, and then click **Save**.

6.  Right-click **TestBasicPortServiceGroup**, and then click **Deploy Service Group**.
    
    After the service group is successfully deployed, a confirmation message appears in the Infolog. When you open the **Inbound ports** form, the **TestBasicPortServiceGroup** port appears in the **Port Names** list as a port of the **Basic** type.

7.  To view the basic port you have created, open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**. The **TestBasicPortServiceGroup** port appears in the **Port Names** list as a port of the **Basic** type.
    

    > [!TIP]
    > <P>To start this service every time that the AOS is restarted, set the <STRONG>AutoDeploy</STRONG> property for the service group to <STRONG>Yes</STRONG>.</P>



## See also

[Using Basic Integration Ports](using-basic-integration-ports.md)

[Managing integration ports](managing-integration-ports.md)

[Integration ports](integration-ports.md)

