---
title: Exporting and importing AIF integration port configurations
TOCTitle: Exporting and importing AIF integration port configurations
ms:assetid: ad13ee26-2867-4324-b522-85f5621e609c
ms:mtpsurl: https://technet.microsoft.com/library/Gg731890(v=AX.60)
ms:contentKeyID: 35132804
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Exporting and importing AIF integration port configurations 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Microsoft Dynamics AX 2012 uses integration ports to manage integration scenarios in services and Application Integration Framework (AIF). You can move integration port configurations between environments, such as from a test environment to a production environment, by using Microsoft Dynamics AX import/export. For information about Microsoft Dynamics AX import/export, see [Data import, export and migration](data-import-export-and-migration.md).

To move integration port configurations from a test environment to a production environment, you must complete the following tasks:

1.  Make sure that the prerequisites have been met. See Prerequisites.

2.  Export the data about integration ports from the source environment. The data is exported as a .dat file. See Export the integration port data.

3.  Import the data about integration ports into the destination environment. See Import the integration port data.

To export or import service metadata, you must use the command-line tool that is named AXUtil.exe. You can find this tool in the ManagementUtilities subfolder of the Program Files folder where you installed Microsoft Dynamics AX. For help, at the command prompt, type AxUtil.exe /?. For more information about exporting and importing metadata, see [Deploying Customizations Across Microsoft Dynamics AX 2012 Environments](https://go.microsoft.com/fwlink/?linkid=221067).

## Prerequisites

Before you copy integration port configurations from a test environment to a production environment, make sure that the following prerequisites have been met:

  - For file-based integrations, the account for Application Object Server (AOS) must have read/write permissions for the directory that is used to import and export data. The directory must not be a hidden or administrative directory, such as a directory that contains a dollar sign ($) in the name.

  - The user who imports the port configurations into the destination environment must belong to a role that has the **Manage services and integrations** privilege. By default, the **System administrator** role has this privilege.

  - All customizations must first be added to the source environment, and the application must compile without errors.

  - All ports must be activated and tested. For ports that are based on NetTCP and HTTP, the Web Service Description Language (WSDL) files must be published. Additionally, a client must be able to start the service through service calls. For ports that are based on the file system adapter or the MSMQ adapter, the corresponding scenario must be tested.

## Export the data about integration ports

1.  Click **System administration** \> **Common** \> **Data export/import** \> **Definition groups**.

2.  Create definition groups. For inbound ports, specify **AifInboundPort** as the root table, and then select all levels of related tables. For outbound ports, specify **AifOutboundPort** as the root table, and then select all levels of related tables.
    
      - During export of intergration ports, users should un-check **BarcodeSetup** and **ExtCodeTable** tables to limit the table count.

3.  (Recommended) Add export criteria by selecting only the ports that you want to export. Filter results by using the **Name** property of the **AifInboundPort** or **AifOutboundPort** table.

4.  Export the data to a local or network file share by using the definition groups that you created. The exported data is contained in a .dat file.


> [!NOTE]
> <P>During export, you may receive the following message: "Table DirPartyCollection was not found." If you receive this message, add export criteria so that only new and customized reports are exported. See step 3.</P>



## Import the data about integration ports

In the destination environment, you import the file that contains the data about integration ports that you exported from the source environment.

1.  Open the **Import options** form. Click **System administration** \> **Common** \> **Data export/import** \> **Import**.

2.  If you exported only selected ports by using export criteria, select **Update existing record** on the **Advanced** tab. Otherwise, existing ports in the destination environment are deleted.

3.  Click **OK** to close the form.

4.  Deactivate each port that you imported. For information about how to deactivate a port, see [Create, edit, or delete an enhanced integration port](create-edit-or-delete-an-enhanced-integration-port.md).

5.  Register services. For information about how to register services, see [Customize service contracts](customize-service-contracts.md).

6.  Update the configuration details for each port. For example, update the URIs that were used in the test environment to URIs that are based on paths in the production environment.
    

    > [!NOTE]
    > <P>For ports that use document filters, if the AifDocumentSetFilterElement table has data, you must update the data in the table after import.</P>



7.  Reactivate each port that you imported.


> [!IMPORTANT]
> <P>If the production environment is part of a cluster, you must restart all AOS instances to guarantee that all configurations are updated.</P>



## See also

[Data import, export and migration](data-import-export-and-migration.md)

