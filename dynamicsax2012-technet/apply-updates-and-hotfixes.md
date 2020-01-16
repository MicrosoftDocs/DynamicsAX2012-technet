---
title: Apply updates and hotfixes
TOCTitle: Apply updates and hotfixes
ms:assetid: 7ff68f32-bb5e-4572-a205-9fb759ebd0ba
ms:mtpsurl: https://technet.microsoft.com/library/Hh335183(v=AX.60)
ms:contentKeyID: 36687407
author: Khairunj
ms.date: 04/20/2016
mtps_version: v=AX.60
---

# Apply updates and hotfixes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes the types of updates that are available for Microsoft Dynamics AX 2012 and the deployment process for updates. Updates include hotfixes, cumulative updates, service packs, and feature packs.


> [!IMPORTANT]
> <P>We strongly recommend that you install all updates in a test or backup environment before you install them in production environments. Then validate the update against the implementation, customizations, data, and processes that are currently used in your organization.</P>



Because of the unique architecture of Microsoft Dynamics AX implementations, many issues can be encountered when you install a code fix. We recommend that you test all business scenarios and customizations to verify that the update is behaving as expected, that the update is not affecting other areas, and that the resulting data is correct.

This topic supplements the information that is included in specific updates.

## Deployment process for updates

Different updates can affect different components of Microsoft Dynamics AX. When you install an update, the update installer indicates which components of Microsoft Dynamics AX are affected by the update.

If an update affects multiple components, we recommend that you follow these steps to apply the update:

1.  Apply the database updates to a single database, apply the Application Object Server (AOS) updates to a single local AOS instance that is associated with the updated database, and apply the client updates to a single local client. Then get the environment running, and validate all business scenarios.
    

    > [!IMPORTANT]
    > <P>Because the model store in Microsoft Dynamics AX 2012 and the Microsoft Dynamics AX 2012 Feature Pack is part of the business database, when you update the database, you also import all code updates.</P>



2.  Apply the database updates to any additional databases by exporting and importing the model store. After your system has been compiled in the test environment, we recommend that you use the Windows PowerShell Import-AXModelStore cmdlets to deploy changes to the production environment. This approach requires the least downtime for your production system. For more information, see [Deploying Customizations Across Microsoft Dynamics AX 2012 Environments (White paper)](deploying-customizations-across-microsoft-dynamics-ax-2012-environments-white-paper.md).

3.  Apply the AOS updates to any additional AOS instances.
    

    > [!IMPORTANT]
    > <P>You cannot apply updates to remote AOS instances by using AXUpdate.exe. You must apply the updates locally.</P>



4.  Deploy changes to Microsoft SQL Server Reporting Services, and then to Enterprise Portal for Microsoft Dynamics AX.

5.  Deploy changes to any retail components.

6.  Mass deploy the updates to your clients. For more information, see [Run AXUpdate in silent mode](run-axupdate-in-silent-mode.md).


> [!IMPORTANT]
> <P>We strongly recommend that all computers in an environment be updated together.</P>



View or download a detailed poster of the update process.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Title</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Microsoft Dynamics AX 2012 Update Process</strong></p>
<img src="images/Hh335183.Updateprocessposter(AX.60).gif" title="Update process poster thumbnail" alt="Update process poster thumbnail" />
<p><a href="http://go.microsoft.com/fwlink/?linkid=306777">Zoom in to the diagram at full detail by using Zoom.it from Microsoft</a></p>
<p><a href="http://go.microsoft.com/fwlink/?linkid=306776">Downloadable PDF and Microsoft Visio versions</a></p></td>
<td><p>This poster describes the types of updates, the recommended installation order, and the detailed update process for Microsoft Dynamics AX 2012. It also provides tips and tricks for managing updates.</p></td>
</tr>
</tbody>
</table>


