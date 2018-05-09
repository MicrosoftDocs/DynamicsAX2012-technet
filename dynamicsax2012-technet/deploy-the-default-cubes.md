---
title: Deploy the default cubes
TOCTitle: Deploy the default cubes
ms:assetid: 581f609e-588c-45ce-bc10-32a863ef4589
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dd309683(v=AX.60)
ms:contentKeyID: 28119359
ms.date: 07/28/2014
mtps_version: v=AX.60
---

# Deploy the default cubes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This article explains how to deploy the default OLAP (online analytical processing) cubes that are included with Microsoft Dynamics AX. There are two ways to deploy these cubes: by using the Analysis Services Project Wizard in Microsoft Dynamics AX, or by using Windows PowerShell.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<tbody>
<tr class="odd">
<td><img src="images/Dd309683.TopicIcons_Task(AX.60).png" title="Tasks" alt="Tasks" />
<p>See what cubes are available</p>
<p>Deploy the default cubes by using the Analysis Services Project Wizard</p>
<p>Deploy the default cubes by using Windows PowerShell</p></td>
<td><img src="images/Dn507140.TopicIcons_Resources(AX.60).png" title="Resources" alt="Resources" />
<p><a href="cube-and-kpi-reference-for-microsoft-dynamics-ax.md">Cube and KPI reference for Microsoft Dynamics AX</a></p>
<p><a href="windows-powershell-for-microsoft-dynamics-ax-cmdlet-reference.md">Windows PowerShell for Microsoft Dynamics AX cmdlet reference</a></p></td>
</tr>
</tbody>
</table>


## See what cubes are available

To deploy the default cubes that are included with Microsoft Dynamics AX, you must deploy a Microsoft SQL Server Analysis Services project. The following table lists the Analysis Services projects that you can deploy, and the cubes that they contain.

<table xmlns="http://www.w3.org/1999/xhtml">
  <tr>
    <th> <p>
   
	 Analysis Services project
  </p> </th>
    <th> <p>
   
	 Cubes in the project
  </p> </th>
    <th> <p>
   
	 Notes
  </p> </th>
  </tr>
  <tr>
    <td> <p> <strong>Dynamics AX</strong> </p> </td>
    <td> <p>
   
	 Accounts payable cube
  </p> <p>
   
	 Accounts receivable cube
  </p> <p>
   
	 Budget control cube*
  </p> <p>
   
	 Budget plan cube*
  </p> <p>
   
	 Environmental sustainability cube
  </p> <p>
   
	 Expense management cube
  </p> <p>
   
	 General ledger cube
  </p> <p>
   
	 Human resources cube**
  </p> <p>
   
	 Inventory value cube*
  </p> <p>
   
	 Payroll cube**
  </p> <p>
   
	 Production cube
  </p> <p>
   
	 Profit tax totals cube*
  </p> <p>
   
	 Project accounting cube
  </p> <p>
   
	 Purchase cube
  </p> <p>
   
	 Retail cube*
  </p> <p>
   
	 Sales and marketing cube*
  </p> <p>
   
	 Sales cube
  </p> <p>
   
	 Trade allowance management cube***
  </p> <p>
   
	 Workflow cube
  </p> </td>
    <td> <p>
   
	 This project must be deployed before any other Analysis Services projects are deployed.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Demand Forecast</strong> </p> </td>
    <td> <p>
   
	 Demand forecast cube***
  </p> </td>
    <td> <p>
   
	 This project is available with Microsoft Dynamics AX 2012 R3.
  </p> </td>
  </tr>
  <tr>
    <td> <p> <strong>Demand Forecast Accuracy</strong> </p> </td>
    <td> <p>
   
	 Demand forecast accuracy cube***
  </p> </td>
    <td> <p>
   
	 This project is available with Microsoft Dynamics AX 2012 R3.
  </p> </td>
  </tr>
  <tr>
    <td colspan="3"> <p>
   
	 * Indicates cubes that are available with Microsoft Dynamics AX 2012 R2 or later.
  </p> <p>
   
	 ** Indicates cubes that are available with cumulative update 7 for Microsoft Dynamics AX 2012 R2 or later.
  </p> <p>
   
	 *** Indicates cubes that are available with Microsoft Dynamics AX 2012 R3 or later.
  </p> <p></p> </td>
  </tr>
</table>


## Deploy the default cubes by using the Analysis Services Project Wizard

The following procedure explains how to deploy an Analysis Services project—and process the cubes that it contains—by using the Analysis Services Project Wizard in Microsoft Dynamics AX.

To complete this procedure, you must be assigned to the System Administrator role or the Information Technology Manager role in Microsoft Dynamics AX.


> [!NOTE]
> <P>If you are using the initial version of Microsoft Dynamics AX 2012, you must be assigned to the System Administrator role to complete this procedure. If you install <A href="https://mbs2.microsoft.com/knowledgebase/kbdisplay.aspx?scid=kb%24en-us%242579565%26wa=wsignin1.0">cumulative update 1 for Microsoft Dynamics AX 2012</A>, users in the Information Technology Manager role can also complete this procedure.</P>



1.  Open the Microsoft Dynamics AX client.

2.  Click **File** \> **Tools** \> **Business Intelligence (BI) tools** \> **SQL Server Analysis Services project wizard**.

3.  On the **Analysis Services project wizard** page, click **Next**.

4.  On the **Select an option** page, click **Deploy**, and then click **Next**.

5.  On the **Select an existing Analysis Services project** page, click **Select a project from the AOT**. Select the project you want to deploy from the list, and then click **Next**.
    

    > [!NOTE]
    > <P>You must deploy the <STRONG>Dynamics AX</STRONG> project first. After you deploy that project, you can deploy other projects.</P>



