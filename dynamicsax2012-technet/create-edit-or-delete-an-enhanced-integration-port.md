---
title: Create, edit, or delete an enhanced integration port
TOCTitle: Create, edit, or delete an enhanced integration port
ms:assetid: a74bc9cc-09ab-4f76-aee2-11da6cc9310d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh202090(v=AX.60)
ms:contentKeyID: 35949340
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Create, edit, or delete an enhanced integration port 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic describes one step in the process for managing integration ports. For more information, see <A href="managing-integration-ports.md">Managing integration ports</A>.</P>



This topic describes how to create, edit, or delete an enhanced integration port. For an overview of integration ports that includes information about the types of ports and the features of those ports, see [Integration ports](integration-ports.md).

## Create an enhanced integration port

To create an enhanced integration port, follow these steps.

1.  To create an inbound integration port, open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.
    
    –or–
    
    To create an outbound integration port, open the **Outbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

2.  Click **New**.

3.  Enter a name and description for the new integration port. The name of a port must begin with a letter and can contain only alphanumeric characters.

4.  Configure the integration port, or click **Close** to save the default configuration. You can modify the configuration later. To view a list of the configuration steps for enhanced integration ports, see [Managing integration ports](managing-integration-ports.md).

## Edit or delete an enhanced integration port

To change the settings for an existing enhanced integration port, or to delete the port, you must first deactivate the port.

1.  To modify an inbound integration port, open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.
    
    –or–
    
    To modify an outbound integration port, open the **Outbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

2.  In the **Port name** field, click the name of the port.

3.  Click **Deactivate** to deactivate the port.

4.  Change the configuration settings. To view a list of the configuration steps for enhanced integration ports, see [Managing integration ports](managing-integration-ports.md).
    
    –or–
    
    Click **Delete** to delete the port.

5.  Click **Activate** to reactivate the integration port.


> [!WARNING]
> <P>If you activate or deactivate an integration port, all integration ports on the instance of Application Object Server (AOS) are reactivated. Do not click the <STRONG>Deactivate</STRONG> or <STRONG>Activate</STRONG> button while integration ports are processing messages.</P>



## Next step

[Configure addresses for enhanced integration ports](configure-addresses-for-enhanced-integration-ports.md)

## See also

[Getting started with services and AIF](getting-started-with-services-and-aif.md)

