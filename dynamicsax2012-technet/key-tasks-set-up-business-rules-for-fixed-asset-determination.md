---
title: 'Key tasks: Set up business rules for fixed asset determination'
TOCTitle: 'Key tasks: Set up business rules for fixed asset determination'
ms:assetid: 1851814e-c357-43ad-a8cd-0a548e7d1f18
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208442(v=AX.60)
ms:contentKeyID: 36056096
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Key tasks: Set up business rules for fixed asset determination 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the procedures in this topic to set up the rules to determine whether a purchase must be treated as a fixed asset. A purchase is treated as a fixed asset if the unit price of the product exceeds a monetary threshold that you define. The monetary threshold for a legal entity can differ from the monetary threshold for your organization. You can create, change, or delete fixed asset rules if you are assigned to a role with appropriate privileges.

You can create qualifier questions to help the system classify a fixed asset into the appropriate fixed asset group. A qualifier is displayed on a purchase requisition when the following conditions are true:

  - A worker selects a product from a procurement category.

  - The unit price of the selected product equals or exceeds the monetary threshold amount for the selected category.

Complete the following prerequisites before you set up business rules for fixed assets.

  - Set up an active procurement category hierarchy. For more information, see [Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md).

  - Associate any products that can potentially be classified as fixed assets with a procurement category in the active procurement category hierarchy. For more information, see [Key tasks: Set up and maintain procurement category hierarchies](key-tasks-set-up-and-maintain-procurement-category-hierarchies.md).

  - Set up fixed asset groups for legal entities. For information, see [Set up fixed asset groups](set-up-fixed-asset-groups.md).

  - Create a currency conversion rate if the currency of a legal entity differs from the organization’s currency. You must do this before you can associate a legal entity rule with an organization-wide fixed asset identifier. For more information, see [Currency exchange rates (form)](https://technet.microsoft.com/en-us/library/hh209477\(v=ax.60\)).

## What do you want to do?

Learn more about...

Create an organization-wide fixed asset identifier

Create an organization-wide fixed asset rule

Create a fixed asset rule for a legal entity

Modify a fixed asset rule

Delete a fixed asset rule

Find form help

## Learn more about...

Click these links to find more information about the concepts that are discussed in this topic.

[About fixed asset determination rules](about-fixed-asset-determination-rules.md)

## Create an organization-wide fixed asset identifier

Use this procedure to set up an organization-wide fixed asset identifier. You must associate the organization-wide fixed asset identifier with a fixed asset group for a legal entity. After you create an organization-wide fixed asset identifier, you can create a monetary threshold and qualifier questions to help the system classify a fixed asset for the organization.

1.  Click **Procurement and sourcing** \> **Setup** \> **Fixed assets** \> **Organization-wide fixed asset identifiers**.

2.  On the **Organization-wide fixed asset identifiers** form, click **New**.

3.  In the **Organization-wide fixed asset identifier** field, enter a unique short name for the identifier.

4.  In the **Name** field, enter a descriptive name for the identifier.
    

    > [!IMPORTANT]
    > <P>You must save a new or modified organization-wide fixed asset identifier before you can associate the identifier with a fixed asset group for a legal entity.</P>



5.  In the **Mapping to fixed asset groups** list, select a legal entity and a fixed asset group to associate with the organization-wide fixed asset identifier. You can associate an organization-wide fixed asset identifier with only one fixed asset group per legal entity.

6.  Repeat steps 2 through 5 to create additional organization wide fixed asset identifiers.

Back to top

## Create an organization-wide fixed asset rule

Use this procedure to create a rule for determining when a product qualifies as a fixed asset for your whole organization. You can create rules for specific procurement categories, and you can create qualifiers that capture information from the worker, such as the intended usage or the expected lifespan of the asset, which help the system determine the correct fixed asset group for a product.

1.  Click **Procurement and sourcing** \> **Setup** \> **Fixed assets** \> **Business rules for fixed assets determination**.

2.  On the **Business rules for fixed assets determination** form, click **New**.

3.  Enter a unique short name and an optional detailed description for the rule.

4.  On the **Procurement categories** tab, click **Add**. Select a procurement category to which this rule applies. The rule automatically applies to all subcategories of the selected procurement category.
    

    > [!NOTE]
    > <P>You can define a rule for a subcategory that overrides the rule from the parent category.</P>



5.  Repeat step 4 to associate the rule with additional procurement categories.
    

    > [!IMPORTANT]
    > <P>You can associate a procurement category with only one organization-wide fixed asset rule.</P>



6.  On the **Organization-wide rule** tab, click **Add threshold**. Enter the minimum capitalization threshold amount, and then select the currency of the organization. If the purchase price of a product exceeds this threshold, the product is treated as a fixed asset.

7.  If you want to specify a date range for the rule, enter the dates in the **Effective** and **Expiration** fields. If you want the rule to always be valid, select an expiration date of **Never**. You can change the expiration date if the rule changes and you can retire the rule if it no longer applies.

8.  In the **Fixed asset group** field, select an organization-wide fixed asset identifier for the rule.

9.  Create qualifiers to help the system apply the appropriate fixed asset group for a product:
    
    1.  Select the **Has qualifiers?** check box.
    
    2.  In the **Description** field, enter a qualifier question. For example, if your organization classifies products that use power as office equipment and classifies products that do not use power as office furniture, your qualifier question might be **Does this item need power to operate?** The qualifier is displayed as a label on the **Fixed assets** FastTab of a purchase requisition when a worker selects a product that qualifies as a fixed asset.
    
    3.  Click **Add**. Enter a unique name for each possible response to the qualifier. For example, enter **Power is needed** and **Power is not needed**.
    
    4.  In the **Description** field, enter a response to each qualifier that corresponds to a fixed asset group. The worker response prompts the system to classify a product into the appropriate fixed asset group.
    
    5.  In the **Fixed asset group** field, enter the name of the fixed asset group that corresponds to each response to the qualifier question.
    
    6.  Optional: Click **Translations** to enter the name of the fixed asset group in another language.

Back to top

## Create a fixed asset rule for a legal entity

Use this procedure to create a fixed asset rule for a legal entity that must comply with local statutory requirements that differ from the organization’s requirements for determining fixed assets. You can also create a rule for a legal entity without a corresponding organization-wide rule.

1.  Click **Procurement and sourcing** \> **Setup** \> **Fixed assets** \> **Business rules for fixed assets determination**.

2.  On the **Business rules for fixed assets determination** form, click **New**.

3.  In the left pane, enter a unique short name and an optional detailed description.

4.  On the **Procurement categories** tab, click **Add**. Select one or more procurement category codes to which the rule applies. The rule automatically applies to all subcategories of the selected procurement categories.
    

    > [!NOTE]
    > <P>You can associate a procurement category code with only one legal-entity fixed asset rule.</P>



5.  On the **Legal entity-specific rule** tab, in the **Legal entity** field, select the name of the legal entity to which the rule applies.

6.  Click **Add threshold**. In the **Capitalization threshold** field, enter the minimum capitalization amount, stated in the currency of the legal entity. If the purchase price of a product exceeds this threshold, the product is treated as a fixed asset.
    

    > [!IMPORTANT]
    > <P>If the legal entity’s currency differs from the organization’s currency, you must create a currency conversion rate before you can associate a legal entity rule with an organization-wide fixed asset identifier.</P>



7.  If you want to specify a date range for a rule, enter the dates in the **Effective** and **Expiration** fields. If you want the rule to always be valid, select an expiration date of **Never**. You can change the expiration date if the rule changes. You can retire the rule if it no longer applies.

8.  In the **Fixed asset group** field, select the fixed asset group to which products are assigned if they meet the threshold rule.

9.  Optional: Create qualifiers. If you associate more than one fixed asset group with a procurement category, you may want to create qualifiers. Qualifiers help the system assign the appropriate fixed asset group to a product.
    
    1.  Select the **Has qualifiers?** check box.
    
    2.  In the **Description** field, enter a qualifier question. The qualifier is displayed as a label on the **Fixed assets** FastTab of a purchase requisition when a worker selects a category item that qualifies as a fixed asset.
    
    3.  Click **Add**. Enter a unique name for each possible response to the qualifier.
    
    4.  In the **Description** field, enter a response to each qualifier that corresponds to a fixed asset group. The worker response to the qualifier prompts the system to classify the product into the appropriate fixed asset group.
    
    5.  In the **Fixed asset group** field, select the fixed asset group that corresponds to each response to the qualifier question.
    
    6.  Repeat the previous two steps for any fixed asset groups that are associated with the procurement category.
    
    7.  Optional: Click **Translations** to enter the name of the fixed asset group in another language.

Back to top

## Modify a fixed asset rule

1.  Click **Procurement and sourcing** \> **Setup** \> **Fixed assets** \> **Business rules for fixed assets determination**.

2.  In the left pane, select the fixed asset rule that you want to modify.

3.  Modify the procurement category, threshold amount, effective date, expiration date, and qualifiers for the rule. You can modify an organization-wide rule, a legal-entity-specific rule, or both.

Back to top

## Delete a fixed asset rule

Use this procedure to delete a fixed asset rule. Deleting a fixed asset rule does not affect fixed assets that are already classified by using the rule.

1.  Click **Procurement and sourcing** \> **Setup** \> **Fixed assets** \> **Business rules for fixed assets determination**.

2.  In the left pane, select the fixed asset rule that you want to delete.

3.  Click **Delete**.

Back to top

## Find form help

[Business rules for fixed asset determination (form)](https://technet.microsoft.com/en-us/library/hh242884\(v=ax.60\))

  


