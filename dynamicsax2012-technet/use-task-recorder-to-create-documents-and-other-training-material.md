---
title: Use Task recorder to create documents and other training material
TOCTitle: Use Task recorder to create documents and other training material
ms:assetid: 1bcbce30-ee14-43c8-9296-15c7b65d51f5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ683224(v=AX.60)
ms:contentKeyID: 49684846
ms.date: 08/20/2014
mtps_version: v=AX.60
f1_keywords:
- document
- documents
- task recorder
- Forms.SysTaskRecorderToolbar
- training
- Forms.SysTaskRecorderPlus
- MsDynAx060.Forms.SysTaskRecorderToolbar
---

# Use Task recorder to create documents and other training material 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic explains how to use Task recorder to quickly document business processes or tasks for training or other purposes. You can use Task recorder to create videos or documents. When you create a document, you can specify a template to use so that all of the documents that you create by using Task recorder have the same look and feel.

Processes and tasks that you might record include the following:

  - Business processes: The purchase order cycle, the sales order payment cycle, or the production planning process.

  - Tasks: Creating a vendor record, setting up budget plans, and generating free text invoices.

Task recorder has two modes: basic and advanced.

**Basic mode**

You can use basic mode to generate a Microsoft Word document and a video recording of the selected business processes. You can then store the documents in a predefined shared folder.

**Advanced mode**

The updated Task recorder includes an advanced mode. Advanced mode captures additional metadata that you can use to create a file that can be uploaded to Business process modeler in Microsoft Dynamics Lifecycle Services. This file includes metadata about the hierarchy, business processes, and Application Object Tree (AOT). It also includes cross-functional flowcharts and activities that you can modify to identify business requirements.

