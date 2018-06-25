---
title: Enable validation parameters
TOCTitle: Enable validation parameters
ms:assetid: ef66623d-1e13-4e0a-bfb5-d4fba8bed126
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551560(v=AX.60)
ms:contentKeyID: 36059919
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- project
- worker
- validation parameters
---

# Enable validation parameters [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can enable validation for projects or workers.

## Project

1.  Click **Project management and accounting** \> **Common** \> **Projects** \> **All projects**.

2.  Select a project.

3.  On the **Action Pane**, on the **Project** tab, in the **Maintain** group, click **Edit**.

4.  On the **Setup** FastTab, select the **Enable category validation** check box.
    
    The validation setup in the **Project/category validation groups** form now applies to the current project. (Click **Project management and accounting** \> **Setup** \> **Validation** \> **Project/category validation groups**.)

## Worker

1.  Click **Human resources** \> **Common** \> **Workers** \> **Workers**.

2.  Select a worker.

3.  On the **Action Pane**, on the **Project management** tab, in the **Setup** group, click **Project setup**.

4.  In the **Project setup** form, select the **Category** check box, the **Project** check box, or both.
    
    If the check boxes are selected, the project parameters apply; if they are cleared, the project parameter settings are ignored.

The validation setup in the forms under the path **Project management and accounting** \> **Setup** \> **Validation** now applies to the current worker.

## Parameter combination overview

The following discussion illustrates the outcome of a combination of the validation parameters defined in the **Project parameters** form on the **Journals** tab.

On the **General** FastTab, you can specify the effect that the validation of a particular combination will have by the options that you select in the **Project/category** field, the **Worker/project** field, and the **Category/worker** field.

Select one of the following options:

  - **None** – All projects/categories, project/workers, or category/workers are shown.

  - **Lookup** – A filtered list of projects/categories, project/workers, and category/workers is shown. Valid options that are not in the list can be entered.

  - **Mandatory** – A specified list of projects/categories, project/workers, and category/workers is shown. Only options that appear in the list can be selected.

## See also

[About validation in projects](about-validation-in-projects.md)

[Projects (form)](https://technet.microsoft.com/en-us/library/aa585245\(v=ax.60\))

[Workers (form)](https://technet.microsoft.com/en-us/library/aa583961\(v=ax.60\))

[Project setup (form)](https://technet.microsoft.com/en-us/library/hh209540\(v=ax.60\))

[Project management and accounting parameters (form)](https://technet.microsoft.com/en-us/library/aa599440\(v=ax.60\))

[Configuring validation for projects](configuring-validation-for-projects.md)

[Define validation connections](define-validation-connections.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

