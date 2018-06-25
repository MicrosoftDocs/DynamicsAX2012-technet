---
title: 'How to: Move the Contents of a Model to a New Model'
TOCTitle: 'How to: Move the Contents of a Model to a New Model'
ms:assetid: d9612531-19db-4487-b617-32a899f81ed4
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh433539(v=AX.60)
ms:contentKeyID: 36941332
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# How to: Move the Contents of a Model to a New Model [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to move the contents of one model to another model in the same layer. You can use either Windows PowerShell cmdlets or the AXUtil command-line utility to perform this task.


> [!NOTE]
> <P>To move only a few elements of a model, see <A href="how-to-move-aot-elements-between-models.md">How to: Move AOT Elements between Models</A>.</P>



### Prepare the system and validate permissions

1.  Drain the client connections that are connected to the Application Object Server (AOS) instance that you are working with. For more information, see [Drain users from an AOS](drain-users-from-an-aos.md).

2.  Validate that you have appropriate permissions to work with the model store:
    
      - Administrative permissions on the local computer
    
      - System Administrator rights in Microsoft Dynamics AX
    
      - In Microsoft SQL Server:
        
          - Membership in the Securityadmin server role on the SQL Server instance
        
          - Membership in the db\_owner role in the Microsoft Dynamics AX database

### Move the contents of one model to another model in the same layer (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Move-AXModel -Model Model -TargetModel Model2
    ```
    
    This command replaces the contents of Model2 with the contents of Model.
    
    For more information, see [Move-AXModel](move-axmodel.md).

### Move the contents of one model to another model in the same layer (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil move /model:model /targetModel:Model2
    
    This command replaces the contents of Model2 with the contents of Model.

## See also

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[AxUtil and Windows PowerShell Commands for Deploying Models](axutil-and-windows-powershell-commands-for-deploying-models.md)

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

