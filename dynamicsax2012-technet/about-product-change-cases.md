---
title: About product change cases
TOCTitle: About product change cases
ms:assetid: d49636d7-048f-461d-93db-1399bc298b5e
ms:mtpsurl: https://technet.microsoft.com/library/Dn505750(v=AX.60)
ms:contentKeyID: 59604024
ms.date: 05/07/2014
mtps_version: v=AX.60
f1_keywords:
- version
- formula
- BOM
- Forms.CaseListPage
- bills of materials
- Forms.CaseDetail
- route
- case management
- product change
- product change case
audience: Application User
ms.search.region: Global
---

# About product change cases 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_


> [!NOTE]
> <P>This topic does not apply to versions of Microsoft Dynamics AX 2012 prior to cumulative update 7 for AX 2012 R2.</P>



This topic describes the Case management features that are specific to product change cases. Product change cases enhance the Case management functionality in Microsoft Dynamics AX to help manufacturing companies document changes to products. Product changes can include component substitutions in the bill of materials (BOMs) or formulas, or changes in the production route. Approvals and validations are available for product change cases, so that you can manage the release of changed BOMs, formulas, and routes to planning and production processes. For more information about the Case management features, see [Case management](case-management.md).

## Are there prerequisites for creating a product change case?

Yes, when you create a product change case, you must assign it to the **Product change** case category type.

In addition to the standard case category features, when you create a case category and assign it to the product change category type, the **Validation rules** FastTab is available. You can enable validation rules to make sure that the information in the product change case is complete and consistent before the case can be closed. For each validation rule, you can specify whether a violation will cause an error message or a warning. An error message must be addressed before a user can close the case. A warning message will not prevent a user from closing the case.

For more information about case categories, see [Case categories (form)](https://technet.microsoft.com/library/hh209319\(v=ax.60\)).

## What can I associate with a product change case?

You can assign all of the entities that case management is designed for. However, product change cases are intended for use with the following entities:

  - Products and released products

  - Formulas

  - Routes


> [!NOTE]
> <P>When you associate a released product with a product change case, the parent product is also associated. Associating a product with a product change case provides visibility into where the item is used in other legal entities. It also makes it easy to navigate from the <STRONG>Case</STRONG> form to the associations.</P>



## Can I enter or attach text or documents to a product change case?

You can enter information in the case log. The case log is available in the following locations:

  - In all forms for the entities that can be associated with a product change case.

  - When you associate an entity with a product change case.

  - In the **Case** form, on the **Case log** FastTab, if you click **Add** to add a new note, **Remove** to delete a selected entry, or **Details** to open the form for the entity.

## I’ve associated an entity by mistake. Can I remove the entity from the case?

Yes, you can delete the associations from the case on the **Associations** FastTab in the **Case** form. However, you cannot delete the entries in the case log.


> [!NOTE]
> <P>If the status of the product change case is <STRONG>Closed</STRONG> or <STRONG>Canceled</STRONG>, you cannot change the case association.</P>



## Can I approve product changes before they are released to production?

Yes, in the **Approve and activate changes** form, you can approve and activate BOMs, routes, BOM versions, and route versions. BOMs and routes are displayed in the upper part of the form. When you select a BOM or route, the versions are displayed in the lower part of the form. You can only approve and activate changes when the status of the product change case is **In process**.

If you have enabled one or more validation rules for the case category, you can validate the product change case before you approve and activate the changes. To run the validation, click the **Validate** button.

Use the **Set action** button to select a new status for an entity. The button is available in the upper and lower part of the form. In the upper part of the form, you can approve a BOM, formula, or route, or clear the current selections if they have not been applied. In the lower part of the form, the following actions are available for the BOM, formula, and route versions:

  - **Approve** – Approve the changes, but do not make them active.

  - **Activate** – Make approved changes active on the specified date.

  - **Approve and activate** – Approve and activate the changes in one step.

  - **Expire** – Make an entity unavailable for use on the specified date.

  - **Clear** – Delete all selections that have not been applied.

You can also use the **Suggest actions** button to automatically recommend the next action on the entities. After you have set the action, use the **Apply actions** button to apply the action.


> [!NOTE]
> <P>The change will take effect on the date that is specified in the <STRONG>Planned effective date</STRONG> field. However, you can override the date for a component by changing it on the line.</P>



## Can I approve and activate changes when electronic signatures are required?

No, product change cases do not support approval and activation when electronic signatures are required. When you associate an entity that requires an electronic signature for approval, such as a BOM, the **Approve and activate** button is not available for the product change case. You must approve and activate the change in the form for the entity.

## Can I view a list of all cases that are related to a product, BOM, formula, or route?

Yes, in the form for the entity, you can display all cases that the entity is associated with by selecting the product or entity, and then clicking **All cases**.

## Can I analyze where an entity is used?

Yes, you can run the **Where-used analysis** feature to view the related BOMs, routes, and finished products that use the BOM or route. These are the entities that can be affected by the product change. The entities that are already associated with the case have a green check mark. The entities that are not already associated with the case, but can be, have a blue plus sign.

Before you run the **Where-used analysis** feature, specify what to include in the analysis. For example, you may want to include a specific number of BOM levels, or only include the routes that have been approved.

By default, the date in the **Planned effective date** field shows the date that is specified in the case. If you change the date on the **Where-used analysis** form, the date is also changed for the case. Additionally, the date acts as a filter for the entities in the analysis results. The analysis displays only BOMs, BOM versions, and route versions that are active on the date.

After you run the analysis, you can associate all of the entities in the analysis results with the case by clicking the **Associate all with the case** button. You can only associate all entities in the analysis, you cannot associate single entities.


> [!NOTE]
> <P>A message is displayed if one or more entities are already associated with the product change case. The message is for information only, and the entity’s association is not duplicated.</P>



## I have formula versions that depend on catch weight. How can I make sure to approve the correct formula version?

In the **BOM versions and route versions** part of the **Approve and activate changes** form, use the **Formula display** button to display information about the formula version in the grid. By default, the formula information is not displayed.

## Can I associate co-products and bi-products with the case? Will that affect approval and activation?

You can associate co-products and bi-products with the case. In the **Approve and activate changes** form, click the **Co-products** button to display related co-products and bi-products.

## Can I release a product to legal entities from a product change case?

No, you must use the standard process to release products to legal entities from the **Products** or **Product details** forms. For more information, see [Key tasks: Release products](key-tasks-release-products.md).

## Why can’t I see all BOM versions, formula versions, and route versions when I approve and activate changes?

This information is displayed only for BOM versions, formula versions, and route versions that are related to the case. Versions that are not related to a product that is associated with the case are not displayed.

## Is approval and activation different if I do it from the case or from the forms for the entities?

No, approval and activation is the same. However, it is easier to make sure that all changes are made if you approve and activate product changes from the case instead of the entity.

## Don't see your question here?

We're working to include as many questions as we can, so that Microsoft Dynamics AX Help will be more useful to people just like you.

Tell us what question you would like to add to this topic. Send email to <adocs@microsoft.com>.

## See also

[Create a product change case](create-a-product-change-case.md)

  