It is important that day-to-day operation of your business be disrupted as little as possible when you install hotfixes. We recommend that you become familiar with the Microsoft Service Management Functions [Operations Framework Guide](http://www.microsoft.com/technet/solutionaccelerators/cits/mo/smf/default.mspx). The Operations Framework guide contains information about how to define processes, establish best practices, and manage IT solutions.

## Evaluate the update, and determine which types of hotfixes it contains

Before you install an update, review the knowledge base (KB) article that is released together with it. The KB article helps you determine whether the update applies to your environment, and how the update might affect your environment.


> [!NOTE]
> <P>If you customized your environment before you received an update, thoroughly review the KB article that describes it. Investigate any objects that are affected by the hotfix to determine whether the changes that are implemented by the hotfix should be merged with customizations in a higher layer, such as BUS, VAR, USR, or CUS.</P>



To determine what type of hotfix an update contains, see the section [Apply updates and hotfixes](apply-updates-and-hotfixes.md)

To determine the build number of the Microsoft Dynamics AX version that you are running, see the section How can I determine which version and build number I’m running?


<p>Microsoft Dynamics AX 2012 R3 :</p>

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Version</p></th>
<th><p>Build</p></th>
<th><p>Availability</p></th>
<th><p>KB Number</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Recent kernel build</p></td>
<td><p>6.3.6000.8881</p></td>
<td><p>Recent</p></td>
<td><p>KB4511784</p></td>
</tr>
<tr class="even">
<td><p>February 2019 Update</p></td>
<td><p>6.3.6000.8149</p></td>
<td><p>20 Apr 2019</p></td>
<td><p>Feb 2019 Release</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative Update 13</p></td>
<td><p>6.3.6000.149</p></td>
<td><p>13 Sep 2017</p></td>
<td><p>KB4032175</p></td>
</tr>
<tr class="even">
<td><p>Cumulative Update 12</p></td>
<td><p>6.3.5000.138</p></td>
<td><p>21 Nov 2016</p></td>
<td><p>KB3199741</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative Update 11</p></td>
<td><p>6.3.4000.127</p></td>
<td><p>29 Jun 2016</p></td>
<td><p>KB3157865</p></td>
</tr>
<tr class="even">
<td><p>Cumulative Update 10</p></td>
<td><p>6.3.3000.110</p></td>
<td><p>24 Nov 2015</p></td>
<td><p>KB3102920</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative Update 9</p></td>
<td><p>	6.3.2000.326</p></td>
<td><p>08 Jun 2015</p></td>
<td><p>KB3063879</p></td>
</tr>
<tr class="even">
<td><p>Cumulative Update 8</p></td>
<td><p>6.3.1000.309</p></td>
<td><p>18 Nov 2014</p></td>
<td><p>KB2998197</p></td>
</tr>
<tr class="odd">
<td><p>RTM</p></td>
<td><p>6.3.164.0</p></td>
<td><p>Apr 2014</p></td>
<td><p>Customer / Partner source</p></td>
</tr>
</tbody>
</table>


<p>Microsoft Dynamics AX 2012 R2 (Mainstream Support ended):</p>

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Version</p></th>
<th><p>Build</p></th>
<th><p>Availability</p></th>
<th><p>KB Number</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Latest kernel build</p></td>
<td><p>6.2.3000.5768</p></td>
<td><p>17 Oct 2018</p></td>
<td><p>KB4465169</p></td>
</tr>
<tr class="even">
<td><p>Cumulative Update 9</p></td>
<td><p>6.2.3000.110</p></td>
<td><p>24 Sep 2015</p></td>
<td><p>KB3092626</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative Update 8</p></td>
<td><p>6.2.2000.14</p></td>
<td><p>06 Mar 2015</p></td>
<td><p>KB3042171</p></td>
</tr>
<tr class="even">
<td><p>Cumulative Update 7</p></td>
<td><p>6.2.1000.4051</p></td>
<td><p>01 Nov 2013</p></td>
<td><p>KB2885603</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative Update 6</p></td>
<td><p>6.2.1000.1437</p></td>
<td><p>26 Jun 2013</p></td>
<td><p>KB2850972</p></td>
</tr>
<tr class="even">
<td><p>Cumulative Update 1</p></td>
<td><p>6.2.1000.156</p></td>
<td><p>26 Feb 2013</p></td>
<td><p>KB2807685</p></td>
</tr>
<tr class="odd">
<td><p>RTM</p></td>
<td><p>6.2.158.0</p></td>
<td><p>01 Dec 2012</p></td>
<td><p>Customer / Partner source</p></td>
</tr>
</tbody>
</table>

<p>Microsoft Dynamics AX 2012 (Mainstream Support ended):</p>

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Version</p></th>
<th><p>Build</p></th>
<th><p>Availability</p></th>
<th><p>KB Number</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Latest kernel build</p></td>
<td><p>	6.0.1108.9267</p></td>
<td><p>30 Oct 2018</p></td>
<td><p>KB4466853</p></td>
</tr>
<tr class="even">
<td><p>Cumulative Update 7</p></td>
<td><p>6.0.1108.6482</p></td>
<td><p>16 Apr 2014</p></td>
<td><p>KB2936810</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative Update 5</p></td>
<td><p>6.0.1108.4316</p></td>
<td><p>29 Apr 2013</p></td>
<td><p>KB2828929</p></td>
</tr>
<tr class="even">
<td><p>Cumulative Update 4</p></td>
<td><p>6.0.1108.2423</p></td>
<td><p>02 Dec 2012</p></td>
<td><p>KB2765124</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative Update 3</p></td>
<td><p>6.0.1108.670</p></td>
<td><p>28 Jun 2012</p></td>
<td><p>KB2709934</p></td>
</tr>
<tr class="even">
<td><p>Cumulative Update 2</p></td>
<td><p>6.0.947.280</p></td>
<td><p>16 Nov 2011</p></td>
<td><p>KB2606916</p></td>
</tr>
<tr class="odd">
<td><p>Cumulative Update 1</p></td>
<td><p>6.0.947.61</p></td>
<td><p>01 Aug 2011</p></td>
<td><p>KB2579565</p></td>
</tr>
<tr class="even">
<td><p>Feature Pack 1</p></td>
<td><p>6.0.947.862</p></td>
<td><p>Solution build 6.1.1108.0</p></td>
<td><p>Customer / Partner</p></td>
</tr>
<tr class="odd">
<td><p>RTM</p></td>
<td><p>6.0.947.0</p></td>
<td><p>01 Aug 2011</p></td>
<td><p>Customer / Partner</p></td>
</tr>
</tbody>
</table>

## Prepare for the update

Before you begin, back up your business and model store databases, and make sure that you understand the time that is required for the update.

  - Back up the database that is being updated. By backing up the database, you can roll back to a known, reliable version if you have to. In this manner, you can reduce downtime if an unexpected error occurs. For more information, see [Back up and recover databases (SQL Server)](back-up-and-recover-databases-sql-server.md).

  - Schedule a time when the fewest system users, or no users, are affected. As a best practice, announce the time of the update in advance, to make sure that users are aware of the pending update and the expected downtime. By notifying all users of the time of the update, you can minimize data loss, data corruption, and loss of productivity.

  - Make sure that the system runs in single-user mode while the hotfix is installed, and that only the administrator is designated to perform the update. Because changes to the code can affect Application Object Server (AOS), the changes can affect users who are currently on the system.
    

    > [!WARNING]
    > <P>Changes to the application may require a compilation or synchronization of the application. These operations increase downtime.</P>



## Install an update

Make sure that business processes or operations can be restored to their original state if problems occur during or after installation.

To install an update, follow the instructions in the associated KB article, and in the following topics, as appropriate:

  - [Apply updates to database, AOS, and clients](apply-updates-to-database-aos-and-clients.md)

  - [Deploy updated reports to a report server](deploy-updated-reports-to-a-report-server.md)

  - [Deploy updates to Enterprise Portal](deploy-updates-to-enterprise-portal.md)

  - [Deploy updates in a retail environment](deploy-updates-in-a-retail-environment.md)

## Validate the update

After an update has been successfully installed, check the install log to make sure that there are no error messages and warnings that can affect the operation of the system. Test the system for the following conditions:

  - The change that was implemented by the update is working as expected.

  - The change has not affected other areas of the system.

  - The Microsoft Dynamics AX application as a whole is working as expected.

## Roll the update to the production environment

After the update has been tested, you must install the update in the production environment. You must install all binary and pre-processing hotfixes, but you can roll the code changes forward to the production environment by importing and exporting the model store. Use the methodology that is described in [Deploying Customizations Across Microsoft Dynamics AX 2012 Environments (White paper)](deploying-customizations-across-microsoft-dynamics-ax-2012-environments-white-paper.md) and [How to: Export and Import a Model Store](how-to-export-and-import-a-model-store.md). By exporting and importing the model store, you can avoid having to compile code in the production environment.

## What’s the difference between a hotfix, cumulative update, Service Pack, and Feature Pack?

This section describes what to expect from hotfixes, cumulative updates, service packs, and feature packs.

## Hotfixes

A hotfix is created to address a specific issue, problem, or customer scenario. A hotfix can address either a single issue or a cumulative set of issues. Hotfixes are distributed only to those customers, partners, and organizations that Microsoft technical support personnel determine can benefit from the changes that are made to the code. Each hotfix includes documentation that indicates what files, tables, code, or functions are changed by the hotfix.

Microsoft publishes a corresponding Knowledge Base (KB) article for every hotfix that is released for every Microsoft product. These products include Microsoft Dynamics AX. These KB articles describe the changes that the hotfix makes to objects, database tables, or files, or other code. Each hotfix is released to address a specific issue or scenario to restore the regular operation of the software. You must review the corresponding KB article to evaluate whether you have to apply the hotfix in your Microsoft Dynamics AX implementation.

## Cumulative updates

A cumulative update (CU) is an update that contains all previous hotfixes to date. Additionally, a CU contains fixes for issues that meet the criteria for hotfix acceptance. These criteria may include the availability of a workaround, the effect on the customer, the reproducibility of the problem, and the complexity of the code that must be changed.

When you plan a deployment that will use any of the industry solutions, we recommend that you install the industry solution before you install cumulative updates.


> [!IMPORTANT]
> <P>Any hotfixes that you previously applied are not included in a cumulative update are lost after you install the cumulative update. You must reapply those hotfixes after your installation.</P>



## Service packs

A service pack is a tested, cumulative set of all hotfixes and updates. Service packs may also contain additional fixes for problems that have been found internally since the release of the product, and a limited number of design changes or features that were requested by customers.

## Feature packs

A feature pack is a group of updates that relate to a feature area or group of functionality. Feature packs contain design changes or features that were requested by customers, and may also contain additional fixes for problems that have been found internally since the release of the product.

## How can I tell what type of hotfix I’m installing?

Microsoft Dynamics AX has the following standard types of hotfix:

  - Binary hotfixes – Objects and components that are installed by using standard Windows installer (MSI) files are patched with Windows Installer Patch (MSP) files and are applied by using AXUpdate.exe. These updates are cumulative: each binary hotfix contains changes from all previously released hotfixes.

  - Application hotfixes – Application hotfixes are those that are provided by using application model (.axmodel) files to any of the Microsoft application patch layers (SYP, GLP, FPP, SLP). Unlike binary hotfixes, application hotfixes target a specific fix.
    

    > [!IMPORTANT]
    > <UL>
    > <LI>
    > <P>Application hotfixes are usually not cumulative. However, an application hotfix may include one or more previous hotfixes if they apply to the same object or dependent objects.</P>
    > <LI>
    > <P>All application hotfix model files must be installed by using AXUpdate.exe; importing these application models manually is explicitly unsupported and may cause errors.</P></LI></UL>



  - Pre-processing hotfixes – Pre-processing hotfixes are applied to data upgrade scripts (for example, DatabaseUpgrade) that are run on Microsoft Dynamics AX 4.0 and Microsoft Dynamics AX 2009 systems before upgrading to Microsoft Dynamics AX 2012.

To determine which type of hotfix is in a KB, you must expand the update package and review the contents. A KB can contain one or more types of hotfixes.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Type of hotfix</p></th>
<th><p>Contents of update package</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Binary</p></td>
<td><p>AXUpdate.exe</p>
<p>AXImpactAnalysis.exe</p>
<p>LicenseTerms folder</p>
<p>Support folder</p>
<p>MSI folder</p></td>
</tr>
<tr class="even">
<td><p>Application</p></td>
<td><p>AXUpdate.exe</p>
<p>AXImpactAnalysis.exe</p>
<p>LicenseTerms folder</p>
<p>Support folder</p>
<p>Models folder</p></td>
</tr>
<tr class="odd">
<td><p>Pre-processing</p></td>
<td><p>LicenseTerms folder</p>
<p>DatabaseUpgrade folder</p></td>
</tr>
</tbody>
</table>


The following table describes the purpose of each file and folder.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>AXImpactAnalysis.exe</p></td>
<td><p>The version of the Update wizard that you can run to analyze the effect of the update on customizations in your environment.</p>
<p>Although AXImpactAnalysis.exe may be included in binary update packages, running it provides no additional information if you run it.</p></td>
</tr>
<tr class="even">
<td><p>AXUpdate.exe</p></td>
<td><p>The Update wizard that you can run to install MSP and model files that are required for the update.</p></td>
</tr>
<tr class="odd">
<td><p>DatabaseUpgrade</p></td>
<td><p>A folder that contains updated pre-processing files that are used to upgrade from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012.</p></td>
</tr>
<tr class="even">
<td><p>LicenseTerms</p></td>
<td><p>A folder that contains the license terms that you must agree to before you can install an update. This folder is used by AXUpdate.exe.</p></td>
</tr>
<tr class="odd">
<td><p>Models</p></td>
<td><p>A folder that contains the models that are being updated. This folder is used by AXUpdate.exe.</p></td>
</tr>
<tr class="even">
<td><p>MSI</p></td>
<td><p>A folder that contains subfolders for the components of Microsoft Dynamics AX that are being updated. Each subfolder contains one or more MSP files. This folder is used by AXUpdate.exe.</p></td>
</tr>
<tr class="odd">
<td><p>Support</p></td>
<td><p>A folder that contains support files and subfolders that are called by AXUpdate.exe. The files and subfolders include language-specific files for AXUpdate.exe. This folder is used by AXUpdate.exe.</p></td>
</tr>
</tbody>
</table>


## How can I tell if an application hotfix contains reports or web parts?

There is no easy way to tell whether an application hotfix contains reports or web parts. We recommend that you assume that all cumulative updates contain both, and redeploy the default reports, and deploy changed web parts to Enterprise Portal.

## How can I determine which version and build number I’m running?

The version of Microsoft Dynamics AX that you are running is shown in the **About Microsoft Dynamics AX** form. You can open this form from the ![Help icon](images/Hh335183.Helpicon(AX.60).png "Help icon") **Help** menu.

Depending on the version and solutions that you have installed, some or all of the following version types are listed:

  - Kernel version

  - Application version

  - Solution version

To determine the meaning of the version number that you are running, see the blog post [Overview of Microsoft Dynamics AX build numbers](http://blogs.msdn.com/b/axsupport/archive/2012/03/29/overview-of-ax-build-numbers.aspx).

## When should I use the Impact Analysis Wizard (AXImpactAnalysis)?

We recommend that you run the Impact Analysis Wizard in a test environment before you install any application update.

## What is the baseline model store?

The baseline model store is a database that has the same schema as the model store. It is used when updates are applied and during upgrades. During the update process, the Impact Analysis Wizard uses the baseline model store to store application updates before they are applied, so that the updates can be compared to existing code. During upgrades from Microsoft Dynamics AX 2009 or Microsoft Dynamics AX 4.0, the **Detect code upgrade conflicts** item on the Code upgrade checklist uses the baseline model store after you have imported existing .xpo files into it.

The content in the baseline model store is overwritten during the update process.

## What does the name of an update package mean?

The following naming convention is used for packages that service Microsoft Dynamics AX: *\<ProductName\>*-KB\<KBNumber\>*-*\<ServicePackLevel\>.exe.

For example, a package might be named DynamicsAX2012-KB123456- SP2.exe. The following table explains the name segments that are used in package names.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Name segment</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><em>&lt;ProductName&gt;</em></p></td>
<td><p>This segment indicates the name of the product that is being serviced. For packages that service Microsoft Dynamics AX 2012, this segment is DynamicsAX2012.</p></td>
</tr>
<tr class="even">
<td><p><em>&lt;KBNumber&gt;</em></p></td>
<td><p>This segment indicates the KB article that corresponds to the package, such as KB123456.</p></td>
</tr>
<tr class="odd">
<td><p><em>&lt;ServicePackLevel&gt;</em></p></td>
<td><p>This segment indicates the service pack level that the package services. This segment is used only for packages that must be applied to a product for which Service Pack 1 or a later version is installed. This segment is not used for packages that service the original release version of a product, for which no service packs are installed.</p></td>
</tr>
</tbody>
</table>


## See also

[Technical diagram posters for Microsoft Dynamics AX 2012](technical-diagram-posters-for-microsoft-dynamics-ax-2012.md)

  