Advanced mode is available by default in Microsoft Dynamics AX 2012 R3 and cumulative update 7 for Microsoft Dynamics AX 2012 R2. If you are working with an earlier version of Microsoft Dynamics AX, you can download the hotfix with the updated version of Task recorder from [Knowledge base article 2863182](http://go.microsoft.com/fwlink/?linkid=309911). For more information, see the following topics:

  - For information about how to use the updated version of Task recorder with Lifecycle Services Business process modeler, see [Upload custom business processes to Business process modeler from Task recorder](upload-custom-business-processes-to-business-process-modeler-from-task-recorder.md).

  - For information about troubleshooting Task recorder, see [Task recorder](task-recorder.md).

## Prerequisites and supported environments

All users who use Task recorder must have write access to a central file share where the recorded output is saved.

The following table shows the requirements for using Task recorder in basic mode and advanced mode.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Requirement</p></th>
<th><p>Basic mode</p></th>
<th><p>Advanced mode</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Required programs</p></td>
<td><ul>
<li><p>Windows Media Player. For more information about Windows Media Player, see <a href="http://windows.microsoft.com/en-us/windows/windows-media-player" class="uri">http://windows.microsoft.com/en-us/windows/windows-media-player</a>.</p></li>
<li><p>Microsoft Word. Word must be installed on the computer where you will use Task recorder. If you don’t have Word installed, the Task recorder generates an XML file.</p></li>
<li><p>Microsoft Dynamics AX and Microsoft Dynamics AX Application Object Server (AOS).</p>
<p>Microsoft Dynamics AX and AOS can be installed on different computers.</p></li>
</ul></td>
<td><ul>
<li><p>All the programs that are required for basic mode.</p>
<div class="alert">

> [!IMPORTANT]
> <P>In advanced mode, Microsoft Dynamics AX and AOS must be installed on the same computer.</P>


</div></li>
<li><p>Microsoft Office</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Additional requirements</p></td>
<td><p>None</p></td>
<td><p>The AOS service account must have write access to the document folder share.</p></td>
</tr>
</tbody>
</table>


## Set up Task recorder parameters

Before you can record business processes and tasks, you must define where the recordings, documents, and templates will be stored. Use the following procedure to define a storage location.

1.  Open Microsoft Dynamics AX, and on the **File** menu, click **Tools** \> **Task recorder** to open the **Task recorder** form.

2.  On the **Action Pane**, on the **Settings** tab, click **Parameters**.

3.  In the **Task recorder parameters** form, browse to or enter the file paths where recordings, documents, and templates will be stored.

You must also create a hierarchy. Task Recorder uses the hierarchy to associate each recording with a business process or task. When you record for the first time after you set up the parameters, a message is displayed that offers to create a default industry and framework, and default hierarchy levels. Click **OK** to have the defaults created for you.

## Prepare to record

The following recommendations will help make sure that you are prepared to complete a successful recording:

  - Be sure that you know all of the steps in the tasks that you plan to perform, and that you have prepared the environment so that you can perform all of the steps.

  - Be ready to perform the task relatively slowly. If you move too quickly, for example if you spend less than one second on a form, Microsoft Dynamics AX may not be able to take a screen shot of the form.

  - Determine the format for the output of your recording, and make sure that the appropriate software is installed on your computer.

  - Be prepared to record the task more than one time. Task recorder may not record all of the screen shots that you want, or you may want to add more steps.

## Output options

After you record a task, the video and Word document are stored in the file location that you selected in the **Parameters** form. The following table provides a list of the features of each document type that you can generate after using Task recorder to record a task. You can select a template to use for Word files.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Output format</p></th>
<th><p>Features</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Microsoft Word</p></td>
<td><p>The Word document output includes:</p>
<ul>
<li><p>Document heading</p></li>
<li><p>Document information including who recorded the task, the date of the recording, the date that the document is generated, and a description of the document.</p></li>
<li><p>A table of contents that lists the forms that are opened during the recording.</p></li>
<li><p>Numbered lists that include the following information:</p>
<ul>
<li><p>A step for each form that indicates how to open it.</p></li>
<li><p>A screen shot for each form.</p></li>
<li><p>Steps that describe which values changed in a form, and, if available, a description of which table that value is stored in.</p></li>
</ul></li>
<li><p>Steps that indicate which buttons to click.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>Windows Media Player</p></td>
<td><p>Windows Media Player takes periodic snapshots that are combined to create a recording of a task.</p></td>
</tr>
<tr class="odd">
<td><p>Business process modeler output files</p></td>
<td><p>These files can be uploaded to Lifecycle Services to provide the business process model maps.</p></td>
</tr>
</tbody>
</table>


## Record a task in basic mode

Use this procedure to record a task using Task recorder in basic mode. For information about how to record a task in Task recorder using advanced mode, see the section **Use Task recorder in advanced mode**.

1.  In Microsoft Dynamics AX, open the form that you will use to complete the task that you’re recording.

2.  On the **File** menu, click **Tools** \> **Task recorder** to open the **Task recorder** form.

3.  Select the node that you are creating a recording for.
    
    You can’t create a recording for the root node. If there is only a root node, you must add a new node.
    
    1.  Select the root node, and then click **New node**.
    
    2.  In the form that opens, enter a name and description for the new node.
    
    3.  In the **Module** field, select the business process that the node represents, and then, in the **Operation group** field, select whether the node is created for a core business process or supporting business process.
    
    4.  Click **Save**.

4.  Click **Start**.

5.  Perform the task that you are recording.

6.  Click **Stop** to stop the recording.

7.  In the **Stop recording** form, click **Yes** to save the recorded sequence of steps, and then enter a name for the recorded task. To easily identify the task later, you can also add a brief description of the task.

## Use Task recorder in advanced mode

When you record a business process or task in advanced mode, you can upload the recorded file and related information to Business process modeler in Lifecycle Services. The procedures in this section explain how to configure Task recorder for advanced mode, configure other information that you need, record a task, and then upload the information to Business process modeler.

## Configure Task recorder for advanced mode

Use this procedure to configure Task recorder for advanced mode.

1.  In Microsoft Dynamics AX, on the **File** menu, click **Tools** \> **Task recorder**.

2.  In the **Task recorder** form, on the **Action Pane**, on the **Settings** tab, click **Industry** to configure a new industry.

3.  Enter information about the industry, and then close the **Industry parameters** form.

4.  In the **Task recorder** form, on the **Settings** tab, click **Framework** to configure a new framework.

5.  Enter information about the new framework, and then close the **Framework parameters** form.

6.  In the **Task recorder** form, on the **Settings** tab, click **Hierarchy levels** to configure the levels for the framework and industry. To capture information for the Business process modeler, select **Advanced** for the combination of a framework and an industry.

7.  Close the **Hierarchy levels** form, and then close the **Task recorder** form.

## Create or upload a business process hierarchy

To use Task Recorder in advanced mode, you must define business process hierarchies. These hierarchies are used to organize business processes as you record them. You can manually create a hierarchy for processes inside Task recorder, or you can create them by using the upload function in Microsoft Excel.

## Create business process hierarchies manually

Use this procedure to create business process hierarchy manually.

1.  In Microsoft Dynamics AX, on the **File** menu, click **Tools** \> **Task recorder**.

2.  In the **Task recorder** form, select a framework and an industry, and then select a node.

3.  Click **New node**, enter information about the node, and then click **Save**.

4.  Optional: Select a node and then click **New node** to create child nodes.

5.  Optional: Use the **Move up**, **Move down**, and **Delete node** buttons to rearrange nodes.

## Upload business process hierarchies by using an Excel template

The business process hierarchy Excel template is available for download by an administrator or developer from the AOT. Once it has been downloaded, other users can complete the template and upload it.

## Download the Excel template

This procedure must be completed by a developer or administrator.

1.  In the AOT, open the shared project SysTaskRecorderPlus.

2.  Under **Resources**, right-click **SysTaskREcorderProcessImportTemplate**, and then click Open.

3.  In the **Preview** form, click **Export**, select a location and file name, and then click **Save**.

4.  After the file has been exported and saved as a template, use this procedure to upload the business process hierarchies.

## Use the Excel template

1.  Open the template in Excel and enter the following data:
    
      - ID
    
      - Process name
    
      - Process description
    
      - Parent ID
    
      - Framework name
    
      - Framework level
    
      - Group
    
      - Module
    
      - Usage profile
    

    > [!NOTE]
    > <P>The values that you enter for the framework name, framework level, and group must also exist in the <STRONG>Industry</STRONG> and <STRONG>Framework</STRONG> forms.</P>



2.  After you enter the information into the Excel template, in Microsoft Dynamics AX, on the **File** menu, click **Tools** \> **Task recorder**.

3.  In the **Task recorder** form, click **Import hierarchy**, and then enter the file name.

4.  Click **Validate** \> **Import hierarchy**. The data is imported into Task recorder.

## Record a task in advanced mode

Use the following procedure to record a task in advanced mode.

1.  Open Microsoft Dynamics AX as an administrator. (Right-click the Microsoft Dynamics AX 2012 icon, and then select **Run as administrator**.)

2.  On the **File** menu, click **Tools** \> **Task recorder**.

3.  In the **Task recorder** form, select the framework and industry, and then expand and select the node to record.

4.  For the selected node, select a module.

5.  Click **Start**. The **Task recorder** form will be minimized.

6.  Complete the task in Microsoft Dynamics AX.
    

    > [!IMPORTANT]
    > <P>The maximum recording length is 10 minutes.</P>



7.  After you finish recording, expand the minimized **Task recorder** form, and then click **Stop**.
    
    The video and the Word document are saved in the folder that you selected in the **Recording file path** field in the **Task recorder parameters** form.

8.  Optional: You can re-record a node; or you can select a node and then click **Clear node**, to delete any associated files.

9.  Optional: After you finish recording, the selected node displays a blue arrow. Select the node and then click **Document** to generate a step-by-step Word document.

10. Optional: To view the video, open the shared folder that you selected in the **Recording file path** field in the **Task recorder parameters** form. Open the subfolder that is named in the format \<Framework\>\_\<Industry\>. For example, if your process name is Create/Distribute purchase orders, the folder name that is created after recording is Create\_4212B2BB.

## Generate a package for Business process modeler in Lifecycle Services

After you have recorded your business processes, you can upload them to Business process modeler. To generate a package file that you can upload, after the processes have been recorded for a framework, in the **Task recorder** form, click **Build package**.


> [!NOTE]
> <P>Each package should be built only one time.</P>



Clicking **Build package** starts a batch job that processes the files. The batch job might take a long time. The length of time will depend on the number items that have already been queued for the batch server. After the batch job is completed, an .axbpm file is generated in the folder that you specified in the **Task recorder parameters** form. The format of the file name is \<Framework\>\_\<Industry\>\<ddmmyyyyhhmm\>.axbpm. This is the file that you upload to Business process modeler.

## Upload the business process files to Business process modeler

The Business process modeler (\*.axbpm) files that are generated by Task recorder can be uploaded to Business process modeler in Lifecycle Services. You can then review and modify the recorded business processes as appropriate. Complete the following steps to upload the business process files:

1.  Sign in to Lifecycle Services. In the **Organization** workspace, select a project.

2.  On the **Project** home page, click the **Business process modeler** tile.

3.  On the **Business process library** page, in the **My projects** or **Corporate library** section, click **Upload**.
    
      - If you upload a business process package to **My projects**, the business processes can be viewed only by you or by the users who you give access to.
    
      - If you upload a business process package to the **Corporate library** section, the business processes can be viewed by all users in your organization.
    
      - If you upload a business process package to **My projects**, you can right-click and then select **Promote** on the app bar. This makes the business processes available in the **Corporate library** section. Only the administrator can approve these promotion requests. You can also promote business processes from the **Corporate library** section to the **Global library** section. Only Microsoft can approve these promotion requests.

4.  On the **Administration** page, in the **New** section, select the industry, and then enter a name and description.

5.  Click **Upload**, select the .axbpm file, and then click **OK**.

You can view the status of the business process upload on the **Administration** page. After the business process package has been uploaded, you can view the business process framework from the **Business process library** page.

## See also

[Upload custom business processes to Business process modeler from Task recorder](upload-custom-business-processes-to-business-process-modeler-from-task-recorder.md)

[Task recorder](task-recorder.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

