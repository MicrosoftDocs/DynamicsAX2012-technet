---
title: Troubleshoot services and AIF
TOCTitle: Troubleshoot services and AIF
ms:assetid: cde3c0a1-cd86-4da7-ae96-af4e380f2d5f
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa548693(v=AX.60)
ms:contentKeyID: 39056467
ms.date: 04/21/2014
mtps_version: v=AX.60
---

# Troubleshoot services and AIF [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to troubleshoot common issues with document exchanges through the Application Integration Framework (AIF).

## Microsoft Visual Studio error messages when consuming services exposed by using the NetTcp adapter

When you expose a service by using the NetTcp adapter, you can consume the service by adding a service reference in Visual Studio. If you specify the service reference by using an Internationalized Domain Name (IDN) you may see error messages and the service reference is not added. To enable recognition of IDN names, you must specify \<idn enabled=”All”/\> for the \<uri\> element in the application configuration file. The following code example shows a configuration used by the Uri class to support parsing of International Resource Identifiers (IRI) and support for IDN names.

    <configuration>
      <uri>
        <idn enabled="All" />
        <iriParsing enabled="true" />
      </uri>
    </configuration>

For more information, see [\<idn\> Element (Uri Settings)](http://go.microsoft.com/fwlink/?linkid=394968%26clcid=0x409).

## Warning message: An error occurred while creating AifWebsites entry –or– Error message: Cannot create a record in Web sites (AifWebsites)

When you install web services on Internet Information Services (IIS), a record for the new website is added to AifWebsites table. If you uninstall web services on IIS, this record is not deleted from the table. This record may cause a warning to be displayed if you reinstall web services on IIS. You can manually delete the record from the AifWebsites table or simply ignore the warning.

## Error message: Call to SSPI failed; see inner exception

You might encounter this error message when you change the Application Object Server (AOS) account. For information about resolving this issue in several different configurations, see [Change the account used by AOS](change-the-account-used-by-aos.md).

## Error message: System.ServiceModel.ActionNotSupportedException

If you make any changes to a service in a service group, you must redeploy the entire group. If you do not redeploy the service group, you may see messages resembling the following when you call the service:

System.ServiceModel.ActionNotSupportedException: The message with Action 'http://schemas.microsoft.com/dynamics/2011/01/services/TSTimesheet/getLabelTranslations' cannot be processed at the receiver, due to a ContractFilter mismatch at the EndpointDispatcher. This may be because of either a contract mismatch (mismatched Actions between sender and receiver) or a binding/security mismatch between the sender and the receiver.  Check that sender and receiver have the same contract and the same binding (including security requirements, e.g. Message, Transport, None).

To redeploy a service group, right-click the name of the service group in the **Service Groups** node of the AOT and then click **Deploy Service Group**.

## Cannot access a web service

You must set the appropriate permissions for any new virtual directory in IIS so that Microsoft Dynamics AX can access the file share. The group that is named Microsoft Dynamics AX Web Service Administrators must have full access to the new virtual directory and file share. If this group does not exist as a local group on the computer, you must create it. You must then add, as a user, the domain account for all AOS instances that require access.

## Message processing is interrupted

If you activate or deactivate an integration port, all integration ports on the instance of AOS are reactivated. Do not activate or deactivate any integration port while messages are being processed.

## File system adapter cannot open file

Directories that are accessed by the file system adapter must grant appropriate access to the domain account under which the AOS runs. If the AOS runs under the NETWORK SERVICE account, you must grant permissions for that specific account. For example, granting full permissions to Everyone will not enable the file system adapter to access the files in the directory or network share accessed by the file system adapter if the AOS runs under the NETWORK SERVICE account.


> [!IMPORTANT]
> <P>We strongly recommend that you use a domain account or a managed service account in a production environment. Use the Network Service account only in development and testing environments. See <A href="create-service-accounts.md">Create service accounts</A>.</P>



## Data policies do not work

When you define a required element as part of a data policy, you must also select **Validate document XML** on the **Processing options** FastTab of the integration port. When XML validation is disabled, AIF does not apply data policies, which may cause unexpected results in some scenarios.

## Upon error in batched requests setting does not work

This setting applies only when you use the file system adapter.

## Cannot add a new transform in the Manage transforms form

You must be logged into Windows Server as an administrator to add a new transform.

## Transforms do not work with synchronous adapters

For synchronous messages, use pipelines for preprocessing and post-processing of AIF messages. Use the **Pipeline XSLT transform** component to apply XSLT transforms in a pipeline or create a .NET assembly-based transform.

## Document filters do not work

Document filters are applied only to documents that have been configured for change tracking. Change tracking must be enabled for the database tables that the document service uses. For more information about how to enable change tracking, see [Configuring and Managing Change Tracking](http://go.microsoft.com/fwlink/?linkid=227482).

## Document versions are not logged

Document versions are not logged for each integration-port-level transform. Document versions are logged only for pipeline components. For example, you can use an XSLT in a pipeline if you want to log the various document versions that are the result of transformations.

## Service operation getChangedKeys returns no entity keys

To use this service operation, you must create at least one document filter. See [Configure processing options](configure-processing-options.md).

## Error message: The open operation did not complete within the allotted timeout

You can receive this error message when the timeout value specified in the Windows Communication Foundation (WCF) configuration is exceeded. To correct this problem, do not leave WCF connections open once you are finished using them. For example, be sure to call the Close method on client instances before they go out of scope. For an example of how to create, use, and close a client object, see [Walkthrough: Exchanging documents by using the NetTcp adapter](walkthrough-exchanging-documents-by-using-the-nettcp-adapter.md).

If you continue to experience timeout errors, change the timeout settings in the WCF adapter configuration in the integration port configuration form.

## Files that have file-name extensions other than .xml do not work for outbound exchanges

The file system adapter in AIF does not support file types other than XML for outbound integration scenarios. Files handled by integration ports that use the file system adapter must use the .xml file-name extension for outbound files.

## Deleting a service requires a “Generate Full CIL” recompile

If you delete a service from the Application Object Tree (AOT), and then you add the service back to the AOT, you must perform a full generation of the common intermediate language (CIL) for the Microsoft .NET Framework. Use the **Generate Full CIL** option on the **Build** menu in the development workspace. For more information, see [X++ Compiled to .NET CIL](https://technet.microsoft.com/en-us/library/gg839855\(v=ax.60\)).

## Additional service operations must be added to the service node separately

The AIF Document Wizard adds operations to the **Service** node in the AOT only one time. For more information, see [Creating New Document Services](creating-new-document-services.md). If you update the service by using the **Update document service** form, you update the Service class but do not change any information under the **Service** node in the AOT. To make new service operations available, you must add them manually to the **Service** node. To open the **Update document service** form, open a development workspace, and then click **Tools** \> **Application Integration Framework** \> **Update document service**.

## AIF does not retrieve RecVersion for documents that contain views

The RecVersion field is not retrieved for documents that contain views. If you set the CheckInvalidFieldAccess database configuration parameter when you test service operations on documents that contain views, the service operations stop, and generate a stack trace or other errors. Therefore, do not set CheckInvalidFieldAccess in a production environment. If document consumers require the RecVersion field to support business logic, you can define a new field in your document that is named myRecVersion. You can then map the myRecVersion field to the RecVersion field of one of the underlying tables in the view. For more information, see [Tables Overview](https://technet.microsoft.com/en-us/library/bb314725\(v=ax.60\)) and [View Overview](https://technet.microsoft.com/en-us/library/cc634339\(v=ax.60\)).

## Do not add custom services and document services to the same integration port

If services that use different serializers, such as XmlSerializer and DataContractSerializer, are hosted on the same port, client proxies can be generated that have duplicate types. In Microsoft Dynamics AX, this situation can occur when service operations for document services and custom services are added to the same port. In this situation, duplicate types can be generated for some of the classes, such as CallContext.

To avoid this situation, always host service operations for custom services and document services on different ports. For more information, see [Managing integration ports](managing-integration-ports.md).

## Error during schema generation when elements in parent and child tables have the same name

When you create tables that will be used in data exchanges, make sure that you use unique names for all fields and data sources. Otherwise, schema generation may fail. For example, if you create tables in a parent/child relationship, and a field in the parent table has the same name as a data source in the child table, schema generation fails, and you receive the following message in the Infolog:

XSD schema contains errors. Multiple definition of element 'http://schemas.microsoft.com/dynamics/2008/01/documents/Query1Document:SubEntity2' causes the content model to become ambiguous. A content model must be formed such that during validation of an element information item sequence, the particle contained directly, indirectly or implicitly therein with which to attempt to validate each item in the sequence in turn can be uniquely determined without examining the content or attributes of that item, and without any information about the items in the remainder of the sequence.

## HTTP is supported only for Internet Information Services

HTTP is supported only in exchanges where Internet Information Services (IIS) is set up. If you use HTTP in an exchange that does not include IIS, AOS may stop, and you may receive an error message that resembles the following message:

An error occurred while receiving the HTTP response to http://localhost-1:8101/DynamicsAx/Services/Endpoints/DocumentManagementService. This could be due to the service endpoint binding not using the HTTP protocol. This could also be due to an HTTP request context being aborted by the server (possibly due to the service shutting down). See server logs for more details.

For more information, see [Install web services on IIS](install-web-services-on-iis.md).

## Outbound messages cannot be delivered by using the MSMQ adapter

If you send an outbound message by using the MSMQ adapter, and the message cannot be delivered for any reason, it goes into the “dead letter queue.” No error log is displayed. To display messages for error conditions when you send messages from Microsoft Dynamics AX by using the Message Queuing transport, you must code the appropriate exception handling from WCF.

## XML schema does not include table fields for which the Visible property is set to No

The AIF Document Service Wizard does not create an entry in the schema for table fields for which the Visible property is set to No, even if the Mandatory property for the fields is set to Yes. These fields, which should never be set by user input, are omitted from the schema. Table fields for which the Visible property is set to No are always set by code that runs in the service. This behavior resembles the behavior of the client. Code in the client sets table fields that are not visible in forms that enable user input.

## Local AOS configuration information that is used for a company

If you try to access data for a company that does not exist on the AOS instance where the integration port for the service is located, you receive an error message. This situation can occur when you move from a development environment to a testing environment, or from testing to production, and different companies are used in each AOS configuration.

To create a service that works in a specific environment, you must create access to the client configuration for that environment in code, and load the company name to use. For more information, see [Manage an AOS configuration](manage-an-aos-configuration.md).


> [!NOTE]
> <P>This situation may occur when you use the Office Add-ins for Microsoft Dynamics AX together with Microsoft Dynamics AX services to import or export data. By default, the Office Add-ins use the local client configuration.</P>



## Always specify SysEntryPointAttribute for services

You must always specify [SysEntryPointAttribute](https://technet.microsoft.com/en-us/library/gg958657\(v=ax.60\)) for service operations. For more information, see [Setting SysEntryPointAttribute for Services](setting-sysentrypointattribute-for-services.md).

The following list shows valid syntax for this security attribute:

  - \[SysEntryPointAttribute(true)\] – Run the service operation by using the caller’s permissions.

  - \[SysEntryPointAttribute(false)\] – Run the service operation without any security restrictions.

If you deploy a port by using a service operation that does not specify SysEntryPointAttribute, you receive an error message that resembles the following message: “SysEntryPointAttribute must be specified on a method exposed as a service operation. Class: AifTestCustomerService, Method: createCustomer.”


> [!NOTE]
> <P>You must specify <A href="https://technet.microsoft.com/en-us/library/gg958657(v=ax.60)">SysEntryPointAttribute</A> for any custom service that you write. The AIF Document Service Wizard adds this attribute to any new document service that you create.</P>



## Data is truncated on a Create or Update operation by document services

If you create or update a field of type str by using a document service operation, and the incoming data string is longer than the field that is defined in the table, the data is truncated. In other words, the data is imported into the field, but any data past the limit for the string length is lost, and you do not receive an error message.

## Fields that are not mandatory, and that have zero or null values are not serialized in outbound transfers

In outbound service operations for documents that are created from Microsoft Dynamics AX tables, AIF does not serialize fields that have null or 0 (zero) values. In other words, the fields do not appear in the outbound XML message. There are two ways to make sure that that a field is serialized:

  - In the code for the service operation, indicate that the field is required. The modified code affects both inbound and outbound transfers, but it does not affect the behavior of the field in forms.

  - In the table, set the **Mandatory** property for the field to **Yes**. Setting the property in the table affects all use of the field, both in forms and in document service operations.

To indicate that the field is required only for the service operation, you must override the AxdBase.initMandatoryFieldsMap method for the document service and declare the field as mandatory in the method. For more information and an example, see initMandatoryFieldsMap.

By setting the **Mandatory** property to **Yes** on the table field, you guarantee that the field is always included in the outbound transfer. This property also enforces the requirement that a non-default value be set for the field when the field is saved to the database. In other words, the field cannot be inserted into the database if the field does not have a valid value. For more information about how to set the **Mandatory** property on table fields, see [Best Practices for Table Field Properties](https://technet.microsoft.com/en-us/library/aa590501\(v=ax.60\)).

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

