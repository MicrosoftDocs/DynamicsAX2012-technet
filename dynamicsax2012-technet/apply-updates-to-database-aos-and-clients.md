---
title: Apply updates to database, AOS, and clients
TOCTitle: Apply updates to database, AOS, and clients
ms:assetid: 5aa25046-422c-4bb7-8fae-5901b3bd426c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh538446(v=AX.60)
ms:contentKeyID: 39508868
ms.date: 12/04/2014
mtps_version: v=AX.60
dev_langs:
- powershell
---

# Apply updates to database, AOS, and clients [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_


> [!NOTE]
> <P>This topic includes information about features that were added or changed for Microsoft Dynamics AX 2012 R3 Cumulative Update 8. For more information, see the section later in this topic.</P>




> [!NOTE]
> <P>The procedure for completing this task has changed for Microsoft Dynamics AX 2012 R3. For information that is specific to Microsoft Dynamics AX 2012 R3, see the section later in this topic.</P>



This topic describes how to download and apply updates to all versions of Microsoft Dynamics AX 2012. The update process varies significantly among versions, so start by choosing the update scenario that applies to your environment.

We recommend that you first install updates in a test environment and then update your production environment. For detailed recommendations, see [Apply updates and hotfixes](apply-updates-and-hotfixes.md).

## Choose an update scenario

The following table describes the update scenarios that are included in this topic.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Scenario</p></th>
<th><p>Relevant sections</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Apply a group of updates to AX 2012 R3</p>
<p></p>
<div class="alert">

> [!IMPORTANT]
> <P>A downloadable guide for installing AX 2012 R3 CU8 is available here: <A href="http://go.microsoft.com/fwlink/?linkid=519005">Cumulative 8 for Microsoft Dynamics AX 2012 R3 Installation Guide</A>.</P>


</div></td>
<td><p>Prepare the environment for updates</p>
<p>Get ready to install an AX 2012 R3 update package</p>
<p>Find, analyze, save and install an update package (R3)</p>
<p>Analyze updates (R3 and CU7)</p>
<p>Install a saved update package (R3)</p>
<p>Perform post-installation steps</p></td>
</tr>
<tr class="even">
<td><p>Apply a single update to AX 2012 R3</p></td>
<td><p>Prepare the environment for updates</p>
<p>Install a single update for AX 2012 R3</p>
<p>Perform post-installation steps</p></td>
</tr>
<tr class="odd">
<td><p>Apply a single update to AX 2012 R2, AX 2012 Feature Pack, AX 2012, or a cumulative update to AX 2012 Feature Pack or AX 2012</p></td>
<td><p>Prepare the environment for updates</p>
<p>Download and extract an update from CustomerSource, PartnerSource, or Lifecycle Services</p>
<p>Analyze the effect of a single update or hotfix on your environment</p>
<p>Install a single update or hotfix</p>
<p>Perform post-installation steps</p></td>
</tr>
<tr class="even">
<td><p>Apply cumulative update 7 for Microsoft Dynamics AX 2012 R2</p></td>
<td><p>Prepare the environment for updates</p>
<p>Uninstall the Data Import/Export Framework or Data Migration Framework</p>
<p>Download and extract AX 2012 R2 cumulative update 7</p>
<p>Analyze and install CU7:</p>
<ul>
<li><p>Install all updates using express installation (CU7)</p></li>
<li><p>Install a subset of a cumulative update (CU7)</p></li>
</ul>
<p>Perform post-installation steps</p></td>
</tr>
<tr class="odd">
<td><p>Apply cumulative update 6 for Microsoft Dynamics AX 2012 R2</p></td>
<td><p>Prepare the environment for updates</p>
<p>Download and extract AX 2012 R2 cumulative update 6</p>
<p>Install updates (CU6)</p>
<p>Analyze updates (CU6)</p>
<p>Perform post-installation steps</p></td>
</tr>
<tr class="even">
<td><p>Deploy updates to the rest of the environment</p></td>
<td><p><a href="deploy-updated-reports-to-a-report-server.md">Deploy updated reports to a report server</a></p>
<p><a href="deploy-updates-to-enterprise-portal.md">Deploy updates to Enterprise Portal</a></p>
<p><a href="deploy-updates-in-a-retail-environment.md">Deploy updates in a retail environment</a></p></td>
</tr>
<tr class="odd">
<td><p>Roll updates to a production environment</p></td>
<td><p>Validate the update</p>
<p>Roll an update forward to the production environment</p></td>
</tr>
</tbody>
</table>


## Prepare the environment for updates

We strongly recommend that you complete the following procedures before you install updates in your environment.

## Back up databases

Before you install any updates, we strongly recommend that you back up any databases in the environment that are affected by the updates. For more information, see [Back up and recover databases (SQL Server)](back-up-and-recover-databases-sql-server.md).

## Export external invoices (required if you are running tax integration for China)

If your environment includes tax integration for China, you must export external invoices before you install updates.

1.  Click **Accounts receivable** \> **Periodic** \> **Tax integration** \> **Export to file**.

2.  On the **Batch** tab, enter a description for the batch, and then click **OK**. By default, all invoices are selected.

## Apply an update package to AX 2012 R3

Updates for AX 2012 R3 are available from Microsoft Dynamics Lifecycle Services. You can download a specific cumulative update package. Alternatively, you can download the **Most recent** update package, which contains the most recent updates in addition to the latest cumulative update. You can then install the whole package or select a subset of the package to apply.

