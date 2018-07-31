---
title: AxUtil and Windows PowerShell Commands for Deploying Models
TOCTitle: AxUtil and Windows PowerShell Commands for Deploying Models
ms:assetid: 403c0715-227d-421e-91b7-ab8c353cf02c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh456294(v=AX.60)
ms:contentKeyID: 36997720
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# AxUtil and Windows PowerShell Commands for Deploying Models 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Two command line tools are available for deploying and managing models and the model store:

  - Windows PowerShell, a command-line scripting tool

  - AXUtil, a command-line utility

Both tools offer the same functionality, but we recommend that you use Windows PowerShell cmdlets, for the following reasons:

  - You can use Windows PowerShell cmdlets to create scripts that combine multiple actions.

  - You can use other Windows PowerShell cmdlets for Microsoft Dynamics AX to add users and user authentication, and to manage configurations for communication between Microsoft Dynamics AX and Microsoft SQL Server Reporting Services.

  - The AXUtil command-line utility is becoming obsolete in a future version of Microsoft Dynamics AX.

The following table describes the Windows PowerShell cmdlets and the equivalent AXUtil commands that can be used to manage models and the model store.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Windows PowerShell cmdlet</p></th>
<th><p>AXUtil command</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Edit-AXModelManifest</p></td>
<td><p>axutil edit</p></td>
<td><p>Modify the properties of a model's manifest.</p>
<p>For more information, see <a href="how-to-view-or-change-the-manifest-properties-of-a-model.md">How to: View or Change the Manifest Properties of a Model</a> and <a href="edit-axmodelmanifest.md">Edit-AXModelManifest</a>.</p></td>
</tr>
<tr class="even">
<td><p>Export-AXModel</p></td>
<td><p>axutil export</p></td>
<td><p>Export a model to an .axmodel file.</p>
<p>For more information, see <a href="how-to-export-and-import-a-model.md">How to: Export and Import a Model</a> and <a href="export-axmodel.md">Export-AXModel</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Export-AXModelStore</p></td>
<td><p>axutil exportstore</p></td>
<td><p>Export a Microsoft Dynamics AX model store to an .axmodelstore file. For more information, see <a href="how-to-export-and-import-a-model-store.md">How to: Export and Import a Model Store</a> and <a href="export-axmodelstore.md">Export-AXModelStore</a>.</p></td>
</tr>
<tr class="even">
<td><p>There is no equivalent Windows PowerShell cmdlet.</p></td>
<td><p>axutil genlicense</p></td>
<td><p>ISVs use this command to generate a customer-specific license file for a solution.</p></td>
</tr>
<tr class="odd">
<td><p>Get-AXModel</p></td>
<td><p>axutil view</p></td>
<td><p>Return a list of the models in the model store, or a list of the elements in a specific model or model file.</p>
<div class="alert">

> [!NOTE]
> <P>Get-AXModel –details and axutil view /verbose return slightly different information.</P>


