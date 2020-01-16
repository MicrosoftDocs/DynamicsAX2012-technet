---
title: 'How to: Export and Import a Model'
TOCTitle: 'How to: Export and Import a Model'
ms:assetid: c2449a03-7574-4b9d-8518-9005b560209f
ms:mtpsurl: https://technet.microsoft.com/library/Hh352314(v=AX.60)
ms:contentKeyID: 36687943
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
dev_langs:
- powershell
---

# How to: Export and Import a Model 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A model is a set of elements in a given layer. Each layer consists of one or more models. Models can be exported to files that have the .axmodel extension. These files are called model files. Model files are deployment artifacts that can be imported into a model store.

A model is permanently associated with the layer that is created in. If you need to move one of your models from one layer to another, you must create a project from the model in the AOT, export the project as an xpo file, create a target model in the desired layer, delete the original model to avoid having to resolve layer conflicts, and import the xpo file to the target model. If you are moving elements between models in the same layer, you can use the **Move to model** command in the AOT.

You can use either Windows PowerShell cmdlets or the AXUtil command-line utility to export models to model files and import model files into a model store.


> [!IMPORTANT]
> <P>In Microsoft Dynamics AX 2012, element IDs and element handles are assigned during installation. Therefore, you must avoid randomizing element IDs and element handles when you install models. In general, never delete a model and then reinstall it. Always install a model over an existing model. For more information, see <A href="maintaining-installation-specific-element-ids-and-element-handles.md">Maintaining Installation-Specific Element IDs and Element Handles</A>.</P>



## Preparing the system

### Drain client connections and validate permissions

1.  Drain the client connections to the Application Object Server (AOS) instance that you are working with. For more information, see [Drain users from an AOS](drain-users-from-an-aos.md).

2.  Validate that you have appropriate permissions to work with the model store:
    
      - Administrative permissions on the local computer
    
      - System Administrator rights in Microsoft Dynamics AX
    
      - In Microsoft SQL Server:
        
          - Membership in the Securityadmin server role on the SQL Server instance
        
          - Membership in the db\_owner role in the Microsoft Dynamics AX database

## Exporting model files

You can export a model file if you want to distribute it internally or to customers. If you plan to distribute a model file to customers, we recommend that you strong-name sign the model. To strong-name sign a model, you must use the [Strong Name Tool](http://msdn.microsoft.com/en-us/library/k5b5tt23\(vs.80\).aspx), SN.exe, to generate a key pair file.

### Export an .axmodel file (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Export-AXModel –Model <name> -File <Filename.axmodel> 
    ```
    
    This example exports the specified model to a file that has the specified file name.
    
    You can use the –Server, –Config, or –Database parameters to specify the environment to export from.
    
    You can also use the -Key parameter to specify the strong-name key pair file to use to sign a model.
    
    For more information, see [Export-AXModel](export-axmodel.md).

3.  You can also use the Sign Tool to sign the file with a digital certificate, or the AXUtil genlicense command to Authenticode sign a file. For more information, see:
    
      - [Sign Tool](http://msdn.microsoft.com/en-us/library/aa387764\(vs.85\).aspx)
    
      - [ISV licensing agreement](http://go.microsoft.com/fwlink/?linkid=228157)

### Export an .axmodel file (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil export /model:<modelname> /file:<filename> /verbose
    
    This example exports the specified model to a file that has the specified file name.
    
    You can use the \[/key:SNK-file\] parameter to specify the strong-name key pair file to use to sign a model.

4.  You can also use the Sign Tool to sign the file with a digital certificate, or the AXUtil genlicense command to Authenticode sign a file. For more information, see:
    
      - [Sign Tool](http://msdn.microsoft.com/en-us/library/aa387764\(vs.85\).aspx)
    
      - [ISV licensing agreement](http://go.microsoft.com/fwlink/?linkid=228157)

## Importing an .axmodel file

When you import a model, elements in the model that you are importing may conflict with another model in the same layer. In this situation, you can create a conflict model in the patch layer that is associated with the layer that you are working in. You can then resolve the conflicts in the conflict model.

By default, when you import a model from Windows PowerShell or AXUtil, the installation mode is set to display the Model code upgrade checklist when the Microsoft Dynamics AX client starts. If you import a model by using Setup.exe, by default, the installation mode does not display the Model code upgrade checklist. For more information about importing a model by using Setup.exe, see:

  - [Install the Microsoft Dynamics AX databases](install-the-microsoft-dynamics-ax-databases.md)

  - [Include cumulative updates and hotfixes in a new installation (slipstreaming)](include-cumulative-updates-and-hotfixes-in-a-new-installation-slipstreaming.md)

By default, optimization steps, such as reindexing the model store, are performed when a model is installed for the first time. Optimization steps are also performed if the number of elements in a model increases by more than 50 percent when the model is reimported. For more information, see [How to: Optimize a Model Store for Runtime](how-to-optimize-a-model-store-for-runtime.md).

### Import an .axmodel file (Windows PowerShell)

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Install-AXModel -File <Filename.axmodel> -Details
    ```
    
    This command installs the specified file in the same layer that it was exported from.
    
    You can use the –Server, –Config, or –Database parameters to specify the environment to import to.
    
    By default, you will be prompted to install the model based on whether it has been signed. The following table describes the prompts shown.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Scenario</p></th>
    <th><p>Prompt</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>The model file is not signed.</p></td>
    <td><p>The model is not signed. Are you sure you want to install this model (Y/N)?</p></td>
    </tr>
    <tr class="even">
    <td><p>The publisher is recognized from the digital certificate.</p></td>
    <td><p>The model is signed by ‘{0}’”. Would you like to continue (Y/N)?</p></td>
    </tr>
    <tr class="odd">
    <td><p>The publisher was not available from the digital certificate.</p></td>
    <td><p>The certificate for the model was not recognized. Are you sure you want to install this model (Y/N)?</p></td>
    </tr>
    <tr class="even">
    <td><p>The provider for the certificate is unknown.</p></td>
    <td><p>The certificate for the model was not recognized. Are you sure you want to install this model (Y/N)?</p></td>
    </tr>
    </tbody>
    </table>
    
    If the installation fails because of a conflict, we recommend that you rerun the cmdlet, and use the **-Conflict Push** option to push the element that has the conflict to the related update layer. You can then resolve the conflict. For more information, see [How to: Resolve Conflicts After Importing a Model](how-to-resolve-conflicts-after-importing-a-model.md).
    
    For more information, see [Install-AXModel](install-axmodel.md).

### Import an .axmodel file (AXUtil)

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil import /file:<filename> /verbose
    
    This command installs the specified file in the same layer that it was exported from.
    
    If the installation fails because of a conflict, we recommend that you rerun the command, and use the **/conflict:push** option to push the element that has the conflict to the related update layer. You can then resolve the conflict. For more information, see [How to: Resolve Conflicts After Importing a Model](how-to-resolve-conflicts-after-importing-a-model.md).

## See also

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[AxUtil and Windows PowerShell Commands for Deploying Models](axutil-and-windows-powershell-commands-for-deploying-models.md)

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

