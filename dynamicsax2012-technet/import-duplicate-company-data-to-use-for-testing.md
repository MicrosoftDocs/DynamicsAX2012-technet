---
title: Import duplicate company data to use for testing
TOCTitle: Import duplicate company data to use for testing
ms:assetid: c3a0cd8d-8b02-4ae8-9670-eef2b366e19a
ms:mtpsurl: https://technet.microsoft.com/library/Hh575244(v=AX.60)
ms:contentKeyID: 39555406
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Import duplicate company data to use for testing 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

In Microsoft Dynamics AX 2009, the duplicate company feature was used extensively to copy data from one company to another. The feature was also used to build development or test environments, and deployment scenarios that moved data from one environment to another. However, this feature became obsolete in Microsoft Dynamics AX 2012.

We recommend that you use the Microsoft Dynamics AX data export and import feature to support scenarios that previously required the duplicate company feature.


> [!IMPORTANT]
> <P>Company, or DataArea, can no longer be used as a data security boundary. Because of changes that were made to the organization model in Microsoft Dynamics AX 2012, data is no longer related to a company or legal entity in a simple relationship that is defined by setting the <STRONG>SaveDataPerCompany</STRONG> metadata property of a table to <STRONG>Yes</STRONG>. Because data relationships are now defined through the <STRONG>Relations</STRONG> metadata property, it is not easy to duplicate all data that is related to a legal entity. Therefore, it may not make business sense to duplicate the data that is related to a legal entity. For example, we created organizational hierarchies in which legal entities and business units have a complex relationship. There is no parent/child relationship between business units and legal entities. Therefore, the duplication of business units based on legal entities in the system is erroneous.</P>



Follow these steps to use an existing legal entity as a template for other legal entities.

1.  Create a legal entity to use as a template.
    
    For more information, see [Create or modify a legal entity](create-or-modify-a-legal-entity.md).

2.  Set all configuration data for the legal entity.

3.  Use the Microsoft Dynamics AX data export and import feature to export the legal entity to a .dat file, such as TMP.dat.
    
    1.  Before you export data, you must create a definition group.
        
        For more information, see [Create definition groups for import and export](create-definition-groups-for-import-and-export.md).
    
    2.  To export configuration data, include the following table groups: **Reference**, **Parameter**, **Group**, **Framework**, and **Miscellaneous**.
        
        To export master data, you must also include the tables that are in the **Main** table group.
        
        Do not include the tables that are in the **Transaction**, **Transaction header**, **Transaction line**, **Worksheet**, **Worksheet header**, and **Worksheet line** table groups. These tables include transaction data.
        
        For a detailed list of all the tables in a table group, see [Table and table group reference](table-and-table-group-reference.md).

4.  In the new environment, create new legal entities, and then import the .dat file that you created into each entity individually.
    
    Shared and per-company data is imported. When other legal entities are subsequently imported into the new legal entities, the shared data is merged.
    
    For more information, see [Import data from another instance of Microsoft Dynamics AX](import-data-from-another-instance-of-microsoft-dynamics-ax.md).

You can use the Microsoft Dynamics AX data import and export feature to import and modify transaction data. However, it can be difficult to create a duplicate environment for transaction data if the **SaveDataPerCompany** property of tables is set to **No**. Instead, we recommend that you use the backup and restore functionality in Microsoft SQL Server to build demo environments in which minor configuration changes can be made to illustrate specific Microsoft Dynamics AX features.

  


