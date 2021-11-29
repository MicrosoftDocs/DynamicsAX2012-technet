---
title: Import AOD files into the new model store
TOCTitle: Import AOD files into the new model store
ms:assetid: af8b370a-d6a9-4973-b260-32f07e49a0e9
ms:mtpsurl: https://technet.microsoft.com/library/Gg731899(v=AX.60)
ms:contentKeyID: 35132816
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SysAODImport
- MsDynAx060.Forms.SysAODImport
---

# Import AOD files into the new model store 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Import the .aod file for the layer that you want to upgrade from the source system into the new model store.

For developer documentation about code upgrade in Microsoft Dynamics AX 2012, see the downloadable [code upgrade white papers](https://go.microsoft.com/fwlink/?linkid=215083). See also *Inside Microsoft Dynamics AX 2009*, Chapter 18: “Code upgrade,” pp. 623–644.

## Importing .aod files into the new model store

### To import .aod files into the new model store

1.  Copy the .aod file for the current layer from the source system to the following folder: %ProgramFiles%\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\bin\\Application\\Appl\\Standard. Do not copy the .aod files for the layers that Microsoft owns into this folder.

2.  Some layers have been renamed in Microsoft Dynamics AX 2012. Rename the .aod file to the new name of the layer in Microsoft Dynamics AX 2012. The following table shows the names of the layers in different versions of Microsoft Dynamics AX.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Microsoft Dynamics AX 4.0 layer</p></th>
    <th><p>Microsoft Dynamics AX 2009 layer</p></th>
    <th><p>Microsoft Dynamics AX 2012 layer(Rename to this)</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>axbup.aod</p></td>
    <td><p>axbup.aod</p></td>
    <td><p>axisp.aod</p></td>
    </tr>
    <tr class="even">
    <td><p>axbus.aod</p></td>
    <td><p>axbus.aod</p></td>
    <td><p>axisv.aod</p></td>
    </tr>
    <tr class="odd">
    <td><p>axlop.aod</p></td>
    <td><p>axsl3.aod</p></td>
    <td><p>axslp.aod</p></td>
    </tr>
    <tr class="even">
    <td><p>axlos.aod</p></td>
    <td><p>axsl2.aod</p></td>
    <td><p>axsln.aod</p></td>
    </tr>
    <tr class="odd">
    <td><p>axdip.aod</p></td>
    <td><p>axsl1.aod</p></td>
    <td><p>axfpp.aod</p></td>
    </tr>
    <tr class="even">
    <td><p>axdis.aod</p></td>
    <td><p>axhfx.aod</p></td>
    <td><p>axfpk.aod</p></td>
    </tr>
    </tbody>
    </table>


3.  In the **Import layer AOD into the new model store** dialog box, select the name of the .aod file that you want to import. When you import layer files, you must start with the lowest layer. However, do not import the layers that Microsoft owns into the new model store.

4.  Select the model that you want to import the .aod file into.

5.  Click **OK** to import the .aod file.
    
    If the .aod file contains items that cannot be imported, An **Infolog** message is displayed. For more information, see the log file referenced in the message. Usually, an application object cannot be imported because of one of the following reasons:
    
      - A method was added to a class that no longer exists in the Application Object Tree (AOT).
    
      - There is an ID conflict between two elements that have the same name and type, but different IDs.
    
      - You customized a hybrid class or a table that supports inheritance.
    
    To resolve these issues, identify all the application objects that were not imported from your Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 system. Export these application objects to an .xpo file. Then import this .xpo file into the Microsoft Dynamics AX 2012 system by clicking **Import** on the AOT toolbar.

6.  In the Code upgrade checklist, continue with the next steps for the layer file that you imported. Then return to this procedure when you are ready to import the layer file for the next layer. You can then import the remaining layers one at a time, starting with the lowest layer.

## See also

[Import label files into the new model store](import-label-files-into-the-new-model-store.md)

  


