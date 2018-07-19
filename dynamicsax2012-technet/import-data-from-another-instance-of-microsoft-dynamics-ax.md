---
title: Import data from another instance of Microsoft Dynamics AX
TOCTitle: Import data from another instance of Microsoft Dynamics AX
ms:assetid: 0191bddd-7002-4839-b1c2-84468f19cafc
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa834324(v=AX.60)
ms:contentKeyID: 35132524
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Import data from another instance of Microsoft Dynamics AX 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use the export operation in Microsoft Dynamics AX to export a subset of data from a single company. You can then use the import operation to move the exported data to another company. This company can be in the same partition, in another partition that is in the same instance of Microsoft Dynamics AX, or in another partition that is in another instance of Microsoft Dynamics AX.

Before you read this topic, we strongly recommend that you read the information in [Plan data import, export, and migration](plan-data-import-export-and-migration.md).

Before you begin, make sure that the current company account is the account that you want to import data into.


> [!NOTE]
> <P>Microsoft Dynamics AX data export and import are designed to export and import tables in companies. The doInsert, doUpdate, and doDelete methods that are called by the export and import functionality cannot be overwritten. Therefore, any application logic that is written at the table level is not called during export and import operations.</P>



For more information about how import operations are processed, see [Use DAT and DEF files to export and import data](use-dat-and-def-files-to-export-and-import-data.md).

## Reliability and performance

Data import is a resource-intensive activity that can affect data integrity.


> [!WARNING]
> <P>Data import operations cannot be rolled back.</P>