## Get ready to install an update package (R3)

We strongly recommend that you complete this procedure before you apply updates.

1.  For each environment that you manage, create a project in Lifecycle Services. For more information, see [Projects (Lifecycle Services, LCS)](projects-lifecycle-services-lcs.md).

2.  Install and run the System diagnostics for each environment, so that the information about your project in Lifecycle Services is accurate.

3.  Download the most recent version of the Update installer.
    
    1.  Log on to Lifecycle Services, open the project that is associated with the environment that you are updating, and then click **Updates**.
    
    2.  Under **Update installer for Microsoft Dynamics AX 2012 R3**, click **Download**.
        
        Save the Update installer to a network location that you can access from the computers in your environment.
    
    3.  Extract the Update installer to every computer in the environment that you might have to apply updates to.
        

        > [!NOTE]
        > <P>To extract the Update installer, you must be an administrator on the local computer.</P>
        > <P>For information about the recommended installation order when you apply updates, see <A href="apply-updates-and-hotfixes.md">Apply updates and hotfixes</A>.</P>



4.  Verify that you have appropriate permissions. To run the Update installer, you must have administrator rights on the local computer and System Administrator rights in Microsoft Dynamics AX.
    
    To install application hotfixes, you must have the following additional rights in Microsoft SQL Server:
    
      - You are a member of the **Securityadmin** server role on the SQL Server instance.
    
      - You are assigned to the **db\_owner** role in the model database.

## Find, analyze, save, and install an update package (R3)

We recommend that you first complete this procedure on an instance of Microsoft Dynamics AX Application Object Server (AOS) that is connected to the appropriate database instance, and select both binary and application hotfixes. In this way, you create as few custom update packages as possible.

1.  On any AOS, client, or database computer in the environment, run the Update installer (AXUpdate), and accept the license terms.

2.  On the **Download or install updates** page, click **Download updates**.

3.  Lifecycle Services opens in a browser window. Log on, and select the appropriate update package.

4.  Optional: If you have access to a project in Lifecycle Services that contains business processes that you want to use to help select appropriate updates, click **Get business process information for a Lifecycle Services project**. Select the appropriate project, and then click **OK**.

5.  After the package downloads, the **Select update type** page opens. Select binary updates, application updates, or both. For more information about hotfix types, see [Apply updates and hotfixes](apply-updates-and-hotfixes.md)
    
    If binary updates are available for the computer that you are installing on, we strongly recommend that you select them in addition to the application updates.

6.  If you selected to install application updates, follow these steps:
    
    1.  On the **Choose a model store** page, select a local instance to update, or click **Find a different model store** to enter the name of a remote database instance.
    
    2.  On the **Select application updates** page, you can select **All updates**, or **Applicable updates**. You can optionally use the **Fix type**, **Module**, **License code**, **Region/Country**, or **Business process** field list to filter the application updates.
        
        You can group application updates by fix type, number of conflicts, business process, or configuration key.
        
        For any hotfix, the **Details** pane displays the KB number and title of the hotfix, the model and layers that the hotfix applies to, and any updates that are included. Review the hotfix details, and then click the **Conflicts** tab to view the conflict summary. Use **Get conflict details** to view additional detailed information or open the Impact Analysis Wizard for a single hotfix.
    
    3.  The **Review conflicts** page lists the number of conflicts that are associated with each model file that will be installed. To review conflicts in detail, click **Impact Analysis Wizard**. For information about how to run the Impact Analysis Wizard, see Analyze updates (R3 and CU7).
    
    4.  On the **Review updates** page, click **Next**.

7.  Optional: On the **Save updates** page, click **Save custom update package**. You can then reuse the installation package that you have created on another computer in your environment.
    
    After the custom update package has been created, you can open the location where it is stored.
    

    > [!NOTE]
    > <P>If you have selected binary updates, all binary updates are saved to the custom update package that you create, regardless of the computer or components that you have chosen to update.</P>



8.  To immediately install the selected updates on the current computer, click **Install selected updates on this computer**, and then click **Next**.

9.  On the **Review components** page, validate that the correct components are selected, and then click **Next**.

10. On the **Ready to install** page, review the summary, and then click **Install**.
    
    When installation is completed, you can see whether each component was installed.

11. Continue with the Perform post-installation steps section of this topic.

12. Use the instructions in the Install a saved update package (R3) section to install the same set of updates on all appropriate computers in your environment.

## Analyze updates (R3 and CU7)

1.  The **Welcome to Microsoft Dynamics AX Update Setup—Impact Analysis Mode** page lists all hotfixes that you previously selected. Click **Next**.

2.  On the **Select client configuration** page, select a client configuration or a configuration file to use for comparison with the updates that you plan to install, and then click **Next**.

3.  On the **Select model store** page, select a model store to analyze, and then click **Next**.
    

    > [!NOTE]
    > <P>The model store that you select must be the same model store that is used by the client configuration that you selected.</P>



4.  On the **Select baseline model store** page, select a baseline model store to use for the impact analysis, and then click **Next**.
    

    > [!NOTE]
    > <P>You can also select a non-local baseline model store or create a new baseline model store.</P>
    > <P>The baseline model store that you select must be the same model store that is used by the client configuration that you selected.</P>
    > <P>The Impact Analysis Wizard deletes the existing contents of the baseline model store to perform the analysis.</P>



