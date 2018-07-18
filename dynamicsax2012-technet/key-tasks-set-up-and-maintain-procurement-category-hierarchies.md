---
title: 'Key tasks: Set up and maintain procurement category hierarchies'
TOCTitle: 'Key tasks: Set up and maintain procurement category hierarchies'
ms:assetid: 590d8f83-2345-473d-bc3b-92eeacdee69e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208974(v=AX.60)
ms:contentKeyID: 36057346
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- vendor
- public sector
- France
- French
- category hierarchy
- procurement category
- approved vendor
- category attribute
- category page
- commodity code
- preferred vendor
- product attribute
- questionnaire
- procurement categories
- category hierarchies
audience: Application User
ms.search.region: Global
---

# Key tasks: Set up and maintain procurement category hierarchies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use a procurement category hierarchy to classify products that your organization purchases for its own use. You can set policies for ordering from categories in the hierarchy, create attributes for categories, and assign vendors as preferred suppliers in a procurement category. Only one active procurement category hierarchy can be defined for an organization.

There are several standard industry classification systems for reporting procurement activities to government agencies or industry organizations. Some of the more common examples are UNSPSC, NAICS, eCl@ss, and NIGP. Your system administrator can import all or part of an external classification system into Microsoft Dynamics AX. You can also manually create categories. For more information about how to import commodity codes into a category hierarchy, see [Import categories (form)](https://technet.microsoft.com/en-us/library/hh242810\(v=ax.60\)).

## What do you want to do?

Learn more about...

Create a procurement category hierarchy

Add product attributes to a procurement category

Add products to a procurement category

Maintain and evaluate vendors in a procurement category

Set up questionnaires for a procurement category

Maintain category attribute values

Assign a category page

Find form help

Find related tasks

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About category hierarchies](about-category-hierarchies.md)

## Create a procurement category hierarchy

1.  Click **Product information management** \> **Setup** \> **Categories** \> **Category hierarchies**. On the **Action Pane**, in the **New** group, click **Category hierarchy**.

2.  In the **Create a category hierarchy** form, enter a name and an optional description of the procurement category hierarchy, and then click **Create**.

