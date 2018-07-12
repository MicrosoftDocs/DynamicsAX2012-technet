---
title: 'Walkthrough: Creating a Report Bound to a Report Data Provider Class (X++ Business Logic)'
TOCTitle: 'Walkthrough: Creating a Report Bound to a Report Data Provider Class (X++ Business Logic)'
ms:assetid: c9681e02-68cd-4be5-a6b0-cbc163070d1a
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg724119(v=AX.60)
ms:contentKeyID: 35133478
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# Walkthrough: Creating a Report Bound to a Report Data Provider Class (X++ Business Logic) 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In this walkthrough, you use a report data provider (RDP) class with business logic to process data and then display the outcome of the business logic on a report.

An RDP class is an X++ class that is used to access and process data for a Reporting Services report. The options for a data source type for a Microsoft Dynamics AX report are query, business logic, and RDP. An RDP class is an appropriate data source type when the following conditions are met.

1.  You cannot query directly for the data you want to render on a report.

2.  The data to be processed and displayed is from Microsoft Dynamics AX.

The following illustration is a preview of the report that you create in this walkthrough.


> [!NOTE]
> <P>The data that displays in your report may vary depending upon the sample data that is available to you.</P>



The following elements are required to set RDP as your data source type.

  - Temporary table – RDP class fills a temporary table with data that will be used by Reporting Services to display the report.

  - Data contract class – defines the parameters in the report.

  - Report data provider class – processes business logic based on parameters and a query, and then returns the tables as a dataset for the report.

This walkthrough illustrates the following tasks:

  - Creating a temporary table

  - Defining a report data provider class

  - Defining the report parameters

  - Defining a method to return data to Reporting Services

  - Adding business logic for the report

  - Creating a reporting project

  - Binding a report to a report data provider class

## Prerequisites

To complete this walkthrough, you need the business intelligence components installed. For information on the installation requirements, see [Install business intelligence components](install-business-intelligence-components.md).

## Creating a Temporary Table

Data for an RDP report is preprocessed and then stored in a temporary table. The temporary table is used by Reporting Services when the report is displayed. A table returned by a method can be a temporary table (**InMemory** or **TempDB**) or a regular table. When the data returned is used for reporting only, it is a best practice to use a temporary table.

  - Use an InMemory temporary table if the dataset is small, for reports that will display fewer than 1000 records.

  - Use a TempDB temporary table for large datasets to improve performance.

