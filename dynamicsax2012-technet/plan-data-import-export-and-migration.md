---
title: Plan data import, export, and migration
TOCTitle: Plan data import, export, and migration
ms:assetid: a05289fb-0f8f-4563-be3c-7c840bfea7e1
ms:mtpsurl: https://technet.microsoft.com/library/Aa548629(v=AX.60)
ms:contentKeyID: 35132789
author: Khairunj
ms.date: 08/20/2014
mtps_version: v=AX.60
---

# Plan data import, export, and migration 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the tools and strategies that you can use when you are planning to import or export Microsoft Dynamics AX data. The topic also describes how to plan to move data from one enterprise resource planning (ERP) system to another. Finally, the topic describes performance and security considerations when you import and export data.

## Common import and export scenarios

Data import and export are performed for many different business reasons throughout the life cycle of an implementation.

Initial configuration scenarios:

  - Export configured entities, and import them into another system.

  - Import table-level data into another system, without references.

  - Import master data and opening balances.

  - Copy entity data to another legal entity.

  - Export and import configuration parameters.

  - Export and import configurations for new companies.

Ongoing maintenance scenarios:

  - Export and import table-level data, together with references.

  - Copy business data from a production environment to a new non-production environment, such as test or development.

  - Copy business data between non-production environments, for example, from a test or user acceptance test environment into a development environment for troubleshooting.

  - Data entry.

  - On a recurring basis, update data from external sources, based on events. For example, import updated standards codes every month.

  - As required, update large data sets from external sources.

  - Archive business data from a production database.

## Select a tool

Data can be imported into and exported from Microsoft Dynamics AX by using various tools and techniques. Before you select a tool, you should understand your business requirements, the available data, and what you want the outcome to be.


> [!IMPORTANT]
> <P>All of the following tools can be used to import and export data, but every operation that manipulates data has risks. It is your responsibility to create regular backups of your data before you use any tool. We strongly recommend that you test your particular uses of the tools you use to determine whether they meet your needs.</P>



The following table lists the common import and export scenarios, and the tools that customers and partners can use.

<table style="width:100%;">
<colgroup>
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
<col style="width: 11%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Scenario</p></th>
<th><p>Data Import/Export Framework</p></th>
<th><p>Microsoft Dynamics ERP RapidStart Services</p></th>
<th><p>In-product import/export (.DAT/Def)</p></th>
<th><p>Microsoft Excel import/export</p></th>
<th><p>Services and Microsoft Dynamics AX Application Integration Framework (AIF)</p></th>
<th><p>Test Data Transfer Tool (beta)</p></th>
<th><p>Microsoft SQL Server backup and recovery</p></th>
<th><p>Intelligent Data Management Framework</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Export configured entities, and import them into another system</p></td>
<td><p>Best</p></td>
<td><p>Do not use</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Import master data and opening balances</p></td>
<td><p>Best</p></td>
<td><p>Possible</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Copy entity data to another legal entity</p></td>
<td><p>Best</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Possible</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Export and import configuration parameters</p></td>
<td><p>Best when data is in unrelated tables</p></td>
<td><p>Best when data is in multiple related tables</p></td>
<td><p></p></td>
<td><p>Possible</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Export and import configurations for new companies</p></td>
<td><p>Possible</p></td>
<td><p>Best</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Export and import table-level data together with references</p></td>
<td><p></p></td>
<td><p>Do not use</p></td>
<td><p>Possible</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Export and import table-level data without references</p></td>
<td><p>Possible</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Possible using table-level import</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>On a recurring basis, update data from external sources, based on events</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Best</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Infrequently, update data from external sources and large data sets</p></td>
<td><p>Best</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Possible</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Data entry</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Best. Use with services.</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Copy business data to a non-production environment</p></td>
<td><p>Possible</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Best</p></td>
<td><p>Possible</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Copy business data from a test environment to a development environment for troubleshooting</p></td>
<td><p>Possible</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Best</p></td>
<td><p>Possible</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p>Copy business data to a new production environment</p></td>
<td><p>Possible</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Do not use.</p></td>
<td><p>Best</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p>Archive business data from a production database</p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p></p></td>
<td><p>Best</p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>The previous table does not describe how to copy a company. Microsoft Dynamics AX 2012 does not support the creation of a duplicate company. To duplicate data from one company to another, one entity at a time, you can use the Data Import/Export Framework.</P>



## Microsoft Dynamics AX 2012 Data Import/Export Framework

The Data Import/Export Framework is an extension that helps you import data into Microsoft Dynamics AX 2012 from files, Open Database Connectivity (ODBC) data sources, and Microsoft Dynamics AX tables. You can import predefined entities, or you can create custom entities for import. You can modify data as it is imported, and you can also verify that data meets specific rules.

