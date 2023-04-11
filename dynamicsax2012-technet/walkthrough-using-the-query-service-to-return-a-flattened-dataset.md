---
title: 'Walkthrough: Using the Query Service to Return a Flattened Dataset'
TOCTitle: 'Walkthrough: Using the Query Service to Return a Flattened Dataset'
ms:assetid: 91f0f205-75a0-4d66-b6d5-b9e32ef09151
ms:mtpsurl: https://technet.microsoft.com/library/Gg841671(v=AX.60)
ms:contentKeyID: 35247435
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Walkthrough: Using the Query Service to Return a Flattened Dataset 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This walkthrough shows you how to call the query service and retrieve data from tables that implement table inheritance in Microsoft Dynamics AX in a flattened data table. This is accomplished by setting the ReturnFlatDataSet property on the query object. When this property is set to true, data from the base table and any derived tables that make up the query data sources is returned in a single DataTable in the DataSet. For more information about how to use the query service to return data from hierarchical tables, see [Walkthrough: Using the Query Service to Query Tables in a Hierarchy](walkthrough-using-the-query-service-to-query-tables-in-a-hierarchy.md).

This walkthrough illustrates the following tasks:

  - Add a reference to the query service.

  - Call the query service and return data from hierarchical tables.

## Prerequisites

To complete this walkthrough you will need:

  - Microsoft Dynamics AX 2012

  - Visual Studio 2008

  - To have created the tables and query in the Hierarchical Tables, Data and Query section of the topic [Creating Query Service Test Data](creating-query-service-test-data.md).

## Add Service References

In order to call the system services, you must first create a project in Visual Studio and add references to the services.

### To add a reference to the query service and the metadata service

1.  Open Visual Studio and create a new project by selecting **File** \> **New Project**.

2.  In the **Project types** tree, select **Visual C\#** \> **Windows** and then click the **Windows Forms Application** template.

3.  Type a project name such as QueryServiceFlatDatasetTest and then click **OK**.

4.  In Solution Explorer, right-click **References** and select **Add Service Reference**.

5.  In the **Address** Field, enter the URL of the query service. For example, http://localhost:8101/DynamicsAx/Services/QueryService.

6.  Click **Go**. In the **Services** tree, you should see the QueryService.

7.  Type QueryServiceReference in the **Namespace** field and then click **OK**.

8.  In Solution Explorer, right-click **References** and select **Add Service Reference**.

9.  In the **Address** Field, enter the URL of the metadata service. For example, http://localhost:8101/DynamicsAx/Services/MetadataService.

10. Click **Go**. In the **Services** tree, you should see the AxMetadataService.

11. Type QueryServiceReference in the **Namespace** field and then click **OK**.

## Call the Services and Retrieve the Data

Now we will write the code that calls the query service and returns the data specified by the TestPartiesInWA query. The code first calls the metadata service to return the TestPartiesInWA query object. Then the code specifies that a flattened data set should be returned by setting the ReturnFlatDataSet property on the query.

### To call the services

1.  In Solution Explorer, double-click **Form1.cs** to display the form in design mode.

2.  Open the Toolbox and add a DataGridView control to Form1. By default, it is named DataGridView1.

3.  In the Form1.cs file, add the following using statements.
    
    ``` csharp
    using System;
    using System.Windows.Forms;
    using System.Collections.Generic;
    using System.Data;
    using QueryServiceFlatDatasetTest.QueryServiceReference;
    using QueryServiceFlatDatasetTest.MetadataServiceReference;
    // Remove these usings after M3, only here for conversion code
    using System.Runtime.Serialization;
    using System.IO;
    ```

4.  In the Form1\_Load event, add the code to call the query service. The Form1.cs file should contain the following code.
    
    ``` csharp
    using System;
    using System.Windows.Forms;
    using System.Collections.Generic;
    using System.Data;
    using QueryServiceFlatDatasetTest.QueryServiceReference;
    using QueryServiceFlatDatasetTest.MetadataServiceReference;
    // Remove these usings after M3, only here for conversion code
    using System.Runtime.Serialization;
    using System.IO;
    
    namespace QueryServiceFlatDatasetTest
    {
        public partial class Form1 : Form
        {
            public Form1()
            {
                InitializeComponent();
            }
    
            private void Form1_Load(object sender, EventArgs e)
            {
                DataSet dataSet;
                Paging paging = null;
                QueryServiceClient client = new QueryServiceClient();
                AxMetadataServiceClient metadataClient = new AxMetadataServiceClient();
    
                // Create the query object.
                MetadataServiceReference.QueryMetadata queryMetadata = 
                    new MetadataServiceReference.QueryMetadata();
    
                // Get the query from the AOT using the metadata service.
                queryMetadata = metadataClient.GetQueryMetadataByName(new[] { "TestPartiesInWA" })[0];
    
                // Set the query property.
                queryMetadata.ReturnFlatDataSet = true;
    
                // This code is here to convert the queryMetadata object due to namespace conflicts w/mdsr and qsr - remove after M3
                using (MemoryStream memoryStream = new MemoryStream())
                {
                    QueryServiceReference.QueryMetadata queryMetadataQS = new QueryServiceReference.QueryMetadata();
    
                    DataContractSerializer mdsSerializer = new DataContractSerializer(typeof(MetadataServiceReference.QueryMetadata));
                    DataContractSerializer qsSerializer = new DataContractSerializer(typeof(QueryServiceReference.QueryMetadata));
                    mdsSerializer.WriteObject(memoryStream, queryMetadata);
                    memoryStream.Seek(0, SeekOrigin.Begin);
                    queryMetadataQS = (QueryServiceReference.QueryMetadata)qsSerializer.ReadObject(memoryStream);
    
                    dataSet = client.ExecuteQuery(queryMetadataQS, ref paging);
                }
    
                // Call the query service with the query retrieved from the metadata service.
                //dataSet = client.ExecuteQuery(queryMetadata, ref paging);
                // Display the flattened dataset in the grid.
                dataGridView1.DataSource = dataSet.Tables["TestPartiesInWA"];
            }
        }
    }
    ```

5.  This code sets the ReturnFlatDataSet property and calls the query service. The data that is returned is contained in a single DataTable in the DataSet. The data is displayed in the grid by setting the grid data source to the DataTable object.

## See also

[Query Service](query-service.md)

[Metadata Service](metadata-service.md)

[Creating Query Service Test Data](creating-query-service-test-data.md)

[Walkthrough: Using the Query Service to Query Tables in a Hierarchy](walkthrough-using-the-query-service-to-query-tables-in-a-hierarchy.md)

