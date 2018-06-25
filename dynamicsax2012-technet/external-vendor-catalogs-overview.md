---
title: External vendor catalogs overview
TOCTitle: External vendor catalogs overview
ms:assetid: 4fb0db50-89cf-4a8d-bd43-5bef11b6683c
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208904(v=AX.60)
ms:contentKeyID: 36057228
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# External vendor catalogs overview [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

If you rely on your vendors to host procurement catalog data for you, you can configure access to the vendor’s external catalog site in Microsoft Dynamics AX so that users can access the vendor’s external catalog directly. You receive the remote access settings from your vendor, and then set up the required configurations in Microsoft Dynamics AX using the **Maintain details for an external catalog** form.

## Set up an externally hosted catalog

To set up an external vendor catalog, complete the following tasks:

1.  Set up a procurement category hierarchy. For more information about how to set up a procurement category hierarchy, see [Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md).

2.  Register the vendor in Microsoft Dynamics AX. Before you can set up configurations to access an external vendor’s catalog, you must first set up the vendor and the vendor contact in Microsoft Dynamics AX. The external catalog’s vendor must also be added to the selected procurement category. For more information about registering vendors in Microsoft Dynamics AX, see [Manage vendor requests overview](manage-vendor-requests-overview.md). For information about how to assign vendor’s to a procurement category, see [Key tasks: Set up and maintain procurement category hierarchies](key-tasks-set-up-and-maintain-procurement-category-hierarchies.md)

3.  Configure the external vendor catalog using the requirements for your vendor’s external catalog site.

4.  Test the vendor’s external catalog configurations in the staging and production environments to verify that the settings are valid and that you can access the vendor’s external catalog.
    

    > [!NOTE]
    > <P>If the vendor does not provide a staging environment, you can only verify the vendor’s external catalog configuration in the vendor’s production environment.</P>



5.  Activate the external catalog.

6.  Add the external vendor catalog link to the procurement catalog. For more information about how to add the external vendor catalog to a procurement catalog, see [Key tasks: Create procurement catalogs](key-tasks-create-procurement-catalogs.md).

## See also

[Set up an external vendor catalog](set-up-an-external-vendor-catalog.md)

[Key tasks: Maintain external vendor catalogs](key-tasks-maintain-external-vendor-catalogs.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

