---
title: Creating Query Service Test Data
TOCTitle: Creating Query Service Test Data
ms:assetid: 3b7a97d5-3d04-4220-89bb-de138239e85c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg861773(v=AX.60)
ms:contentKeyID: 35242898
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Creating Query Service Test Data [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic contains X++ jobs that create tables, table data, queries, and other database artifacts that are referenced in the Microsoft Dynamics AX Developer Help. These artifacts can be used to demonstrate calls to the [query service](query-service.md). This topic includes the following tasks:

  - Create tables that demonstrate a table hierarchy.

  - Add data to the hierarchical tables.

  - Create a query that returns records from the hierarchical tables.

  - Create a table that contains date effective fields.

  - Add data to the date effective table.

## Hierarchical Tables, Data and Query

The following jobs create tables that implement table inheritance, populate those tables with sample data, and create a query that accesses the tables. In this scenario, the tables contain parties which can be either an organization or a person. For more information about Table Inheritance, see [Table Inheritance Overview](https://technet.microsoft.com/en-us/library/gg881053\(v=ax.60\)).

### Create the Hierarchical Tables

The following job creates a table hierarchy in the Application Object Tree (AOT). It creates the following artifacts:

  - A base table named TestParty.

  - A table that derives from the TestParty table named TestOrganization.

  - A table that derives from the TestParty table named TestPerson.

<!-- end list -->

   ```X++
   static void CreateHierarchicalTables(Args _args)
    {
    
        #AOT
        Treenode tableNode;
        Treenode field;
        AOTTableFieldList FieldList;
        ;
        tableNode = treenode::findNode(#TablesPath);
    
        // Create the base table.
        tableNode = tableNode.AOTadd("TestParty");
        tableNode.AOTsetProperty("SupportInheritance", "Yes");
        tableNode.AOTsave();
    
        // Add fields to the base table.
        FieldList = tableNode.AOTfindChild("Fields");
        FieldList.addInt64("InstanceRelationType");
        FieldList.addString("Name");
        field = FieldList.AOTfindChild("Name");
        field.AOTsetProperty("StringSize", "50");
        FieldList.addString("StreetAddress");
        field = FieldList.AOTfindChild("StreetAddress");
        field.AOTsetProperty("StringSize", "50");
        FieldList.addString("City");
        field = FieldList.AOTfindChild("City");
        field.AOTsetProperty("StringSize", "50");
        FieldList.addString("StateProvince");
        field = FieldList.AOTfindChild("StateProvince");
        field.AOTsetProperty("StringSize", "50");
        FieldList.addString("PostalCode");
        field = FieldList.AOTfindChild("PostalCode");
        field.AOTsetProperty("StringSize", "50");
        FieldList.addString("Country");
        field = FieldList.AOTfindChild("Country");
        field.AOTsetProperty("StringSize", "50");
        FieldList.addString("Phone");
        field = FieldList.AOTfindChild("Phone");
        field.AOTsetProperty("StringSize", "50");
        FieldList.addString("Email");
        field = FieldList.AOTfindChild("Email");
        field.AOTsetProperty("StringSize", "50");
        tableNode.AOTsave();
    
        tableNode.AOTsetProperty("InstanceRelationType", "InstanceRelationType");
        tableNode.AOTsave();
        tableNode.AOTcompile();
    
        // Create the first derived table.
        tableNode = treenode::findNode(#TablesPath);
    
        tableNode = tableNode.AOTadd("TestOrganization");
        tableNode.AOTsetProperty("SupportInheritance", "Yes");
        tableNode.AOTsetProperty("Extends", "TestParty");
        tableNode.AOTsave();
    
        // Add fields to the first derived table.
        FieldList = tableNode.AOTfindChild("Fields");
        FieldList.addInteger("NumberOfEmployees");
        FieldList.addString("DUNSNumber");
        field = FieldList.AOTfindChild("DUNSNumber");
        field.AOTsetProperty("StringSize", "50");
        tableNode.AOTsave();
        tableNode.AOTcompile();
        tableNode.AOTrefresh();
    
        // Create the second derived table.
        tableNode = treenode::findNode(#TablesPath);
    
        tableNode = tableNode.AOTadd("TestPerson");
        tableNode.AOTsetProperty("SupportInheritance", "Yes");
        tableNode.AOTsetProperty("Extends", "TestParty");
        tableNode.AOTsave();
    
        // Add fields to the second derived table.
        FieldList = tableNode.AOTfindChild("Fields");
        FieldList.addString("FirstName");
        field = FieldList.AOTfindChild("FirstName");
        field.AOTsetProperty("StringSize", "50");
        FieldList.addString("LastName");
        field = FieldList.AOTfindChild("LastName");
        field.AOTsetProperty("StringSize", "50");
        FieldList.addString("MiddleName");
        field = FieldList.AOTfindChild("MiddleName");
        field.AOTsetProperty("StringSize", "50");
        FieldList.addInteger("Gender");
        FieldList.addDate("BirthDate");
        tableNode.AOTsave();
        tableNode.AOTcompile();
        tableNode.AOTrefresh();
    }
   ```

### Add Data to the Hierarchical Tables

The following job adds data to the test tables created in the previous step.

```X++
    static void AddHierarchicalTableData(Args _args)
    {
        // Add data to the TestOrganization table.
        #AOT
        TestOrganization org;
        TestPerson person;
        ;
        // Synchronize the tables.
        appl.dbSynchronize(tableNum(TestParty));
        appl.dbSynchronize(tableNum(TestOrganization));
        appl.dbSynchronize(tablenum(TestPerson));
    
        // Add a record to TestOrganization table.
        org.Name = "Northwind Traders";
        org.StreetAddress = "123 Main Street";
        org.City = "Seattle";
        org.StateProvince= "WA";
        org.PostalCode = "92108";
        org.Country = "USA";
        org.Phone = "206-555-1212";
        org.Email = "info@northwind.com";
        org.NumberOfEmployees = 250;
        org.DunsNumber= "123456789";
    
        org.insert();
    
        // Add a record to TestPerson table.
        person.FirstName = "Molly";
        person.LastName = "Clark";
        person.Gender = 1;
        person.BirthDate = str2Date("23/02/1968", 123);
        person.StreetAddress = "123 West Main Street";
        person.City = "Bellevue";
        person.StateProvince= "WA";
        person.PostalCode = "92008";
        person.Country = "USA";
        person.Phone = "425-555-1212";
        person.Email = "molly@hotmail.com";
    
        person.insert();
    
    }
```

### Create the Hierarchical Query

The following job creates a query that accesses the hierarchical tables.

```X++
    static void CreateHierarchicalQuery(Args _args)
    {
        TreeNode                treeNode;
        Query                   query;
        QueryBuildDataSource    qbds;
        QueryBuildRange         qbr;
        str                     queryName = "TestPartiesInWA";
        #AOT
        ;
        treeNode = TreeNode::findNode(#QueriesPath);
        query = treeNode.AOTfindChild(queryName);
         if (!query)
        {
            // Add the query to the AOT.
                treeNode.AOTadd(queryName);
            query = treeNode.AOTfindChild(queryName);
            // Add the data source and rename it.
            qbds  = query.addDataSource(tablenum(TestParty));
            qbds.name('TestParty');
            // Add a range to return only parties in WA.
            qbr   = qbds.addRange(fieldnum(TestParty, StateProvince));
            qbr.value('WA');
            query.AOTcompile();
            query.AOTsave();
         }
    }
```

## Date Effective Table and Data

The following jobs create a table that implements date effective fields and populate the table with sample data. In this scenario, the table contains employees. Multiple records for a single employee can occur in the table, but each record must have different values for the ValidFrom and ValidTo fields, and there can be no overlap in the dates. For more information about date effective tables and fields, see [Valid Time State Tables and Date Effective Data](https://technet.microsoft.com/en-us/library/gg861781\(v=ax.60\)).

### Create the Date Effective Table

The following job creates a table that contains date effective fields.

```X++
    static void AddDateEffectiveTable(Args _args)
    {
        #AOT
        #TreeNodeSysNodeType
        Treenode tableNode;
        Treenode field;
        AOTTableFieldList FieldList;
        Treenode indexNode;
        Treenode fieldsNode;
        str strPropValue;
        ;
        tableNode = treenode::findNode(#TablesPath);
    
        // Create the base table.
        tableNode = tableNode.AOTadd("TestEmployee");
    
        // Add fields to the base table.
        FieldList = tableNode.AOTfindChild("Fields");
        FieldList.addInteger("EmployeeId");
        FieldList.addString("FirstName");
        field = FieldList.AOTfindChild("FirstName");
        field.AOTsetProperty("StringSize", "50");
        FieldList.addString("LastName");
        field = FieldList.AOTfindChild("LastName");
        field.AOTsetProperty("StringSize", "50");
    
        // Set the table property to add the date effective fields.
        tableNode.AOTsetProperty("ValidTimeStateFieldType", "Date");
    
        // Add the index.
        indexNode = tableNode.AOTfindChild("Indexes");
        indexNode.AOTadd("EmpIdValidFromValidTo");
        indexNode.AOTsave();
    
        indexNode = indexNode.AOTfindChild("EmpIdValidFromValidTo");
    
        // Set the index properties.
        indexNode.AOTsetProperty("AllowDuplicates", "No");
        indexNode.AOTsetProperty("AlternateKey", "Yes");
        indexNode.AOTsetProperty("ValidTimeStateKey", "Yes");
    
        // Add the fields to the index.
        field = FieldList.AOTfindChild("EmployeeId");
        indexNode.AOTadd(field.AOTname());
        tableNode.AOTsave();
    
        // Compile and synchronize the table.
        tableNode.AOTcompile();
        appl.dbSynchronize(tableNode.applObjectId());
    
        tableNode.AOTrefresh();
    }
```

### Add Data to the Date Effective Table

The following job adds data to the date effective table created in the previous step.

```X++
    static void AddDateEffectiveTableData(Args _args)
    {
        // Add data to the TestEmployee table.
        #AOT
        TestEmployee emp;
        ;
        // Synchronize the tables.
        appl.dbSynchronize(tableNum(TestEmployee));
        
        ttsbegin;
    
        // Add records to the Employee table.
        emp.FirstName = "Molly";
        emp.LastName = "Clark";
        emp.EmployeeId = 1234567;
        emp.ValidFrom = str2date("02/09/2007", 213);
        emp.ValidTo = str2date("12/03/2007", 213);
    
        emp.insert();
    
        emp.FirstName = "Molly";
        emp.LastName = "Clark";
        emp.EmployeeId = 1234567;
        emp.ValidFrom = str2date("12/04/2007", 213);
        emp.ValidTo = str2date("08/10/2009", 213);
    
        emp.insert();
        
        ttscommit;
    }
```

## See also

[Walkthrough: Using the Query Service to Query Tables in a Hierarchy](walkthrough-using-the-query-service-to-query-tables-in-a-hierarchy.md)

[Walkthrough: Using the Query Service to Query Date Effective Tables](walkthrough-using-the-query-service-to-query-date-effective-tables.md)

