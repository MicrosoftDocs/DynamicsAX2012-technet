---
title: 'Walkthrough: Creating Reports in the AOT (MorphX Reporting Tools)'
TOCTitle: 'Walkthrough: Creating Reports in the AOT'
ms:assetid: 3f060743-32bd-4d08-9112-e5086c392adc
ms:mtpsurl: https://technet.microsoft.com/library/Cc967382(v=AX.60)
ms:contentKeyID: 35290297
author: tonyafehr
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# Walkthrough: Creating Reports in the AOT (MorphX Reporting Tools) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create reports that display data that is retrieved by using a query. You can create these reports by using the Application Object Tree (AOT) or by using the **Report Wizard**.


> [!NOTE]
> <P>To access the <STRONG>Report Wizard</STRONG>, click <STRONG>Tools</STRONG> &gt; <STRONG>Wizards</STRONG> &gt; <STRONG>Report Wizard</STRONG>.</P>



In this walkthrough, you will use the AOT to create a report. You will perform the following tasks to create a report by using the AOT:

  - Create and populate tables to use as the data sources for the report

  - Create the report


> [!NOTE]
> <P>The example companies, organizations, products, domain names, e-mail addresses, logos, people, places, and events depicted herein are fictitious.&nbsp; No association with any real company, organization, product, domain name, email address, logo, person, places, or events is intended or should be inferred.</P>



## Creating Tables to Use as the Data Sources for the Report

