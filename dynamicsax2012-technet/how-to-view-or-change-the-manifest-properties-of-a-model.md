---
title: 'How to: View or Change the Manifest Properties of a Model'
TOCTitle: 'How to: View or Change the Manifest Properties of a Model'
ms:assetid: 5d080225-e5c2-4c8c-bf8a-df2c4e70b129
ms:mtpsurl: https://technet.microsoft.com/library/Hh433512(v=AX.60)
ms:contentKeyID: 36941293
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# How to: View or Change the Manifest Properties of a Model 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to view and change the properties of a model. You can use either Windows PowerShell cmdlets or the AXUtil command-line utility to perform this task.

### Prepare the system and validate permissions

1.  Drain the client connections that are connected to the Application Object Server (AOS) instance that you are working with. For more information, see [Drain users from an AOS](drain-users-from-an-aos.md).

2.  Validate that you have appropriate permissions to work with the model store:
    
      - Administrative permissions on the local computer
    
      - System Administrator rights in Microsoft Dynamics AX
    
      - In Microsoft SQL Server:
        
          - Membership in the Securityadmin server role on the SQL Server instance
        
          - Membership in the db\_owner role in the Microsoft Dynamics AX database

### View the contents of a model manifest (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type one of the following commands, and then press ENTER.
    
    ``` powershell
    Get-AXModelManifest -Model <Modelname> -XML
    ```
    
    ``` powershell
    Get-AXModelManifest -File <Filename.axmodel> 
    ```
    
    The first command returns the properties of a model. When the -XML parameter is added, this command also generates an XML version of a model manifest.
    
    The following example shows the output of the first command.
    
    ``` powershell
    <?xml version="1.0" encoding="utf-8"?> 
    <ModelManifest SchemaVersion="1.9" ModelFileVersion="17" ElementCount="0"> 
    <Name>ModelName</Name> 
    <DisplayName>ModelName</DisplayName> 
    <Description /> 
    <Publisher /> 
    <Signed>false</Signed> 
    <Category>Standard</Category> 
    <InstallMode>Standard</InstallMode> 
    <Version>1.0.0.0</Version> 
    <Layer>ISV</Layer> 
    <DependencyState /> 
    </ModelManifest>PS C:\Windows\system32> 
    ```
    
    The second command returns the properties of an .axmodel file.
    
    For more information, see [Get-AXModelManifest](get-axmodelmanifest.md).

### View the contents of a model manifest (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type one of the following commands, and then press ENTER.
    
  ```
      axutil manifest /model:<modelname> /xml
  ```
  
  ```
      axutil manifest /file:<filename>
  ```

    The first command returns the properties of a model. When the /XML parameter is added, this command also generates an XML version of a model manifest.
    
    The following example shows the output of the first command.
    
        <?xml version="1.0" encoding="utf-8"?>
        <ModelManifest SchemaVersion="1.9" ModelFileVersion="18" ElementCount="0" ModelB
        uildVersion="">
          <Name>modelname</Name>
          <DisplayName>modelname</DisplayName>
          <Description />
          <Publisher />
          <Signed>false</Signed>
          <Category>Standard</Category>
          <InstallMode>Standard</InstallMode>
          <Version>1.0.0.0</Version>
          <Layer>ISV</Layer>
          <DependencyState />
        </ModelManifest>
    
    The second command returns the properties of a model file.

### Change the manifest properties of a model (Windows PowerShell)

1.  Determine which properties you want to change:
    
      - Name
    
      - DisplayName
    
      - Description
    
      - Publisher
    
      - Version – A four-part indicator, in the format Number.Number.Number.Number.
    
      - InstallMode – Possible values include Standard, Overwrite, and Conflict. Standard stops the import process if a conflicting model element is encountered in the same layer. Overwrite replaces the existing model element with the imported model element. Conflict creates a conflict model in the related update layer. This conflict model contains the conflicting model element.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Edit-AXModelManifest -Model <Modelname> -ManifestProperty "Propertyname = Value"
    ```
    
    You can also use the ManifestFile parameter to specify an XML file that contains the properties of the model that you want to use.
    
    For more information, see [Edit-AXModelManifest](edit-axmodelmanifest.md).

### Change the properties of a model (AXUtil)

1.  Determine which properties you want to change:
    
      - Name
    
      - DisplayName
    
      - Description
    
      - Publisher
    
      - Version – A four-part indicator, in the format Number.Number.Number.Number.
    
      - InstallMode – Possible values include Standard, Overwrite, and Conflict. Standard stops the import process if a conflicting model element is encountered in the same layer. Overwrite replaces the existing model element with the imported model element. Conflict creates a conflict model in the related update layer. This conflict model contains the conflicting model element.

2.  On the **Start** menu, click **Command prompt**.

3.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

4.  At the command prompt, type the following command, and then press ENTER.
    
        axutil edit /model:<modelname> /manifest:PropertyName=Value

    You can also use the @modelxml parameter and pipe the parameters to a file. In this way, you can specify an XML file that contains the properties of the model that you want to use.
    
        axutil edit /model:<modelname> @modelxml | /File=Filename

## See also

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[AxUtil and Windows PowerShell Commands for Deploying Models](axutil-and-windows-powershell-commands-for-deploying-models.md)

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

