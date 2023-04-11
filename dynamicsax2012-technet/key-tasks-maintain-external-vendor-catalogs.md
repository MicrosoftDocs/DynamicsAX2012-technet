---
title: 'Key tasks: Maintain external vendor catalogs'
TOCTitle: 'Key tasks: Maintain external vendor catalogs'
ms:assetid: b1bce455-9743-41b6-a53f-f04abbdc50cb
ms:mtpsurl: https://technet.microsoft.com/library/Hh242747(v=AX.60)
ms:contentKeyID: 36059054
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- vendors
- vendor catalog
- external vendor
- external vendors
- vender catalogs
audience: Application User
ms.search.region: Global
---

# Key tasks: Maintain external vendor catalogs 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you configure access to a vendor’s external catalog site, you can maintain the catalog by doing the following:

  - Verify that the external vendor catalog configurations are correct and test that the vendor catalog site opens correctly. You can test the configurations on the vendor’s external staging site, their production site, or both.

  - Activate the external vendor catalog configurations and add the external vendor catalog to your procurement catalog so that it can be made available on your procurement site. After the external vendor catalog is added to the procurement site, employees can view and access the vendor’s catalog site when they search for items and services.
    
    Inactivate the external vendor catalog to prevent users from accessing the vendor’s catalog website.

  - Update the configuration settings for the external vendor catalog whenever the vendor changes the configuration data. Configuration data can include information such as the destination URL or key values that are required for the user to access the vendor’s catalog website.

## What do you want to do?

Learn more about...

Validate external catalog configurations

Activate or inactivate an external catalog

Modify configuration data for an external catalog

Delete an external catalog

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[External vendor catalogs overview](external-vendor-catalogs-overview.md)

## Validate external catalog configurations

Before you activate an external catalog so that users can access it, you can test the catalog configurations to verify that they are correct.

### Validate the external catalog production site settings

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **External catalogs**.

2.  On the **External catalogs** list page, double-click the external catalog that you want to test.

3.  In the **Maintain details for an external catalog** form, on the **Remote production site settings** FastTab, click **Validate settings**.

If your production settings are correct, the external vendor’s catalog site opens.


> [!NOTE]
> <P>When you view the external vendor's catalog site during validation, you cannot order items and services from the vendor. To order items and services, you must access the vendor's catalog site through Enterprise Portal for Microsoft Dynamics AX.</P>



### Optional: Validate the external catalog staging site settings

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **External catalogs**.

2.  On the **External catalogs** list page, double-click the external catalog that you want to test.

3.  In the **Maintain details for an external catalog** form, on the **Remote staging site settings** FastTab, click **Validate settings**.

If your staging settings are correct, the external vendor’s catalog site opens on the staging site.

Back to top

## Activate or inactivate an external catalog

To add an external vendor’s catalog to the procurement catalog and to give employees access to the external vendor’s catalog site, you activate the external catalog. To remove access to the external vendor’s catalog site, you inactivate the external catalog.

### Activate an external catalog

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **External catalogs**.

2.  On the **External catalogs** list page, select the external catalog that you want to activate.

3.  On the **Action Pane**, on the **External catalog** tab, click **Activate catalog**.

4.  In the **Confirmation** message, click **OK**.

### Inactivate an external catalog

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **External catalogs**.

2.  On the **External catalogs** list page, select the external catalog that you want to inactivate.

3.  On the **Action Pane**, on the **External catalog** tab, click **Inactivate catalog**.

4.  In the **Confirmation** message, click **OK**.

Back to top

## Modify configuration data for an external catalog

Use this procedure to modify the configuration data for an external catalog when a vendor updates access configurations for their external vendor catalog site.

1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **External catalogs**.

2.  On the **External catalogs** list page, double-click the external catalog that you want to modify.

3.  In the **Maintain details for an external catalog** form, on the **Remote production site settings** FastTab, enter the updated configuration data. If the vendor uses a remote staging site setting, enter the updated configuration data on the **Remote staging site settings** FastTab also.

4.  On the **Remote production site settings** FastTab, click **Validate settings** to validate the updated configuration settings on the external vendor’s catalog production site.

5.  Optional: On the **Remote staging site settings** FastTab, click **Validate settings** to validate the updated configuration settings on the external vendor’s catalog staging site.

Back to top

## Delete an external catalog

Use this procedure to delete an external catalog from Microsoft Dynamics AX.


> [!NOTE]
> <P>If a product from the external vendor catalog has been requested, the external vendor catalog cannot be deleted. Instead, the external vendor catalog is set to a status of inactive. If you want to remove access to the external vendor’s catalog site, but not delete it, change the external catalog status to <STRONG>Inactive</STRONG>.</P>



1.  Click **Procurement and sourcing** \> **Common** \> **Catalogs** \> **External catalogs**.

2.  On the **External catalogs** list page, select the external catalog that you want to delete.

3.  On the **Action Pane**, on the **External catalog** tab, click **Delete**.

4.  In the **Confirmation** message, click **OK**.

Back to top

## Find form help

[External catalogs (list page)](https://technet.microsoft.com/library/hh208570\(v=ax.60\))

[Maintain details for an external catalog (form)](https://technet.microsoft.com/library/hh242254\(v=ax.60\))

## Find related tasks

[Set up an external vendor catalog](set-up-an-external-vendor-catalog.md)

  