In this procedure you create a table to use as a data source for the report. For more information, see [How to: Create Tables](https://technet.microsoft.com/library/aa882181\(v=ax.60\)).

### To create a table to use as a data source for the report

1.  In the AOT, expand **Data Dictionary**, right-click **Tables**, and then click **New Table**.

2.  Right-click the new table and then click **Properties**.

3.  On the **Properties** sheet of the new table, set the **Name** property to **Employee**.

4.  In the AOT, expand the **Employee** node, right-click **Fields**, point to **New**, and then click **String**.

5.  On the **Properties** sheet of the new field, set the **Name** property to **EmpId**.

6.  In the AOT, expand the **Employee** node in the AOT, right-click **Fields**, point to **New**, and then click **String**.

7.  On the **Properties** sheet of the new field, set the **Name** property to **FirstName**.

8.  In the AOT, expand the **Employee** node in the AOT, right-click **Fields**, point to **New**, and then click **String**.

9.  On the **Properties** sheet of the new field, set the **Name** property to **LastName** and set the **StringSize** property to **25**.

10. In the AOT, expand the **Employee** node, right-click **Fields**, point to **New**, and then click **String**.

11. On the **Properties** sheet of the new field, set the **Name** property to **DeptId**.

In this procedure you create a second table that will be used as a data source for the report.

### To create another table to use as a data source for the report

1.  In the AOT, expand **Data Dictionary**, right-click **Tables**, and then click **New Table**.

2.  Right-click the new table and then click **Properties**.

3.  On the **Properties** sheet of the new table, set the **Name** property to **Department**.

4.  In the AOT, expand the **Department** node, right-click **Fields**, point to **New**, and then click **String**.

5.  On the **Properties** sheet of the new field, set the **Name** property to **DeptId**.

6.  In the AOT, expand the **Department** node, right-click **Fields**, point to **New**, and then click **String**.

7.  On the **Properties** sheet of the new field, set the **Name** property to **DeptName** and set the **StringSize** property to **25**.

8.  In the AOT, expand the **Department** node, right-click **Fields**, point to **New**, and then click **String**.

9.  On the **Properties** sheet of the new field, set the **Name** property to **Location** and set the **StringSize** property to **25**.

## Populating the Tables

Now you can populate the tables with data that will be displayed in the report.


> [!NOTE]
> <P>You can create forms that you can use to add data to tables, but for this walkthrough it is not necessary.</P>



### To populate the Employee table

1.  In the AOT, expand **Data Dictionary**, expand the **Tables** node, right-click **Employee**, and then click **Open**.

2.  Enter the following data into the **Employee** table and save your changes.
    

    > [!NOTE]
    > <P>Press CTRL+N to add a new row of data or ALT+F9 to delete a row.</P>

    
    <table>
    <colgroup>
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    <col style="width: 25%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>EmpId</p></th>
    <th><p>FirstName</p></th>
    <th><p>LastName</p></th>
    <th><p>DeptId</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>0001</p></td>
    <td><p>Maria</p></td>
    <td><p>Cameron</p></td>
    <td><p>Acct</p></td>
    </tr>
    <tr class="even">
    <td><p>0002</p></td>
    <td><p>Eran</p></td>
    <td><p>Havel</p></td>
    <td><p>Acct</p></td>
    </tr>
    <tr class="odd">
    <td><p>0003</p></td>
    <td><p>Pal</p></td>
    <td><p>Petersen</p></td>
    <td><p>Mfg</p></td>
    </tr>
    <tr class="even">
    <td><p>0004</p></td>
    <td><p>Kim</p></td>
    <td><p>Ralls</p></td>
    <td><p>Mfg</p></td>
    </tr>
    <tr class="odd">
    <td><p>0005</p></td>
    <td><p>Rebecca</p></td>
    <td><p>Laszlo</p></td>
    <td><p>IT</p></td>
    </tr>
    <tr class="even">
    <td><p>0006</p></td>
    <td><p>Nicholas</p></td>
    <td><p>Christopoulos</p></td>
    <td><p>IT</p></td>
    </tr>
    <tr class="odd">
    <td><p>0007</p></td>
    <td><p>Erik</p></td>
    <td><p>Anderson</p></td>
    <td><p>Eng</p></td>
    </tr>
    <tr class="even">
    <td><p>0008</p></td>
    <td><p>Ben</p></td>
    <td><p>Smith</p></td>
    <td><p>Eng</p></td>
    </tr>
    </tbody>
    </table>


3.  

### To populate the Department table

1.  In the AOT, expand **Data Dictionary**, expand the **Tables** node, right-click **Department**, and then click **Open**.

2.  Enter the following data into the **Department** table and save your changes.
    

    > [!NOTE]
    > <P>Press CTRL+N to add a new row of data or ALT+F9 to delete a row.</P>

    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>DeptId</p></th>
    <th><p>DeptName</p></th>
    <th><p>Location</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Acct</p></td>
    <td><p>Accounting</p></td>
    <td><p>Fargo, ND</p></td>
    </tr>
    <tr class="even">
    <td><p>Mfg</p></td>
    <td><p>Manufacturing</p></td>
    <td><p>Fargo, ND</p></td>
    </tr>
    <tr class="odd">
    <td><p>IT</p></td>
    <td><p>Information Technology</p></td>
    <td><p>Fargo, ND</p></td>
    </tr>
    <tr class="even">
    <td><p>Eng</p></td>
    <td><p>Engineering</p></td>
    <td><p>Washington D.C.</p></td>
    </tr>
    </tbody>
    </table>


3.  

## Creating the Report

In this procedure you will use the AOT to create a report that displays information from the table you created.

### To create the report by using the AOT

1.  In the AOT, right-click **Reports**, and then click **New Report**.

2.  Right-click the new report and then click **Properties**.

3.  On the **Properties** sheet of the new report, set the **Name** property to **EmployeeReport**.

## Creating a Query for the Report

You can specify the data to display and the way to present the data in the report by creating a query in the AOT. For more information, see [How to: Create Queries by using the AOT](https://technet.microsoft.com/library/bb314753\(v=ax.60\)).


> [!NOTE]
> <P>You can also create a query by using X++ (see <A href="https://technet.microsoft.com/library/aa638454(v=ax.60)">How to: Create Queries by Using X++</A>). Under the <STRONG>EmployeeReport</STRONG> node, right-click <STRONG>Methods</STRONG>, point to <STRONG>Override Method</STRONG>, and then click <STRONG>Fetch</STRONG>. Use the Query system classes to create a query. For more information, see <A href="how-to-override-the-fetch-method-to-filter-data-for-reports-morphx-reporting-tools.md">How to: Override the fetch Method to Filter Data for Reports (MorphX Reporting Tools)</A>.</P>



First you must specify the data sources to use in the query and the relationship between the two data sources (tables). In this case, the DeptId field is the primary key of the Department table and is a foreign key of the Employee table. For more information, see [How to: Add Multiple Data Sources to a Query](https://technet.microsoft.com/library/aa880078\(v=ax.60\)).

### To join the Employee table with the Department table in the report

1.  In the AOT, expand the **Reports** node, expand the **EmployeeReport** node, expand the **Data** **Sources** node, expand the **Query** node, right-click the nested **Data Sources** node, and then click **New Data Source**.

2.  On the **Properties** sheet of the new data source, set the **Table** property to **Employee** and set the **Name** property to **Employee**.

3.  Under the new **Employee(Employee)** node, right-click the nested **Data Sources** node, and then click **New Data Source**.

4.  On the **Properties** sheet of the new data source, set the **Table** property to **Department** and set the **Name** property to **Department**.

5.  Under the new **Department(Department)** node, right-click **Relations**, and then click **New Relation**.

6.  On the **Properties** sheet of the new relation, set the **JoinDataSource** property to **Employee**, set the **Field** property to **DeptId**, and set the **RelatedField** property to **DeptId**.

## Specifying Query Properties

You can specify what data is returned and how it is displayed in the report by specifying things like a range or a sort order. For more information, see [How to: Create Queries by using the AOT](https://technet.microsoft.com/library/bb314753\(v=ax.60\)). For this report, specify that the query return all employees in Fargo, ND. Create a new range on the Location field of the Department data source.

### To define the range of data to display in the report

1.  In the AOT, expand the **Reports** node, expand the **EmployeeReport** node, expand the **Data Sources** node, expand the **Query** node, expand the nested **Data Sources** node, expand the **Employee(Employee)** node, expand the nested **Data Sources** node, expand the **Department(Department)** node, right-click **Ranges**, and then click **New Range**.

2.  On the **Properties** sheet of the new range, set the **Field** property to **Location**, set the **Name** property to **Location**, and set the **Value** property to **="Fargo, ND"**.
    

    > [!NOTE]
    > <P>You must include the quotation marks in this case so that the comma is not treated as a delimiter.</P>



### To specify the order by which to display the data in the report

1.  In the AOT, expand the **Reports** node, expand the **EmployeeReport** node, expand the **Data Sources** node, expand the **Query** node, expand the nested **Data Sources** node, expand the **Employee(Employee)** node, right-click **Order By**, and then click **New Field**.

2.  On the **Properties** sheet of the new control, set the **DataSource** property to **Employee**, set the **Field** property to **LastName**, and set the **Direction** property to **Ascending**.

## Creating a Report Design

### To create a report design

1.  In the AOT expand the **Reports** node, expand the **EmployeeReport** node, right-click **Designs**, and then click **New Report Design**.

2.  On the Properties sheet of the new report design, set the **Name** property to **EmployeeReportDesign**.
    

    > [!NOTE]
    > <P>To base the report design on a template, set the <STRONG>ReportTemplate</STRONG> property to one of the predefined report templates.</P>



3.  Right-click the **EmployeeReportDesign** node and then click **Generate Design**.

4.  Expand the **Generated Design** node, expand the **Section Group: Employee** node, expand the **Body:Employee\_Body** node, expand the **Section Group: Department** node, right-click **Body:Department\_Body**, point to **New control**, and then click **Field from Employee**.

5.  Drag the **EmpId**, **LastName**, and **FirstName** fields onto the **Body:Department\_Body** node.

6.  Right-click **Body:Department\_Body**, point to **New control**, and then click **Field from Department**.

7.  Drag the **DeptId**, **DeptName**, and **Location** fields onto the **Body:Department\_Body** node.

8.  Arrange the fields in the order in which you want them to appear in the report.
    

    > [!NOTE]
    > <P>You can also edit the report design by right-clicking the report design and then clicking <STRONG>Edit</STRONG>. You can then move fields around in the Visual Report Designer.</P>



## Viewing the Report

### To view the new report

1.  In the AOT, expand the **Reports** node, right-click **EmployeeReport**, and then click **Open**.

2.  Click **OK** twice and verify the data that you entered into the tables. **Erik Anderson** and **Ben Smith** should not appear in the report because their department is not in Fargo, ND.

## See also

[How to: Create Queries by using the AOT](https://technet.microsoft.com/library/bb314753\(v=ax.60\))

[How to: Add Multiple Data Sources to a Query](https://technet.microsoft.com/library/aa880078\(v=ax.60\))

[How to: Create Queries by Using X++](https://technet.microsoft.com/library/aa638454\(v=ax.60\))

[How to: Override the fetch Method to Filter Data for Reports (MorphX Reporting Tools)](how-to-override-the-fetch-method-to-filter-data-for-reports-morphx-reporting-tools.md)

