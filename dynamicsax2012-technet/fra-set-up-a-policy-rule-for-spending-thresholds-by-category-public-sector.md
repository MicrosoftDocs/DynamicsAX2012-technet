---
title: (FRA) Set up a policy rule for spending thresholds by category (Public sector)
TOCTitle: (FRA) Set up a policy rule for spending thresholds by category (Public sector)
ms:assetid: 82d072c5-f44d-461e-9e67-19fe1f2954cf
ms:mtpsurl: https://technet.microsoft.com/library/Hh208547(v=AX.60)
ms:contentKeyID: 36056304
author: tonyafehr
ms.date: 03/25/2015
mtps_version: v=AX.60
f1_keywords:
- policies
- category
- categories
- policy
- public sector
- France
- French
- policy rule
- spending threshold
- policy rules
- category policy rule
- category policy rules
- spending thresholds
audience: Application User
ms.search.region: France
---

# (FRA) Set up a policy rule for spending thresholds by category (Public sector) 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To meet public sector regulatory requirements in France, you may have to set spending thresholds for purchases in the procurement categories defined by the Clé de Contrôle Marché.

By implementing a **Spending thresholds by category** policy rule with your purchasing policies, you can use the effective date attributes, predicted expenditure amounts, and threshold amounts to support your procurement practices and to ensure the efficient and effective use of public funds.


> [!NOTE]
> <P>This topic has been updated to include information about features that were added or changed in the following hotfix for Microsoft Dynamics AX 2012 R3 Cumulative Update 8: KB3047235</P>The <STRONG>Spending thresholds by category</STRONG> policy rule is available only if the following conditions are met: 
> <UL>
> <LI>
> <P>The <STRONG>Public Sector</STRONG> configuration key is selected.</P>
> <LI>
> <P>The <STRONG>French regulatory</STRONG> configuration subkey is selected.</P>
> <LI>
> <P>In Microsoft Dynamics AX 2012 R3 Cumulative Update 8, the <STRONG>Commitments (France)</STRONG> regulatory document type is selected in the <STRONG>Budget parameters</STRONG> form, when the following hotfix is installed: KB3047235</P>
> <LI>
> <P>In cumulative update 7 for Microsoft Dynamics AX 2012, the <STRONG>Use French public sector accounting rules</STRONG> check box is selected in the <STRONG>Budget parameters</STRONG> form.</P></LI></UL>
> <P>In versions of Microsoft Dynamics AX 2012 prior to cumulative update 7, only the <STRONG>Public Sector</STRONG> configuration key must be selected, but the primary address of the legal entity must be in France.</P>



To set up a policy rule for spending thresholds by category, use the following steps.

1.  Click **Procurement and sourcing** \> **Setup** \> **Policies** \> **Purchasing policies**.

2.  Double-click the policy to modify or create rules for.

3.  On the **Policy rules** FastTab, select **Spending thresholds by category**. In the **Policy rules** pane, double-click a policy rule or click **Create policy rule**.
    
    Because the policy rule is effective as soon as it is created, the **Effective date** field will show the current date and time. The **Expiration date** field, by default, is **Never**, which indicates that the policy rule does not expire. If you want to set an expiration date for the policy rule, you can do so after you close this form.

4.  From the **Available categories** list, select a category to define spending thresholds for.

5.  Select the **Activate threshold at this hierarchy node** check box.

6.  Click **New**.

7.  Enter the **Key** defined by your organization for the selected category.

8.  In the **Effective** field, enter the date that you want the key for the selected category to take effect.
    
    This date applies to the selected category key, not to the policy rule. The policy rule itself takes effect as soon as it is created.

9.  In the **Expiration** field, enter the date that you want the key for the selected category to expire.
    
    This date applies to the selected category key, not to the policy rule. If the policy rule expires, all spending thresholds associated with it expire at that time, even if a later expiration date is set here.

10. (Optional) In the **Estimated amount** field, enter the amount that you expect to be purchased in this category.

11. In the **Threshold amount** field, enter the maximum amount that can be purchased before the formal procurement process is required.
    
    A default value for this field may be set up in the **Category hierarchy** form.

12. Select the type of purchasing procedure that is required when expenditures in the selected category exceed the threshold amount.
    
      - **Only Procédure complète**: Select this option if the procédure complete is required.
    
      - **None**: Select this option if purchases that exceed the threshold amount are not permitted.
    
      - **Both Procédure complète and Procédure adaptée**: Select this option if either the procédure complete or a procédure adaptée is permitted.
    
      - **Any**: Select this option if neither the procédure complete nor a procédure adaptée is required.

13. Close the form.

14. (Optional) If you want to set an expiration date for the policy rule, make sure that **Spending thresholds by category** is still selected in the **Policy rule type:** list. Click **Change date** in the **Policy rules** pane, enter the expiration date, and then close the form.

## See also

[Purchasing policy (form)](https://technet.microsoft.com/library/hh209627\(v=ax.60\))

[Procurement categories (form)](https://technet.microsoft.com/library/hh227365\(v=ax.60\))

[Category hierarchy (form)](https://technet.microsoft.com/library/hh209524\(v=ax.60\))

[Key tasks: Create purchasing policies](key-tasks-create-purchasing-policies.md)

[(FRA) Spending thresholds by category policy rule (form) (Public sector)](https://technet.microsoft.com/library/hh208581\(v=ax.60\))

  


