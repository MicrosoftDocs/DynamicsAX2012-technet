---
title: Upgrade AIF code
TOCTitle: Upgrade AIF code
ms:assetid: a74f5ffd-cb0e-4610-b351-095fb181ca40
ms:mtpsurl: https://technet.microsoft.com/library/Gg731887(v=AX.60)
ms:contentKeyID: 35132798
author: tonyafehr
ms.date: 05/05/2014
mtps_version: v=AX.60
f1_keywords:
- code
- data
- services
- upgrade
- AIF
---

# Upgrade AIF code 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Application Integration Framework (AIF) is used to exchange data between Microsoft Dynamics AX and external systems. During the upgrade process, the **Data upgrade checklist** includes a step for the upgrade of AIF code. This topic describes this step of the **Data upgrade checklist**.

Click **System administration** \> **Setup** \> **Checklists** \> **Data upgrade checklist**. Then, in the checklist pane, expand **Finalize upgrade**. Click **Upgrade AIF code**. This step may take a while. When the step is completed, check the Infolog to verify that no errors occurred. This step includes the following two processes:

  - **Code upgrade** – This process creates new service classes, data classes, and service nodes in the Application Object Tree (AOT).

  - **Data upgrade** – This process upgrades all AIF-related records in the database.
    

    > [!IMPORTANT]
    > <P>The upgrade of AIF code and data is a two-step process. You must successfully upgrade the AIF code before you can upgrade the AIF data. For more information, see <A href="upgrade-additional-features.md">Upgrade additional features</A>.</P>



## Before you upgrade

Before you upgrade, you should be familiar with services and AIF. For more information, see [Services and Application Integration Framework (AIF)](services-and-application-integration-framework-aif.md).

Review the following sections before you begin the upgrade process.

## Process messages on the source system

Before you run the upgrade process, make sure that all the AIF messages have been processed on the system that is being upgraded. Check the following locations to verify that all the messages have been processed:

  - **All inbound message locations** – These locations include file system directories, Message Queuing queues, and any locations where AIF receives inbound messages.

  - **The queue manager** – All messages in the queue manager are unprocessed and must be deleted. Click **System administration** \> **Periodic** \> **Services and Application Integration Framework** \> **Queue manager**.

## Upgrade considerations

The enhancements to services and AIF in Microsoft Dynamics AX 2012 cause significant changes in functionality, configuration, database schemas, and document schemas, or .xsd files. When you plan an upgrade from an earlier version of Microsoft Dynamics AX, consider the following guidelines:

  - You must recompile and test all interfaces that used the earlier version of Microsoft Dynamics AX to make sure that the interfaces work with services in Microsoft Dynamics AX 2012.

  - In Microsoft Dynamics AX 2012, the MSMQ and BizTalk adapters are replaced with equivalent functionality that is provided by Windows Communication Foundation (WCF). You must recompile any automated integration processes that used these adapters, such as Microsoft BizTalk Server orchestration.

  - The upgrade framework changes AIF endpoints and related configurations to integration ports in Microsoft Dynamics AX 2012. When the upgrade process is completed, you must configure these integration ports before you can use Microsoft Dynamics AX 2012 services and AIF functionality.

## Upgrade AIF code

This section describes the process that Microsoft Dynamics AX 2012 uses to upgrade AIF code.

## Code upgrade

The step for the upgrade of AIF code upgrades existing Axd \<Document\> classes and methods. During the code upgrade, the following classes are upgraded:

  - The Axd \<Document\> classes that are included with Microsoft Dynamics AX

  - Custom Axd \<Document\> classes

  - Custom classes that implement the AifServicable interface

## Data upgrade

During the data upgrade, AIF data in the Microsoft Dynamics AX database is upgraded. Configuration settings for AIF endpoints are copied to configuration settings for integration ports.

## After the upgrade

