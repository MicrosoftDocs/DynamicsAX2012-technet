---
title: Set up a procurement catalog policy rule
TOCTitle: Set up a procurement catalog policy rule
ms:assetid: d00cc5a8-1aad-4e06-95e4-71f1be38b548
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242915(v=AX.60)
ms:contentKeyID: 36059483
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Set up a procurement catalog policy rule 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You must set up a catalog policy rule as part of your purchasing policy to control which catalog is displayed on the procurement site. The catalog policy rule is configured for the organizations that are selected on the **Purchasing policy** form. If a user has been granted permission to order products on behalf of another user, Microsoft Dynamics AX uses the catalog policy rule that is defined for the requester’s legal entity and operating unit to determine which catalog to display on the procurement site. Before you can define a catalog policy rule, you must create a procurement catalog and then publish it.

Use the following procedure to set up a catalog policy rule to apply to users who are associated with selected organizations within your company.

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**. On the **Purchasing policies** list page, either select and double-click an existing purchasing policy, or on the **Policy** tab, click **Policy** to create a new one.

2.  In the **Purchasing policy** form, on the **Policy rules** tab, select the **Catalog policy rule** from the **Policy rule type:** list, and then click **Create policy rule**.

3.  In the **Catalog policy rule** form, enter the date range that the policy should be valid. This date range controls when the catalog will be available on the procurement site.

4.  In the **Catalog** field, select the catalog that will be available on the procurement site for all users who are assigned to the organizations that are selected on the **Policy organizations** FastTab. Only procurement catalogs with a publishing status of **Active** appear in the list.

## See also

[Key tasks: Create purchasing policies](key-tasks-create-purchasing-policies.md)

[Catalog policy rule (form)](https://technet.microsoft.com/en-us/library/hh242247\(v=ax.60\))

[Key tasks: Create procurement catalogs](key-tasks-create-procurement-catalogs.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

