---
title: 'How to: View and Verify Contents of a Model'
TOCTitle: 'How to: View and Verify Contents of a Model'
ms:assetid: 947da5f7-a41b-4cae-9730-f48c27981477
ms:mtpsurl: https://technet.microsoft.com/library/Hh433532(v=AX.60)
ms:contentKeyID: 36941321
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# How to: View and Verify Contents of a Model 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to view and verify the contents of a model.

You can use either Windows PowerShell cmdlets or the AXUtil command-line utility to perform this task.

### Validate permissions

  - Validate that you have appropriate permissions to work with the model store:
    
      - Administrative permissions on the local computer
    
      - System Administrator rights in Microsoft Dynamics AX
    
      - In Microsoft SQL Server:
        
          - Membership in the Securityadmin server role on the SQL Server instance
        
          - Membership in the db\_owner role in the Microsoft Dynamics AX database

### List the elements of a model (Windows PowerShell)

  - To view a list of the elements in a model or model file, at the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    (Get-AXModel -Model <Modelname>) –Details | Out-String
    ```
    
    For more information, see [Get-AXModel](get-axmodel.md).

### List the elements of a model (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  To view a list of the elements in a model, at the command prompt, type the following command, and then press ENTER.
    
        axutil view /model
        :<modelname> 

### Validate that a model file contains data (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Test-AXModelData –Model <ModelName> -Verbose
    ```
    
    This command verifies whether data exists in the specified model.
    
    The following example shows the output of this command.
    
        VERBOSE: AXUtil 6.0 - Microsoft Dynamics AX Admin Utility (6.0.906.0) 
        (c) Copyright, Microsoft Corporation, 2011. All rights reserved. 
        VERBOSE: 
        VERBOSE: The AXUtil command was started in the mode: EXISTS. 
        VERBOSE: 
        VERBOSE: Working against model store CONTOSO/MicrosoftDynamicsAX. 
        VERBOSE: 
        VERBOSE: Model data exists in Modelname model. 
        VERBOSE:
    
    For more information, see [Test-AXModelData](test-axmodeldata.md).

### Validate that a model file contains data (AXUtil)

  - At the command prompt, type the following command, and then press ENTER.
    
        axutil exists /model:<modelname> 
    
    This command verifies whether data exists in the specified model.
    
    The following example shows the output of this command.
    
        The AXUtil command was started in the mode: exists.
        Working against model store Contoso/MicrosoftDynamicsAX.
        Model data exists in Modelname model.

## See also

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[AxUtil and Windows PowerShell Commands for Deploying Models](axutil-and-windows-powershell-commands-for-deploying-models.md)

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

