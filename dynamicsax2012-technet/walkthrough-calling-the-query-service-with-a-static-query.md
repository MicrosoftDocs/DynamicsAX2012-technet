---
title: 'Walkthrough: Calling the Query Service with a Static Query'
TOCTitle: 'Walkthrough: Calling the Query Service with a Static Query'
ms:assetid: b1571cb5-08eb-403c-aeb6-1f3c0c7e3176
ms:mtpsurl: https://technet.microsoft.com/library/Gg863932(v=AX.60)
ms:contentKeyID: 35249738
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Walkthrough: Calling the Query Service with a Static Query 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Microsoft Dynamics AX query service runs a query that you specify and returns the data in a dataset. When you call the query service, you can specify a static query, that is, a query that is already defined in the Application Object Tree (AOT). In this walkthrough, you will call the query service from a C\# program and display customer and customer transaction data in grids on a form.

This walkthrough illustrates the following tasks:

  - Add a reference to the query service.

  - Call the query service with a static query name and display the data.

## Prerequisites

To complete this walkthrough you will need:

  - Microsoft Dynamics AX 2012

  - Visual Studio 2010

The code in this topic runs against the default company of the current user. Therefore, you should ensure that you have data in the CustTable table for that company.

## Add a Reference to the Query Service

In order to call the query service, you must first create a project in Visual Studio and add a reference to the service.

### To add a reference to the query service

1.  Open Visual Studio and create a new project by selecting **File** \> **New**\> **Project**.

2.  In the **Project types** tree, select **Visual C\#** \> **Windows** and then click the **Windows Forms Application** template.

3.  Type a project name such as QueryServiceStaticTest and then click **OK**.

4.  In Solution Explorer, right-click **References** and select **Add Service Reference**.

5.  In the **Address** Field, enter the URL of the service. For example, http://\<servername\>:8101/DynamicsAx/Services/QueryService.

6.  Click **Go**. In the **Services** tree, you should see the QueryService.

7.  Type QueryServiceReference in the **Namespace** field and then click **OK**.

## Call the Service and Retrieve the Data

Now we will write the code that calls the query service and returns the data specified by the CustTable query.

### To call the query service

1.  In Solution Explorer, double-click **Form1.cs** to display the form in design mode.

2.  Open the Toolbox and add three DataGridView controls to Form1. By default, they will be named DataGridView1, DataGridView2, and DataGridView3.

3.  In the Form1.cs file, add the following using statement.
    
    ``` csharp
    using QueryServiceStaticTest.QueryServiceReference;
    ```

4.  In the Form1\_Load event, add the code to call the query service. The Form1.cs file should contain the following code.
    
    ``` csharp
    using System;
    using System.Data;
    using System.Windows.Forms;
    using QueryServiceStaticTest.QueryServiceReference;
    
    namespace QueryServiceStaticTest
    {
        public partial class Form1 : Form
        {
            public Form1()
            {
                InitializeComponent();
                this.Load += new EventHandler(Form1_Load);
    
            }
    
            private void Form1_Load(object sender, EventArgs e)
            {
                QueryServiceClient client = new QueryServiceClient();
    
                DataSet dataSet;
                Paging paging = null;
    
                // Create the binding source objects.
                BindingSource custBindingSource = new BindingSource();
                BindingSource custTransBindingSource = new BindingSource();
                BindingSource custTransOpenBindingSource = new BindingSource();
    
                // Set the grid datasources to binding source objects.
                dataGridView1.DataSource = custBindingSource;
                dataGridView2.DataSource = custTransBindingSource;
                dataGridView3.DataSource = custTransOpenBindingSource;
    
                // Call the CustTable query using the query service.
                dataSet = client.ExecuteStaticQuery("CustTable", ref paging);
    
                // Set the binding source data sources and data members.
                // CustTable_CustTrans and CustTrans_CustTransOpen are table relations
                // in the dataset.
                custBindingSource.DataSource = dataSet;
                custBindingSource.DataMember = "CustTable";
    
                custTransBindingSource.DataSource = custBindingSource;
                custTransBindingSource.DataMember = "CustTable_CustTrans";
    
                custTransOpenBindingSource.DataSource = custTransBindingSource;
                custTransOpenBindingSource.DataMember = "CustTrans_CustTransOpen";
    
            }
        }
    }
    ```

5.  Run the program. This code calls the query service and passes in the name of the CustTable static query. The results of the query are returned in a dataset and displayed in the three grids.
    
    The first grid contains customer records, the second grid contains customer transactions, and the third grid contains open customer transactions. The grids are bound to the dataset and use the existing table relations so if you click a customer, the transactions for that customer appear in the second grid. If you click on a transaction, the open transactions for that customer appear in the third grid. The relations are defined in data sources of the static query in the AOT.

## See also

[Query Service](query-service.md)

[Query Service Security](query-service-security.md)

[Handling Large Datasets Returned by the Query Service](handling-large-datasets-returned-by-the-query-service.md)

