---
title: Create attribute types
TOCTitle: Create attribute types
ms:assetid: 230531f6-8a29-4b3b-af19-9257c9443752
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580585(v=AX.60)
ms:contentKeyID: 39519067
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Create attribute types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Attribute types specify the set of data types for attributes that are used in a product configuration model. You can use the following data types in a product model:

  - **Text** – Select this type when you want to create a fixed list of values.

  - **Boolean** – Select this type when you want to use true or false values.

  - **Integer** – Select this type when you want to create a range of fixed numerical values.

  - **Decimal** – Select this type to include decimal values.


> [!NOTE]
> <P>You can use decimal values, text without a fixed list, and integers without ranges in a product configuration model. However, you cannot use these data types when you write a constraint.</P>




> [!WARNING]
> <P>Solver Foundation constraint solver only supports text with a fixed list, Boolean values, and integers with ranges. The following data types are displayed in the list in the <STRONG>Type</STRONG> field but cannot be used in a product model:</P>
> <UL>
> <LI>
> <P><STRONG>Currency</STRONG></P>
> <LI>
> <P><STRONG>DateTime</STRONG></P></LI></UL>



## Create an attribute type

1.  Click **Product information management** \> **Common** \> **Product configuration models**.

2.  On the **Action Pane**, click **Attribute types**.

3.  In the **Specify requested period allocation** form, click **New** on the toolbar.

4.  In the **Name** field, enter a name for the attribute type.

5.  In the **Type** field, select one of the following data types for the attributes of the configuration model:
    
      - **Integer** – If you select this type, you can select the **Value range** check box to add a **Range** FastTab to the form. You can then specify a valid range for values for the attribute type.
        

        > [!NOTE]
        > <P>The <STRONG>Unit of measure</STRONG> field is not used in product configuration models.</P>

    
      - **Text** – If you select this type, you must select the **Add** check box to add a **Values** FastTab to the form. You can then add the list of values and solver values.
    
      - **Boolean** – If you select this type, the set of values is either true or false.
    
      - **Decimal** – If you select this type, you can specify a decimal number for an attribute assigned to the product configuration model.
        

        > [!WARNING]
        > <P>The <STRONG>Decimal</STRONG> data type cannot be used in a constraint in a product configuration model.</P>



## See also

[Add an attribute to a component](add-an-attribute-to-a-component.md)

  