6.  On the **Deployment options** page, follow the instructions for the version of Microsoft Dynamics AX that you are using.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>If you are using this version:</p></th>
    <th><p>Follow these steps:</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Microsoft Dynamics AX 2012 R3</p></td>
    <td><ol>
    <li><p>Select the <strong>Deploy</strong> check box. The Analysis Services project will be associated with the Microsoft Dynamics AX partition that you are currently logged into.</p>
    <p>If the name of the Analysis Services server is incorrect, click <strong>Cancel</strong> to close this wizard. Then open the <strong>Analysis servers</strong> form (<strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Business intelligence</strong> &gt; <strong>Analysis Services</strong> &gt; <strong>Analysis servers</strong>) to enter the correct name of the server.</p></li>
    <li><p>By default, the database that is created is named in the following way: <strong>[Analysis Services project name] + [Partition Key Name]</strong>. If you want the database to have a different name, click the name. Then enter the new name.</p></li>
    <li><p>Select the <strong>Process the project after it is successfully deployed</strong> check box.</p></li>
    <li><p>Click <strong>Next</strong> to deploy the project and process the cubes that are in it.</p></li>
    </ol></td>
    </tr>
    <tr class="even">
    <td><p>Microsoft Dynamics AX 2012 R2</p></td>
    <td><ol>
    <li><p>Select the <strong>Deploy</strong> check box that is associated with the Microsoft Dynamics AX partition that you are currently logged into.</p>
    <p>If the name of the Analysis Services server that is used by the partition is incorrect, click <strong>Cancel</strong> to close this wizard. Then open the <strong>Analysis servers</strong> form (<strong>System administration</strong> &gt; <strong>Setup</strong> &gt; <strong>Business intelligence</strong> &gt; <strong>Analysis Services</strong> &gt; <strong>Analysis servers</strong>) to enter the correct name of the server.</p></li>
    <li><p>By default, the database that is created for each partition is named <strong>Dynamics AX [Partition Key Name]</strong>. If you want the database to have a different name, click the name. Then enter the new name.</p></li>
    <li><p>Select the <strong>Process the project after it is successfully deployed</strong> check box.</p></li>
    <li><p>Click <strong>Next</strong> to deploy the project and process the cubes that are in it.</p></li>
    </ol></td>
    </tr>
    <tr class="odd">
    <td><p>The initial version of Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack</p></td>
    <td><ol>
    <li><p>Select the <strong>Deploy the project</strong> check box.</p></li>
    <li><p>Enter the name of the server that is running Analysis Services.</p></li>
    <li><p>Click <strong>Create new database</strong>.</p>
    <p>By default, the database is named <strong>Dynamics AX</strong>. If you want the database to have a different name, enter a new name.</p>
    <div class="alert">

    > [!IMPORTANT]
    > <P>If you enter a new name for the database, you must modify the DynamicsAXOLAP data source. For more information, see <A href="update-the-olap-data-source.md">Update the OLAP data source</A>.</P>


    </div></li>
    <li><p>Select the <strong>Process the project after it is successfully deployed</strong> check box.</p></li>
    <li><p>Click <strong>Next</strong> to deploy the project and process the cubes that are in it.</p></li>
    </ol></td>
    </tr>
    </tbody>
    </table>


7.  On the **Deploying** page, click **Next** when the deployment is completed.

8.  Click **Finish** to close the wizard.

## Deploy the default cubes by using Windows PowerShell

The following procedure explains how to deploy an Analysis Services project—and process the cubes that it contains—by using Windows PowerShell.

To complete this procedure, you must meet the following requirements:

  - You must be using Microsoft Dynamics AX 2012 R2 or later.

  - You must be assigned to the System Administrator role in Microsoft Dynamics AX.

  - You must be assigned to the Administrators group on the computer from which you’ll run Windows PowerShell.

  - You must install the SQL Server 2008 R2 Analysis Management Objects (AMO) on the computer from which you’ll run Windows PowerShell. You can download AMO from this [page](http://www.microsoft.com/en-us/download/details.aspx?id=16978).

  - You must be assigned to the Server Administrator role in Analysis Services.

  - You must be assigned to the Administrators group on the server that runs Analysis Services.

<!-- end list -->

1.  Open Windows PowerShell as an administrator by following these steps:
    
    1.  Click **Start** \> **Administrative Tools**.
    
    2.  Right-click the **Microsoft Dynamics AX 2012 Management Shell** option.
    
    3.  Click **Run as administrator**.

2.  View a list of the Analysis Services projects that are in the Application Object Tree (AOT) by entering the following command:
    
        Get-AXAnalysisProjectDetail
    

    > [!NOTE]
    > <P>You must deploy the <STRONG>Dynamics AX</STRONG> project first. After you deploy that project, you can deploy other projects.</P>



3.  Deploy an Analysis Services project. The Publish-AXAnalysisProject command is used to deploy and process a project. The following examples show how to use this command. For more information, see [Publish-AXAnalysisProject](publish-axanalysisproject.md).
    
      - To deploy and process a project for all partitions in your Microsoft Dynamics AX installation, enter the following command:
        
            Publish-AXAnalysisProject –ProjectName [SSASProjectName] –ServerName [SSASServerName]
    
      - To deploy and process a project for a specific partition in your Microsoft Dynamics AX installation, enter the following command:
        
            Publish-AXAnalysisProject –ProjectName [SSASProjectName] –PartitionKeys [PartitionKey1] -ServerName [SSASServerName]
    
      - To deploy and process a project for two specific partitions in your Microsoft Dynamics AX installation, enter the following command:
        
            Publish-AXAnalysisProject –ProjectName [SSASProjectName] –PartitionKeys [PartitionKey1], [PartitionKey2] -ServerName [SSASServerName]

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

