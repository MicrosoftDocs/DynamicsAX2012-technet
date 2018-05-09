---
title: 'Walkthrough: Using the Metadata Service to Get Table Field Labels'
TOCTitle: 'Walkthrough: Using the Metadata Service to Get Table Field Labels'
ms:assetid: f1951083-4bb0-4c17-a783-d44eab36fb87
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg848138(v=AX.60)
ms:contentKeyID: 35253368
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Walkthrough: Using the Metadata Service to Get Table Field Labels 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The metadata service is one of the system services exposed by Microsoft Dynamics AX and that adheres to the Windows Communication Foundation (WCF) protocols and standards. This service enables you to retrieve information about AOT objects such as tables, services, extended data types (EDTs), enums, and so on. In this walkthrough, you will call the metadata service from a C\# program and return field names and field labels for all the fields in a particular table as specified by the table ID.

This walkthrough illustrates the following tasks:

  - Add a reference to the metadata service.

  - Call the service and retrieve the metadata.

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX 2012

  - Visual Studio 2010

## Add a Reference to the Metadata Service

In order to call the metadata service, you must first create a project in Visual Studio and add a reference to the service.

### To add a reference to the metadata service

1.  Open Visual Studio and create a new project by selecting **File** \> **New** \> **Project**.

2.  In the **Installed Templates** tree, select **Visual C\#** \> **Windows** and then click the **Console Application** template.

3.  Type a project name such as MetadataSvcGetFieldLabels and then click **OK**.

4.  In Solution Explorer, right-click **References** and select **Add Service Reference**.

5.  In the **Address** Field, enter the URL of the service. For example, http://servername:8101/DynamicsAx/Services/MetadataService.

6.  Click **Go**. In the **Services** tree, you should see the AxMetadataService.

7.  Type MetadataServiceReference in the **Namespace** field and then click **OK**.

## Call the Service and Retrieve the Metadata

Now we will write the code that calls the metadata service and returns the metadata for a single query.

### To call the metadata service

1.  In the Program.cs file, add the following using statements.
    
    ``` csharp
    using System;
    using MetadataSvcGetFieldLabels.MetadataServiceReference;
    ```

2.  In the Program.cs file Main method add the code to call the service. The contents of the Program.cs file should resemble the following:
    
    ``` csharp
    using System;
    using MetadataSvcGetFieldLabels.MetadataServiceReference;
    
    
    namespace MetadataSvcGetFieldLabels
    {
        class Program
        {
            static void Main(string[] args)
            {
                AxMetadataServiceClient client = new AxMetadataServiceClient();
    
                try
                {
                    // The table ID of the SalesTable.
                    int[] tableIDs = new int[1];
                    tableIDs[0] = 366;
    
                    // Gets the table metadata.
                    TableMetadata[] tableMetadata = client.GetTableMetadataById(tableIDs);
                    TableMetadata salesTable = tableMetadata[0];
    
                    foreach (DataFieldMetadata fieldMetadata in salesTable.Fields)
                    {
                        // Print the field name and the label for the field to the console.
                        System.Console.WriteLine("Field named: {0}, Field label: {1}", fieldMetadata.Name, 
                               client.GetLabelMetadataForLanguageById("EN-US", new string[] { fieldMetadata.LabelId })[0].LabelString);
                    }
                    Console.ReadKey(true);
    
                    client.Close();
                }
                catch
                {
                    client.Abort();
                    throw;
                }
            }
         }
     }
    ```

3.  Run the program. The program loops through the fields in the SalesTable table and writes the name of each field and the field label to the console window. The output resembles the following:
    
    ``` csharp
    Field named: SalesId, Field label: Sales order
    Field named: SalesName, Field label: Name
    Field named: Reservation, Field label: Reservation
    Field named: CustAccount, Field label: Customer account
    Field named: InvoiceAccount, Field label: Invoice account
    …
    ```
    
    Notice that the code calls the GetLabelMetadataForLanguageById method and takes a parameter that specifies a language. This method can be used for localization code because it enables you to return a label in a specific language. You can retrieve the language values by calling the [GetLanguages](https://technet.microsoft.com/en-us/library/hh188013\(v=ax.60\)) method.
    

    > [!TIP]
    > <P>If you run the code and receive a message size exception, you may need to modify settings in the app.config file. For more information, see Message Size Error in <A href="troubleshooting-system-services.md">Troubleshooting System Services</A></P>




> [!NOTE]
> <P>If you run this code sample and the program returns field labels such as @SYS1234 instead of the actual field label, it may be because the user calling the service is not a valid user in Microsoft Dynamics AX. Try adding the user under which the service is being called as a Microsoft Dynamics AX user and run the program again.</P>



## Next Steps

The [TableMetadata](https://technet.microsoft.com/en-us/library/hh130058\(v=ax.60\)) class contains all the methods and properties for a single table. If you are working with other objects such as queries, you can access the data through the corresponding metadata object, for example, the [QueryMetadata](https://technet.microsoft.com/en-us/library/hh151954\(v=ax.60\)) class.

## See also

[AIF System Services](aif-system-services.md)

[Metadata Service](metadata-service.md)

[Walkthrough: Calling the Metadata Service](walkthrough-calling-the-metadata-service.md)

[Troubleshooting System Services](troubleshooting-system-services.md)