3.  In the **Category hierarchy** form, create a new category hierarchy. For more information about how to set up a category hierarchy, see [Category hierarchy (form)](https://technet.microsoft.com/en-us/library/hh209524\(v=ax.60\)).

4.  Assign the category hierarchy to the **Procurement category hierarchy** type. For more information about category hierarchy types, see [Category hierarchy types (form)](https://technet.microsoft.com/en-us/library/hh227389\(v=ax.60\)).

After you create a category hierarchy, you can assign category attributes, commodity codes, category pages, and project categories to the parent category and subcategories. For more information, see [Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md).

Back to top

## Add product attributes to a procurement category

Use this procedure to assign product attributes to categories. All products in a category have the same product attributes. When you assign products to the category, you set up the values for product attributes. Product attributes are displayed in the Employee services portal in Enterprise Portal for Microsoft Dynamics AX.

For example, you assign the product attributes **Installation** and **Warranty** to a category. You set up the product attributes as **Required**. You assign the product **Computer** to the category, and set the value for both **Installation** and **Warranty** to **Yes**. When an employee orders a computer from the category, the employee sees that installation and warranty are included in the price of the laptop. For more information about product attributes, see [Product attributes (form)](https://technet.microsoft.com/en-us/library/hh242306\(v=ax.60\)).

1.  Click **Procurement and sourcing** \> **Setup** \> **Categories** \> **Procurement categories**.

2.  In the **Procurement categories: %1** form, select a category in the left pane, and then on the **Product attributes** FastTab, click **Add**.

3.  In the **Product attributes** form, select the product attributes that you want to associate with the selected procurement category. Click **Select -\>**, and then click **OK**.

4.  On the **Product attributes** FastTab, select the characteristics for each product attribute. Select from the following options:
    
      - **Required** – Select this check box to require a value for the product attribute for products that you assign to the category.
    
      - **Internal** – Select this check box to specify whether the product attribute is displayed in Enterprise Portal.
    
      - **Searchable** – Select this check box to include the product attribute in searches for product attributes in Enterprise Portal.

5.  If the selected category is a subcategory, select the **Inherit attributes from parent category:** check box to assign the same product attributes to the subcategory that you assign to its parent category.

Back to top

## Add products to a procurement category

Use this procedure to assign products to categories.

1.  Click **Procurement and sourcing** \> **Setup** \> **Categories** \> **Procurement categories**.

2.  In the **Procurement categories: %1** form, select a category in the left pane, and then on the **Products** FastTab, click **Add**.

3.  In the **Add products** form, select the products that you want to assign to the selected procurement category, click **Select -\>**, and then click **OK**.

Back to top

## Maintain and evaluate vendors in a procurement category

Use this procedure to add a vendor to a procurement category and to specify whether a vendor is preferred in the category. When you delete a vendor from a category, the historical transactions with the vendor in the category are not deleted.

In the Employee services portal in Enterprise Portal, an employee can request to add a new vendor to a procurement category and to extend existing vendors to additional procurement categories. For more information about category requests, see [About workflow statuses for category extension requests](about-workflow-statuses-for-category-extension-requests.md).

1.  Click **Procurement and sourcing** \> **Setup** \> **Categories** \> **Procurement categories**.

2.  In the **Procurement categories: %1** form, select a category in the left pane, and then on the **Vendors** FastTab, click **Add**.

3.  In the **Add vendors** form, select the vendors that you want to assign to the procurement category, click **Select -\>**, and then click **OK**.

4.  To delete a selected vendor from the category, on the **Vendors** FastTab, click **Remove**.

5.  Click **Evaluation** to open the **Rating on vendor evaluation criteria** form, where you can rate a vendor’s performance in the selected category. For more information, see [Rating on vendor evaluation criteria (form)](https://technet.microsoft.com/en-us/library/hh242562\(v=ax.60\)).
    

    > [!NOTE]
    > <P>Before you can evaluate a vendor, you must create vendor evaluation criterion groups and criteria, and then assign an evaluation criterion group to the category. For more information about how to set up and rate a vendor, see <A href="https://technet.microsoft.com/en-us/library/hh242832(v=ax.60)">Key tasks: Set up vendor ratings for categories</A>.</P>



6.  In the **Vendor status** field, select a status. By default, the vendor status is set to **Approved**. You can change the vendor status to **Preferred**, and then set up a policy rule to require employees to order only from preferred vendors. For more information about category policy rules, see [Set up policies for category hierarchies](set-up-policies-for-category-hierarchies.md).

7.  Select the **Inherit vendors from parent category:** check box to assign the same vendors to the selected subcategory that you assign to its parent category. The approved or preferred status of a vendor is also inherited.

Back to top

## Set up questionnaires for a procurement category

Use this procedure to assign a questionnaire to a procurement category. You can use questionnaires to understand a new vendor’s business and products, and to determine the vendor’s ability to provide products in a procurement category. When a vendor requests to do business in a procurement category, you can require the vendor to complete a questionnaire for that category. For more information about how to create a vendor questionnaire, see [Add questionnaire (form)](https://technet.microsoft.com/en-us/library/hh242743\(v=ax.60\)).

1.  Click **Procurement and sourcing** \> **Setup** \> **Categories** \> **Procurement categories**.

2.  In the **Procurement categories: %1** form, select a category in the left pane, and then on the **Questionnaires** FastTab, click **Add**.

3.  In the **Add questionnaire** form, select the questionnaire that you want to associate with the selected procurement category, click **Select -\>**, and then click **OK**. The activity type describes the intent of the questionnaire.

4.  To delete a questionnaire from a category, select the questionnaire, and then click **Remove**.

Back to top

## Maintain category attribute values

Use this procedure to enter values for category attributes. You assign category attributes when you create a procurement category hierarchy in the **Category hierarchy** form.

For example, you assign the category attribute **Category contact** to a category in the **Procurement categories: %1** form. In the **Category hierarchy** form, you enter the name of the person to contact for questions about the procurement category. The name of the person is the value for the category attribute **Category contact**.

1.  Click **Procurement and sourcing** \> **Setup** \> **Categories** \> **Procurement categories**.

2.  In the **Procurement categories: %1** form, select a category in the left pane.

3.  On the **Category attribute values** FastTab, select a category attribute. In the **General** section on the right side of the FastTab, in the **Value:** field, enter a value for the category attribute for the type indicated. Examples of value types are **Text**, **Currency**, **Boolean**, **Decimal**, and **Integer**.

4.  To translate a value into another language, click the button on the right side of the **Value:** field.

5.  To clear a value from a category attribute, click **Reset value**.

Back to top

## Assign a category page

Use this procedure to add a category page to a procurement category. You can create category pages in the **Category hierarchy** form. A category page contains information about the procurement category. Examples of this information include information about the type of products in a category, images of products in a category, and announcements such as sales or discounts that are available in a category. Category pages are displayed in the Employee services portal in Enterprise Portal.

1.  Click **Procurement and sourcing** \> **Setup** \> **Categories** \> **Procurement categories**.

2.  In the **Procurement categories: %1** form, select a category in the left pane.

3.  On the **Category page** FastTab, in the **Category page:** field, select the category page that you want to display in Enterprise Portal for the selected procurement category. The selected category page is displayed on the **Category page** FastTab so that you can review the page.

Back to top

## Find form help

[Category hierarchy (form)](https://technet.microsoft.com/en-us/library/hh209524\(v=ax.60\))

[Category hierarchy types (form)](https://technet.microsoft.com/en-us/library/hh227389\(v=ax.60\))

[Procurement categories (form)](https://technet.microsoft.com/en-us/library/hh227365\(v=ax.60\))

[Vendor evaluation criterion group (form)](https://technet.microsoft.com/en-us/library/hh242894\(v=ax.60\))

[Vendor evaluation criteria (form)](https://technet.microsoft.com/en-us/library/hh209715\(v=ax.60\))

[Add vendor evaluation criterion groups (form)](https://technet.microsoft.com/en-us/library/hh242726\(v=ax.60\))

[Add questionnaire (form)](https://technet.microsoft.com/en-us/library/hh242743\(v=ax.60\))

## Find related tasks

[Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md)

[Set up policies for category hierarchies](set-up-policies-for-category-hierarchies.md)

  


