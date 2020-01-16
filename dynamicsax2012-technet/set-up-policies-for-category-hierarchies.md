---
title: Set up policies for category hierarchies
TOCTitle: Set up policies for category hierarchies
ms:assetid: 2afa5f99-c3fe-435a-a9fe-99f78f1f2612
ms:mtpsurl: https://technet.microsoft.com/library/Hh208504(v=AX.60)
ms:contentKeyID: 36056242
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- policies
- category
- categories
- policy
- category hierarchy
- category hierarchies
- category hierarchy policy
- policies for category hierarchies
audience: Application User
ms.search.region: Global
---

# Set up policies for category hierarchies 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Policies are business rules that you define to help control your internal processes and enforce your overall business strategy. If your organization classifies products that it purchases in a procurement category hierarchy, you can create policies to manage employee access to categories. You can also define rules for ordering products in specific categories in the procurement category hierarchy.

## Create a category access rule

Use this procedure to set up rules for limiting access to procurement categories.

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**. On the **Action Pane**, in the **New** group, click **Policy**.

2.  In the **Purchasing policy** form, on the **General** FastTab, enter a unique name and an optional description for the policy.

3.  On the **Policy organizations** FastTab, select the organization and legal entities to which this category policy applies.

4.  On the **Policy rules** FastTab, in the left pane, click **Category access policy rule**. Then click **Create policy rule**.

5.  In the **Category access policy rule** form, select the dates on which the policy starts and ends. If you leave the **Effective date** and **Expiration date** fields blank, the policy is always valid.

6.  Select the **Include parent rule** check box to apply the category access policy rule of the parent organization to the category.

7.  In the **Available categories** pane, select the categories to which the rule applies. When you select a category, all the categories that are higher in the hierarchy are also added to the **Selected categories** list.

8.  Select the **Include subcategories** check box to apply the rule to all subcategories of the selected category.

The procurement site in the Employee services portal uses the category access rule to control which procurement categories users have access to. When a user accesses the procurement site, the system determines which purchasing policy and category access rule to apply based on the legal entity and operational unit that the employee belongs to.

## Create a category policy rule

Use this procedure to set up rules for ordering products in a category.


> [!NOTE]
> <P>Public sector entities in France can define a policy rule to manage spending thresholds by category, as required by the Clé de Contrôle Marché. For more information, see <A href="fra-set-up-a-policy-rule-for-spending-thresholds-by-category-public-sector.md">(FRA) Set up a policy rule for spending thresholds by category (Public sector)</A>.</P>



1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**. On the **Action Pane**, in the **New** group, click **Policy**.

2.  In the **Purchasing policy** form, on the **General** FastTab, enter a unique name and an optional description for the policy.

3.  On the **Policy organizations** FastTab, select the organization and legal entities to which this category policy applies.

4.  On the **Policy rules** FastTab, in the left pane, click **Category policy rule**. Then click **Create policy rule**.

5.  In the **Category policy rule** form, select the dates on which the policy starts and ends. If you leave the **Effective date** and **Expiration date** fields blank, the policy is always valid.

6.  In the **Category policy data** list, select a category to which the rule applies.
    

    > [!NOTE]
    > <P>The policy rule that you define for a parent category is assigned to its child categories if no policy rule has been defined for the child categories.</P>



7.  In the **Vendor selection** field, select a rule to control the selection of vendors in the category. Select one of the following options:
    
      - **Allow only vendors that are preferred for this category** – Employees must purchase only from preferred vendors.
    
      - **Allow only vendors that are preferred or approved for this category** – Employees can purchase from preferred vendors or approved vendors.
    
      - **Do not allow vendor selection in this category** – The employee cannot select a vendor. The vendor is selected during the review process.
    
      - **Allow all vendors** – There are no restrictions on vendor selection.

8.  Select the **Show questionnaires?** check box if requesters must complete a questionnaire when they request products in the specified category. The questionnaire is displayed when the requester selects a category item in a purchase requisition or in Enterprise Portal for Microsoft Dynamics AX.

9.  In the **Category matching policy** field, select the matching policy to apply when purchase order lines are reconciled against a vendor invoice. Select one of the following options:
    
      - **Company policy** – The matching policy from the organization level must be followed.
    
      - **Three-way matching**– The price and quantity on the purchase order, product receipt, and invoice must match.
    
      - **Two-way matching** – The price and quantity on the purchase order and invoice must match.
    
      - **Not required** – Matching is not required.

10. Select the **Receiving requirements** check box if you want to verify that you have received the correct quantity of products before recording the purchase.

11. Select the **Deduction requirements** check box if you want to verify that deductions for products that are returned to the vendor are correct before recording the return transaction.

12. Select the **Accrue purchase expense on receipt** check box if you want to record the amount payable to the vendor upon receipt of the product receipt for a purchase order line instead of upon receipt of the vendor invoice.

## See also

[Category access policy rule (form)](https://technet.microsoft.com/library/hh227513\(v=ax.60\))

[Category policy rule (form)](https://technet.microsoft.com/library/hh209240\(v=ax.60\))

  


