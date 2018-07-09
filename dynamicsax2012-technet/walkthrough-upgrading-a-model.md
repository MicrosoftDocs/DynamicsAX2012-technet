---
title: 'Walkthrough: Upgrading a Model'
TOCTitle: 'Walkthrough: Upgrading a Model'
ms:assetid: b9ee10ac-8f86-4fcb-b50a-8683ecf79439
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh456302(v=AX.60)
ms:contentKeyID: 36997728
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Walkthrough: Upgrading a Model [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This walkthrough describes how to upgrade an existing model. To upgrade a model, you import the modified model over the existing model. This topic assumes that you have already modified the model in the Application Object Tree (AOT), and that you have created an .axmodel file.


> [!WARNING]
> <P>In Microsoft Dynamics AX 2012, element IDs and element handles are assigned during installation. Therefore, you must avoid randomizing element IDs and element handles when you install models. In general, never delete a model and then reinstall it. Always install a model over an existing model. For more information, see <A href="maintaining-installation-specific-element-ids-and-element-handles.md">Maintaining Installation-Specific Element IDs and Element Handles</A>.</P>



We recommend that you observe the following best practices:

  - Do not delete a model, and then reimport it. Instead, import the model over the existing model.

  - Before you import a model or model store, back up the database on the target system.

## Prerequisites

### Drain client connections and validate permissions

1.  Drain the client connections that are connected to the Application Object Server (AOS) instance that you are working with. For more information, see [Drain users from an AOS](drain-users-from-an-aos.md).

2.  Validate that you have appropriate permissions to work with the model store:
    
      - Administrative permissions on the local computer
    
      - System Administrator rights in Microsoft Dynamics AX
    
      - In Microsoft SQL Server:
        
          - Membership in the Securityadmin server role on the SQL Server instance
        
          - Membership in the db\_owner role in the Microsoft Dynamics AX database

## Walkthrough: Upgrade a model (Windows PowerShell)

### Export the .axmodel file (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
        Export-AXModel –Model <name> -File <Filename.axmodel> -Details
    
    This command exports the specified model to a file that has the specified file name.

### Import the .axmodel file (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
        Install-AXModel -File <Filename.axmodel> -Details
    
    This command installs the specified file in the same layer that it was exported from.
    
    If the installation fails because of a conflict, we recommend that you rerun the cmdlet. When you rerun the cmdlet, use the **–Conflict Push** option to push the element that has the conflict to the related update layer. You can then resolve the conflict. For more information, see [How to: Resolve Conflicts After Importing a Model](how-to-resolve-conflicts-after-importing-a-model.md).

## Walkthrough: Upgrade a model (AXUtil)

### Export the .axmodel file (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil export /model:<modelname> /file:<filename> /verbose

### Import the .axmodel file (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil import /file:<filename> /verbose
    
    This command installs the specified file in the same layer that it was exported from.
    
    If the installation fails because of a conflict, we recommend that you rerun the command. When you rerun the command, use the **/conflict:push** option to push the element that has the conflict to the related update layer. You can then resolve the conflict. For more information, see [How to: Resolve Conflicts After Importing a Model](how-to-resolve-conflicts-after-importing-a-model.md).

## See also

[Export-AXModel](export-axmodel.md)

[Install-AXModel](install-axmodel.md)

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[AxUtil and Windows PowerShell Commands for Deploying Models](axutil-and-windows-powershell-commands-for-deploying-models.md)

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