5.  The **Review the impact analysis configuration** page displays the selected configuration. For the **Select layers to analyze** field, select whether to analyze all layers or only layers that include changes, and then click **Start Analysis**.
    

    > [!WARNING]
    > <P><STRONG>Select layers to analyze</STRONG> is not available unless you have installed application hotfix KB 2885584, compiled the application, and started the Impact analysis wizard.</P>

    
    The **Analyzing impact** page is displayed until the analysis is completed.

6.  The **Results** page lists the objects that are affected and the number of cross-references. Click **Open the impact analysis results log file** to view the results.

7.  Click **Advanced** to open the AX 2012 R2 client to view the details of the impact analysis.

8.  Close the AX 2012 client.

9.  Close the Impact Analysis Wizard.

## Install a saved update package (R3)

By saving a custom update package, you can streamline the update process. When you create a custom update package, you no longer have to download an update package or select the application hotfixes to install when you install updates. Instead, the parts of the update package that you have already selected can be applied quickly in a new location.

1.  Run the Update installer on the computer where you want to install a saved update package.

2.  On the **Download or install updates** page, click **Install updates**, and then enter or browse to the location of the update package that you previously saved.

3.  On the **Select update type** page, select binary updates, application updates, or both.

4.  If you chose to install application updates, follow these steps:
    
    1.  On the **Choose a model store** page, select a local instance to update, or click **Find a different model store** to enter the name of a remote database instance.
    
    2.  The **Review conflicts** page lists the number of conflicts that are associated with each model file that will be installed. To review conflicts in detail, click **Impact Analysis Wizard**. For information about how to run the Impact Analysis Wizard, see Analyze updates (R3 and CU7).
    
    3.  On the **Review updates** page, click **Next**.

5.  On the **Review components** page, validate that the correct components are selected, and then click **Next**.

6.  On the **Ready to install** page, review the summary, and then click **Install**.
    
    When installation is completed, you can see whether each component was installed.

7.  Continue with the Perform post-installation steps section of this topic.

## Install a single update for AX 2012 R3

If you download a single update for AX 2012 R3 from Lifecycle Services, CustomerSource, or PartnerSource, a modified version of the Update installer is included with the update.

1.  Run the Update installer (AXUpdate), and accept the license terms.

2.  On the **Review components** page, select the components to update, and then click **Next**.

3.  If database components are available, and you apply them, follow these steps:
    
    1.  On the **Choose a model store** page, select a local instance to update, or click **Find a different model store** to enter the name of a remote database instance.
    
    2.  The **Review conflicts** page lists the number of conflicts that are associated with each model file that will be installed. To review conflicts in detail, click **Impact Analysis Wizard**. For information about how to run the Impact Analysis Wizard, see Analyze updates (R3 and CU7).
    
    3.  On the **Review updates** page, click **Next**.

4.  On the **Review components** page, verify that the correct components are selected, and then click **Next**.

5.  On the **Ready to install** page, review the summary, and then click **Install**.
    
    When installation is completed, you can see whether each component was installed.

6.  Continue with the Perform post-installation steps section of this topic.

## Apply a single update to AX 2012 R2, AX 2012 Feature Pack, AX 2012, or a cumulative update to AX 2012 Feature Pack or AX 2012

## Download and extract an update from CustomerSource, PartnerSource, or Lifecycle Services

To find an update, you can browse or search on CustomerSource, PartnerSource, or Lifecycle Services.

