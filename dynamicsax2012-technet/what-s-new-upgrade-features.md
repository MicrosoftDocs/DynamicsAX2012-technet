---
title: "What's new: Upgrade features"
TOCTitle: Upgrade features
ms:assetid: 1c3d473b-5615-44fd-b8b5-afc69780e543
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh271439(v=AX.60)
ms:contentKeyID: 36384072
ms.date: 05/01/2014
mtps_version: v=AX.60
---

# What's new: Upgrade features 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic has been updated to address upgrade to Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012 R2, and Microsoft Dynamics AX 2012 R3.

The Microsoft Dynamics AX 2012 upgrade process is designed to keep downtime to a minimum. Shorter downtime means less impact on operations and lower total cost of upgrade.

## The source-to-target model for full upgrades

Upgrades from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009 to Microsoft Dynamics AX 2012 require two computer systems that operate in parallel:

  - The *source* system, which remains in production for most of the upgrade process

  - The *target* system with the latest Microsoft Dynamics AX version

In previous versions of Microsoft Dynamics AX, all upgrade tasks were performed on a single production system, requiring the system to be offline through the entire process. Difficulties that arose had to be resolved under time pressure before business operations could resume. Now, under the source-to-target model, issues involving the upgrade of business data are mostly resolved on the source system with no interruption of operations. Similarly, procedures for upgrading customized application code are carried out on the offline target system.

When data preprocessing on the source system is complete, and the target system is ready, the source system is taken offline, the prepared business data is copied to the target system, and upgrade scripts are run. After testing, the target system can go live.


> [!IMPORTANT]
> <P>Source-to-target upgrade requires that the source system and target system be installed on separate server computers. Although side-by-side installation on a single computer is possible, we recommend that you use this approach only for testing purposes. For more information, see <A href="hardware-and-software-requirements.md">Hardware and software requirements</A>.</P>



The following diagram shows the phases of an upgrade that follows the source-to-target model.

![Source-to-target upgrade model](images/Hh271439.Upgrade_Source-To-Target_Diagram(AX.60).gif "Source-to-target upgrade model")

## In-place upgrades

The upgrade framework for Microsoft Dynamics AX 2012 also provides a procedure for upgrading between versions within a major release. *In-place* upgrades do not follow the source-to-target model. Instead, all of the upgrade tasks are performed on the production system while it is offline.

The following diagram shows the phases of an in-place upgrade.

![In-place upgrade](images/Hh271439.Upgrade_In-Place_Diagram(AX.60).png "In-place upgrade")


> [!TIP]
> <P>For information about in-place upgrades between Microsoft Dynamics AX 2012, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012 R2, and Microsoft Dynamics AX 2012 R3, see <A href="scenario-perform-in-place-upgrade-to-ax-2012-r2-or-ax-2012-r3.md">Scenario: Perform in-place upgrade to AX 2012 R2 or AX 2012 R3</A> and <A href="scenario-perform-in-place-upgrade-to-ax-2012-feature-pack.md">Scenario: Perform in-place upgrade to AX 2012 Feature Pack</A>.</P>



## Checklists for each stage and type of upgrade

Previous releases of Microsoft Dynamics AX implemented upgrades on a single computer system, and a single upgrade checklist contained all the core upgrade tasks. Under the source-to-target upgrade model, there are now several checklists and related forms to help you organize upgrade tasks on the source and target systems. Additional checklists have been added for in-place upgrades that are performed between versions within a major releases.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Checklist</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Preprocessing upgrade checklist</strong></p></td>
<td><p>Tasks that prepare data on the source system for export into the database schema of a Microsoft Dynamics AX 2012 or later system</p></td>
</tr>
<tr class="even">
<td><p><strong>AOD code upgrade checklist</strong></p></td>
<td><p>Tasks that are involved in migrating any customized code in legacy AOD files to the model architecture of a Microsoft Dynamics AX 2012 or later system</p></td>
</tr>
<tr class="odd">
<td><p><strong>Model code upgrade checklist</strong></p></td>
<td><p>Tasks that are involved in migrating any customized code in legacy models to the most recent Microsoft Dynamics AX release</p></td>
</tr>
<tr class="even">
<td><p><strong>Data upgrade checklist</strong></p></td>
<td><p>Tasks that are involved in upgrading imported data on a Microsoft Dynamics AX 2012 or later target system</p></td>
</tr>
<tr class="odd">
<td><p><strong>Software update checklist</strong></p></td>
<td><p>Used for in-place upgrade from Microsoft Dynamics AX 2012 to Microsoft Dynamics AX 2012 Feature Pack. In Microsoft Dynamics AX 2012 R2 and Microsoft Dynamics AX 2012 R3, the upgrade framework replaces this checklist with the <strong>Code upgrade checklist for in-place upgrade</strong> and the <strong>Data upgrade checklist for in-place upgrade</strong>.</p>
<div class="alert">

> [!NOTE]
> <P>The <STRONG>Software update checklist</STRONG> is still used for hotfixes and updates.</P>


</div></td>
</tr>
<tr class="even">
<td><p><strong>Retail POS redeployment checklist</strong></p></td>
<td><p>Tasks that are involved in redeploying point-of-sale (POS) terminals after the head-office system has been upgraded to Microsoft Dynamics AX 2012 R2 and up-to-date POS software has been installed in the stores</p>
<div class="alert">

> [!WARNING]
> <P>This checklist is removed in Microsoft Dynamics AX 2012 R3.</P>


