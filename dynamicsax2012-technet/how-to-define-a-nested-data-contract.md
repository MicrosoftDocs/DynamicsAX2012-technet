---
title: 'How to: Define a Nested Data Contract'
TOCTitle: 'How to: Define a Nested Data Contract'
ms:assetid: 433423d6-5cde-40c1-8892-cc4bf9aafa9d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731913(v=AX.60)
ms:contentKeyID: 35132839
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Define a Nested Data Contract [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Create a nested data contract class when you have a parameter that you want to reuse on many reports that are bound to a report data provider (RDP) class. An RDP class is an X++ class that is used to access and process data for a report. X++ classes are created in the AOT and an RDP class will be bound to a report by using the Visual Studio tools for Microsoft Dynamics AX.

The following two classes are required to use Report Data Provider as your data source type:

  - Data contract class – defines the parameters in the report.

  - RDP class – processes business logic based on a query and parameters that are defined in the data contract class, and then returns the tables as a dataset for the report.

A data contract class is an X++ class that has getters, setters, and the DataContractAttribute attribute. A nested data contract is defined the same as other data contract classes. It is a nested data contract when it is used by another class. After you define the nested data contract, you can reuse it in your code where those parameters are appropriate. In the following example you will define a nested data contract class. The example that is used creates a Boolean parameter that determines whether to include tax.

## Defining a Nested Data Contract Class

An RDP class must have a data contract if the report has one or more report parameters. This example defines one report parameter to prompt the user whether to include tax. A data contract is an X++ class that has getters, setters, and the attribute DataContractAttribute. The data contract defines the parameters that the report uses. The following example illustrates defining a data contract class that will be nested and reused.

### To define a data contract class

1.  In the AOT, right-click the **Classes** node, and then select **New Class**.

2.  Right-click the new class, click **Rename**, and then enter **SrsRDPNestedContractSample**.

3.  Expand **SrsRDPNestedContractSample**, right-click **classDeclaration**, and then click **View Code**.

4.  In code editor, enter the following code in the class declaration to define the class.

<!-- end list -->

    [DataContractAttribute]
    public class SrsRDPNestedContractSample
    {
        boolean inclTax;
    }

A data contract class has methods with the DataMemberAttribute attribute. The name that follows the attribute is the parameter name that displays in Visual Studio when you bind a report data set to the RDP class. The following example illustrates a data contract method for the nested data contract example.

### To define data contract methods

1.  Right-click **SrsRDPNestedContractSample**, point to **New**, and then click **Method**.

2.  Edit the method so that it contains the following code.

<!-- end list -->

    [DataMemberAttribute(“InclTax”)]
    public boolean parmInclTax(boolean _inclTax = inclTax)
    {
        inclTax = _inclTax;
        return inclTax;
    }

## Use the Nested Data Contract

Next, use the nested data contract that you defined. By using the nested data contract, you will add the parameter that determines whether to include tax that is defined in the nested data contract. The following example illustrates a data contract class declaration that adds the SrsRdpNestedContractSample nested data contract.

### To use the nested data contract

1.  In the AOT, right-click the **Classes** node, and then select **New Class**.

2.  Right-click the new class, click **Rename**, and then enter **SrsRDPContractSample**.

3.  Expand **SrsRDPContractSample**, right-click **classDeclaration**, and then click **View Code**.

4.  In code editor, enter the following code in the class declaration to define the class.


    [DataContractAttribute]
    public class SrsRDPContractSample
    {
        AccountNum = accountNum;
        CustAccountStatment accountStmt;
        SrsRdpNestedContractSample nestedContract;
    }

A data contract class has methods with the DataMemberAttribute attribute. In this section, add a method for each report parameter and name them parmAccountNum, parmAccountStmt, and parmNestedContract. The following example illustrates a data contract method named parmAccountNum.

### To define data contract methods

1.  Right-click **SrsRDPContractSample**, point to **New**, and then click **Method**.

2.  Edit the method so that it contains the following code.
    
        [DataMemberAttribute(“AccountNum”)]
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
    
        [DataMemberAttribute]
        public SrsRdpNestedContractSample parmNestedContract(SrsRdpNestedContractSample _nestedContract = nestedContract)
        {
            nestedContract = _nestedContract;
            return nestedContract;
        }

### Create a Temporary Table

Data for an RDP report is preprocessed and then stored in a temporary table. The temporary table is used by Reporting Services when the report is displayed. A table that is returned by a method can be a temporary table (InMemory or TempDB) or a regular table. You can have one or more methods return tables. When the data that is returned is used for reporting only, it is a best practice to use a temporary table because the data in the tables will are cleaned after the report is run.

  - Use an InMemory temporary table if the data set is small, such as 1000 records.

  - Use a TempDB temporary table for large data sets to improve performance.


> [!NOTE]
> <P></P>



For more information, see [Temporary Tables and the TableType Property](https://technet.microsoft.com/en-us/library/gg863308\(v=ax.60\)). In this section you will create a temporary table to store the data for the report.

### To create a temporary table

1.  In the AOT, expand the **Data Dictionary** node, right-click the **Tables** node, and then click **New Table**.

2.  Right-click the table, and then click **Properties**.

3.  In the Properties window, set the **Name** property to **TmpCustTableSample** and set the **Table Type** property to **TempDB**. This will define the table as a SQL Server temporary table. Set the **SaveDataPerCompany** property to **Yes** if the data that is returned depends on the company context from which the report is run.

4.  Expand the node next to the **TmpCustTableSample** table so that you can see the **Fields** node.

5.  Press Ctrl+D to open another AOT window and move the window so that you can see both AOT windows.

6.  In the second AOT, expand the Data Dictionary node, expand the Extended Data Types node, and drag the following types to the Field node in the first AOT window:
    
      - AccountNum
    
      - CustName
    
      - LogisticsAddressing
    
      - CustGroupId
    
      - Phone
    
      - CustInvoiceAccount
    
      - ActionDays
    
      - InclTax

7.  In the second AOT window, expand the **Base Enums** node and drag the **CustAccountStatement** enumeration to the **Fields** node of the first AOT window.

### Define a Report Data Provider Class

In this section you define an RDP class that uses the nested data contract. The RDP class is a data provider that lets you add business logic for the data that is displayed on a report. An RDP class is an X++ class that extends the SRSReportDataProviderBase class. The following list describes the attributes that are attached to the RDP class for this example:

  - Attach the SRSReportQueryAttribute attribute to the query specified in the parmQuery method in the RDP class. For this example, set the attribute to the Cust query.

  - Attach the SRSReportParameterAttribute attribute to specify the data contract class that defines the report parameters for the report. For this example, set the attribute to the SrsRDPContractSample data contract.

### To define a report data provider class

1.  In the AOT, right-click the **Classes** node, and then click **New Class**.

2.  Right-click the new class, click **Rename**, and then enter **SrsRDPSampleClass**.

3.  Expand **SrsRDPSampleClass**, right-click **classDeclaration**, and then click **Code**.

4.  In code editor, enter the following code in the class declaration to define the class.
    
        [
            SRSReportQueryAttribute(querystr(Cust)),
            SRSReportParameterAttribute(classstr(SrsRDPContractSample))
        ]
        public class SrsRdpSampleClass extends SRSReportDataProviderBase
        {
            TmpCustTableSample tmpCust;
        }

Your code gets parameters from the end user, processes business logic to generate data in a table, and then returns the table to display in the report. You define a method that returns a table of the data that you process in the RDP class to Reporting Services. In this section, add a method named getTmpCustTable and attach the SRSReportDataSetAttribute attribute to indicate the dataset for the report.

### To define a method to return data to Reporting Services

1.  Right-click **SrsRdpSampleClass**, point to **New**, and then click **Method**.

2.  Edit the method so that it contains the following code.

<!-- end list -->

    [SRSReportDataSetAttribute(“TmpCust”)]
    public TmpCustTableSample getTmpCustTable()
    {
        select * from tmpCust;
        return tmpCust;
    }

You will provide the report business logic in the processReport method. The processReport method computes data and populates the data tables that are returned to Reporting Services. Override the processReport method to provide business logic for your report. The following example gets the value of the boolInclTax parameter from the nested data contract.

### To add business logic for the report

  - Right-click **SrsRdpSampleClass**, point to **New**, and then click **Method**.

<!-- end list -->

    public void processReport()
    {
        AccountNum              accntNum;
        CustAccountStatement    custAcctStmt;
        boolean                 boolInclTax;
        Query                   query;
        QueryRun                qr;
        QueryBuildDataSource    queryBuildDataSource;
        QueryBuildRange         queryBuildRange;
        CustTable               queryCustTable;
    
        SrsRdpContractSample    dataContract;
    
        // Get the query from the runtime using a dynamic query.
        query = this.parmQuery();
            
        // Get the parameters passed from runtime.
        dataContract = this.parmDataContract();
        accntNum = dataContract.parmAccountNum();
        custAcctStmt = dataContract.parmAccountStmt();
                
        // Get the parameters from the nested contract.        
        nestedDataContract = dataContract.parmNestedContract();    
        boolInclTax = nestedDataContract.parmInclTax();
            
        // Add parameters to the query.
        queryBuildDataSource = query.dataSourceTable(tablenum(CustTable));
            
            
        if(accntNum)
        {
            queryBuildRange = queryBuildDataSource.findRange(fieldnum(CustTable, AccountNum));
            if (!queryBuildRange)
            {
                queryBuildRange = queryBuildDataSource.addRange(fieldnum(CustTable, AccountNum));
            }
            // If an account number has not been set, then use the parameter value to set it.
            if(!queryBuildRange.value())
                queryBuildRange.value(accntNum);
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
        qr = new QueryRun(query);
        ttsbegin;
        while(qr.next())
        {
            tmpCust.clear();
            queryCustTable = qr.get(tablenum(CustTable));
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

 The next step is to create a report bound to the RDP class by using the Visual Studio tools for Microsoft Dynamics AX.

For more information, see [Creating Reports Overview](creating-reports-overview.md). For the complete steps to bind an RDP class to a report, see [Walkthrough: Creating a Report Bound to a Report Data Provider Class (X++ Business Logic)](walkthrough-creating-a-report-bound-to-a-report-data-provider-class-x-business-logic.md).

## See also

[How to: Group and Order Report Parameters by Using a Data Contract Class](how-to-group-and-order-report-parameters-by-using-a-data-contract-class.md)

[Guidance for Choosing the Data Source Type](guidance-for-choosing-the-data-source-type.md)

[Creating Reports Overview](creating-reports-overview.md)