The following table describes how key concepts and configuration settings change when you upgrade from Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Microsoft Dynamics AX 2009 feature</p></th>
<th><p>Microsoft Dynamics AX 2012 feature</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AIF endpoints</p></td>
<td><p>Integration ports</p></td>
<td><p>The concept of integration ports replaces the concept of AIF endpoints. The <strong>Inbound ports</strong> form and the <strong>Outbound ports</strong> form replace the AIF configuration forms. Endpoints that exposed the Microsoft Dynamics AX functionality are converted to inbound integration ports. Endpoints that submitted messages are converted to outbound integration ports.</p>
<p>AIF endpoints become integration ports that have a similar name. The upgrade framework combines the endpoint name and the company name to create the name of the integration port. For example, an endpoint in CompanyB that is named EndpointA becomes an integration port that is named EndpointACompanyB.</p></td>
</tr>
<tr class="even">
<td><p>Endpoint constraints</p></td>
<td><p>This feature is not converted.</p></td>
<td><p>Information about endpoint constraints is not copied to Microsoft Dynamics AX 2012. You must use the legal values framework and the forms for inbound and outbound integration ports to configure constraints. Configure each integration port to apply service and parameter restrictions.</p></td>
</tr>
<tr class="odd">
<td><p>Endpoint data and action policies</p></td>
<td><p>The schema and operation constraints are applied to the integration ports.</p></td>
<td><p>Information about data and action policies is not copied. In Microsoft Dynamics AX 2009, data and action policies were applied at the action level. In Microsoft Dynamics AX 2012, data and action policies are applied at the level of the integration port. Therefore, you must use the forms for inbound and outbound integration ports to define your data and action policies after the upgrade.</p>
<div class="alert">

> [!NOTE]
> <P>In earlier versions of Microsoft Dynamics AX, you were required to assign data policies to each endpoint action policy. In Microsoft Dynamics AX 2012, the configuration of data policies is optional.</P>


</div></td>
</tr>
<tr class="even">
<td><p>AIF adapters</p></td>
<td><p>Integration ports</p></td>
<td><p>Information about AIF adapters is not copied. Use the forms for integration ports to associate adapters with integration ports.</p></td>
</tr>
<tr class="odd">
<td><p>AIF channels</p></td>
<td><p>Address of integration ports</p></td>
<td><p>Information about AIF channels is not copied. Use the forms for inbound and outbound integration ports to configure the address and response address for each integration port.</p>
<p>In earlier versions of Microsoft Dynamics AX, you could associate an endpoint with multiple channels or addresses. In Microsoft Dynamics AX 2012, each integration port has one address for inbound messages and one address for responses.</p></td>
</tr>
<tr class="even">
<td><p>AIF pipelines</p></td>
<td><p>Integration port pipelines</p></td>
<td><p>AIF pipelines are automatically upgraded to integration port pipelines.</p></td>
</tr>
<tr class="odd">
<td><p>Service code attributes</p></td>
<td><p>Microsoft Dynamics AX 2012 services framework</p></td>
<td><p>During the upgrade process, the service code is marked with the appropriate attributes, such as create, read, or find. This step enables the auto-inference feature in Microsoft Dynamics AX 2012 to work with the upgraded code.</p>
<div class="alert">

> [!IMPORTANT]
> <P>You must configure each upgraded service to assign appropriate attributes. For more information, see the next row.</P>


</div></td>
</tr>
<tr class="even">
<td><p>The configuration is always company-specific.</p></td>
<td><p>By default, the configuration is not company-specific.</p></td>
<td><p>In earlier versions of Microsoft Dynamics AX, each AIF endpoint was associated with a specific company. In Microsoft Dynamics AX 2012, integration ports do not have to be associated with a specific company. However, you can use the forms for inbound and outbound integration ports to restrict service calls to a specific company. For an inbound message, the services framework retrieves the company ID from the message header. If the message header does not contain a company ID, the services framework uses the default company ID that is associated with the user who submitted the message.</p></td>
</tr>
<tr class="odd">
<td><p>Service reference</p></td>
<td><p>Microsoft Visual Studio project</p></td>
<td><p>In Microsoft Dynamics AX 2012, references to external web services are no longer directly added to the AOT. Instead, these references should be created in a Visual Studio project which can then be added to the AOT.</p>
<p>It is possible to import service references into Microsoft Dynamics AX 2012 from Microsoft Dynamics AX 2009. If you choose to do this, you may see the following errors during the importing process. You can safely ignore these errors and use the service reference:</p>
<ul>
<li><p>Specified web references root directory does not exist.</p></li>
<li><p>.NET assembly is locked by the AOS. Restart the AOS to load the new assembly.</p></li>
</ul></td>
</tr>
</tbody>
</table>


