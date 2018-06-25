---
title: Maintain open product releases
TOCTitle: Maintain open product releases
ms:assetid: e00eea92-6d49-46b8-b58e-05c4eb1657f8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh545535(v=AX.60)
ms:contentKeyID: 37832540
ms.date: 05/02/2014
mtps_version: v=AX.60
f1_keywords:
- open product release
- products to release
- product to be released
---

# Maintain open product releases [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

An open product release is created when the release of a product cannot be completed. An incomplete release can, for example, occur if the product, the product master, or the product variants that are included in the release session already exist in the company that you attempt to release to.

## Maintaining open product releases

Open product releases can be tracked from the **Open product releases** form. From this form, you can filter on the time of the release failure and the user who initiated the release. You can also perform the following tasks:

  - Troubleshoot why a product failed to be released. For this purpose, you use separate Infologs for products and product masters and for variants.

  - Delete obsolete release sessions.

  - Resolve issues and repeat the release. For example, if the release failed because the product master of a product variant already exists in the target company, you can exclude the product master from the release to resolve the issue.

## Track open product releases

1.  Click **Product information management** \> **Periodic** \> **Open product releases**.

2.  Select a release session in the **Release session** field.

## Troubleshoot open product releases

1.  Click **Product information management** \> **Periodic** \> **Open product releases**.

2.  In the **Release session** field, select a release session.

3.  Select a product.

4.  Click the **View infolog** buttons for the product or product master and for the product variants.
    

    > [!TIP]
    > <P>If the <STRONG>Infolog</STRONG> field contains a <STRONG>Yes</STRONG>, there is a release issue that is related to the product. There are separate buttons of the type <STRONG>View infolog</STRONG> for products and product variants. The messages that are displayed for products and product variants depend on the problem that occurred during the release session.</P>



## Delete a release session

1.  Click **Product information management** \> **Periodic** \> **Open product releases**.

2.  In the **Release session** field, select a release session.

3.  Select a product, and then click **Delete**.
    

    > [!NOTE]
    > <P>When you delete a release session from the <STRONG>Open product releases</STRONG> form, only the release session is deleted. The products included in the release session remain available in the company where they are created and in companies that they have already been released to.</P>



## Exclude a product master from a release

1.  Click **Product information management** \> **Periodic** \> **Open product releases**.

2.  In the **Release session** field, select a release session.

3.  Select a product.

4.  Click **Product details**, and on the **Action Pane**, in the **Product authorization** group, click **Release products**.

5.  In the **Release products** form, clear the **Include product master** check box.

6.  Click the **Select companies** link, select a target company, and then click **OK**.

## See also

[Key tasks: Release products](key-tasks-release-products.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

