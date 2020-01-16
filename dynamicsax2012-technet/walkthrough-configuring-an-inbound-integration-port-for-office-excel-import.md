---
title: 'Walkthrough: Configuring an inbound integration port for Office Excel import'
TOCTitle: 'Walkthrough: Configuring an inbound integration port for Office Excel import'
ms:assetid: 618ae9ca-8a4e-41bf-8ca6-070733472fb7
ms:mtpsurl: https://technet.microsoft.com/library/Hh433513(v=AX.60)
ms:contentKeyID: 36941294
author: Khairunj
ms.date: 04/29/2014
mtps_version: v=AX.60
---

# Walkthrough: Configuring an inbound integration port for Office Excel import 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Data in Microsoft Excel can be modified by using any document service that has a Create or Update service operation, and that uses a file adapter or net.tcp. Before you can use a document service, you must register it, add it to an inbound integration port, activate the port, and then expose the service.

Only the following document services from Microsoft Dynamics AX 2012 are supported without modification in the Excel Add-in: BudgetTransaction, EMSMeterReading, EMSSubstanceFlow, GeneralJournal, ProductionPickingList, ProjectHourJournalS, SysImportBusSector, VendGroup, and VendRequestSignup.

Additional services can be constructed to extend the scenarios in which Excel can be used to update, create, and delete business data in Microsoft Dynamics AX.


> [!NOTE]
> <P>The configuration of integration ports for Excel import is a specific example of the procedures that are used to configure any integration port. For more general information, see <A href="managing-integration-ports.md">Managing integration ports</A>.</P>



## Set up a document service that can be used with the Excel Add-in

A service must be registered before it can be used. Some services that are included with Microsoft Dynamics AX 2012 are automatically registered during installation. We recommend that you register services before you use features of Application Integration Framework (AIF) for the first time. Whenever a new service is added to the Application Object Tree (AOT), you must register the service. Registration makes the service available in the configuration forms for enhanced integration ports. Use the following procedure to register services.

### Register a service

1.  Click **System administration** \> **Setup** \> **Checklists** \> **Initialization checklist**.

2.  Expand the **Initialize system** node.

3.  Click **Set up Application Integration Framework**.
    
    Microsoft Dynamics AX registers adapters, basic ports, and services. Registration can take some time to be completed.

### Create an inbound integration port that can be used with Excel

1.  To create an inbound integration port, open the **Inbound ports** form. Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.

2.  Click **New**.

3.  Enter a name and description for the new integration port. The name of a port must begin with a letter and can contain only alphanumeric characters.

4.  On the **Service contract customizations** FastTab, click **Service operations** to open the **Select service operations** form.

5.  In the **Selected service operations** list, click the service operations that you want to expose. To select multiple service operations, hold down the CTRL key, and then click each service operation. To select a range of service operations, hold down the SHIFT key, and then click the first and last service operations in the range.

6.  If the service operations that you want do not appear in the **Selected service operations** list, select the service operations in the **Remaining service operations** list, and then click the left arrow button. The service operations that you selected are moved to the **Selected service operations** list. To move service operations back to the **Remaining service operations** list, select the service operations in the **Selected service operations** list, and then click the right arrow button.

7.  Close the form.

8.  Click **Activate**.

## See also

[Use Microsoft Excel to import and export data](use-microsoft-excel-to-import-and-export-data.md)

  