</div>
<p>For more information, see <a href="how-to-view-and-verify-contents-of-a-model.md">How to: View and Verify Contents of a Model</a> and <a href="get-axmodel.md">Get-AXModel</a>.</p></td>
</tr>
<tr class="even">
<td><p>Get-AXModelManifest</p></td>
<td><p>axutil manifest</p></td>
<td><p>Retrieve the properties of a model file.</p>
<p>For more information, see <a href="how-to-view-and-verify-contents-of-a-model.md">How to: View and Verify Contents of a Model</a> and <a href="get-axmodelmanifest.md">Get-AXModelManifest</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Get-Help &lt;cmdlets&gt;</p></td>
<td><p>axutil /help</p></td>
<td><p>Get help for a command.</p></td>
</tr>
<tr class="even">
<td><p>Grant-AXModelStore</p></td>
<td><p>axutil grant</p></td>
<td><p>Grant the account that an instance of Application Object Server (AOS) runs as permissions to the model store in the Microsoft Dynamics AX database. For more information, see <a href="grant-axmodelstore.md">Grant-AXModelStore</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Import-AXModelStore</p></td>
<td><p>axutil importstore</p></td>
<td><p>Import a model store from a file to a database.</p>
<p>For more information, see <a href="how-to-export-and-import-a-model-store.md">How to: Export and Import a Model Store</a> and <a href="import-axmodelstore.md">Import-AXModelStore</a>.</p></td>
</tr>
<tr class="even">
<td><p>Initialize-AXModelStore</p></td>
<td><p>axutil schema</p></td>
<td><p>Create an empty model store that is associated with the specified schema, update the existing schema for a model store, or remove a non-default model store.</p>
<p>For more information, see <a href="how-to-create-drop-or-reinitialize-a-model-store.md">How to: Create, Drop, or Reinitialize a Model Store</a> and <a href="initialize-axmodelstore.md">Initialize-AXModelStore</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Install-AXModel</p></td>
<td><p>axutil import</p></td>
<td><p>Install a model from an .axmodel file to the model store.</p>
<p>For more information, see <a href="how-to-export-and-import-a-model.md">How to: Export and Import a Model</a> and <a href="install-axmodel.md">Install-AXModel</a>.</p></td>
</tr>
<tr class="even">
<td><p>Move-AXModel</p></td>
<td><p>axutil move</p></td>
<td><p>Move the content of one model in the Microsoft Dynamics AX model store to another model in the same layer.</p>
<p>For more information, see <a href="how-to-view-or-change-the-manifest-properties-of-a-model.md">How to: View or Change the Manifest Properties of a Model</a> and <a href="move-axmodel.md">Move-AXModel</a>.</p></td>
</tr>
<tr class="odd">
<td><p>New-AXModel</p></td>
<td><p>axutil create</p></td>
<td><p>Create an empty model in a Microsoft Dynamics AX model store. You can specify properties for the model by passing in either a manifest file or a series of manifest properties.</p>
<p>For more information, see <a href="how-to-create-a-new-model-from-the-command-line.md">How to: Create a New Model from the Command Line</a> and <a href="new-axmodel.md">New-AXModel</a>.</p></td>
</tr>
<tr class="even">
<td><p>Optimize-AXModelStore</p></td>
<td><p>axutil optimize</p></td>
<td><p>Run a series of steps to optimize the model store for run-time performance.</p>
<p>For more information, see <a href="how-to-optimize-a-model-store-for-runtime.md">How to: Optimize a Model Store for Runtime</a> and <a href="optimize-axmodelstore.md">Optimize-AXModelStore</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Set-AXModelStore</p></td>
<td><p>axutil set</p></td>
<td><p>Set a flag in the model store that indicates the action that is taken when a model is modified. If the -InstallMode parameter is used, a dialog box appears when the Microsoft Dynamics AX client is started after a model has been modified. From the dialog box, you can open the Model code upgrade checklist.</p>
<p>By default, when you import a model from Windows PowerShell or AXUtil, the installation mode is set to display the Model code upgrade checklist when the Microsoft Dynamics AX client starts.</p>
<p>For more information, see <a href="set-axmodelstore.md">Set-AXModelStore</a>.</p></td>
</tr>
<tr class="even">
<td><p>Test-AXModelData</p></td>
<td><p>axutil exists</p></td>
<td><p>Verify whether a specified model or layer contains data.</p>
<p>For more information, see <a href="how-to-view-and-verify-contents-of-a-model.md">How to: View and Verify Contents of a Model</a> and <a href="test-axmodeldata.md">Test-AXModelData</a>.</p></td>
</tr>
<tr class="odd">
<td><p>Uninstall-AXModel</p></td>
<td><p>axutil delete</p></td>
<td><p>Remove a model from the model store in the Microsoft Dynamics AX database.</p>
<p>For more information, see <a href="how-to-remove-uninstall-a-model.md">How to: Remove (Uninstall) a Model</a> and <a href="uninstall-axmodel.md">Uninstall-AXModel</a>.</p></td>
</tr>
</tbody>
</table>


## Windows PowerShell

After you install Microsoft Dynamics AX, the applicable Windows PowerShell cmdlets are available from the Microsoft Dynamics AX Management Shell. For more information about other Windows PowerShell cmdlets, and for information about how to write scripts, see [Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md).

To obtain help for any Windows PowerShell cmdlet, use the Get-Help cmdlet.

### Access Windows PowerShell

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, enter the Get-Help command, and then press ENTER.
    
        Get-Help AXModel 
    
    The command in this example returns a list of all model-related cmdlets.
    
        Get-Help Export-AXModel -Full
    
    The code in this example retrieves help for the Export-AXModel cmdlet.

## AXUtil

After you install Microsoft Dynamics AX, the applicable AXUtil commands are available from the directory for Microsoft Dynamics AX Management Utilities.

To view the Help for AXUtil, enter the command AXUtil /?.

### Access AXUtil

1.  On the **Start** menu, click **Command prompt**.

2.  Navigate to the directory for the management utilities. Typically, the location of this directory is %ProgramFiles%\\Microsoft Dynamics AX\\60\\ManagementUtilities.

3.  At the command prompt, type the following command, and then press ENTER.
    
        axutil /?
    
    This command displays the Help for AXUtil.

## See also

[Models, Layers, and the Model Store](models-layers-and-the-model-store.md)

[Administering Microsoft Dynamics AX by using Windows PowerShell](administering-microsoft-dynamics-ax-by-using-windows-powershell.md)

[Windows PowerShell for Microsoft Dynamics AX](windows-powershell-for-microsoft-dynamics-ax.md)

  