## After you upgrade

After you upgrade, you must configure the SysEntryPointAttribute attribute and validate the migration of AIF endpoints.

## Configure SysEntryPointAttribute

Microsoft Dynamics AX 2012 does not automatically assign the SysEntryPointAttribute attribute to service classes that are upgraded. Follow these steps for each service that you are upgrading.

1.  In the AOT, expand the **Services** node, and find the service that is being upgraded. Open the **Properties** pane, find the corresponding class name for the service, and make a note of the class name.

2.  In the AOT, expand the **Classes** node, and find the entry for the class that you found in the previous step.

3.  For each service operation in the class, add a SysEntryPointAttribute attribute that uses a value of true or false. We recommend that you set the value to true, so that the service operation accepts the permissions that are assigned to it by the role-based security framework in Microsoft Dynamics AX.
    
    The following example code shows how to add the attribute to the create operation of the SalesSalesOrderService class.
    
    ``` 
     [AifDocumentCreateAttribute, SysEntryPointAttribute(true)] 
    public AifEntityKeyList create(SalesSalesOrder _salesSalesOrder) 
    { return this.createList(_salesSalesOrder); }
    ```

## Validate the migration of AIF endpoints

Use the Microsoft Dynamics AX 2012 forms for inbound and outbound integration ports to validate and configure the AIF endpoints that you migrated.

1.  Open the Microsoft Dynamics AX client.

2.  Initialize AIF to register adapters and services:
    
    1.  Click **System administration** \> **Setup** \> **Checklists** \> **Initialization checklist**.
    
    2.  Expand the **Initialize system** node.
    
    3.  Click **Set up Application Integration Framework**.

3.  Open each form for the configuration of integration ports:
    
    1.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Inbound ports**.
    
    2.  Click **System administration** \> **Setup** \> **Services and Application Integration Framework** \> **Outbound ports**.

4.  Review the list of integration ports to make sure that the AIF endpoints have been migrated as integration ports.

5.  For each integration port, validate the migrated settings, and provide any settings that were not migrated:
    
    1.  In the **Address** group, select an appropriate adapter in the **Adapter** field.
    
    2.  Click **Configure** to configure the adapter that you selected.
    
    3.  In the **URI** field, select an appropriate value for the URI.
    
    4.  Expose the service operations. Select **Expose service operations**, and then click **Service operations**.
    
    5.  Manually configure data policies and legal values. Select **Customize documents**, and then click **Data policies**.
    
    6.  Use the **Processing options** FastTab to configure processing settings. Processing settings include settings that control the behavior when errors are encountered in a batch. These settings also control the preprocessing of requests and post-processing of responses.
    
    7.  Use the **Troubleshooting** FastTab to configure troubleshooting settings. Troubleshooting settings include settings that control the logging mode and the propagation of errors.
    
    8.  Use the **Security** FastTab to configure security settings. Security settings include settings that control restrictions on authorized users and trusted intermediary users. These settings also control whether the integration port is restricted to a specific company.
    
    9.  In a browser, open the Microsoft Dynamics AX Web service, and confirm that the Web server returns the WSDL page. Use the following URL to open the Web service:
        
            net.tcp:// AOS_SERVICE_HOST/DynamicsAx/Services/ServiceName?wsdl
        

        > [!NOTE]
        > <P>By default, Microsoft Dynamics AX uses port 8081.</P>



## For more information

For details about how to configure integration ports in services and AIF, see the documentation on the [TechNet Web site](https://go.microsoft.com/fwlink/?linkid=217341).

  


