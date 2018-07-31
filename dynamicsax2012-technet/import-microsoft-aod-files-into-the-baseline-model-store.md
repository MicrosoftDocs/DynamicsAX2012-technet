---
title: Import Microsoft AOD files into the baseline model store
TOCTitle: Import Microsoft AOD files into the baseline model store
ms:assetid: 1d84cd11-89e3-4c55-aa9e-9145600ea298
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Gg188981(v=AX.60)
ms:contentKeyID: 35410561
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Forms.SysAODImport
- MsDynAx060.Forms.SysAODImport
---

# Import Microsoft AOD files into the baseline model store 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Import Microsoft application files, or .aod files, from the source system into the baseline model store.

For more information about how to upgrade code, see the white papers that are available at [http://go.microsoft.com/fwlink/?LinkID=215083](http://go.microsoft.com/fwlink/?linkid=215083).

## Importing Microsoft .aod files into the baseline model store

### To import Microsoft .aod files into the baseline model store

1.  On the server, create a folder named Old in the following location: %ProgramFiles%\\Microsoft Dynamics AX\\60\\Server\\MicrosoftDynamicsAX\\bin\\Application\\Appl\\Standard.

2.  Copy the Microsoft .aod files from the source system to the Old folder.

3.  Some layers have been renamed in Microsoft Dynamics AX 2012. Rename each .aod file to the new name of the layer in Microsoft Dynamics AX 2012. The following table shows the names of the layers in different versions of Microsoft Dynamics AX.
    
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
    <th><p>Microsoft Dynamics AX 2012 layer (Rename to this)</p></th>
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


4.  In the **Import Microsoft AODs into the baseline model store** dialog box, select the name of the layer file that you want to import. When you import layers, you must start with the lowest layer.

5.  Click **OK** to import the .aod file.
    
    If the .aod file contains items that cannot be imported, an **Infolog** message is displayed. For more information, see the log file referenced in the message. Usually, an application object cannot be imported for one of the following reasons:
    
      - A method was added to a class that no longer exists in the Application Object Tree (AOT).
    
      - There is an ID conflict between two elements that have the same name and type, but different IDs.
    
      - You customized a hybrid class or a table that supports inheritance.
    
    To resolve these issues, identify the application objects that were not imported from your Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 system. Export all of these application objects to an .xpo file. Then import the .xpo file into the Microsoft Dynamics AX 2012 system by clicking **Import** on the AOT toolbar.

6.  Continue with the next steps in the **AOD code upgrade checklist**.
    

    > [!IMPORTANT]
    > <P>You must first import the layers that Microsoft owns. You can then import the remaining layers one at a time, starting with the lowest layer.</P>



## See also

[Import AOD files into the baseline model store](import-aod-files-into-the-baseline-model-store.md)

  