We provide the following landing pages for hotfixes and cumulative updates on [AX 2012 R2 Hotfix landing page](http://go.microsoft.com/fwlink/?linkid=329036%26clcid=0x409) and [AX 2012 Hotfix landing page](http://go.microsoft.com/fwlink/?linkid=232954).

You can also use [Issue Search on Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306503), or search [CustomerSource](http://go.microsoft.com/fwlink/?linkid=210925) or [PartnerSource](http://go.microsoft.com/fwlink/?linkid=210926) for Knowledge Base (KB) articles, and for information about hotfixes and updates that have been released. On CustomerSource or PartnerSource, search for the term hotfix or cumulative update. If you do not find information about the specific issue that you are experiencing, you can try one of the following options:

  - Open a support request by contacting your partner or value-added reseller (VAR).

  - If you are enrolled in a support plan directly with Microsoft, log on to [CustomerSource](https://mbs.microsoft.com/support/newstart.aspx), and submit a new support request.

Updates for Microsoft Dynamics AX are shipped as self-extracting executable files. Before you can install an update, you must extract the files that are required to install it.

1.  Download the update.

2.  Double-click the downloaded file to extract the contents.
    
    We recommend that you extract the files to a location that can be accessed from all servers and clients that you plan to update.

## Analyze the effect of a single update or hotfix on your environment (CU6 and earlier)

Microsoft Dynamics AX updates are shipped together with the Impact Analysis tool, AXImpactAnalysis.exe. This tool is a version of the update installer that helps you determine the effect that an update has on your environment before you install the update.

1.  Browse to the location where you extracted the files for the service pack, right-click **AXImpactAnalysis.exe**, and then click **Run as Administrator**.

2.  On the **Welcome to Microsoft Dynamics AX Update Setup—Impact Analysis Mode** page, click **Next**.

3.  On the **License terms** page, review the license terms. Select the option to accept the license terms, and then click **Next**.

4.  On the **Select client configuration** page, select a client configuration or a configuration file to analyze, and then click **Next**.

5.  On the **Select model store** page, select a model store to analyze, and then click **Next**.
    

    > [!NOTE]
    > <P>The model store that you select must be the same model store that is used by the client configuration that you selected.</P>



6.  On the **Select baseline model store** page, select a baseline model store to use for the impact analysis, and then click **Next**.
    

    > [!NOTE]
    > <P>The model store that you select must be the same model store that is used by the client configuration that you selected.</P>
    > <P>AXImpactAnalysis.exe deletes the existing contents of the baseline model store to perform the analysis.</P>



7.  A list of affected objects is displayed. Click **Impact Analysis** to open the Microsoft Dynamics AX client and view detailed results of the impact analysis.
    
    You can use the **Impact Analysis** form to view details about the objects that are affected by the update, and to export the results. You can perform the following actions:
    
      - **Compare code** – Click **Compare** to open the **Comparison Results** form. From this form, the changes that were made to an object that was loaded during the impact analysis can be compared with the same object in two other layers.
    
      - **Review cross-references** – The bottom pane of the tool loads the cross-reference data for the selected object. The data that is presented resembles the data that is presented in the **Cross References Used By** view. If cross-reference data is not available, this pane provides an option to update the cross-reference data. For new objects that do not exist in the Microsoft Dynamics AX Application Object Tree (AOT), no cross-reference data is available.

8.  Export the results of the impact analysis, so that you can more quickly make changes after you install the update.
    
    The following options are available. We recommend that you select **Impact Analysis State**.
    
      - **Summary** – Save the information about the objects that are loaded in the form to an XML file that you select. Also save information about the layers where the objects exist, and the number of cross-references.
    
      - **Cross Reference Data** – Save more detailed information about the cross-references of the objects by using Resource Description Format (RDF). For more information about RDF, see [http://www.w3.org/RDF/](http://www.w3.org/rdf/).
    
      - **Impact Analysis State (IAS)** – Save the objects that are loaded in the form to an XML file. This file has an .ias file name extension. After you save the objects to an .ias file, you can load the same list of objects into the **Impact Analysis** form later. This capability is helpful when you must install a hotfix, because you might want to save the list of objects before you start the installation. After the installation is completed, you can reload the objects for additional analysis.

## Install a single update or hotfix (CU6 and earlier)

1.  Browse to the location where you extracted the files for the update, and then double-click **AxUpdate.exe**.

2.  On the **Welcome to Microsoft Dynamics AX Update Setup** page, click **Next**.

3.  On the **License terms** page, review the license terms. Select the option to accept the license terms, and then click **Next**.

4.  On the **Select components** page, in the list of components that can be updated, select the components to update, and then click **Next**.
    
    If you update a database instance, you can select the name of the instance to update the local instance. Alternatively, you can select **Other** to select a remote instance to update. In this case, a **Database instance** page is displayed, where you can select the remote instance.

5.  On the **Ready to install** page, review the summary of the components that are being updated, and then click **Install**.

6.  When the update is completed, click **Finish** to close the wizard.

7.  After the installation is completed, examine the log files that were created by AXUpdate.exe. By default, log files are saved to a subfolder of the %ALLUSERSPROFILE%\\Microsoft\\Dynamics AX\\Dynamics AX Setup Logs folder.

8.  Continue with the Perform post-installation steps section.

## Apply cumulative update 7 for Microsoft Dynamics AX 2012 R2

The installer for cumulative update 7 introduced was updated significantly from prior releases. For details about the features added see: [What's new: Update installer](what-s-new-update-installer.md).


> [!IMPORTANT]
> <P>If you have previously installed the Data Import/Export Framework from InformationSource, you must fully uninstall it before installing cumulative update 7 for Microsoft Dynamics AX 2012 R2.</P>
> <P>If you previously applied any hotfixes that are not included in a cumulative update, these hotfixes are lost during installation. You must reapply the hotfixes after installation.</P>



Cumulative update 7 offers the following installation options:

  - Install all CU7 updates (express installation)

  - Install a subset of cumulative update 7
    
    1.  Install CU7 binary updates on a computer
    
    2.  Install the Data Import/Export Framework (binary updates)
    
    3.  Install CU7 application updates


> [!IMPORTANT]
> <P>Users upgrading from a previous AX 2012 R2 version may experience compiler errors on a few forms that were not intentionally modified in the previous version. These compiler errors may appear on the following forms – SalesTable, SalesQuotationProjTable, and SalesQuotationTable.</P>
> <P>To work around this issue, see the blog post <A href="http://blogs.msdn.com/b/axsupport/archive/2013/11/06/unexpected-compiler-errors-installing-cumulative-update-7-for-microsoft-dynamics-ax-2012-r2.aspx">Unexpected Compiler Errors installing Cumulative Update 7 for Microsoft Dynamics AX 2012 R2</A>.</P>



## Uninstall the Data Import/Export Framework or Data Migration Framework (CU7)

If you have previously installed the Data Import/Export Framework from InformationSource, you must fully uninstall it before installing cumulative update 7 for Microsoft Dynamics AX 2012 R2.

1.  Use **Control Panel \> Add/Remove Programs** to remove all Data Import/Export Framework or Data Migration Framework binary files.

2.  Uninstall any model from the FPK layer with a name that begins with DMF. For more information about uninstalling models, see [How to: Remove (Uninstall) a Model](how-to-remove-uninstall-a-model.md).

## Download and extract CU7

Cumulative update 7 is available for download on CustomerSource, in [KB885603](http://go.microsoft.com/fwlink/?linkid=329979).

Follow the recommendations in the section Download and extract an update from CustomerSource, PartnerSource, or Lifecycle Services to extract the download.

## Install all updates using express installation (CU7)

1.  Browse to the location where you extracted the files for the update, and then double-click **AxUpdate.exe**.

2.  On the **Welcome to Microsoft Dynamics AX Update Setup** page, click **Next**.

3.  On the **Software license terms** page, review the license terms, and then click **Accept and continue**.

4.  On the **Select packages to update** page, select the packages to update, and then click **Next**.
    
    Only updates that are available for installation can be selected.

5.  Select all applicable packages that can be installed, and then click **Next**. You must select **Database** as one of the packages.

6.  On the **Choose a model store** page, select a local instance to update, or click **Add existing model store** to enter the name of a remote database instance.

7.  On the **Select type of installation** page, click **Express installation**.
    
    Review the updates (model files) that will be installed. To review conflicts, you can click **Show conflict details for all updates**. To review updates in detail, click **Impact Analysis Wizard**. For information about how to run the Impact Analysis Wizard, see Run the Impact Analysis Wizard to analyze updates (MSDAX63\_2nd and CU7).

8.  On the **Review updates to be installed** page, click **Next**.

9.  On the **Ready to install** page, review the summary, and then click **Install**.

10. Continue with the Perform post-installation steps section.

## Install a subset of a cumulative update (CU7)

The update installer lets you install a subset of a cumulative update.


> [!IMPORTANT]
> <P>We strongly recommend that you perform the following procedures in the order listed.</P>



## Install binary updates for Microsoft Dynamics AX Application Object Server (AOS), the client, components, Setup, or Microsoft Dynamics AX 2012 for Retail (CU7)

Use the following procedure to install any binary update.


> [!IMPORTANT]
> <P>All binary updates on a computer must be updated at the same time. If more than one AOS instance is installed, all the instances must be updated.</P>



1.  Browse to the location where you extracted the files for the update, and then double-click **AxUpdate.exe**.

2.  On the **Welcome to Microsoft Dynamics AX Update Setup** page, click **Next**.

3.  On the **Software license terms** page, review the license terms, and then click **Accept and continue**.

4.  On the **Select packages to update** page, select the packages to update, and then click **Next**.
    
    Only updates that are available for installation can be selected.

5.  Clear **Database**, select all other packages that can be installed on the local computer, and then click **Next**.

6.  On the **Review updates to be installed** page, click **Next**.

7.  On the **Ready to install** page, review the summary, select the **Automatically restart the AOS instances after installation** check box, and then click **Install**.

8.  After the installation is completed, verify that the updates were installed successfully and then exit the wizard.

9.  In order to be able to use Advanced installation mode to choose specific application hotfixes to apply to the database, you must first install the binary components including the client, reinitialize the model store, and then return to the update installer. For information about reinitializing the model store, see: Reinitialize the model store.

10. Continue with either the Install the Data Import/Export Framework (binary) section or the Perform post-installation steps section.

## Install the Data Import/Export Framework binary updates (CU7)

As of cumulative update 7, you can install the Data Import/Export Framework from the update installer. For an overview of the Data Import/Export Framework, see [Data import/export framework user guide (DIXF, DMF)](data-import-export-framework-user-guide-dixf-dmf.md).


> [!WARNING]
> <P>These instructions only work when SQL Server 2008 or SQL Server 2012 Integration Services are installed. To install Data Import/Export Framework with later versions of SQL Server Integration Services, see <A href="install-the-ax-2012-r2-cu7-version-of-the-data-import-export-framework-for-use-with-sql-server-2014-dixf.md">Install the AX 2012 R2 CU7 version of the Data import/export framework for use with SQL Server 2014 (DIXF)</A>.</P>
> <P>Note that no matter the version, updates to DIXF can be installed by using the update installer.</P>
> <P>If you have previously installed the Data Import/Export Framework from InformationSource or Lifecycle Services, you must fully uninstall it before installing again with cumulative update 7 for Microsoft Dynamics AX 2012 R2. For more information, see Uninstall the Data Import/Export Framework or Data Migration Framework.</P>



1.  Browse to the location where you extracted the files for the update, and then double-click **AxUpdate.exe**.

2.  On the **Welcome to Microsoft Dynamics AX Update Setup** page, click **Next**.

3.  On the **Software license terms** page, review the license terms, and then click **Accept and continue**.

4.  On the **Select packages to update** page, select the components of the Data Import/Export Framework that can be installed on the local computer, and then click **Next**.

5.  The prerequisite validation check runs. Address any issues that the prerequisite check finds outside the installer, and then restart the validation check. When all prerequisites have been found, click **Next**.

6.  If you are installing on the computer that runs Microsoft SQL Server Integration Services, specify a service account and the version of SQL Server that is running. We recommend that you use the AOS service account.
    
    –or–
    
    If you are installing on the AOS computer, specify the name of the server that is running SQL Server Integration Services.

7.  On the **Review updates to be installed** page, click **Next**.

8.  On the **Ready to install** page, review the summary, select the **Automatically restart the AOS instances after installation** check box, and then click **Install**.

9.  After the installation is completed, verify that the updates were installed successfully, and then exit the wizard.

## Install application (database) updates (CU7)

To update application features, you update the database. The Update wizard lets you apply all application updates. Alternatively, you can select application updates to install based on module, configuration key, locale, or the business processes that you have modeled in Microsoft Dynamics Lifecycle Services.

1.  Browse to the location where you extracted the files for the update, and then double-click **AxUpdate.exe**.

2.  On the **Welcome to Microsoft Dynamics AX Update Setup** page, click **Next**.

3.  On the **Software license terms** page, review the license terms, and then click **Accept and continue**.

4.  On the **Select packages to update** page, select all applicable packages that can be installed on the local computer, and then click **Next**. You must select **Database** as one of the packages.

5.  On the **Choose a model store** page, select a local instance to update, or click **Add existing model store** to enter the name of a remote database instance.

6.  On the **Select type of installation** page, click **Advanced installation**.

7.  Optional: If you have access to a project in Lifecycle Services that contains business processes that you want to use to help select appropriate updates, click **Log on to Microsoft Dynamics Lifecycle Services**, and then click **Next**. When a browser window opens, follow these steps:
    
    1.  Log on to Lifecycle Services.
    
    2.  If the **Lifecycle Services License terms** page opens, click **Accept and continue**.
    
    3.  Select a Lifecycle Services project and then click **OK**.
        
        Once the business process information has been retrieved, the browser window closes.

8.  On the **Select application updates** page, click **Applicable updates**. You can optionally use the **Group by** list to filter the application updates by module, country/region, configuration key, or business process.
    
    For any hotfix, the details pane displays the title of the hotfix, the model and layers that the hotfix applies to, and any updates that are included. Review the hotfix details, and then click the **Conflicts** tab to view the conflict summary. Use **Get conflict details** to view additional detailed information or open the Impact Analysis Wizard for a single hotfix.
    

    > [!IMPORTANT]
    > <P>We strongly recommend that you install hotfixes <STRONG>KB 2885584</STRONG> (Impact wizard update) and <STRONG>KB 2894100</STRONG> (Update checklist merge code feature) with any installation, so that you get the full functionality of the changes made to the update features.</P>



9.  Select all appropriate hotfixes for your environment, and then click **Next**.
    
    The **Review updates to be installed** page opens. This page lists the models that will be installed and the details (model name, description, layer, and updates that are included).

10. On the **Review updates to be installed** page, we recommend that you click **Show conflict details for all updates**, and then, on the **Conflict details** page, click **Impact Analysis Wizard**. For information about the Impact Analysis Wizard, see Run the Impact Analysis Wizard to analyze updates (MSDAX63\_2nd and CU7).
    
    You may also want to click **Export update list**, so that you can later use the file to speed up applying application updates to another computer.

11. On the **Review updates to be installed** page, click **Next**.

12. On the **Ready to install** page, review the summary, and then click **Install**.

13. After the installation is completed, verify that the updates were installed successfully, and then exit the wizard.

14. Continue with the Perform post-installation steps section.

## Apply cumulative update 6 for Microsoft Dynamics AX 2012

This section describes how to install and analyze updates for cumulative update 6.


> [!NOTE]
> <P>If you previously applied any hotfixes that are not included in a cumulative update, these hotfixes are lost during installation. You must reapply the hotfixes after installation.</P>



## Download and extract CU6

Cumulative update 6 is available for download on CustomerSource, in [KB 2850972](http://go.microsoft.com/fwlink/?linkid=309870).

Follow the recommendations in the section Download and extract an update from CustomerSource, PartnerSource, or Lifecycle Services to extract the download.

## Install updates (CU6)


> [!WARNING]
> <P>In order to be able to choose specific application hotfixes to apply to the database, you must first install the binary components including the client and then reinitialize the model store, and then return to the update installer.</P>
> <P>For instructions for reinitializing the model store, see Reinitialize the model store.</P>



1.  Browse to the location where you extracted the files for the update, and then double-click **AxUpdate.exe**.

2.  On the **Welcome to Microsoft Dynamics AX Update Setup** page, click **Next**.

3.  On the **License terms** page, review the license terms. Select the option to accept the license terms, and then click **Next**.

4.  If you do not select **Database**, go to step 6.
    
    –or–
    
    If you select **Database**, follow these steps:
    
    1.  On the **Database instances** page, select a local instance to update, or enter the name of a remote database instance.
    
    2.  On the **Select type of installation** page, select **Express** or **Advanced**.
        
          - If you select **Express**, all hotfixes in the update will be installed. Go to step 5.
        
          - If you select **Advanced**, you can select which hotfixes to install on the **Select database updates** page.
    
    3.  On the **Select database updates** page, select the hotfixes to install, and then click **Next**. The information that is displayed changes based on your selection.
        
          - You can select individual hotfixes in the update to install, based on the module, country/region, or configuration key.
            
            Click **Display only applicable updates based on installed and licensed features** to filter the list further.
            
            For each hotfix that you select, the page displays the title of the hotfix, the model and layers that the hotfix applies to, and any updates that are included.
        
          - Click **Get conflict summary** to show the number of objects that are affected. These objects include tables, classes, forms, and reports.
        
          - For more information, click **Get conflict details** to view a list of conflicts and details about each. To further analyze the effect of the conflicts, click **Launch Impact Analysis Wizard**. For information about the wizard, see Run the Impact Analysis wizard (recommended).

5.  The **Review updates to be installed** page opens. This page lists the models that will be installed and the details (model name, description, layer, and updates that are included).
    
    Optional but strongly recommended: Click **Show conflict details for all updates** to start the Impact Analysis Wizard for the selected updates. For more information, see Run the Impact Analysis wizard (recommended).

6.  On the **Ready to install** page, review the summary of the components that are being updated, and then click **Install**.

7.  When the update is completed, click **Finish** to close the wizard.

8.  After the installation is completed, examine the log files that were created by AXUpdate.exe. By default, log files are saved to a subfolder of the %ALLUSERSPROFILE%\\Microsoft\\Dynamics AX\\Dynamics AX Setup Logs folder.

9.  Continue with the Perform post-installation steps section.

## Analyze updates (CU6)

1.  On the **Welcome to Microsoft Dynamics AX Update Setup—Impact Analysis Mode** page, click **Next**.

2.  On the **Select client configuration** page, select a client configuration or a configuration file to analyze, and then click **Next**.

3.  On the **Select model store** page, select a model store to analyze, and then click **Next**.
    

    > [!NOTE]
    > <P>The model store that you select must be the same model store that is used by the client configuration that you selected.</P>



4.  On the **Select baseline model store** page, select a baseline model store to use for the impact analysis, and then click **Next**.
    

    > [!NOTE]
    > <P>You can also select a non-local baseline model store or create a new baseline model store.</P>
    > <P>The baseline model store that you select must be the same model store that is used by the client configuration that you selected.</P>
    > <P>The Impact Analysis Wizard deletes the existing contents of the baseline model store to perform the analysis.</P>



5.  The **Review the impact analysis configuration** page displays the selected configuration. Click **Start Analysis**.
    
    The **Analyzing impact** page is displayed until the analysis is completed.

6.  The **Results** page lists the objects that are affected and the number of cross-references. Click **Open the impact analysis results log file** to view the results.

7.  Close the wizard.

## Perform post-installation steps

The procedures in this section must be performed after the installation has been successfully completed.

## Reinitialize the model store

Many hotfixes require that you reinitialize the model store after installation. You should assume that all cumulative updates require reinitializing. The hotfix description indicates whether this step is required. You can use either Windows PowerShell or AXUtil to perform this step.

1.  On the **Start** menu, point to **All Programs**, point to **Administrative Tools**, and then click **Microsoft Dynamics AX Management Shell**.

2.  At the Windows PowerShell command prompt, PS C:\\\>, type the following command, and then press ENTER.
    
    ``` powershell
    Initialize-AXModelStore 
    ```
    
    This command reinitializes the default model store.
    
    For more information, see [Initialize-AXModelStore](initialize-axmodelstore.md).

## Restart AOS and Internet Information Services (IIS)

You must restart both AOS and IIS after the installation is completed.

1.  Restart the AOS service for the instance.
    

    > [!NOTE]
    > <P>If labels are not displayed correctly after you start the client, you may not have restarted the AOS instance.</P>
    > <P>If you did restart the AOS and you are still not seeing correct labels, you may need to remove the .ald (label) files from the folder C:\Program Files\Microsoft Dynamics AX\60\Server\&lt;instancename&gt;\bin\Application\Appl\Standard, and then restart the AOS.</P>



2.  If Enterprise Portal for Microsoft Dynamics AX is deployed in your environment, open a Command Prompt window on the Enterprise Portal server, type iisreset, and then press ENTER.
    

    > [!WARNING]
    > <P>If you do not restart IIS, you receive the following message, and Enterprise Portal is not deployed to other servers if you try to redeploy: “Could not load type ‘Microsoft.Dynamics.Framework.Portal.EPSoapSecurity’”</P>



## Complete the software update checklist

Before the changes to the model store that were included in the update can be fully implemented, you must complete additional tasks. The software update checklist helps you complete these tasks.


> [!NOTE]
> <P>The software update checklist is available by default in AX 2012 R3, and in AX 2012 R2 CU7. It is also available in application hotfixes and cumulative updates that have a version number of 6.0.947.339 or higher. When you start the client, if you do not see the <STRONG>Start the software update checklist</STRONG> option that is mentioned in the following procedure, install hotfix KB2616405.</P>
> <P>The <STRONG>Merge code automatically</STRONG> checklist item is available by default in Microsoft Dynamics AX 2012 R3. It was added to the checklist in cumulative update 7 for Microsoft Dynamics AX 2012 R2, in hotfix <STRONG>KB 2894100</STRONG> (Update checklist merge code feature).</P>



The **Merge code automatically** feature simplifies the process of installing hotfixes and fixing conflicts between hotfixes and the customizations in an environment. It compares the model elements in the customization layer with the corresponding elements in the hotfix and SYS layers. Where there are differences in the code between these elements, the feature attempts to resolve the differences in a way that preserves both the customization and hotfix functionality. This is not always possible, and some conflicts will require manual effort to resolve. All changes are made in the active customization layer.

When conflicts are resolved, all of the code from each layer involved in the merge appears in the customization layer with appropriate annotations. Code that the tool does not evaluate as applicable is commented, while code that is applicable and should be included in the result is left uncommented. This preserves the information used to make the merge decision so that it can be easily reviewed while still fixing compilation and functional issues in the code that resulted from hotfix installation. When conflicts cannot be resolved automatically, a TODO comment is added to the code and the code is annotated.

The typical process for using this feature is:

1.  After installing an update, open the client in the lowest layer with customizations that you want to merge hotfix changes into.

2.  Run the software update checklist.

3.  Compile the application.

4.  Click **Merge code automatically**.

5.  Specify the title for the project to be created when prompted, and then run the tool.
    
    After the comparison has completed, a form displays the results of the merge. For changes that were merged successfully, the changes should be reviewed to ensure that they are correct. For changes that remain in conflict, the user must manually investigate and merge conflicts.

6.  After resolving all conflicts, compile the application again and perform whatever functional testing is required to ensure that all conflicts have been merged.

7.  Repeat for each layer that contains customizations.

## Run the software update checklist

1.  Start the Microsoft Dynamics AX client.
    
    When you start the client, you receive the following message: “The model store has been modified.”

2.  Click **Start the software update checklist**.

3.  Complete the items on the checklist, in the order in which they are listed.
    
    <table>
    <colgroup>
    <col style="width: 50%" />
    <col style="width: 50%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Checklist section</p></th>
    <th><p>Option and description</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p><strong>Upgrade preparation</strong></p></td>
    <td><p><strong>Restart Application Object Server</strong></p>
    <p>We recommend that you restart the AOS instance before you start the client. However, if you did not restart the AOS instance, restart it now, and then mark this task complete.</p></td>
    </tr>
    <tr class="even">
    <td><p><strong>Code upgrade</strong></p></td>
    <td><p><strong>Compile application</strong></p>
    <p>This option compiles X++ code for the application. Compilation can require an hour or longer.</p></td>
    </tr>
    <tr class="odd">
    <td><p></p></td>
    <td><p><strong>Detect code upgrade conflicts</strong></p>
    <p>This option creates upgrade projects that contain conflicting model elements.</p></td>
    </tr>
    <tr class="even">
    <td><p></p></td>
    <td><p><strong>Merge code automatically</strong></p>
    <p>This control is not available in versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</p>
    <p>This option resolves conflicts with existing code automatically where possible, and creates a merge project that you can review.</p>
    <div class="alert">

    > [!NOTE]
    > <P>For CU7, This option will not function until you have compiled the application the first time after installing hotfix <STRONG>KB 2894100</STRONG>.</P>


    </div></td>
    </tr>
    <tr class="odd">
    <td><p></p></td>
    <td><p><strong>Compile into .NET CIL</strong></p>
    <p>After you have resolved any conflicts for the code upgrade, you can use this option to compile the application into common intermediate language (CIL) code for the Microsoft .NET Framework.</p></td>
    </tr>
    <tr class="even">
    <td><p></p></td>
    <td><p><strong>Restart all AOS instances automatically</strong></p>
    <p>We recommend that you restart all AOS instances to make sure that the code used to run batch processing is up to date.</p></td>
    </tr>
    <tr class="odd">
    <td><p><strong>Data upgrade</strong></p></td>
    <td><p><strong>Detect update scripts (Required)</strong></p>
    <p>This option finds and registers update scripts that require additional processing.</p>
    <p>The appearance of the checklist varies, depending on whether update scripts are detected.</p></td>
    </tr>
    <tr class="even">
    <td><p></p></td>
    <td><p><strong>Presynchronize</strong></p>
    <p>This option appears only if upgrade scripts were detected.</p></td>
    </tr>
    <tr class="odd">
    <td><p></p></td>
    <td><p><strong>Synchronize database</strong></p>
    <p>This option is required even if update scripts were not detected.</p></td>
    </tr>
    <tr class="even">
    <td><p></p></td>
    <td><p><strong>Launch data upgrade (required)</strong></p>
    <p>This option appears only if upgrade scripts were detected. This option opens the data upgrade checklist. For information about how to complete the data upgrade, see <a href="launch-data-upgrade.md">Launch data upgrade</a>.</p></td>
    </tr>
    <tr class="odd">
    <td><p></p></td>
    <td><p><strong>Upgrade additional features</strong></p>
    <p>This option appears only if upgrade scripts were detected. This option opens the <strong>Data upgrade cockpit</strong> form. For more information, see <a href="https://technet.microsoft.com/en-us/library/aa572565(v=ax.60)">Data upgrade cockpit (form)</a>.</p></td>
    </tr>
    </tbody>
    </table>


## Next steps

In your test environment, after you have installed updates on the database, AOS instance, and client, you should deploy required updates to the report server, Enterprise Portal, and retail components. For more information, see the following resources:

  - [Deploy updated reports to a report server](deploy-updated-reports-to-a-report-server.md)

  - [Deploy updates to Enterprise Portal](deploy-updates-to-enterprise-portal.md)

  - [Deploy updates in a retail environment](deploy-updates-in-a-retail-environment.md)

## Validate the update

After an update has been successfully installed, check the install log to make sure that there are no error messages and warnings that can affect the operation of the system. Test the system for the following conditions:

  - The change that was implemented by the update is working as you expected.

  - The change has not affected other areas of the system.

  - The Microsoft Dynamics AX application as a whole is working as you expected.

## Roll an update forward to the production environment

After the update has been tested, you must install the update in the production environment. You must install all binary and pre-processing hotfixes, but should roll the application changes forward to the production environment by importing and exporting the model store. Use the methodology that is described in [Deploying Customizations Across Microsoft Dynamics AX 2012 Environments (White paper)](deploying-customizations-across-microsoft-dynamics-ax-2012-environments-white-paper.md) and [How to: Export and Import a Model Store](how-to-export-and-import-a-model-store.md). By exporting and importing the model store, you can avoid having to compile code in the production environment.

## See also

[Technical diagram posters for Microsoft Dynamics AX 2012](technical-diagram-posters-for-microsoft-dynamics-ax-2012.md)

[Include cumulative updates and hotfixes in a new installation (slipstreaming)](include-cumulative-updates-and-hotfixes-in-a-new-installation-slipstreaming.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

