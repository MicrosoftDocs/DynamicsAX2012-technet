---
title: 'Walkthrough: Using the Query Service to Query Date Effective Tables'
TOCTitle: 'Walkthrough: Using the Query Service to Query Date Effective Tables'
ms:assetid: 3398a45d-6f5a-4c71-9403-d1655b3b6484
ms:mtpsurl: https://technet.microsoft.com/library/Gg844682(v=AX.60)
ms:contentKeyID: 35241996
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Walkthrough: Using the Query Service to Query Date Effective Tables 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This walkthrough shows you how to call the query service and retrieve data from tables that contain date effective fields. This support enables you to use the query service to build a query that returns data based on specific time periods. In this walkthrough, you use the metadata service to retrieve a static query from the Application Object Tree (AOT). Then you add a date range to the query and use the query service to issue the query. For more information about date effective fields in tables, see [Valid Time State Tables and Date Effective Data](https://technet.microsoft.com/library/gg861781\(v=ax.60\))

This walkthrough illustrates the following tasks:

  - Add references to the query service and the metadata service.

  - Call the query service and return data from date effective tables.

## Prerequisites

To complete this walkthrough you will need:

  - Microsoft Dynamics AX 2012

  - Visual Studio 2010

  - To have created the tables and query in the Date Effective Table and Data section of the topic [Creating Query Service Test Data](creating-query-service-test-data.md).

## Add Service References

In order to call the system services, you must first create a project in Visual Studio and add references to the services.

### To add a reference to the query service and the metadata service

1.  Open Visual Studio and create a new project by selecting **File** \> **New Project**.

2.  In the **Project types** tree, select **Visual C\#** \> **Windows** and then click the **Console Application** template.

3.  Type a project name such as QueryServiceDateEffectiveTest and then click **OK**.

4.  In Solution Explorer, right-click **References** and select **Add Service Reference**.

5.  In the **Address** Field, enter the URL of the query service. For example, http://localhost:8101/DynamicsAx/Services/QueryService.

6.  Click **Go**. In the **Services** tree, you should see the QueryService.

7.  Type QueryServiceReference in the **Namespace** field and then click **OK**.

8.  In Solution Explorer, right-click **References** and select **Add Service Reference**.

9.  In the **Address** Field, enter the URL of the metadata service. For example, http://localhost:8101/DynamicsAx/Services/MetadataService.

10. Click **Go**. In the **Services** tree, you should see the AxMetadataService.

11. Type QueryServiceReference in the **Namespace** field and then click **OK**.

## Call the Services and Display the Data

The code first calls the metadata service to return the TestEmployees query object. Then the code specifies the query type by setting the ValidTimeStateQueryType property on the query. Finally, the code adds a date range to the query.

The following code example sets a date range on the query so that the only records that are returned are those in which a date value in the ValidFrom and ValidTo date range falls in the range specified on the query. In this example, the query range specified is July 1, 2007 through July 31, 2007.

### To call the services

1.  In Solution Explorer, double-click **Program.cs**.

2.  In the Program.cs file, add the following using statements.
    
    ``` csharp
    using System;
    using System.Data;
    using System.Runtime.Serialization;
    using System.IO;
    ```

3.  In the Main method, add the code to get the query, add the range, and then call the query service. The Program.cs file should contain the following code.
    
    ``` csharp
    using System;
    using System.Data;
    using System.Runtime.Serialization;
    using System.IO;
    
    namespace QueryServiceDateEffectiveTest
    {
        class Program
        {
            static void Main(string[] args)
            {
                DateTime startDate = new DateTime(2007, 7, 01);
                DateTime endDate = new DateTime(2007, 7, 31);
                DataSet dataSet;
                Paging paging = null;
                QueryServiceClient client = new QueryServiceClient();
                AxMetadataServiceClient metadataClient = new AxMetadataServiceClient();
    
                // Create the query object.
                QueryMetadataServiceReference.QueryMetadata queryMetadata = new QueryMetadataServiceReference.QueryMetadata();
                
                // Get the query from the AOT using the metadata service.
                queryMetadata = metadataClient.GetQueryMetadataByName(new[] 
                    { "TestEmployees" })[0];
    
                // Set the date range on the query.
                queryMetadata.ValidTimeStateQueryType = 
                QueryMetadataServiceReference.ValidTimeStateQueryType.Range;
                queryMetadata.ValidTimeStateValidFromDateTime = startDate; 
                queryMetadata.ValidTimeStateValidToDateTime = endDate; 
    
                // Call the query service with the query retrieved 
                // from the metadata service.
                //dataSet = client.ExecuteQuery(queryMetadata, ref paging);
    
                DataTable testEmployee = new DataTable();
                testEmployee = dataSet.Tables["TestEmployee"];
    
                // Loop through the TestEmployee table and display the results.
                if (testEmployee != null && testEmployee.Rows.Count > 0)
                {
                    foreach (DataRow row in testEmployee.Rows)
                    {
                        Console.WriteLine(row["EmployeeId"].ToString() + 
                            "\t" + row["FirstName"].ToString() + "\t" +
                            row["LastName"].ToString() + "\t" +
                            row["ValidFrom"].ToString() + "\t" +
                            row["ValidTo"].ToString());
                    }
                    Console.ReadLine();
                }
    
            }
        }
    }
    ```

4.  Run the program. This code adds a date range to the TestEmployees static query and calls the query service. Each employee returned by the query is displayed to the console. When you run the query against the test data, it returns only one valid record. The output resembles:
    
    1234567 Molly Clark 2/9/2007 12:00:00 AM 12/3/2007 12:00:00 AM

## See also

[Query Service](query-service.md)

[Metadata Service](metadata-service.md)

[Creating Query Service Test Data](creating-query-service-test-data.md)

[Valid Time State Tables and Date Effective Data](https://technet.microsoft.com/library/gg861781\(v=ax.60\))

