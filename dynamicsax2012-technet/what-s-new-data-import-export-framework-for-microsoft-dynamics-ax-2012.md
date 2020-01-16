---
title: "What's new: Data Import/Export Framework for Microsoft Dynamics AX 2012"
TOCTitle: Data Import/Export Framework for Microsoft Dynamics AX 2012
ms:assetid: 3ebed1f3-2574-4cf7-a0f3-2f44056df723
ms:mtpsurl: https://technet.microsoft.com/library/Dn507098(v=AX.60)
ms:contentKeyID: 59623188
author: Khairunj
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Data Import/Export Framework for Microsoft Dynamics AX 2012 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

The Data Import/Export Framework is a feature that helps you export data and import it into Microsoft Dynamics AX. It is included in Microsoft Dynamics AX 2012 R3. Prior to Microsoft Dynamics AX 2012 R3, it was available as a separate download. For more information about Data Import/Export Framework, see [Data import/export framework user guide (DIXF, DMF)](data-import-export-framework-user-guide-dixf-dmf.md).

## Releases

The following sections describe the features that have been added in each release.

## Microsoft Dynamics AX 2012 R3

Date: May 2014

This release includes the following features:

  - A new security group for the Data Import/Export Framework, **Microsoft Dynamics AX Data Import Export Framework Service User**.

  - Additional entities: Resource requirements, Operations, and Route relation.

  - Staging-level validation of data that contains role separators.

  - Support for SQL Server 2014.

  - Additional data sources when you use Data Import/Export Framework as an Application Integration Framework (AIF) service. These include files, ODBC, and other Microsoft Dynamics AX instances. You can also now use a Data Import/Export Framework as an AIF service to export data to a file.

  - Staging-level conversion of fields that use the GUID data type.

  - The Custom Entity wizard now creates the class and functions of a new entity, in addition to the staging table, project, and query.

  - Error files for data import/export operations are now created in XML instead of in plain text for easier parsing.

  - You can now use a role separator in export as well as import operations, to delimit multiple values in the same field.

## Cumulative update 7 release

Date: October 2013

This release is available only for cumulative update 7 for Microsoft Dynamics AX 2012 R2.

[Download cumulative update 7](https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%2cen-us%2c2885603)

This release includes the following features:

  - Additional entities for configuration, Microsoft Project, Fiscal books, Microsoft Dynamics AX 2012 for Retail

  - Support for XML data sources

  - Support for Microsoft Excel data sources

  - Role-based security for processing groups

  - UI for comparing entities across companies

  - UI for copying entities across companies

## Initial release

Date: March 2013

[Download the release from InformationSource](https://go.microsoft.com/fwlink/?linkid=255246)

This release includes the following features:

  - 70 out-of-box entities.

  - Custom entity creation wizard.

  - Support for Microsoft Dynamics AX 2012 RTM, Microsoft Dynamics AX 2012 Feature Pack, and Microsoft Dynamics AX 2012 R2.

  - Support for Microsoft SQL Server 2008 and Microsoft SQL Server 2012.

  - Import entity data from multiple sources: files (delimited and fixed width) and Open Database Connectivity (ODBC).

  - Export entity data from AX 2012 to other AX 2012 environments or files.

  - Copy entity data across legal entities.

  - Mapping UI.

  - Support for parallel execution from staging to target by using several batch task values.

  - Use a folder as input for running periodic imports.

  - Error handling: Skip rows that contain errors.

  - Set-based operations for moving data from staging to target.

  - Support for default values.

  - Support for number sequences.

  - Support for external key mapping.

  - Source to target in a single step.

  - Support for multiple instances of Microsoft Dynamics AX Application Object Server (AOS).

  


