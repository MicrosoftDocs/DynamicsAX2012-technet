---
title: Set up derived financial hierarchies (Public sector)
TOCTitle: Set up derived financial hierarchies (Public sector)
ms:assetid: cd855ad4-ddbb-4302-a038-acc3e66758f8
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208586(v=AX.60)
ms:contentKeyID: 36056372
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- derived financial hierarchies
---

# Set up derived financial hierarchies (Public sector) [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

To meet Common Government-wide Accounting Classification (CGAC) requirements, public sector organizations can use derived financial hierarchies to collect and analyze posted transaction data for specific main account numbers, full account numbers, and financial dimension values.

Typically, category hierarchies are set up to classify transactions for reporting and analysis based on the financial dimensions in an account structure at the time of posting. However, public sector organizations can set up category hierarchies with a **Derived financial hierarchy** category type. Then filter rules for the derived financial hierarchy can be defined to create financial categories and dimension values that are not part of the account number. The financial categories and dimension values defined in the filter rules are derived from the account number dimension values that are used in the posted transactions.

Derived financial hierarchies give organizations a more flexible approach to grouping transactions for ad hoc analytics. This allows them to categorize transactions without having to expand the account structure to include the additional categories or dimensions they want to track.

## Prerequisites

To set up derived financial hierarchies, you should be familiar with category hierarchies and financial dimensions. For more information, see [About category hierarchies](about-category-hierarchies.md) and [Create a financial dimension](create-a-financial-dimension.md).


> [!NOTE]
> <P>This process is available only if the <STRONG>Public Sector</STRONG> configuration key is selected.</P>



## Example

To collect account numbers used in the posted transactions for employee programs not associated with financial dimensions, you could do the following:

  - Create a category hierarchy named **Employee programs** with a parent node named **Programs** and two child nodes named **Employee wellness** and **Employee education**.

  - Assign the **Derived financial hierarchy** category type to the **Employee programs** category hierarchy.

  - Associate the **Employee programs** derived financial hierarchy with the legal entity.

  - Use the **Derived financial hierarchies** form to create filter rules for the main accounts and financial dimension values associated with the **Employee wellness** and **Employee education** nodes in the **Employee programs** derived financial hierarchy.

  - In the filter results, view account numbers and their account and financial dimension details.

## Set up a derived financial hierarchy

1.  To create a category hierarchy, click **Product information management** \> **Setup** \> **Categories** \> **Category hierarchies**.
    
    From the example, you would create a category hierarchy named **Employee programs** with a parent node named **Programs** and two child nodes named **Employee wellness** and **Employee education**. For more information, see [Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md).

2.  To assign the **Derived financial hierarchy** category type to a category hierarchy, click **Product information management** \> **Setup** \> **Categories** \> **Category hierarchy types**.
    
    From the example, you would assign the **Derived financial hierarchy** category type to the **Employee programs** category hierarchy. For more information, see [Category hierarchy types (form)](https://technet.microsoft.com/en-us/library/hh227389\(v=ax.60\)).

3.  To associate the derived financial hierarchy with a legal entity, click **General ledger** \> **Setup** \> **Financial dimensions** \> **Associate derived financial hierarchies**.

4.  To create filter rules for the nodes in the derived financial hierarchy, click **General ledger** \> **Setup** \> **Financial dimensions** \> **Derived financial hierarchies**.
    
    From the example, you would create filter rules for the **Employee wellness** and **Employee education** nodes.

5.  On the **Derived financial hierarchies** form, do the following:
    
    1.  Click **Derived financial hierarchy** to select a derived financial hierarchy that has been associated with the legal entity.
    
    2.  Select a child node and then click **Edit filter**.
    
    3.  Click **Add filter** to create a filter rule for the selected node. To enter multiple dimension values in the **Value** field, enter a comma without spaces as a separator – for example **100,110** or **Benefits,Insurance**.
        
        You can create filter rules for each financial dimension in the node.
    
    4.  Click **Activate filter** and then click **View filter results**.
        
        The **Filter results** form opens where you can view the account numbers associated with the dimension values in posted transactions. Move the cursor over an account number to display the **Account and financial dimension details**.
    
    5.  Click **Export to Microsoft Excel** to open a workbook that contains the account numbers.

## See also

[Derived financial hierarchies (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208496\(v=ax.60\))

[Associate derived financial hierarchies (form) (Public sector)](https://technet.microsoft.com/en-us/library/hh208604\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