Different versions of the Data Import/Export Framework are available depending on what release of Microsoft Dynamics AX 2012 you have installed. To see what version to use, as well as for documentation and information about the Data Import/Export Framework, see the [Data import/export framework user guide (DIXF, DMF)](data-import-export-framework-user-guide-dixf-dmf.md).

**Intended users:** Application users, developers, and functional users

**Key features:**

  - Support for import from files, ODBC data sources, and Microsoft Dynamics AX tables

  - Bulk processing

  - Synchronous processing

**Recommended uses:** Use this tool when you must perform the following tasks:

  - Import data from another ERP system that uses dissimilar data structures. You can use the Data Import/Export Framework to map data to Microsoft Dynamics AX entities.

  - Import data that requires transformation, such as changes to number sequences.

**Underlying technology:** SQL Server Integration Services

## RapidStart Services

RapidStart Services lets partners and customers configure an installation of Microsoft Dynamics AX by using a cloud-based, interview-style questionnaire. The questionnaire uses general terminology about business processes instead of terms that are specific to Microsoft Dynamics AX. Partners can create, maintain, and reuse configurations that reflect their custom solutions. Partners can also create additional question groups and questions to enlarge the scope of a configuration.

RapidStart Services is available for download from [CustomerSource](https://go.microsoft.com/fwlink/?linkid=210925) and [PartnerSource](https://go.microsoft.com/fwlink/?linkid=210926).

**Intended users:** Partners and application users

**Recommended uses:** Use RapidStart Services to create an initial configuration that can then be imported into other instances of Microsoft Dynamics AX.

**Underlying technology:** Data Import/Export Framework

## In-product import/export (.DAT/Def)

In-product import/export is a mechanism for transferring data between different Microsoft Dynamics AX instances. In-product import/export is available from **System administration** \> **System administration**.

**Intended users:** Functional users and developers

**Uses:** You can use this tool in the following situations, but other tools may be available and more suitable in these situations. See earlier section, “Select a tool”, for a list of common import and export scenarios.

  - The source and target are Microsoft Dynamics AX instances.

  - No cleansing of data by end users is required.

  - You are moving data from one company to another.
    

    > [!NOTE]
    > <P>Data can be exported from a company that is in one partition and imported into another company that is in another partition.</P>
    > <P>Data cannot be imported into and exported from multiple companies at the same time.</P>



**Non-recommended uses:** We recommend that you not use this tool when you must complete the following tasks:

  - Set up master data.

  - Move configuration metadata to a new environment.

For more information about Microsoft Dynamics AX export and import, see [Use DAT and DEF files to export and import data](use-dat-and-def-files-to-export-and-import-data.md).

## Excel Add-in for Microsoft Dynamics AX

Excel import is a tool that can be used for data that is in an Excel format or in a comma-separated list. You can use predefined or custom templates to help users import data.

**Intended users:** Application users

**Recommended uses:** Use this tool in the following situations:

  - Minimal data cleansing by end users is required.

  - You are handling low to medium data volumes (\<10,000 records).

  - You are working with simple data structures that can easily be flattened, such as a list of items.

  - No business logic is required outside an existing document service.

**Non-recommended uses:** Large data sets, content that requires the application of business logic, and data sets that require data cleansing

For more information about Excel import, see [Using the Microsoft Dynamics AX Add-in for Excel](using-the-microsoft-dynamics-ax-add-in-for-excel.md).

## AIF web services

You can use AIF web services to import and export data. AIF web services are included with Microsoft Dynamics AX.

**Intended users:** Application users and system administrators for non-customized web services, and developers for customized web services

**Recommended uses:** Use this tool when you must complete the following tasks:

  - Import many similar records, and repeat the same import at regular intervals. In this scenario, use AIF web services that use inbound ports and pipelines.

  - Take data that is in an existing file format, such as an XML export from another system, and process the data so that it matches the schema that is expected by existing or customized AIF document services. You can author transformations in either XSLT or managed code. Document services must be customized if the underlying tables and entities have been customized.

  - Access Microsoft Dynamics AX business logic. You might have to use this approach when the structure of the data is not easily represented as tables, or if the web service that you want to use is not supported by the Excel Add-in.

For more information about how to use AIF, see [Services and Application Integration Framework (AIF)](services-and-application-integration-framework-aif.md).

## Test Data Transfer Tool (beta)

The Microsoft Dynamics AX 2012 Test Data Transfer Tool (beta) is a command-line tool that exports data from and imports data into a Microsoft Dynamics AX 2012 business database in a non-production (development or test) environment.

The Test Data Transfer Tool (beta) is available from the [InformationSource services download page](https://go.microsoft.com/fwlink/?linkid=228148). For documentation and information about the Test Data Transfer Tool (beta), see [Test Data Transfer Tool (beta) for Microsoft Dynamics AX 2012](test-data-transfer-tool-beta-for-microsoft-dynamics-ax-2012.md).


> [!IMPORTANT]
> <P>Importing data into a production environment from the Test Data Transfer Tool (beta) is not supported. The Test Data Transfer Tool (beta) can be used only to export data from a production environment, and then import the data into a test or development environment.</P>



**Intended users:** Only advanced users should use this tool. You should be a database administrator or a developer who has experience using SQL Server. You must also have permissions to read from or write directly to the Microsoft Dynamics AX database that you are working with, and to execute applications directly on the computer that is hosting the database.

**Recommended uses:** Use this tool when you must complete the following tasks:

  - Export or import a large multi-company data set in a non-production environment.

  - Move data between non-production Microsoft Dynamics AX environments that have slightly different customizations.

  - Store business data in a version control system.

  - Export or import data without running an instance of Microsoft Dynamics AX Application Object Server (AOS) in a non-production environment.

**Key features:**

  - Because the import makes minimal changes to the data, the tool helps guarantee that the data remains stable over time. For example, the tool never renumbers RecIDs.

  - The data file format is text-based. Therefore, the data file can be compared with earlier versions and can be stored in a version control system.

  - The data file format is a standard format that is produced and understood by the SQL Server bcp Utility.

  - The tool enables export filtering, so that specified tables, columns, or rows can be easily excluded from the export.

  - The tool updates entity IDs, such as table IDs, class IDs, and extended data type IDs, so that the IDs match the IDs of the target system.

  - The tool handles differences between builds of Microsoft Dynamics AX 2012 that often occur during development. Therefore, data can often be imported without user intervention, even when the table definitions have changed. For example, renaming tables or fields does not prevent import.

**Key considerations:**

  - Importing data into a production environment from the Test Data Transfer Tool (beta) is not supported.

  - The tool does not make sure that any data that you export is complete or coherent. However, the tool does export the data that you ask it to export.

  - The tool does not make sure that any data that you import produces a complete or coherent database. However, the tool does import the data that you ask it to import.

**Underlying technology:** SQL Server bcp Utility

## SQL Server backup and recovery / restore

You must use SQL Server backup and recovery to move business data to a new environment. Before the restored database can function in the new environment, you must adjust certain values, such as server names, domain names, user accounts, and URLs. For more information, see the blog post [Moving between Microsoft Dynamics AX 2012 Environments](https://blogs.msdn.com/b/axsupport/archive/2011/11/07/moving-between-microsoft-dynamics-ax-2012-environments.aspx).

**Intended users:** System administrators and database administrators

**Recommended uses:** Use this tool when you must perform the following tasks:

  - Archive data to another database.

  - Frequently manage database size.

**Underlying technology:** SQL Server Integration Services

## Intelligent Data Management Framework

The Intelligent Data Management Framework for Microsoft Dynamics AX (IDMF) lets system administrators optimize the performance of Microsoft Dynamics AX installations by making it easier to archive data, and maintain an optimal database size.

The IDMF is available from the [InformationSource services download page](https://go.microsoft.com/fwlink/?linkid=228149). For documentation and information about IDMF, see [Microsoft Dynamics AX Intelligent Data Management Framework (IDMF)](microsoft-dynamics-ax-intelligent-data-management-framework-idmf.md).

**Intended users:** System administrators and database administrators

**Recommended uses:**

## Manual data entry

Use Microsoft Dynamics AX forms to enter data, and to copy and paste some data for low-volume data entry. This approach helps guarantee that all required business logic is performed.

## Comparing tools

The following table provides a deeper comparison of the tools.

<table>
<colgroup>
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
<col style="width: 12%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Tool</p></th>
<th><p>Performance considerations</p></th>
<th><p>Recommended size of the data files</p></th>
<th><p>Required type of processing</p></th>
<th><p>Import type</p></th>
<th><p>Processing location</p></th>
<th><p>Required knowledge of Microsoft Dynamics AX</p></th>
<th><p>Support for custom code</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Data Import/Export Framework</p></td>
<td><p>Good for bulk data, server side</p></td>
<td><p>Large</p></td>
<td><p>Synchronous or asynchronous</p></td>
<td><p></p>
<p>Files</p>
<p>ODBC data sources</p>
<p>Microsoft Dynamics AX tables</p></td>
<td><p>Server</p></td>
<td><p>Minimal to thorough, depending on the scenario</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>RapidStart Services</p></td>
<td><p>Not applicable (configuration data only)</p></td>
<td><p>Not applicable (configuration data only)</p></td>
<td><p>Synchronous</p></td>
<td><p>Configuration data only</p></td>
<td><p>Not applicable (configuration data only)</p></td>
<td><p>None</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>Excel Add-in</p></td>
<td><p>Good for small to medium data size</p></td>
<td><p>Small to medium</p></td>
<td><p>Synchronous</p></td>
<td><p>Files</p></td>
<td><p>Client</p></td>
<td><p>Minimal to thorough, depending on the scenario</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>In-product import/export (.DAT/Def)</p></td>
<td><p>Good for data that has fewer than three levels of related tables</p></td>
<td><p>Large</p></td>
<td><p>Synchronous or asynchronous</p></td>
<td><p>Microsoft Dynamics AX tables</p></td>
<td><p>Client or server</p></td>
<td><p>Thorough</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>AIF web services</p></td>
<td><p>Row-based processing</p></td>
<td><p>Any size, row-based processing only</p></td>
<td><p>Synchronous or asynchronous</p></td>
<td><p>XML files</p>
<p>WCF</p></td>
<td><p>Server</p></td>
<td><p>Thorough</p></td>
<td><p>Yes</p></td>
</tr>
<tr class="even">
<td><p>Test Data Transfer Tool (beta)</p></td>
<td><p>Good for moving an entire business database, to a non-production server, server-side processing</p></td>
<td><p>Full database</p></td>
<td><p>Synchronous</p></td>
<td><p>Database</p></td>
<td><p>Server</p></td>
<td><p>Thorough</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>Manual data entry</p></td>
<td><p></p></td>
<td><p>Small to medium</p></td>
<td><p>Synchronous</p></td>
<td><p></p></td>
<td><p>Client</p></td>
<td><p>Not deep</p></td>
<td><p>No</p></td>
</tr>
</tbody>
</table>


## Prepare to import data

If you are moving from another ERP system to Microsoft Dynamics AX, you must import master and reference data.


> [!NOTE]
> <P>We recommend that you not import transactional data or historical data into Microsoft Dynamics AX. Instead, close all open transactions that you can before import, so that totals can be imported. Maintain the database that contained your previous transactional data for reporting and compliance purposes.</P>



Data import is a complex process that usually requires many iterations. The import process includes the following general steps:

1.  Identify the data in your existing system that must be imported.

2.  Consider cleaning up the data in your existing system. For example, determine whether old records can be deleted or archived, whether the current database contains duplicate records, and whether you want to change numbering schemes.

3.  Become familiar with the relevant data structures in Microsoft Dynamics AX that the data from your existing system must be moved to.
    

    > [!NOTE]
    > <P>Data from one table in another system might have to be moved into multiple tables in Microsoft Dynamics AX.</P>



4.  Based on the information earlier in this topic, determine the appropriate tools and techniques for the data that you must migrate.

5.  Prepare a test Microsoft Dynamics AX environment.
    

    > [!NOTE]
    > <P>The required configuration for master records must be completed before you import data.</P>



6.  Create a backup of your existing system and your Microsoft Dynamics AX environment before you import any data.

7.  Perform a trial import of all types of data that are required.
    

    > [!NOTE]
    > <P>Expect to encounter errors the first time that you perform an import. Review the errors that you encounter, make any fixes that are required, and perform the import again.</P>



## Reliability and performance

Data export and import are resource-intensive activities that can affect data integrity.


> [!WARNING]
> <P>Data import operations cannot be rolled back.</P>



Consider the following recommendations before you begin import or export:

  - Plan to first perform a backup of both the source and target data.

  - Data import should be the only process that is running that affects data.
    

    > [!WARNING]
    > <P>We strongly recommend that you shut down Enterprise Portal for Microsoft Dynamics AX and SharePoint Products during data import. Otherwise, data might become corrupted.</P>



  - Perform all exports and imports outside core working hours, preferably in a non-production environment.

## Security and personally identifiable information

When you export or import Microsoft Dynamics AX tables, store them in a folder that has appropriately restrictive permissions. Many tables in Microsoft Dynamics AX contain sensitive information, such as the global address book tables and the UserInfo tables. If you allow table data to be edited and then imported into the system, you risk providing increased access to the Microsoft Dynamics AX system.

## See also

[Data import/export framework user guide (DIXF, DMF)](data-import-export-framework-user-guide-dixf-dmf.md)

[Use Microsoft Excel to import and export data](use-microsoft-excel-to-import-and-export-data.md)

[Use DAT and DEF files to export and import data](use-dat-and-def-files-to-export-and-import-data.md)

[Services and Application Integration Framework (AIF)](services-and-application-integration-framework-aif.md)

[Test Data Transfer Tool (beta) for Microsoft Dynamics AX 2012](test-data-transfer-tool-beta-for-microsoft-dynamics-ax-2012.md)

  


