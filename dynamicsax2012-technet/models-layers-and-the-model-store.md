---
title: Models, Layers, and the Model Store
TOCTitle: Models, Layers, and the Model Store
ms:assetid: cc7eb6ff-a5de-4a7e-a758-af783ce0ace0
ms:mtpsurl: https://technet.microsoft.com/library/Hh335184(v=AX.60)
ms:contentKeyID: 36687408
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Models, Layers, and the Model Store 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Models were introduced in Microsoft Dynamics AX 2012 to help partners and customers more easily install and maintain multiple solutions side by side in the same layer. This topic introduces the concept of models, and describes how models relate to layers and label files. This topic also describes the model store, which is a database in which all application elements for Microsoft Dynamics AX are stored.

## Models

A model is a set of elements in a given layer. Each layer consists of one or more models. Each layer contains one system-generated model that is specific to that layer. Every element in a layer belongs to only one model. In other words, no element can belong to two models in the same layer, and every element must belong to a model.

A default model owned by Microsoft exists in each layer. Default models cannot be modified.

A model is permanently associated with the layer that the model was created in. If you need to move one of your models from one layer to another, you must create a project from the model in the Application Object Tree (AOT), export the project as an xpo file, create a target model in the desired layer, delete the original model to avoid having to resolve layer conflicts, and import the xpo file to the target model. If you are moving elements between models in the same layer, you can use the **Move to model** command in the AOT.

Models are stored in the model store. The model store is a database in which all application elements for Microsoft Dynamics AX are stored. Customizations are also stored in the model store. The model store replaces the Application Object Data (AOD) files that were used in earlier versions of Microsoft Dynamics AX. Models that have been installed in the model store are used at run time.


> [!IMPORTANT]
> <P>In Microsoft Dynamics AX 2012 R2, the model store was moved into a database that is separate from the business database.</P>



Models can be exported to files that have the .axmodel extension. These files are called model files. Model files are deployment artifacts. Model files can be signed with strong name signing and Microsoft Authenticode signing.

### ![Hh335184.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Hh335184.collapse_all(en-us,AX.60).gif")Models and label files

In Microsoft Dynamics AX 2012, label files, or ALD files, are part of models. A label file must be added to a model before the model can be installed. After a model has been installed, ALD files are pulled from the model store to the local of Application Object Server (AOS) instance when the AOS is started. When the AOS is shut down, the ALD files are pushed back to the model store.

ALD files from earlier versions of Microsoft Dynamics AX are not part of a model file. However, you can import these files into the model store from the **Label Files** section of the AOT. Use the **Create from file** shortcut command.


> [!IMPORTANT]
> <P>The ALD file from an earlier version of Microsoft Dynamics AX must not be located in the application folder of AOS. Otherwise, you cannot import the file.</P>



### ![Hh335184.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Hh335184.collapse_all(en-us,AX.60).gif")How models improve the installation and maintenance of side-by-side customizations

In earlier versions of Microsoft Dynamics AX, multiple partner solutions could not exist side by side in the same layer. However, models now enable side-by-side customizations. Additionally, the following improvements help you work with side-by-side customizations:

  - The development environment for Microsoft Dynamics AX lets you create a project for each model that is installed. Therefore, you can quickly see all the installed customizations in a layer for a given model.

  - When you import a model, elements in the model that you are importing may conflict with another model in the same layer. You can now create a conflict model in the patch layer that is associated with the layer that you are working in. You can then resolve the conflicts in the conflict model. In earlier versions, no warnings about conflicts were displayed. Instead, elements were just replaced.

  - You can now leave the rest of the layer intact when you uninstall a model. In earlier versions, if you wanted to uninstall customizations, you had to either remove the customizations manually from the AOT or remove the layer.


> [!IMPORTANT]
> <P>Element IDs are now specific to each installation. In other words, the same method or class has a different element ID in different installations. To maintain installation-specific element IDs when you import and export models and model stores, you must strictly follow specific procedures. If you do not follow the correct procedure when you import or update models, IDs can become randomized, and data integrity can be affected. For more information, see <A href="maintaining-installation-specific-element-ids-and-element-handles.md">Maintaining Installation-Specific Element IDs and Element Handles</A>.</P>



### ![Hh335184.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "Hh335184.collapse_all(en-us,AX.60).gif")Working with label files across solutions

We recommend that you use one label file per solution to simplify installation.

If you find that you require multiple label files, we recommend that you create a single shared, cross-solution label file and package it as a model file. Then, when you install solutions, you must install two models: the solution itself and the label model.

If you want to ship additional languages, you can add the languages to the solution model, increment the model's version number, and then reimport the model.

For more information, see [Import label files into the new model store](import-label-files-into-the-new-model-store.md).

## Installing metadata

Metadata can be installed in various ways. The following table describes each installation method that is available.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p></p></th>
<th><p>XPO files</p></th>
<th><p>Model files</p></th>
<th><p>Model store files</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Installation tool</p></td>
<td><p>MorphX</p></td>
<td><p>AXUtil.exe or Windows PowerShell cmdlets</p></td>
<td><p>AXUtil.exe or Windows PowerShell cmdlets</p></td>
</tr>
<tr class="even">
<td><p>The files can be uninstalled.</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
</tr>
<tr class="odd">
<td><p>The files can be signed.</p></td>
<td><p>No</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>Microsoft Dynamics AX element IDs are preserved.</p></td>
<td><p>Yes, if the elements already exist in the target model store</p></td>
<td><p>Yes, if the elements already exist in the target model store</p></td>
<td><p>Yes, all element IDs of the source model store are preserved.</p></td>
</tr>
<tr class="odd">
<td><p>Compilation is required after installation.</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
</tr>
<tr class="even">
<td><p>CIL generation is required after installation.</p></td>
<td><p>Yes</p></td>
<td><p>Yes</p></td>
<td><p>No</p></td>
</tr>
</tbody>
</table>



> [!IMPORTANT]
> <P>To avoid ID conflicts, we recommend that you do not use xpo export/import to move customizations in environments in which you are primarily relying on importing and exporting models and model stores.</P>



The following table describes the scenarios in which we recommend you use each installation method.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Scenario</p></th>
<th><p>Recommended installation method</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Distributing a solution to customers</p></td>
<td><p>Model files</p></td>
</tr>
<tr class="even">
<td><p>Deploying a solution in a development or test environment</p></td>
<td><p>Model files or XPO files</p></td>
</tr>
<tr class="odd">
<td><p>Deploying a solution to a production environment</p></td>
<td><p>Model store files</p></td>
</tr>
</tbody>
</table>

  
**Announcements:** New book: "Inside Microsoft Dynamics AX 2012 R3" now available. Get your copy at the [MS Press Store](https://www.microsoftpressstore.com/store/inside-microsoft-dynamics-ax-2012-r3-9780735685109).