</div></td>
</tr>
<tr class="odd">
<td><p><strong>Code upgrade checklist for in-place upgrade</strong></p></td>
<td><p>Code upgrade tasks for in-place upgrades to Microsoft Dynamics AX 2012 R2 from Microsoft Dynamics AX 2012 or Microsoft Dynamics AX 2012 Feature Pack</p></td>
</tr>
<tr class="even">
<td><p><strong>Data upgrade checklist for in-place upgrade</strong></p></td>
<td><p>Data upgrade tasks for in-place upgrades to Microsoft Dynamics AX 2012 R3 or Microsoft Dynamics AX 2012 R2 from earlier versions of Microsoft Dynamics AX 2012</p></td>
</tr>
</tbody>
</table>


## The upgrade state transfer tool

In a source-to-target upgrade, the most labor-intensive phase is data preprocessing. If you follow best practices, you will perform your upgrade first on a non-production system. Therefore, you will spend considerable time completing data preprocessing on a test source system. The upgrade state transfer tool lets you take full advantage of the results of that effort by transferring the preprocessed data from the test system to your production system. For more information, see [Using the preprocessing upgrade state transfer tool](using-the-preprocessing-upgrade-state-transfer-tool.md).

## Validating row counts after an upgrade

The **Compare data upgrade row counts** task in the **Data upgrade checklist** checks the data integrity on the Microsoft Dynamics AX 2012 target system after an upgrade. Row counts that are correctly correlated among the source, shadow, and target tables suggest, but do not confirm, that the bulk copying and data upgrade were completed successfully. For more information, see [Compare data upgrade row counts](compare-data-upgrade-row-counts.md).

## Enhanced code upgrade toolset

This feature is provided by Microsoft Dynamics AX 2012 R3 and Microsoft Dynamics AX 2012 R2 only.

The code upgrade toolset for detecting and resolving conflicts between standard and customized code now provides code analysis based on code conflict rules. The rules describe code conflicts involving changes in X++ classes and methods, and provide suggested resolutions. You can add your own rules to the ones provided by Microsoft. You have the option of allowing rule violations to be resolved automatically, or you can open a development project that is created and resolve the conflicts manually. For more information, see [Using the preprocessing upgrade state transfer tool](using-the-preprocessing-upgrade-state-transfer-tool.md).

Microsoft Dynamics AX 2012 R3 introduces two additional enhancements related to code upgrade.

  - In the code upgrade tool, you can now elect to allow multiple versions of some methods to be merged automatically during upgrade. For information, see [Detect code upgrade conflicts (form)](https://technet.microsoft.com/en-us/library/hh272148\(v=ax.60\)).

  - The command-line tool AxBuild provides speedier code compilation than the standard AOT compilation utility. For information, see [Compile application](compile-application.md).

## Support for data partitioning

This feature is provided by Microsoft Dynamics AX 2012 R3 and Microsoft Dynamics AX 2012 R2 only.

As of Microsoft Dynamics AX 2012 R2, data isolation or tenancy is enabled by means of data partitions. For example, an organization that is a holding company has several subsidiaries. If the management of the organization does not want employees of one subsidiary to have access to the data for other subsidiaries, data partitions can provide the boundaries that are required for data isolation but enable the metadata that supports business processes to be shared.

When upgrading from Microsoft Dynamics AX 4.0 or Microsoft Dynamics AX 2009, it is important that you first evaluate whether you require data isolation between companies. For example, the source system may have used companies as a means of data isolation. However, there is much data that is shared between companies in Microsoft Dynamics AX 2012 R3 and Microsoft Dynamics AX 2012 R2. For example, products and parties are global for all companies in a partition. If you do not want such data to be shared, you must create additional partitions. In any case, metadata such as role definitions will be shared across all partitions.

During the upgrade process, you will be given the option to create new partitions. If you choose to create new partitions, you will then map companies from the source environment to partitions in the target environment. If you do not have to isolate data between companies, you do not have to create additional partitions. The default partition that is created during installation is sufficient for your requirements.

For more information, see the product documentation.

## Split of database into data and metadata

This feature is provided by Microsoft Dynamics AX 2012 R3 and Microsoft Dynamics AX 2012 R2 only.

During minor-version upgrade to Microsoft Dynamics AX 2012 R3 or Microsoft Dynamics AX 2012 R2 from AX 2012 or AX 2012 Feature Pack, the single Microsoft Dynamics AX database will be split into two databases, one for business data and one for application metadata. This change enables easier maintenance and backup of the databases.

## Enhanced international support

This feature is provided by Microsoft Dynamics AX 2012 R3 and Microsoft Dynamics AX 2012 R2 only.

Upgrade is supported for internationalized versions of Microsoft Dynamics AX including versions for the following countries or regions:

  - Brazil

  - China

  - Eastern Europe/Russia

  - India

  - Japan

## Multi-version support for retail POS redeployment

This feature is provided by Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 R2 only.

Upgrade of retail functionality requires redeployment (replacement and reconfiguration) of the legacy POS software on each terminal in each store. You must perform this redeployment during a tightly constrained time window to avoid disrupting retail activities. Although previous releases required that all stores be upgraded at the same time, Microsoft Dynamics AX 2012 and Microsoft Dynamics AX 2012 R2 support operations using two versions of Microsoft Dynamics AX POS register software at the same time. Multi-version support lets upgrade administrators upgrade one store at a time while maintaining normal operations in stores that are still awaiting upgrade.

  


