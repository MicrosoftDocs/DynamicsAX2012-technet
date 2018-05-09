---
title: 'Walkthrough: Using the Query Service to Query Tables in a Hierarchy'
TOCTitle: 'Walkthrough: Using the Query Service to Query Tables in a Hierarchy'
ms:assetid: 15c944d2-e4a6-4d7b-b790-83567a96a0b9
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg843785(v=AX.60)
ms:contentKeyID: 35240628
ms.date: 11/07/2012
mtps_version: v=AX.60
dev_langs:
- csharp
---

# Walkthrough: Using the Query Service to Query Tables in a Hierarchy 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This walkthrough shows you how to call the query service and retrieve data from tables that implement table inheritance in Microsoft Dynamics AX. When the query service returns data from tables that are part of a table hierarchy, it returns the data for the base table and for each table that derives from the base table in DataTable objects in a single DataSet. The records in the base DataTable are related to the derived DataTables through DataRelation objects. For more information about table inheritance, see [Walkthrough: Creating Base and Derived Tables](https://technet.microsoft.com/en-us/library/gg844024\(v=ax.60\)).

This walkthrough illustrates the following tasks:

  - Add a reference to the query service.

  - Call the query service and return data from hierarchical tables.

## Prerequisites

To complete this walkthrough, you will need:

  - Microsoft Dynamics AX 2012

  - Visual Studio 2008

  - To have created the tables and query in the Hierarchical Tables, Data and Query section of the topic [Creating Query Service Test Data](creating-query-service-test-data.md)

## Add a Reference to the Query Service

In order to call the query service, you must first create a project in Visual Studio and add a reference to the service.

### To add a reference to the query service

1.  Open Visual Studio and create a new project by selecting **File** \> **New Project**.

2.  In the **Project types** tree, select **Visual C\#** \> **Windows** and then click the **Console Application** template.

3.  Type a project name such as QueryServiceTableInheritanceTest and then click **OK**.

4.  In Solution Explorer, right-click **References** and select **Add Service Reference**.

5.  In the **Address** Field, enter the URL of the service. For example, http://localhost:8101/DynamicsAx/Services/QueryService.

6.  Click **Go**. In the **Services** tree, you should see the QueryService.

7.  Type QueryServiceReference in the **Namespace** field and then click **OK**.

## Call the Service and Display the Data

Now we will write the code that calls the query service and returns the data specified by the PartiesInWA query.

### To call the query service

1.  In Solution Explorer, double-click **Program.cs**.

2.  In the Program.cs file, add the following using statements.
    
    ``` csharp
    using System;
    using System.Data;
    using QueryServiceTableInheritanceTest.QueryServiceReference;
    ```

3.  In the Main method, add the code to call the query service. The Program.cs file should contain the following code.
    
    ``` csharp
    using System;
    using System.Data;
    using QueryServiceTableInheritanceTest.QueryServiceReference;
    
    namespace QueryServiceTableInheritanceTest
    {
        class Program
        {
            static void Main(string[] args)
            {
                QueryServiceClient client = new QueryServiceClient();
    
                DataSet dataSet;
                DataTable party;
                Paging paging = null;
    
                // Call the query service with the query name.
                dataSet = client.ExecuteStaticQuery("TestPartiesInWA", ref paging);
    
                // Get the base table Party.
                party = dataSet.Tables["TestParty.TestParty"];
                string strParty = "";
    
                if (party != null && party.Rows.Count > 0)
                {
                    // Loop through each record in Party. 
                    foreach (DataRow row in party.Rows)
                    {
                        strParty = "";
                        // Get the rows from the TestOrganization table through the table relation.
                        DataRow[] childrows = row.GetChildRows("TestParty.TestParty_TestParty.TestOrganization");
                        foreach (DataRow childrow in childrows)
                        {
                            strParty = row["Name"] + "\t" + row["City"] + "\t" + row["StateProvince"] + 
                                "\t" + row["Email"] + "\t" + childrow["DUNSNumber"];
                        }
                        // Get the rows from the TestPerson table through the table relation.
                        childrows = row.GetChildRows("TestParty.TestParty_TestParty.TestPerson");
                        foreach (DataRow childrow in childrows)
                        {
                            strParty = childrow["FirstName"] + " " + childrow["LastName"] + "\t" + row["City"] + 
                                "\t" + row["StateProvince"] + "\t" + row["Email"] + "\t" +
                                DateTime.Parse(childrow["BirthDate"].ToString()).ToShortDateString();
                        }
                        // Display the organization or person data.
                        Console.WriteLine(strParty);
                    }
                }
                else
                {
                    Console.WriteLine("No records returned in Party table.");
                }
    
                Console.ReadLine();
            }
        }
    }
    ```

4.  Run the program. This code calls the query service and passes in the name of the PartiesInWA static query. The code loops through the records in the base table, and for each record, there will be either a related person record or an organization record. Each party returned by the query is displayed to the console. The output resembles the following:
    
    Northwind Traders        Seattle        WA        info@northwind.com          123456789
    
    Molly Clark              Bellevue       WA        molly@hotmail.com           2/23/1968

## See also

[Query Service](query-service.md)

[Walkthrough: Calling the Query Service with a Static Query](walkthrough-calling-the-query-service-with-a-static-query.md)

[Walkthrough: Creating Base and Derived Tables](https://technet.microsoft.com/en-us/library/gg844024\(v=ax.60\))

