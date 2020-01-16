---
title: Metadata Service
TOCTitle: Metadata Service
ms:assetid: c736aa71-20e8-4d7f-8270-ca393aafc8a0
ms:mtpsurl: https://technet.microsoft.com/library/Gg880762(v=AX.60)
ms:contentKeyID: 35251136
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Metadata Service 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The metadata service returns information about AOT objects in Microsoft Dynamics AX such as tables, services, extended data types (EDTs), enums, and so on. The metadata service is:

  - automatically installed

  - by default, hosted by the Application Object Server (AOS)

  - always available

  - a Windows Communication Foundation (WCF) service that adheres to WCF protocols and standards

## How the Metadata Service Works

The metadata service has two types of service operations:

  - Service operations that return names or keys – these service operations return the names or keys for all queries, tables, menus, and so on. The names are returned in a string array. The name of the metadata service operation specifies the names that are returned. For example, the GetQueryNames method returns a string array of names for all the queries in the installation.

  - Service operations that return metadata – these service operations take a string array of names, an integer array of IDs, or an array of key objects (such as MenuItemKeys\[ \]) and return the metadata for those objects. Each of these service operations returns an array of metadata objects.
    
    For example, the signature of the service operation to retrieve query metadata is: QueryMetadata\[\] GetQueryMetadataByName(string\[\] queryNames). The QueryMetadata objects that are returned in the QueryMetadata\[\] array derive from the [QueryMetadata](https://technet.microsoft.com/library/hh151954\(v=ax.60\)) class.

To use the metadata service, you call the service operation to retrieve the object names. Then, you call the metadata service operation and pass in the name or names to retrieve the metadata for those objects as shown in the following code:

``` csharp
    static void Main(string[] args)
        {
            AxMetadataServiceClient client = new AxMetadataServiceClient();

            try
            {

                 // Gets the names of all services in a string array.
                string[] services = client.GetServiceNames();

                // Loops through all the service names and prints them to the console.
                foreach (string serviceName in services)
                {
                    Console.WriteLine("Service named: {0}", serviceName);
                }

                // Gets the name of the first service.
                string[] serviceNames = new string[1];
                serviceNames[0] = services[0];


                // Gets the metadata for the first service.
                ServiceMetadata[] serviceMetadata = client.GetServiceMetadataByName(serviceNames);


                client.Close();
            }
            catch
            {
                client.Abort();
                throw;
            }

        }
```

For more information about calling the metadata service, see [Walkthrough: Calling the Metadata Service](walkthrough-calling-the-metadata-service.md).

The following table lists the metadata service operations that return object names or keys.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service operation</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>string[] GetQueryNames()</p></td>
<td><p>Returns the names for all queries defined in the AOT.</p></td>
</tr>
<tr class="even">
<td><p>string[] GetTableNames()</p></td>
<td><p>Returns the names for all tables defined in the AOT.</p></td>
</tr>
<tr class="odd">
<td><p>string[] GetMenuNames()</p></td>
<td><p>Returns the names for all menus defined in the AOT.</p></td>
</tr>
<tr class="even">
<td><p>MenuItemKey[] GetMenuItemKeys()</p></td>
<td><p>Returns the keys for all menu items.</p></td>
</tr>
<tr class="odd">
<td><p>string[] GetServiceNames()</p></td>
<td><p>Returns the fully-qualified, unique XML names for all published services in Microsoft Dynamics AX. For example, http://schemas.microsoft.com/dynamics/2008/01/services/SalesOrderService.</p></td>
</tr>
<tr class="even">
<td><p>string[] GetService GroupNames()</p></td>
<td><p>Returns all the names for service groups found in the Service Groups node in the AOT.</p></td>
</tr>
<tr class="odd">
<td><p>string[] GetExtendedDataTypeNames()</p></td>
<td><p>Returns the names for all EDTs defined in the AOT.</p></td>
</tr>
<tr class="even">
<td><p>string[] GetEnumNames()</p></td>
<td><p>Returns the names for all enums defined in the AOT.</p></td>
</tr>
<tr class="odd">
<td><p>string[] GetLabelNames()</p></td>
<td><p>Returns the names for all labels defined in the label file. The labels are returned in the @SYSnnnn format.</p></td>
</tr>
<tr class="even">
<td><p>string[] GetInfoPartNames()</p></td>
<td><p>Returns the names for all info parts.</p></td>
</tr>
<tr class="odd">
<td><p>string[] GetWebMenuNames()</p></td>
<td><p>Returns the names for all web menus.</p></td>
</tr>
<tr class="even">
<td><p>WebMenuItemKeys[] GetWebMenuItemKeys()</p></td>
<td><p>Returns the keys for all web menu items.</p></td>
</tr>
<tr class="odd">
<td><p>string[] GetListPageNames()</p></td>
<td><p>Returns the names for all list pages.</p></td>
</tr>
<tr class="even">
<td><p>string[] GetCueNames()</p></td>
<td><p>Returns the names for all cues.</p></td>
</tr>
<tr class="odd">
<td><p>string[] GetCueGroupNames()</p></td>
<td><p>Returns the names for all cue groups.</p></td>
</tr>
<tr class="even">
<td><p>string[] GetFormPartNames()</p></td>
<td><p>Returns the names for all form parts.</p></td>
</tr>
<tr class="odd">
<td><p>string[] GetWebControlNames()</p></td>
<td><p>Returns the names for all web controls.</p></td>
</tr>
<tr class="even">
<td><p>string[] GetWebPageDefinitioNodeNames()</p></td>
<td><p>Returns the names for all web page definition nodes.</p></td>
</tr>
</tbody>
</table>


The following table lists the metadata service operations that return object metadata.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Service operation</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>QueryMetadata[] GetQueryMetadataByName(string[] queryNames)</p></td>
<td><p>Takes a string array of query names and returns the metadata for the queries with the specified names.</p></td>
</tr>
<tr class="even">
<td><p>TableMetadata[] GetTableMetadataByName(string[] tableNames)</p></td>
<td><p>Takes a string array of table names and returns the metadata for tables with the specified names.</p></td>
</tr>
<tr class="odd">
<td><p>TableMetadata[] GetTableMetadataByID(int[] tableIds)</p></td>
<td><p>Takes an integer array of table IDs and returns the metadata for all tables with the specified IDs.</p></td>
</tr>
<tr class="even">
<td><p>TableMetadata[] GetTableMetadataByTypeDiscriminatorValue(long[] typeDiscriminatorValues)</p></td>
<td><p>Takes an array of type discriminator values and returns metadata for all tables that have that discriminator value.</p></td>
</tr>
<tr class="odd">
<td><p>MenuMetadata[] GetMenuMetadataByName(string[] menuNames)</p></td>
<td><p>Takes a string array of menu names and returns the metadata for all menus with the specified names.</p></td>
</tr>
<tr class="even">
<td><p>MenuItemMetadata[] GetMenuItemMetadata(MenuItemKey[] menuItemKey)</p></td>
<td><p>Takes an array of menu item keys and returns the metadata for the specified menu items. Menu item keys are retrieved by calling the GetMenuItemKeys service operation.</p></td>
</tr>
<tr class="odd">
<td><p>ServiceMetadata[] GetServiceMetadataByName(string[] serviceNames)</p></td>
<td><p>Takes a string array of service names and returns the metadata for all services that have the specified names.</p></td>
</tr>
<tr class="even">
<td><p>ServiceGroupMetadata[] GetServiceGroupMetadataByName(string[] serviceGroupNames)</p></td>
<td><p>Takes a string array of service group names and returns the metadata for all service groups that have the specified names.</p></td>
</tr>
<tr class="odd">
<td><p>ExtendedDataTypeMetadata[] GetExtendedDataTypeMetadataByID(int[] edtIds)</p></td>
<td><p>Takes an integer array of extended data type IDs and returns the metadata for all extended data types with the specified IDs.</p></td>
</tr>
<tr class="even">
<td><p>ExtendedDataTypeMetadata[] GetExtendedDataTypeMetadataByName(string[] edtNames) ()</p></td>
<td><p>Takes a string array of extended data type names and returns the metadata for all EDTs with the specified names.</p></td>
</tr>
<tr class="odd">
<td><p>EnumMetadata[] GetEnumMetadataByID(int[] enumIDs)</p></td>
<td><p>Takes a string array of enum IDs and returns the metadata for all the enums with the specified names.</p></td>
</tr>
<tr class="even">
<td><p>EnumMetadata[] GetEnumMetadataByName(string[] enumNames)</p></td>
<td><p>Takes a string array of enum names and returns the metadata for all enums with the specified names.</p></td>
</tr>
<tr class="odd">
<td><p>LabelMetadata[] GetLabelMetadataById(string[] labelIds)</p></td>
<td><p>Takes a string array of label IDs and returns the metadata for the specified labels. The label IDs are in the format @SYSnnnn and the metadata is returned in the installation default language.</p></td>
</tr>
<tr class="even">
<td><p>LabelMetadata[] GetLabelMetadataForLanguageById(string languageId, string[] labelIDs)</p></td>
<td><p>Takes a string variable that contains the language ID and a string array of label IDs and returns the metadata for the specified labels in the specified language. The label IDs are in the format @SYSnnnn. The language ID is retrieved by calling the GetLanguages service operation.</p></td>
</tr>
<tr class="odd">
<td><p>WebMenuMetadata[] GetWebMenuMetadataByName(string[] menuNames)</p></td>
<td><p>Takes a string array of web menu names and returns the metadata for all web menus with the specified names.</p></td>
</tr>
<tr class="even">
<td><p>WebMenuItemMetadata[] GetWebMenuItemMetadata(WebMenuItemKey[] webMenuKey)</p></td>
<td><p>Takes an array of web menu item keys and returns the metadata for all web menu items with the specified keys. The web menu item keys are retrieved by calling the GetWebMenuItemKeys service operation.</p></td>
</tr>
<tr class="odd">
<td><p>InfoPartMetadata[] GetInfoPartMetadataByName(string[] infoPartNames)</p></td>
<td><p>Takes a string array of info part names and returns the metadata for all info part names with the specified names.</p></td>
</tr>
<tr class="even">
<td><p>DimensionMetadata[] GetDimensionMetadataByID(int[] dimensionIDs)</p></td>
<td><p>Takes a string array of dimension IDs and returns the metadata for all the dimensions with the specified names.</p></td>
</tr>
<tr class="odd">
<td><p>DimensionMetadata[] GetDimensionMetadataByName(string[] dimensionNames)</p></td>
<td><p>Takes a string array of dimension names and returns the metadata for dimensions with the specified names.</p></td>
</tr>
<tr class="even">
<td><p>ListPageMetadata[] GetListPageMetadataByName(string[] listPageNames)</p></td>
<td><p>Takes a string array of list page names and returns the metadata for list pages with the specified names.</p></td>
</tr>
<tr class="odd">
<td><p>CueMetadata[] GetCueMetadataByName(string[] cueNames)</p></td>
<td><p>Takes a string array of cue names and returns the metadata for cues with the specified names.</p></td>
</tr>
<tr class="even">
<td><p>CueGroupMetadata[] GetCueGroupMetadataByName(string[] cueGroupNames)</p></td>
<td><p>Takes a string array of cue group names and returns the metadata for cue groups with the specified names.</p></td>
</tr>
<tr class="odd">
<td><p>FormPartMetadata[] GetFormPartMetadataByName(string[] formPartNames)</p></td>
<td><p>Takes a string array of form part names and returns the metadata for form parts with the specified names.</p></td>
</tr>
<tr class="even">
<td><p>WebControlMetadata[] GetWebControlMetadataByName(string[] webControlNames)</p></td>
<td><p>Takes a string array of web control names and returns the metadata for web controls with the specified names.</p></td>
</tr>
<tr class="odd">
<td><p>WebPageDefinitionMetadata[] GetWebPageDefinitionMetadataByName(string[] webPageDefinitionNodeNames)</p></td>
<td><p>Takes a string array of web page definition node names and returns the metadata for web page definition nodes with the specified names.</p></td>
</tr>
</tbody>
</table>


These service operations return an array of metadata objects. The metadata object contains the actual metadata. The type of metadata object returned depends on the service operation. For example, the GetQueryMetadataByName service operation returns an array of QueryMetadata objects. The QueryMetadata object contains the metadata for a single query and this metadata is exposed through the object methods and properties. For example, the QueryMetadata object has properties such as Name, QueryType, DataSources, and AllowCrossCompany.

The metadata classes reside in the [Microsoft.Dynamics.AX.Framework.Services.Metadata.Contracts](https://technet.microsoft.com/library/hh187940\(v=ax.60\)) namespace. Some commonly used top-level metadata classes include the following:

  - [DimensionMetadata](https://technet.microsoft.com/library/hh130620\(v=ax.60\))

  - [EnumMetadata](https://technet.microsoft.com/library/hh186490\(v=ax.60\))

  - [FieldMetadata](https://technet.microsoft.com/library/hh186915\(v=ax.60\))

  - [FormControlMetadata](https://technet.microsoft.com/library/hh152904\(v=ax.60\))

  - [LabelMetadata](https://technet.microsoft.com/library/hh131663\(v=ax.60\))

  - [ListPageMetadata](https://technet.microsoft.com/library/hh130921\(v=ax.60\))

  - [MenuMetadata](https://technet.microsoft.com/library/hh186739\(v=ax.60\))

  - [MenuItemMetadata](https://technet.microsoft.com/library/hh152260\(v=ax.60\))

  - [QueryMetadata](https://technet.microsoft.com/library/hh151954\(v=ax.60\))

  - [ServiceMetadata](https://technet.microsoft.com/library/hh152855\(v=ax.60\))

  - [ServiceGroupMetadata](https://technet.microsoft.com/library/hh153356\(v=ax.60\))

  - [TableMetadata](https://technet.microsoft.com/library/hh130058\(v=ax.60\))

### Metadata Service Architecture

The metadata service is a WCF service that is contained in the Microsoft.Dynamics.AX.Services.Metadata.Service.dll assembly. This assembly is located in the server Bin directory. Depending on your configuration, the assembly is located in a directory such as C:\\Program Files\\Microsoft Dynamics AX\\\<version\>\\Server\\MicrosoftDynamicsAX\\Bin.

The metadata service has the following configuration default values:

  - It is hosted by the AOS on port 8201 and the URL is net.tcp://servername:8201/DynamicsAx/Services/MetadataService.

  - The service WSDL URL is http://servername:8101/DynamicsAx/Services/MetadataService

  - It uses the netTcpBinding binding.

These settings will vary depending on what port number the service port and the WSDL port have been configured to use.

The configuration settings for the metadata service are found in the Ax32Serv.config file which is also located in the server Bin directory.

## Metadata Service Security

Only authenticated Microsoft Dynamics AX users can access the metadata service. In order to retrieve data by using the metadata service, you must have a valid username in Microsoft Dynamics AX. The metadata service uses Windows integrated security. Therefore, when a caller invokes the metadata service, the system verifies the credentials under which the calling client is running and verifies that the username is a valid Microsoft Dynamics AX user.

The metadata service is available to all authenticated users. Therefore, all security roles have the same access level to metadata information.

## See also

[AIF System Services](aif-system-services.md)

[Metadata Service Class Diagrams](metadata-service-class-diagrams.md)

[Walkthrough: Calling the Metadata Service](walkthrough-calling-the-metadata-service.md)

[Walkthrough: Using the Metadata Service to Get Table Field Labels](walkthrough-using-the-metadata-service-to-get-table-field-labels.md)

