---
title: 'How to: Use a Report Data Provider Class in a Report'
TOCTitle: 'How to: Use a Report Data Provider Class in a Report'
ms:assetid: 46bf4823-0c76-4327-a1e1-29500258d632
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg731917(v=AX.60)
ms:contentKeyID: 35132844
ms.date: 04/17/2013
mtps_version: v=AX.60
---

# How to: Use a Report Data Provider Class in a Report 


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A report data provider (RDP) class is an X++ class that is used to access and process data for a report. An RDP class is an appropriate data source type when the following conditions are met:

  - You cannot query directly for the data you want to render on a report.

  - The data to be processed and displayed is from Microsoft Dynamics AX.

For more information, see [Guidance for Choosing the Data Source Type](guidance-for-choosing-the-data-source-type.md).

A report parameter provides a way to choose report data, connect related reports together, and vary the report presentation. It is used when generating the report data set. The parameters that an RDP class will reference are defined in a data contract class. The following two classes are required to be able to set **Report Data Provider** as your data source type on a report with parameters.

  - Data Contract Class – defines the parameters in the report.

  - Report Data Provider Class – processes business logic based on a query and parameters defined in the data contract class, and then returns the tables as a dataset for the report.

## To define a data contract class

A data contract is an X++ class that has getters, setters and the DataContractAttribute attribute. You create the RDP and data contract classes in the MorphX code editor. For information about how to create an X++ class, see [Declaration of Classes](https://technet.microsoft.com/en-us/library/aa631180\(v=ax.60\)).

The following example illustrates the code to declare a data contract class.


   ```X++
   [DataContractAttribute]
    public class SrsRDPContractSample
    {
        AccountNum accountNum;
        CustAccountStatment accountStmt;
        boolean inclTax;
    }
   ```

A data contract class has methods with the DataMemberAttribute attribute. The name that follows the attribute is the parameter name that displays in Visual Studio when you bind a report data set to the RDP class. Add a method named parmAccountNum in code editor.

The following example illustrates the code for the parmAccountNum method.

   ```X++
   [DataMemberAttribute("AccountNum")]
    public AccountNum parmAccountNum(AccountNum _accountNum = accountNum)
    {
        accountNum = _accountNum;
        return accountNum;
    }
   ```

Add a method named parmAccountStmt in code editor.

The following example illustrates the code for the parmAccountStmt method.

   ```X++
   [DataMemberAttribute("CustAccountStatement")]
    public CustAccountStatement parmAccountStmt(CustAccountStatement _accountStmt = accountStmt)
    {
        accountStmt = _accountStmt;
        return accountStmt;
    }
   ```

Add a method named parmInclTax in code editor.

The following example illustrates the code for the parmInclTax method.

   ```X++
   [DataMemberAttribute("InclTax")]
    public boolean parmInclTax(boolean _inclTax = inclTax)
    {
        inclTax = _inclTax;
        return inclTax;
    }
   ``` 

### To define a report data provider class

An RDP class extends the SRSReportDataProviderBase class. You set the SRSReportParameterAttribute attribute to the data contract you created for the RDP class. The data contract defines the parameters that the report uses. You set the SRSReportQueryAttribute attribute to the query specified in the parmQuery method in the RDP class.

The following example illustrates an RDP class declaration that uses the SrsRDPContractSample data contract class and the Cust query.

   ```X++
   [
        SRSReportQueryAttribute('Cust'),
        SRSReportParameterAttribute(classstr(SrsRDPContractSample))
    ]
    public class SrsRdpSampleClass extends SRSReportDataProviderBase
    {
        TmpCustTableSample tmpCust;
    }
   ```

Your code will get parameters from the end user, process business logic to generate data in a table and then return the table to render in the report. You will define a method that returns a table of the data that you process in the RDP class.

A table returned by a method can be a temporary table (InMemory or TempDB) or a regular table. When the data returned is used for reporting only, it is a best practice to use a temporary table.

  - Use an InMemory temporary table if the data set is small, like 1000 records.

  - Use a TempDB temporary table for large data sets to improve performance.

You can have one or more methods return tables.


> [!NOTE]
> <P>If the data returned depends on the company context the report is run from, then the tables returned by the RDP class must have the table property <STRONG>SaveDataPerCompany</STRONG> set to <STRONG>Yes</STRONG>.</P>



The following example illustrates an RDP class method named getTmpCustTable.

   ```X++
   [SRSReportDataSetAttribute('TmpCust')]
    public TmpCustTableSample getTmpCustTable()
    {
        select * from tmpCust;
        return tmpCust;
    }
   ```

You will provide the report business logic in the processReport method. Override the processReport method to provide business logic for your report.

The following example illustrates how the processReport method computes data and populates the data tables that will be returned to Reporting Services.

```X++
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
        boolInclTax = dataContract.parmInclTax();
            
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
            tmpCust.Name = queryCustTable.name();
            tmpCust.Address = queryCustTable.address();
            tmpCust.CustGroup = queryCustTable.CustGroup;
            tmpCust.Phone = queryCustTable.phone();
            tmpCust.InvoiceAccount = queryCustTable.InvoiceAccount;
            tmpCust.AccountStatement = queryCustTable.AccountStatement;
            tmpCust.InclTax = queryCustTable.InclTax;
            tmpCust.insert();
        }
        ttscommit;
    }
```

 The next step is to create a report using the Visual Studio tools for Microsoft Dynamics AX. For more information, see [Creating Reports Overview](creating-reports-overview.md). For the complete steps to bind a report data provider class to a report, see [Walkthrough: Creating a Report Bound to a Report Data Provider Class (X++ Business Logic)](walkthrough-creating-a-report-bound-to-a-report-data-provider-class-x-business-logic.md).

## See also

[How to: Group and Order Report Parameters by Using a Data Contract Class](how-to-group-and-order-report-parameters-by-using-a-data-contract-class.md)

[Guidance for Choosing the Data Source Type](guidance-for-choosing-the-data-source-type.md)

