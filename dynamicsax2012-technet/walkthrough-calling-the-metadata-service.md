---
title: 'Walkthrough: Calling the Metadata Service'
TOCTitle: 'Walkthrough: Calling the Metadata Service'
ms:assetid: 01191d78-4386-42b7-a5ad-b1c5186398a3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg839793(v=AX.60)
ms:contentKeyID: 35240056
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Walkthrough: Calling the Metadata Service 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The metadata service is one of the system services exposed by Microsoft Dynamics AX and that adheres to the Windows Communication Foundation (WCF) protocols and standards. This service enables you to retrieve information about AOT objects such as tables, services, extended data types (EDTs), enums, and so on. In this walkthrough, you will call the metadata service from a C\# program and return metadata for a specific query.

This walkthrough illustrates the following tasks:

  - Add a reference to the metadata service.

  - Call the service and retrieve the metadata.

## Prerequisites

To complete this walkthrough you will need:

  - Microsoft Dynamics AX 2012

  - Visual Studio 2010

## Add a Reference to the Metadata Service

In order to call the metadata service, you must first create a project in Visual Studio and add a reference to the service.

### To add a reference to the metadata service

1.  Open Visual Studio and create a new project by selecting **File** \> **New** \> **Project**.

2.  In the **Installed Templates** tree, select **Visual C\#** \> **Windows** and click the **Console Application** template.

3.  Type a project name such as MetadataServiceTest and click **OK**.

4.  In Solution Explorer, right-click **References** and select **Add Service Reference**.

5.  In the **Address** Field, enter the URL of the service. For example, http://servername:8101/DynamicsAx/Services/MetadataService.

6.  Click **Go**. In the **Services** tree, you should see the AxMetadataService.

7.  In the **Namespace** field, type MetadataServiceReference and click **OK**.

## Call the Service and Retrieve the Metadata

Now we will write the code that calls the metadata service and returns the metadata for a single query.

### To call the metadata service

1.  In the Program.cs file, add the following using statements.
    
    ``` csharp
    using System;
    using MetadataServiceTest.MetadataServiceReference;
    ```

2.  In the Program.cs Main method, add the code to call the service. The contents of the Program.cs file should look as follows:
    
    ``` csharp
    using System;
    using MetadataServiceTest.MetadataServiceReference;
    
    namespace MetadataServiceTest
    {
        class Program
        {
            static void Main(string[] args)
            {
    
                AxMetadataServiceClient client = new AxMetadataServiceClient();
    
                try
                {
                    // Gets the names of all queries in a string array.
                    string[] queries = client.GetQueryNames();
    
                    // Loops through all the query names.
                    foreach (string queryName in queries)
                    {
                        if (queryName == "AxdSalesOrder")
                        {
                            // Stores the name of the AxdSalesOrder query.
                            string[] limitedNames = new string[1];
                            limitedNames[0] = queryName;
                            // Writes the name of the query to the console.
                            Console.WriteLine("Query named: {0}", queryName);
    
                            // Gets the metadata for the AxdSalesOrder query.
                            QueryMetadata[] queryMetadata = client.GetQueryMetadataByName(limitedNames);
                            // Creates a query metadata object.
                            QueryMetadata querySalesOrder = queryMetadata[0];
    
    
                            // Loops through thequery data sources and writes them to the console.
                            foreach (QueryDataSourceMetadata queryDS in querySalesOrder.DataSources)
                            {
                                RecursivelyIterateDataSources(queryDS);
                            }
                            Console.ReadKey(true);
                        }
                    }
                    client.Close();
                }
                catch
                {
                    client.Abort();
                    throw;
                }
    
            }
    
            static void RecursivelyIterateDataSources(QueryDataSourceMetadata parent)
            {
                Console.WriteLine("Query data source named: {0}", parent.Name.ToString());
    
                // Loops through the query data sources and writes them to the console.
                foreach (QueryDataSourceMetadata queryDS in parent.DataSources)
                {
                    RecursivelyIterateDataSources(queryDS);
                }
            }
        }
    }
    ```

3.  Run the program. The program writes the name of the AxdSalesOrder query and the names of the query data sources to the console window. The output looks like the following:
    
    ``` csharp
    Query named: AxdSalesOrder
    Query data source named: SalesTable
    Query data source named: TableDlvAddr
    Query data source named: TableCarrierAddr
    Query data source named: SalesLine
    Query data source named: LineDlvAddr
    Query data source named: LineCarrierAddr
    Query data source named: InventDim
    Query data source named: DocuRefLine
    Query data source named: MarkupTransLine
    Query data source named: DocuRefHeader
    Query data source named: MarkupTransHeader
    Query data source named: CreditCardAuthTrans
    ```
    

    > [!TIP]
    > <P>If you run the code and receive a message size exception, you may need to modify settings in the app.config file on the server and client. For more information, see Message Size Error in <A href="troubleshooting-system-services.md">Troubleshooting System Services</A>.</P>



## Next Steps

The [QueryMetadata](https://technet.microsoft.com/en-us/library/hh151954\(v=ax.60\)) class contains all the methods and properties for a single query. If you are working with other objects such as tables, you can access the data through the corresponding metadata object, for example, the [QueryMetadata](https://technet.microsoft.com/en-us/library/hh151954\(v=ax.60\)) class. All of the metadata contracts are contained in the [Microsoft.Dynamics.AX.Framework.Services.Metadata.Contracts](https://technet.microsoft.com/en-us/library/hh187940\(v=ax.60\)) namespace.

## See also

[AIF System Services](aif-system-services.md)

[Metadata Service](metadata-service.md)

[Walkthrough: Using the Metadata Service to Get Table Field Labels](walkthrough-using-the-metadata-service-to-get-table-field-labels.md)

[Troubleshooting System Services](troubleshooting-system-services.md)