Consider the following recommendations before you begin a data import:

  - If you plan to perform many import operations, we recommend that you put the data file and transaction log file for Microsoft SQL Server on separate spindles to minimize contention. For more information about best practices for the placement of SQL Server log files and data files, see [Storage Top 10 Best Practices](http://go.microsoft.com/fwlink/?linkid=216182).

  - We recommend that you or the database administrator actively manage the size of the transaction log file after large import operations. During the import process, Microsoft Dynamics AX creates staging tables, and then drops them after the import is completed. Therefore, the transaction log file is likely to grow significantly during a data import. For more information about how to manage the size of the transaction log file, see [Managing the Size of the Transaction Log File](http://go.microsoft.com/fwlink/?linkid=216188).

  - We strongly recommend that you shut down Enterprise Portal for Microsoft Dynamics AX and Microsoft SharePoint products during a data import, so that the import is the only active process that affects data. Otherwise, data can be corrupted.

  - Back up both the source data and the target data.

  - Perform all data imports outside core working hours.

## Security for importing data

When you export or import Microsoft Dynamics AX tables, the folder that you store the tables in must have permissions that are appropriately restricted. Access to the data in the following tables can expose confidential information or security information:

  - SysConfig

  - SysUserInfo

  - UserInfo


> [!NOTE]
> <P>Tables that are protected by extensible data security are protected when they are exported. However, if the same policy is not set up on the system that you import the tables into, the tables are not protected when they are imported. We strongly recommend that you configure the same policies for extensible data security on both the system that you import tables into and the system that you export tables from, to help protect your data.</P>



## Import data

1.  Click **System administration** \> **Common** \> **Data export/import** \> **Import**.

2.  On the **General** tab, select the definition group or data file that you want to import.

3.  On the **Advanced** tab, select the options that meet your needs:
    
      - **Include shared tables** – Include tables that are not specific to company accounts.
        

        > [!NOTE]
        > <P>To import shared tables from a data file or definition group, you must select <STRONG>Include shared tables</STRONG>. Otherwise, even if the definition group or data file contains shared tables, the shared tables are not imported.</P>
        > <P>By default, <STRONG>Include shared tables</STRONG> is selected.</P>
        > <P>If you import a dataset that includes shared data more than one time, for different companies, the shared data for all companies is affected by the import operation.</P>

    
      - **Include system tables** – Import data that is stored in system tables.
        

        > [!NOTE]
        > <P>In general, we recommend that you do not import system tables because the imported data can conflict with the data that is already configured in the Microsoft Dynamics AX environment.</P>
        > <P>To import system tables from a data file or definition group, you must select <STRONG>Include system tables</STRONG>. Otherwise, even if the definition group or data file contains system tables, the system tables are not imported.</P>

    
      - **Update existing record** – Update data during the import.
        
        The system checks whether each record in the import file already exists. If a record already exists, the existing data is overwritten with new data from the import file. This method is time-consuming, but it is useful when the purpose of the data import is to update existing information.
        
        Tables that do not have unique indexes do not support the **Update existing record** option.
        

        > [!IMPORTANT]
        > <P>If you are importing AIF or services-related tables, such as AifInboundPort, do not select <STRONG>Update existing record</STRONG>.</P>

    

    > [!NOTE]
    > <P>If you select both <STRONG>Update existing record</STRONG> and <STRONG>Include system tables</STRONG>, cross-company data is updated.</P>



4.  On the **Batch** tab, select the batch group that you want the import file to be processed with. All import jobs are run as batch tasks.
    

    > [!NOTE]
    > <P>Batch tasks for data import are run on Application Object Server (AOS). Therefore, the AOS service account must have access to the file that you are importing from. Make sure that you place the file in a location that the AOS service account has access to.</P>



5.  When the data import is completed, the Infolog displays information about the number of records that were imported. The **Select tables** form also displays import information on the **Log files** tab.

## Tables that you should not import data in to

Several tables cannot be exported from Microsoft Dynamics AX. These tables are known as blocked tables. Data can be imported into blocked tables. However, we recommend that you not import data into blocked tables because most of these tables contain metadata. Therefore, if you import data into these tables, your Microsoft Dynamics AX installation can be corrupted. The following list includes the tables that you should not import data in to.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><p>LanguageTable</p></td>
<td><p>SqlDictionary</p></td>
</tr>
<tr class="even">
<td><p>SecurableObject</p></td>
<td><p>SqlParameters</p></td>
</tr>
<tr class="odd">
<td><p>SecurityCondition</p></td>
<td><p>SqlStatistics</p></td>
</tr>
<tr class="even">
<td><p>SecurityEntryPointLink</p></td>
<td><p>SqlStorage</p></td>
</tr>
<tr class="odd">
<td><p>SecurityPermission</p></td>
<td><p>SysExpImpRecords</p></td>
</tr>
<tr class="even">
<td><p>SecurityRole</p></td>
<td><p>SysInheritanceRelations</p></td>
</tr>
<tr class="odd">
<td><p>SecurityRoleCondition</p></td>
<td><p>SysLastValue</p></td>
</tr>
<tr class="even">
<td><p>SecurityRoleExplodedGraph</p></td>
<td><p>SysLicenseCodeSort</p></td>
</tr>
<tr class="odd">
<td><p>SecurityRolePermissionOverride</p></td>
<td><p>SysOld2NewRecId</p></td>
</tr>
<tr class="even">
<td><p>SecurityRoleTaskGrant</p></td>
<td><p>SysSetupLog</p></td>
</tr>
<tr class="odd">
<td><p>SecuritySubRole</p></td>
<td><p>SystemSequences</p></td>
</tr>
<tr class="even">
<td><p>SecuritySubTask</p></td>
<td><p>SysTraceTable</p></td>
</tr>
<tr class="odd">
<td><p>SecurityTask</p></td>
<td><p>SysXppAssembly</p></td>
</tr>
<tr class="even">
<td><p>SecurityTaskEntryPoint</p></td>
<td><p>TimeZonesList</p></td>
</tr>
<tr class="odd">
<td><p>SecurityTaskExplodedGraph</p></td>
<td><p>TimeZonesRulesData</p></td>
</tr>
<tr class="even">
<td><p>SecurityTaskPermission</p></td>
<td><p>UtilElements</p></td>
</tr>
<tr class="odd">
<td><p>SecurityTaskPermissionOverride</p></td>
<td><p>UtilIdElements</p></td>
</tr>
<tr class="even">
<td><p>SqlDescribe</p></td>
<td><p>UtilIdElementsOld</p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>UtilModels</p></td>
</tr>
</tbody>
</table>


## See also

[Export data to another instance of Microsoft Dynamics AX](export-data-to-another-instance-of-microsoft-dynamics-ax.md)

  


