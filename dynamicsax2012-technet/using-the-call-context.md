---
title: Using the Call Context
TOCTitle: Using the Call Context
ms:assetid: b905d5be-8d2b-4937-90a7-e90e77d5d43d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh582244(v=AX.60)
ms:contentKeyID: 39533580
ms.date: 04/17/2013
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Using the Call Context [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Call context values are exposed by all Microsoft Dynamics AX services to enable service clients to pass context information specific to Microsoft Dynamics AX. The call context values contain information that is used in the execution of the service call such as a unique message ID and the Microsoft Dynamics AX user and company. These values are sent with Application Integration Framework (AIF) messages as part of the message header.

If you do not specify any values for the call context, the system generates defaults. To use the default values for the call context, you can pass null for the first parameter of the call to the method that calls the service operation, or you can leave the tags out of the message header.


> [!WARNING]
> <P>The data contract for the call context is not published as part of the Web Service Description Language (WSDL) files for the query service and the metadata service. If you want to set any call context values for these services, you must create the code to set the values for the system service call.</P>




> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed for Microsoft Dynamics AX 2012 R2.</P>



## CallContext Properties

The following table lists the CallContext properties and their values. All of the properties have default values. That is, if you do not specifically set the CallContext properties when you call a service operation, the default values are used.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Property</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Message ID</p></td>
<td><p>This is the GUID that uniquely identifies each document.</p>
<p>If you do not specify a message ID, the system generates one. However, if you want to identify a particular message for debugging, you must specify the message ID as part of the call context.</p>
<p>For information about how to use the message ID to check for duplicate messages, see <a href="how-to-enable-checking-for-duplicate-messages.md">How to: Enable Checking for Duplicate Messages</a>.</p></td>
</tr>
<tr class="even">
<td><p>LogonAsUser</p></td>
<td><p>This is the Microsoft Dynamics AX user who performs the service operation. It uses the submitting user (calling user) in the format “domain\user.”</p>
<p>If LogonAsUser is not specified then the user who makes the service operation call is used. The default user depends on the adapter that is selected. For example, when you use the file system adapter the default user is the owner of the folder where the file resides.</p>
<p></p>
<div class="alert">

> [!IMPORTANT]
> <P>This user must have sufficient permissions in Microsoft Dynamics AX to perform the requested operation. There are significant security considerations for this parameter. For more information, see <A href="services-and-aif-security-and-protection.md">Services and AIF security and protection</A>.</P>


</div></td>
</tr>
<tr class="odd">
<td><p>Company</p></td>
<td><p>This is the Microsoft Dynamics AX company for the data on which the service operation is performed.</p>
<p>If Company is not specified then the calling user’s default company is used.</p></td>
</tr>
<tr class="even">
<td><p>Language</p></td>
<td><p>This is the Microsoft Dynamics AX LanguageID for the language that is used to display messages.</p>
<p>The default value for Language is “en-us.”</p></td>
</tr>
<tr class="odd">
<td><p>Partition Key</p></td>
<td><p>This value identifies the partition that contains data that is referenced by the service operation.</p>
<p>The default value for PartitionKey is the default partition set for the calling user.</p>
<p>For more information about data partitions, see <a href="data-partitioning-architecture.md">Data partitioning architecture</a>.</p>
<p>This option is available only if Microsoft Dynamics AX 2012 R2 is installed.</p></td>
</tr>
</tbody>
</table>


## Using the Call Context Values in a Synchronous Call

For any document service or custom service, you must create an integration port to expose the service operation. For synchronous exchanges that use the **NetTcp** or **Http** adapters, you add the service reference to the external client project at design time by using the **WSDL URI** on the **Inbound ports** form.

### Setting the Call Context Values

In the following example, you must first complete the following steps:

1.  Create an inbound port that uses the **NetTcp** adapter. For more information, see [Create, edit, or delete an enhanced integration port](create-edit-or-delete-an-enhanced-integration-port.md).

2.  Expose the create operation for the Sales Order Service as **SalesSalesOrderService.create**. For more information, see [Customize service contracts](customize-service-contracts.md).

3.  Add the service reference for the Sales Order Service to a project in Visual Studio using the WSDL URI that is created when you activate the port. For more information, see [Consuming Microsoft Dynamics AX Services from an External Client](consuming-microsoft-dynamics-ax-services-from-an-external-client.md).

The following code example illustrates setting the call context values in C\# in preparation for calling the create method on the sales order document service.

``` csharp

// Create an instance of the SalesOrderServiceClient.
            SalesOrderServiceClient proxy = new SalesOrderServiceClient();

// Create an instance of the CallContext class.
CallContext context = new CallContext();

// Set the value for Company.
context.Company = "dat";

// Set the value for LogonAsUser.
context.LogonAsUser = "yourdomain\userid";

// Set the value for language.
context.Language = "en-us";

 //Create an instance of the document class AxdSalesOrder.

            AxdSalesOrder salesOrder = new AxdSalesOrder();


```

The following example continues the example above and illustrates a call to the create method to create a sales order using the Sales Order Service. The code for setting the individual values in the sales order has been omitted.

    // Call the create method on the service and pass the CallContext and
    // the initialized sales order document. 
    
    EntityKey[] returnedSalesOrderEntityKey = proxy.create(context, salesOrder);

## Using the Call Context Values in the Message Header

The following XML illustrates the call context values in the AIF message header.

    <Header>
        <MessageId>MessageId1</MessageId>
        <LogonAsUser>domain\user1</LogonAsUser>
        <PartitionKey>PartitionKey1</PartitionKey>
        <Company>Company1</Company>
        <Action>create</Action>
    
      </Header>


> [!NOTE]
> <P>The &lt;PartitonKey&gt; tag is only available if Microsoft Dynamics AX 2012 R2 is installed.</P>



## See also

[Consuming Microsoft Dynamics AX Services from an External Client](consuming-microsoft-dynamics-ax-services-from-an-external-client.md)

[Walkthrough: Exchanging documents by using the NetTcp adapter](walkthrough-exchanging-documents-by-using-the-nettcp-adapter.md)

[Message Header](message-header.md)

[Query Service](query-service.md)

[Metadata Service](metadata-service.md)

