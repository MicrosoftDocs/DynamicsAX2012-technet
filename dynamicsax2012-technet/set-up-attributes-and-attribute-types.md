---
title: Set up attributes and attribute types
TOCTitle: Set up attributes and attribute types
ms:assetid: f72d49b8-121f-4cd3-b1fc-9ca0d25ccf8d
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh227548(v=AX.60)
ms:contentKeyID: 36060029
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- attributes
- products
- attribute types
- procurement categories
- procurement catalogs
---

# Set up attributes and attribute types 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Attributes identify the details that you want to maintain for your products. You can assign attributes to a product through the procurement category that the product is assigned to. When you add a procurement category and its associated products to your procurement catalog, the attributes that are assigned to the procurement category are displayed on the procurement site.

When you define attributes, you must first define the attribute type. You can then assign the attribute type to the attribute. The attribute type identifies the type of data that can be entered for a specific attribute. The attribute type also defines a list or range of valid values that can be used for the attribute.

For more information about how to assign attributes to product categories, see [Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md).

## Define attribute types

1.  Click **Product information management** \> **Setup** \> **Attributes** \> **Attribute types**.

2.  In the **Attribute types** form, click **New** to add a new attribute type.

3.  On the **General** FastTab, enter a name for the attribute type. Then, in the **Type** field, select the type of data that can be entered for attributes that are assigned to this data type.

4.  If the attribute type is **Decimal** or **Integer**, select a unit of measure.

5.  To define a fixed list of values for the attribute type, select the **Fixed list** check box. Then, on the **Values** FastTab, add the list of values.
    

    > [!NOTE]
    > <P>The <STRONG>Fixed list</STRONG> check box is available only for the <STRONG>Text</STRONG> attribute type.</P>



6.  To define a range of valid values for the attribute type, select the **Value range** check box. Then, on the **Range** FastTab, enter the valid range of values.
    

    > [!NOTE]
    > <P>The <STRONG>Value range</STRONG> check box is available only for the <STRONG>Currency</STRONG>, <STRONG>DateTime</STRONG>, <STRONG>Decimal</STRONG>, and <STRONG>Integer</STRONG> attribute types.</P>



## Define attributes

1.  Click **Product information management** \> **Setup** \> **Attributes** \> **Attributes**.

2.  In the **Attributes** form, click **New** to add a new attribute.

3.  Enter the name, friendly name, description, and any help text that you want to display to the user for the attribute.

4.  In the **Attribute type** field, select the attribute type to assign to the attribute.

5.  Depending on your version of the program, follow one of these steps:
    
      - In Microsoft Dynamics AX 2012 R2: Click **Edit** to enter the attribute details if you add an attribute that is assigned an attribute type of **HtmlDomain**, **ImageDomain**, or **VideoDomain**.
    
      - Otherwise, in the **Default value** field, enter the value or range of values that is displayed by default when this attribute is assigned to a product, retail, or procurement category.
        

        > [!NOTE]
        > <P>Depending on the attribute type that you select, the <STRONG>Default value</STRONG> field may be displayed either as a check box or as a field. You may have to enter additional data, such as a unit of measure or currency.</P>



6.  Click **Translate**, and then, in the **Text translation** form, enter the name, description, friendly name, and help text for the attribute in different languages.

7.  Repeat steps 2 through 6 to add more attributes.

## See also

[Attributes (form)](https://technet.microsoft.com/en-us/library/hh242817\(v=ax.60\))

[Attribute types (form)](https://technet.microsoft.com/en-us/library/hh227367\(v=ax.60\))

[Attribute groups (form) (Retail)](https://technet.microsoft.com/en-us/library/jj728740\(v=ax.60\))

[Key tasks: Set up a category hierarchy](key-tasks-set-up-a-category-hierarchy.md)

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

