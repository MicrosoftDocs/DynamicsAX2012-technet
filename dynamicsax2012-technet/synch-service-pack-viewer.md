---
title: Synch Service Pack Viewer
TOCTitle: Synch Service Pack Viewer
ms:assetid: 93002074-d4d3-4efe-9678-014f77e42f39
ms:mtpsurl: https://technet.microsoft.com/library/JJ879323(v=AX.60)
ms:contentKeyID: 50639280
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
---

# Synch Service Pack Viewer 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

Commerce Data Exchange: Synch Service Pack Viewer is a tool that helps you examine the data that is contained in the packages that are sent and received by Synch Service. Use Pack Viewer as a troubleshooting resource when you experience an issue with data synchronization or replication.

## Save package files for viewing in Pack Viewer

Package files are available for viewing only if you specify in Synch Service Settings that the package files should be saved. Complete the following procedure to configure this option.


> [!NOTE]
> <P>You must have administrative credentials to open the Synch Service Settings wizard.</P>



1.  Click **Start** \> **All Programs** \> **Microsoft Dynamics AX** \> **Commerce Data Exchange** \> **Synch Service** \> **Service Settings** to open the wizard.

2.  Select the instance of Synch Service to configure, and then click through the wizard to apply the following settings:
    
      - On the **Synch Service specific properties** page, in the **Working Directory** field, type the path of, or browse to, the folder where you want to save the packages.
    
      - On the **Server debugging properties** page, select the **Keep Package Files** check box, and then click **Finish**.
        
        If you do not select this check box, package files are saved only when Synch Service encounters an error during processing of a package.
        

        > [!Caution]
        > <P>Although you can save all packages as a message archive, this option can consume disk space quickly. We recommend that you clear the <STRONG>Keep Package Files</STRONG> check box when you have finished troubleshooting.</P>



For more information about the Synch Service Settings wizard, see [Configure settings for Synch Service](configure-settings-for-synch-service.md).

## Convert files by using Pack Viewer

Pack Viewer converts package files from binary format into XML files that you can open in Notepad or another text editor. A package can contain any of the following items:

  - The database query that is used

  - The data that must be inserted

  - Both the query and the data

Use the following procedure to convert files.

1.  Click **Start** \> **All Programs** \> **Microsoft Dynamics AX** \> **Commerce Data Exchange** \> **Synch Service** \> **Pack Viewer** to open Pack Viewer.

2.  In the **File to convert** field, type the path and name of, or browse to, the file to convert. The files are located in the directory that you specified in Synch Service Settings.

3.  In the **Extract to folder** field, type the path of, or browse to, the folder that will contain the XML file that is generated.
    
    There is one XML file for the header and one for each table that is included in the package. The files are stored in a folder that has the same name as the package.

4.  If you want the destination folder to open in Windows Explorer when the conversion is completed, select the **Open Folder** check box.

5.  Click **Convert**.

6.  In Notepad or another text editor, open the destination file.

## File formats

Use the information in the following tables to help identify the files that you convert by using Pack Viewer.

### ![JJ879323.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ879323.collapse_all(en-us,AX.60).gif")Synch Service at headquarters

For the Synch Service instance that connects to Microsoft Dynamics AX, the following file formats are used for temporary files.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Job type</p></th>
<th><p>Message direction</p></th>
<th><p>File suffix</p></th>
<th><p>File description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>A or N</p></td>
<td><p>Incoming</p></td>
<td><p>I</p></td>
<td><p>Database read request from Microsoft Dynamics AX</p></td>
</tr>
<tr class="even">
<td><p>A or N</p></td>
<td><p>Outgoing</p></td>
<td><p>R</p></td>
<td><p>Data package sent to the channel</p></td>
</tr>
<tr class="odd">
<td><p>P</p></td>
<td><p>Incoming</p></td>
<td><p>I</p></td>
<td><p>Data package received from the channel</p></td>
</tr>
<tr class="even">
<td><p>P</p></td>
<td><p>Outgoing</p></td>
<td><p>I</p></td>
<td><p>Data package sent to Microsoft Dynamics AX</p>
  
> [!Note]  
> Both incoming and outgoing data packages for P jobs have the same suffix. In order to view content in an outgoing data package, you must change the suffix for the corresponding file to R. If you do not change the suffix, an error will be displayed when you attempt to view the package.
 
</td>
</tr>
</tbody>
</table>


### ![JJ879323.collapse\_all(en-us,AX.60).gif](images/Gg841655.collapse_all(en-us,AX.60).gif "JJ879323.collapse_all(en-us,AX.60).gif")Synch Service at the channel

For the Synch Service instance that connects to the retail channel database, the following file formats are used for temporary files.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Job type</p></th>
<th><p>Message direction</p></th>
<th><p>File suffix</p></th>
<th><p>File description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>A or N</p></td>
<td><p>Incoming</p></td>
<td><p>I</p></td>
<td><p>Data package received from headquarters</p></td>
</tr>
<tr class="even">
<td><p>A or N</p></td>
<td><p>Outgoing</p></td>
<td><p>I</p></td>
<td><p>Data package sent to the channel database</p>

> [!Note]  
> Both incoming and outgoing data packages for A and N jobs have the same suffix. In order to view content in an outgoing data package, you must change the suffix for the corresponding file to R. If you do not change the suffix, an error will be displayed when you attempt to view the package.
 
</td>
</tr>
<tr class="odd">
<td><p>P</p></td>
<td><p>Incoming</p></td>
<td><p>I</p></td>
<td><p>Data upload request received from headquarters</p></td>
</tr>
<tr class="even">
<td><p>P</p></td>
<td><p>Outgoing</p></td>
<td><p>R</p></td>
<td><p>Data package sent to headquarters</p></td>
</tr>
</tbody>
</table>

  


