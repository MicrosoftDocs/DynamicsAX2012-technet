---
title: 'How to: Optimize a Model Store for Runtime'
TOCTitle: 'How to: Optimize a Model Store for Runtime'
ms:assetid: 84cd8b9d-fc39-45d9-8115-78383e2996b6
ms:mtpsurl: https://technet.microsoft.com/library/Hh433531(v=AX.60)
ms:contentKeyID: 36941319
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# How to: Optimize a Model Store for Runtime 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to optimize a model store after changes have been made to the models that it contains. The optimization commands perform a series of steps that optimize the model store for run-time performance. As part of this process, the database that contains the model store is re-indexed and has a DBCC SHRINKDATABASE command performed on it.


> [!IMPORTANT]
> <P>By default, the optimization steps that this topic describes are performed when a model is installed for the first time. These steps are also performed if the number of elements in a model increases by more than 50 percent when the model is reimported, or when the model store that contains the model is imported.</P>



We recommend that you manually optimize a model store after you have completed significant deletions, insertions, or updates.


> [!IMPORTANT]
> <P>In versions of Microsoft Dynamics AX 2012 prior to Microsoft Dynamics AX 2012 R2, the model store tables are stored in the same database as the business data. If your environment contains a large combined business and model store database, we recommend that you avoid running the Microsoft Dynamics AX optimization command. Instead, we suggest that you create a Microsoft SQL Server maintenance plan that reindexes the database.</P>



You can use either Windows PowerShell cmdlets or the AXUtil command-line utility to perform this task.

### Drain client connections and validate permissions

1.  Drain the client connections that are connected to the Application Object Server (AOS) instance that you are working with. For more information, see [Drain users from an AOS](drain-users-from-an-aos.md).

2.  Validate that you have appropriate permissions to work with the model store:
    
      - Administrative permissions on the local computer
    
      - System Administrator rights in Microsoft Dynamics AX
    
      - In Microsoft SQL Server:
        
          - Membership in the Securityadmin server role on the SQL Server instance
        
          - Membership in the db\_owner role in the Microsoft Dynamics AX database

### Optimize a model store (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Optimize-AXModelStore 
    ```
    
    For more information, see [Optimize-AXModelStore](optimize-axmodelstore.md).

### Optimize a model store (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil optimize

## See also

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[AxUtil and Windows PowerShell Commands for Deploying Models](axutil-and-windows-powershell-commands-for-deploying-models.md)

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

