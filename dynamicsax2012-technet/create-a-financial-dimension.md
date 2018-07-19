---
title: Create a financial dimension
TOCTitle: Create a financial dimension
ms:assetid: ac9eeb95-4cb0-4352-ae89-0524cdba31a5
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh242697(v=AX.60)
ms:contentKeyID: 36058919
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- financial dimension
- create a financial dimension
- create financial dimensions
audience: Application User
ms.search.region: Global
---

# Create a financial dimension 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Financial dimensions** form to create financial dimensions that you can use as account segments for shared charts of accounts.

After you have created the financial dimensions, use the **Financial dimension values** form to assign additional properties to each financial dimension.

Although you can use financial dimensions to represent legal entities without creating the legal entities in Microsoft Dynamics AX, financial dimensions aren’t designed to address the operational or business needs of legal entities. The interunit accounting functionality in Microsoft Dynamics AX is designed to address only the accounting entries that are created by each transaction.

Before you set up financial dimensions as legal entities, evaluate your business processes in the following areas to determine if this setup will work for your organization:

  - Inventory

  - Sales and purchases between financial dimensions and legal entities

  - Sales tax calculation and reporting

  - Operational reporting

Some examples of the limitations include the following:

  - You can use sales tax functionality only with legal entities, not with financial dimensions.

  - Some reports don't include financial dimensions, so you can't always report by financial dimension unless those reports are modified.

To create a user-defined financial dimension, in the **Use values from** field, select **\< Custom dimension \>**.

1.  Click **General ledger** \> **Setup** \> **Financial dimensions** \> **Financial dimensions**.

2.  Click **New**.

3.  In the **Use values from** field, select a system-defined entity to base the financial dimension on. Financial dimension values are created from this selection. For example, to create dimension values for projects, select **Projects**. A dimension value will be created for each project name.

4.  Enter the name of the financial dimension. The name cannot contain spaces, numbers, or symbols.

5.  In the **Report column name** field, enter the name of the financial dimension to be displayed as a column name on reports.

6.  In the **Dimension value mask** field, enter a format mask to use when financial dimension values are created. A format mask limits the amount and type of information that you can enter for dimension values.
    
    You can enter characters that remain the same for each dimension value, such as letters or a hyphen. You can also enter number signs (\#) and ampersands (&) as placeholders for letters and numbers that will change every time that a dimension value is created. Use a number sign (\#) as a placeholder for a number and an ampersand (&) as a placeholder for a letter.
    
    **Example**
    
    To limit the dimension value to the letters CC and three numbers, you enter CC-\#\#\# as the format mask.
    
    This field is available only when you select **\< Custom dimension \>** in the **Use values from** field.

7.  Click **Financial dimension values** to open the **Financial dimension values** form, where you can create or update custom list dimension values and set properties for all financial dimension values. Click **Close** when you finish.

8.  Click **Translations** to open the **Text translation** form, where you can enter text to be displayed in different languages for the selected financial dimension. Click **Close** when you finish.

9.  Click **Main account translation** to open the **Text translation** form, where you can enter text to be displayed in different languages for the main account.

## See also

[Financial dimension values (form)](https://technet.microsoft.com/en-us/library/hh242667\(v=ax.60\))

[Text translation (form)](https://technet.microsoft.com/en-us/library/hh697726\(v=ax.60\))

  