For more information, see [Temporary Tables and the TableType Property](https://technet.microsoft.com/en-us/library/gg863308\(v=ax.60\)). In this section you will create a temporary table to store the data for the report.

### To create a temporary table

1.  In the AOT, expand the **Data Dictionary** node, right-click the **Tables** node, and then click **New Table**.

2.  Right-click the table, and click **Properties**.

3.  In the Properties window, set the **Name** property to **TmpCustTableSample** and set the **Table Type** property to **TempDB**. This will define the table as a SQL Server temporary table.

4.  Expand the node next to the **TmpCustTableSample** table so that you can see the **Fields** node.

5.  Press Ctrl+D to open another AOT window and move the window so you can see both AOT windows.

6.  In the second AOT, expand the **Data Dictionary** node, expand the **Extended Data Types** node, and drag the following types to the **Field** node in the first AOT window:
    
      - AccountNum
    
      - CustName
    
      - LogisticsAddressing
    
      - CustGroupId
    
      - Phone
    
      - CustInvoiceAccount
    
      - ActionDays
    
      - InclTax

7.  In the second AOT window, expand the **Base Enums** node and drag the **CustAccountStatement** enumeration to the **Fields** node of the first AOT window.

## Defining a Report Data Provider Class

The RDP class is a data provider that allows you to add business logic for the data that is displayed on a report. The business logic for this example prompts the end user for parameter values, processes business logic to generate data in a table, and then returns the table to render in the report. In this section, you define the RDP class by extending the SRSReportDataProviderBase class. Then add the TmpCustTableSample table as a global variable. The following list describes the attributes that are attached to the RDP class for this example:

  - Attach the SRSReportQueryAttribute attribute to specify the query to use to get the data for the report.
    
    For this example, set the attribute to the Cust query.

  - Attach the SRSReportParameterAttribute attribute to specify the data contract class that defines the report parameters for the report.
    
    For this example, set the attribute to the SrsRDPContractSampledata contract.

### To define a report data provider class

1.  In the AOT, right-click the **Classes** node, and then click **New Class**.

2.  Right-click the new class, click **Rename**, and then enter **SrsRDPSampleClass**.

3.  Expand **SrsRDPSampleClass**, right-click **classDeclaration**, and then click **View Code**.

4.  In code editor, enter the following code in the class declaration to define the class.
    
        [
            SRSReportQueryAttribute (querystr(Cust)),
            SRSReportParameterAttribute(classstr(SrsRDPContractSample))
        ]
        public class SrsRdpSampleClass extends SRSReportDataProviderBase
        {
            TmpCustTableSample tmpCust;
        }

## Defining a Data Contract Class

An RDP class must have a data contract if the report has one or more report parameters. This example defines three report parameters for account number, account statement, and whether to include tax. When you print the report, you can specify which data to print based on the report parameters. For example, you can specify to only print transactions for account number 4000.

A data contract is an X++ class with getters, setters, and the DataMemberAttribute attribute. The data contract defines the parameters that the report uses.

### To define a data contract class

1.  In the AOT, right-click the **Classes** node, and then select **New Class**.

2.  Right-click the new class, click **Rename**, and then enter **SrsRDPContractSample**.

3.  Expand **SrsRDPContractSample**, right-click **classDeclaration**, and then click **View Code**.

4.  In code editor, enter the following code in the class declaration to define the class.
    
        [DataContractAttribute]
        public class SrsRDPContractSample
        {
            AccountNum accountNum;
            CustAccountStatement accountStmt;
            boolean inclTax;
        }

A data contract class has methods with the DataMemberAttribute attribute. The name that follows this attribute is the parameter name that displays in Visual Studio when you bind a report data set to the RDP class. In this section, add a method for each of the report parameters and name them parmAccountNum, parmAccountStmt, and parmInclTax.

### To define data contract methods

1.  Right-click **SrsRDPContractSample**, point to **New**, and then click **Method**.

2.  Edit the method so that it contains the following code.
    
        [DataMemberAttribute("AccountNum")]
        public AccountNum parmAccountNum(AccountNum _accountNum = accountNum)
        {
            accountNum = _accountNum;
            return accountNum;
        }

3.  Right-click **SrsRDPContractSample**, point to **New**, and then click **Method**.

4.  Edit the method so that it contains the following code.
    
        [DataMemberAttribute("CustAccountStatement")]
        public CustAccountStatement parmAccountStmt(CustAccountStatement _accountStmt = accountStmt)
        {
            accountStmt = _accountStmt;
            return accountStmt;
        }

5.  Right-click **SrsRDPContractSample**, point to **New**, and then click **Method**.

6.  Edit the method so that it contains the following code.
    
        [DataMemberAttribute("InclTax")]
        public boolean parmInclTax(boolean _inclTax = inclTax)
        {
            inclTax = _inclTax;
            return inclTax;
        }

## Defining a Method to Return Data to Reporting Services

A method to return the processed data in the temporary table to Reporting Services is needed. In this section, add a method named **getTmpCustTable** and attach the SRSReportDataSetAttribute attribute to indicate the dataset for the report.

### To define a method to return the data to Reporting Services

1.  Right-click **SrsRdpSampleClass**, point to **New**, and then click **Method**.

2.  Edit the method so that it contains the following code.
    
        [SRSReportDataSetAttribute("TmpCust")]
        public TmpCustTableSample getTmpCustTable()
        {
            select * from tmpCust;
            return tmpCust;
        }

## Adding Business Logic for the Report

The business logic for this example prompts the end user for parameter values, processes business logic to generate data in a table, and then returns the table to render in the report.

The report business logic is provided in the processReport method. This method is called by Reporting Services at runtime. The following example illustrates how the processReport method computes data and populates the data table that is returned to Reporting Services. In this section, override the processReport method to provide business logic for your report.

### To add business logic for the report

1.  Right-click **SrsRdpSampleClass**, point to **Override method**, and then click **processReport**.

2.  Edit the method so that it contains the following code.
    
        public void processReport()
        {
            AccountNum              accountNumber;
            CustAccountStatement    custAcctStmt;
            boolean                 boolInclTax;
            Query                   query;
            QueryRun                queryRun;
            QueryBuildDataSource    queryBuildDataSource;
            QueryBuildRange         queryBuildRange;
            CustTable               queryCustTable;
        
            SrsRdpContractSample    dataContract;
        
            // Get the query from the runtime using a dynamic query. 
            // This base class method reads the query specified in the SRSReportQueryAttribute attribute.
            query = this.parmQuery();
                
            // Get the parameters passed from runtime. 
            // The base class methods read the SRSReportParameterAttribute attribute. 
            dataContract = this.parmDataContract();
            accountNumber = dataContract.parmAccountNum();
            custAcctStmt = dataContract.parmAccountStmt();
            boolInclTax = dataContract.parmInclTax();
                
            // Add parameters to the query.
            queryBuildDataSource = query.dataSourceTable(tablenum(CustTable));
                
                
            if(accountNumber)
            {
                queryBuildRange = queryBuildDataSource.findRange(fieldnum(CustTable, AccountNum));
                if (!queryBuildRange)
                {
                    queryBuildRange = queryBuildDataSource.addRange(fieldnum(CustTable, AccountNum));
                }
                // If an account number has not been set, then use the parameter value to set it.
                if(!queryBuildRange.value())
                    queryBuildRange.value(accountNumber);
            }        
                
            if(custAcctStmt)
            {
                queryBuildRange = queryBuildDataSource.findRange(fieldnum(CustTable, AccountStatement));
                if (!queryBuildRange)
                {
                    queryBuildRange = queryBuildDataSource.addRange(fieldnum(CustTable, AccountStatement));
                }
                // If an account statement has not been set, then use the parameter value to set it.
                if(!queryBuildRange.value())
                    queryBuildRange.value(int2str(custAcctStmt));
            }
                
            if(boolInclTax)
            {
                queryBuildRange = queryBuildDataSource.findRange(fieldnum(CustTable, InclTax));
                if (!queryBuildRange)
                {
                    queryBuildRange = queryBuildDataSource.addRange(fieldnum(CustTable, InclTax));
                }
                // If flag to include tax has not been set, then use the parameter value to set it.
                if(!queryBuildRange.value())
                    queryBuildRange.value(int2str(boolInclTax));
            }        
                
            // Run the query with modified ranges.
            queryRun = new QueryRun(query);
            ttsbegin;
            while(queryRun.next())
            {
                tmpCust.clear();
                      queryCustTable = queryRun.get(tablenum(CustTable));
                tmpCust.AccountNum = queryCustTable.AccountNum;
                tmpCust.CustName = queryCustTable.name();
                tmpCust.LogisticsAddressing = queryCustTable.address();
                tmpCust.CustGroupId = queryCustTable.CustGroup;
                tmpCust.Phone = queryCustTable.phone();
                tmpCust.CustInvoiceAccount = queryCustTable.InvoiceAccount;
                tmpCust.CustAccountStatement = queryCustTable.AccountStatement;
                tmpCust.InclTax = queryCustTable.InclTax;
                tmpCust.insert();
        
            }
            ttscommit;
        }

## Creating a Reporting Project

Next, create a reporting project in Microsoft Visual Studio. When you create a reporting project, you use the Report Model to create a Reporting Services report.

### To create a reporting project

1.  Open Microsoft Visual Studio.

2.  On the **File** menu, point to **New**, and then click **Project**. The **New Project** dialog box displays.

3.  In the **Installed Templates** pane, click **Microsoft Dynamics AX**. In the **Templates** pane, click **Report Model**.

4.  In the **Name** box, type SampleRDPReport, and in the **Location** box, type a location.

5.  Click **OK**.
    
    A reporting project contains a report model where you can add a report to the model.

## Binding a Report to a Report Data Provider Class

Now that you have created a reporting project, you are ready to define an auto design report that displays data from the Cust query. The following procedure explains how to create an auto design report that uses the RDP class as the data source.

### To create an auto design report

1.  In Solution Explorer, right-click the **ReportModel** node, point to **Add** and then click **Report**.

2.  In Model Editor, right-click the **Report1** node, and then click **Rename**.

3.  Type CustomerReport as the name.

4.  Right-click the **Datasets** node, and then click **Add Dataset**.

5.  In the **Properties** window, specify the following values.
    
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
    <td><p><strong>Data Source</strong></p></td>
    <td><p><strong>Dynamics AX</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Data Source Type</strong></p></td>
    <td><p><strong>Report Data Provider</strong></p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Default Layout</strong></p></td>
    <td><p><strong>Table</strong></p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Dynamic Filters</strong></p></td>
    <td><p><strong>True</strong></p>
    <div>

    > [!NOTE]
    > <P>This setting is for dynamic parameters on the report. Setting the property to <STRONG>True</STRONG> allows you to filter the report by setting a range on any fields from the data source table.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Name</strong></p></td>
    <td><p>Customer</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Query</strong></p></td>
    <td><p>Click the ellipsis button (…). A dialog box displays where you can select an RDP class that is defined in the AOT and identify the fields that you want to use. Select the <strong>SrsRDPSampleClass</strong> class and click <strong>Next</strong>. In the <strong>Select Fields</strong> dialog box, keep all the checkboxes selected, and click <strong>OK</strong>.</p>
    <div>

    > [!NOTE]
    > <P>Based on what you select, the Query property value is updated. In this case, the query is <STRONG>SELECT * FROM SrsRDPSampleClass.TmpCust</STRONG>.</P>


    </div></td>
    </tr>
    </tbody>
    </table>


6.  In Model Editor, select the **Customer** node and drag it onto the **Designs** node. An auto design named **AutoDesign1** is created for the report.
    

    > [!NOTE]
    > <P>If you expand the <STRONG>Parameters</STRONG> node you see the parameters that you defined in the data contract class. When you define nested data contract parameters, they are listed under the <STRONG>Parameters</STRONG> node also.</P>
    > <P>Select the <STRONG>SrsRDPSampleClass_DynamicParameter</STRONG> parameter. In the <STRONG>Properties</STRONG> window, the <STRONG>AOT Query</STRONG> property is set to the query specified in the parmQuery method in the RDP class.</P>



7.  Select **AutoDesign1** and then click the **Preview** button.

8.  Enter a value for **Account number** and **Account statement** that returns data and then click the **Report** tab to preview the report.
    

    > [!NOTE]
    > <P>You can use * to display all of the account numbers on the report. <STRONG>Account statement</STRONG> is an enumeration and there is no wild card value for enumerations. Check your sample data to determine a valid enumeration value for <STRONG>Account statement</STRONG>.</P>
    > <P>The Select button displays because you set the <STRONG>Dynamic Filters</STRONG> property to <STRONG>True</STRONG> on the dataset. You have the option to click the <STRONG>Select</STRONG> button to specify a range to filter the report and limit the data that displays on the report.</P>



The next steps are to add layout and style templates, deploy, and add the report to a menu item so you can see it in Microsoft Dynamics AX.

## See also

[How to: Deploy Reports to a Report Server](how-to-deploy-reports-to-a-report-server.md)

[How to: Create a Menu Item for a Report](how-to-create-a-menu-item-for-a-report.md)

[How to: Create an Auto Design for a Report](how-to-create-an-auto-design-for-a-report.md)

[Creating Reports Overview](creating-reports-overview.md)

[Walkthrough: Referencing a Report Parameter from Multiple Datasets in a Precision Design Report](walkthrough-referencing-a-report-parameter-from-multiple-datasets-in-a-precision-design-report.md)

