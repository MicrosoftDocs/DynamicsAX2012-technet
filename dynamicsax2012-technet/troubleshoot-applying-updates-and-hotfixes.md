---
title: Troubleshoot applying updates and hotfixes
TOCTitle: Troubleshoot applying updates and hotfixes
ms:assetid: 8ec5b487-267a-46ff-bfb7-8efc6ec61dee
ms:mtpsurl: https://technet.microsoft.com/library/JJ161010(v=AX.60)
ms:contentKeyID: 47903500
author: Khairunj
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Troubleshoot applying updates and hotfixes 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes common issues that you may encounter when applying updates, and how to work around them. It also describes how to roll back an update.

Issues are listed by the error message or symptom that you may encounter.

## You experience X++ compilation errors or CIL generation errors after you apply a hotfix

If you are experiencing X++ compilation errors or Common Intermediate Language (CIL) generation errors after you apply a hotfix, you most likely have a code conflict between layers.

## Resolution

Review the code in a test system, and work with an X++ developer to check whether code in one layer conflicts with a change in another layer. Check whether your customizations conflict with the hotfixes in the SYP or FPP layer. For more information, see [How to: Resolve Conflicts After Importing a Model](how-to-resolve-conflicts-after-importing-a-model.md).


> [!IMPORTANT]
> <P>Support does not address code conflicts, because we are not familiar with the intent of your customizations and do not know how the conflicts should be handled.</P>



## AXUpdate.exe cannot detect a model store database or a database instance cannot be updated

AXUpdate.exe is unable to detect a model store in which to install a hotfix. Additionally, if you manually supply a model store location to AXUpdate.exe, an error is displayed that indicates that the hotfix is not applicable because the database instance cannot be updated.


> [!NOTE]
> <P>Many times, when you encounter this error, the hotfix you are working with may already have been installed.</P>
> <P>You may need to query the manifests of the Microsoft models to determine whether a particular hotfix, and a specific build of the hotfix have been installed. For more information about model manifests, see <A href="how-to-view-or-change-the-manifest-properties-of-a-model.md">How to: View or Change the Manifest Properties of a Model</A>.</P>



## Additional information

This issue can occur when you install hotfixes with build version numbers between 6.0.947.339 – 6.0.1108.1199 to a model store database that has a higher build-versioned hotfix already installed.

Hotfixes versioned 6.0.1108.1200 or higher do not exhibit this issue, however, these hotfixes can continue to impact the installation of lower-versioned hotfixes.

## Resolution

You can resolve this issue by using the new version of AxSetupSP.exe that is shipped in [Hotfix KB 2665135](https://mbs.microsoft.com/knowledgebase/kbdisplay.aspx?wtntzsmnwukntmmytpnryvznnpwyswvqrrxvwprvzmrknonr) on CustomerSource.

To resolve this issue:

1.  Extract Hotfix KB 2665135.

2.  Replace the AxSetupSP.exe located in the Support subdirectory with the version released in Hotfix KB 2665135.

## Some previous updates are no longer installed after I install a new update

Sometimes hotfixes replace or encompass the code from previous hotfixes. When this occurs, the replaced hotfixes are removed during installation.

Installing a cumulative update can remove hotfixes that were not contained in the update.

## Resolution

There is no need forcibly reinstall a hotfix that has been removed because it was encompassed by a later hotfix.

If a cumulative update has removed a hotfix that was not contained in it, you must reinstall the hotfix.

## During X++ compilation, you receive an "empty SQL descriptor" error

This error message occurs when you have turned off configuration keys that were used earlier.

## Resolution

This error message should not prevent you from installing updates. You can continue with the checklist, provided that there are no other X++ compilation errors to resolve.

## In the Software Update checklist, you see "The project already exists"

A previous update project is present on your system.

## I want to uninstall an update

To uninstall a binary or kernel hotfix, use **Control Panel** \> **Programs and Features** \> **View Installed Updates**. Locate the KB number that you want to remove, right-click the file, and then select **Uninstall**. The kernel version build reverts to the version that was previously installed.

To reverse an application hotfix, you must restore a database backup that you created before you installed the hotfix.

## Application hotfixes encompass classes other than the class that is directly affected

It may seem that a hotfix includes more classes than are required. Additional classes are often included in a hotfix because of dependencies that are created by the hotfix process.

When a hotfix is created, the servicing process creates a dependency between the objects in the hotfix. For example, if a hotfix modifies two classes, a dependency is created between the classes. Therefore, whenever one class is included in a hotfix, the other class is also included as a dependency. This behavior is required to ensure the integrity of the hotfix. Because a hotfix contains the whole fix together with all encompassed software updates, we do not regress on functionality that was previously shipped.

For a more detailed explanation, see the post [Understanding Application Dependencies in Dynamics AX 2009 Hotfixes](https://blogs.technet.com/b/dynamicsaxse/archive/2011/05/11/understanding-dependencies-in-dynamics-ax-2009-hotfixes.aspx) on the Microsoft Dynamics AX Sustained Engineering blog.

## Roll back an update

If errors or issues occur during or after installation of an update, the update must be uninstalled, and the system must be rolled back. Follow these steps to restore your system to the last known, reliable version:

1.  If an update installed any binary files, uninstall the update by using the **Add or Remove Programs** item in Control Panel.

2.  Restore the database backups.

3.  Synchronize the application with the database, if synchronization is required, to return the implementation to pre-update conditions.

4.  **Optional:** If you require help troubleshooting the installation errors or issues, open a support request by contacting your partner or value added reseller (VAR). Alternatively, if you are enrolled in a support plan directly with Microsoft, you can log on to CustomerSource and submit a new support request.

  


