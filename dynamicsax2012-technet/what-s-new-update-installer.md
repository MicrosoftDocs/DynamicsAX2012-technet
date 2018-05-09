---
title: "What's new: Update installer"
TOCTitle: Update installer
ms:assetid: 3226a0b2-7273-4a98-8ca3-faf9865385ee
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Dn529284(v=AX.60)
ms:contentKeyID: 59644560
ms.date: 04/28/2015
mtps_version: v=AX.60
---

# What's new: Update installer 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

This topic describes the new features of the update installer in Microsoft Dynamics AX.

## New features in Microsoft Dynamics AX 2012 R3

For AX 2012 R3, the update installer that is used for cumulative updates or a group of the most recent updates is now available in Microsoft Dynamics Lifecycle Services (LCS). To install a group of updates on an existing system, follow these steps:

1.  Sign in to LCS, click a project, and then click an environment.

2.  Under **Recommended updates**, click the tile for the type of update to install.

3.  You can search the list of updates, and also filter it by criteria such as module, license code, and country/region.

4.  Click an update to view details of the update and an impact analysis.

5.  Click **Add hotfix to package** to add the selected update and any dependent updates to the download package.
    
    You can also select multiple updates in the left pane, and then click **Add** to add all of them to the download package at the same time.

6.  Click **Download package** to review the updates that you selected and a cumulative impact analysis.

7.  Download your custom update package, and install the updates on the appropriate computers in the environment.

Groups of updates that can be used for slipstream installations can also be downloaded from Lifecycle Services.


> [!IMPORTANT]
> <P>Updates intended for slipstreaming cannot be installed by using the update installer, nor can updates intended for use with the update installer be slipstreamed.</P>



## New features in cumulative update 7 for Microsoft Dynamics AX 2012 R2

We have revised the interface of the update installer (AXUpdate.exe) and Impact Analysis Wizard (AXImpactAnalysis.exe) for cumulative update 7 for Microsoft Dynamics AX 2012 R2. We have also modified the software update checklist. The following features have been added.

  - Database (application) updates can be installed either through express or advanced mode. In express mode, all appropriate hotfixes are installed.
    
    Advanced mode offers many new features, including:
    
      - Filtering available hotfixes based on module, country/region or configuration key, or business processes imported from [Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306503) (if your organization has a project with business processes configured in Lifecycle Services).
    
      - The ability to export a list of updates to a file, so that you can later use the file to speed up applying application updates to another computer.

  - The Impact analysis wizard now enables you to select specific layers to analyze. To have access to this functionality, you must install application hotfix KB 2885584 from the cumulative update, and compile the application before running the Impact analysis wizard.

  - In the software update checklist, the **Merge code automatically** checklist item was added. This feature simplifies the process of installing hotfixes and fixing conflicts between hotfixes and the customizations in an environment. It compares the model elements in the customization layer with the corresponding elements in the hotfix and SYS layers. Where there are differences in the code between these elements, the feature attempts to resolve the differences in a way that preserves both the customization and hotfix functionality. This is not always possible, and some conflicts will require manual effort to resolve. All changes are made in the active customization layer.
    
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

  - The Data Import/Export Framework can now be installed by using the update installer.

## New features in cumulative update 6 for Microsoft Dynamics AX 2012 R2

The following features have been added to the installation wizard for cumulative update 6 for Microsoft Dynamics AX 2012 R2.

Database (application) updates can be installed either through express or advanced mode. In express mode, all appropriate hotfixes are installed.

Advanced mode supports the following features

  - Ability to select applicable application updates only.

  - Support for filtering hotfixes to install by module, country/region or configuration key.

  - Conflict summary for each hotfix displays the number of potential conflicts for a hotfix.

  - Conflict details provide further information about potential conflicts.

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

