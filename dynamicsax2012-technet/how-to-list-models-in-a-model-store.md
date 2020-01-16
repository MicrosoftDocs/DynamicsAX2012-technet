---
title: 'How to: List Models in a Model Store'
TOCTitle: 'How to: List Models in a Model Store'
ms:assetid: fd8c9a60-d3c0-4332-a296-2c973f8b89d8
ms:mtpsurl: https://technet.microsoft.com/library/Hh433542(v=AX.60)
ms:contentKeyID: 36941335
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# How to: List Models in a Model Store 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to list the models that are in the model store. You can use either Windows PowerShell cmdlets or the AXUtil command-line utility to perform this task.

### Validate permissions

  - Validate that you have appropriate permissions to work with the model store:
    
      - Administrative permissions on the local computer
    
      - System Administrator rights in Microsoft Dynamics AX
    
      - In Microsoft SQL Server:
        
          - Membership in the Securityadmin server role on the SQL Server instance
        
          - Membership in the db\_owner role in the Microsoft Dynamics AX database

### List models (Windows PowerShell)

1.  To list the models in a layer, at the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Get-AXModel -Layer <LayerName>
    ```

2.  To list the models in the model store, at the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
        Get-AXModel
    
    For more information, see [Get-AXModel](get-axmodel.md).

### List models (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  To list the models in a layer, at the command prompt, type the following command, and then press ENTER.
    
        axutil list /layer
        :<layername> 

4.  To list the models in the model store, at the command prompt, type the following command, and then press ENTER.
    
        axutil list

## See also

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[AxUtil and Windows PowerShell Commands for Deploying Models](axutil-and-windows-powershell-commands-for-deploying-models.md)

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

