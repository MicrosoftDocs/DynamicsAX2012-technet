---
title: Set up attributes and attribute types (Retail essentials)
TOCTitle: Set up attributes and attribute types (Retail essentials)
ms:assetid: 2ca305fa-53ef-4393-8af2-489a4b08a7e9
ms:mtpsurl: https://technet.microsoft.com/library/Dn876697(v=AX.60)
ms:contentKeyID: 63384781
author: Khairunj
ms.date: 12/17/2014
mtps_version: v=AX.60
---

# Set up attributes and attribute types (Retail essentials) 


Attributes identify the details that you want to maintain for your products. You can assign attributes to a product through the category that the product is assigned to.

When you define attributes, you must first define the attribute type. You can then assign the attribute type to the attribute. The attribute type identifies the type of data that can be entered for a specific attribute. The attribute type also defines a list or range of valid values that can be used for the attribute.

## Define attribute types

1.  Click **Retail essentials** \> **Merchandising** \> **Setup** \> **Attributes** \> **Attribute types**.

2.  In the **Attribute types** form, click **New** to add a new attribute type.

3.  On the **General** FastTab, enter a name for the attribute type. In the **Type** field, select the type of data that can be entered for attributes that are assigned to this data type.

4.  If the attribute type is **Decimal** or **Integer**, select a unit of measure.

5.  To define a fixed list of values for the attribute type, select the **Fixed list** check box. On the **Values** FastTab, add the list of values.
    

    > [!NOTE]
    > <P>The <STRONG>Fixed list</STRONG> check box is available only for the <STRONG>Text</STRONG> attribute type.</P>



6.  To define a range of valid values for the attribute type, select the **Value range** check box. On the **Range** FastTab, enter the valid range of values.
    

    > [!NOTE]
    > <P>The <STRONG>Value range</STRONG> check box is available only for the <STRONG>Currency</STRONG>, <STRONG>DateTime</STRONG>, <STRONG>Decimal</STRONG>, and <STRONG>Integer</STRONG> attribute types.</P>



## Define attributes

1.  Click **Retail essentials** \> **Merchandising** \> **Setup** \> **Attributes** \> **Attributes**.

2.  In the **Attributes** form, click **New** to add a new attribute.

3.  Enter the name, friendly name, description, and any help text that you want to display to the user for the attribute.

4.  In the **Attribute type** field, select the attribute type to assign to the attribute.

5.  In the **Default value** field, enter the value or range of values that is displayed by default when this attribute is assigned to a product, retail, or procurement category.
    

    > [!NOTE]
    > <P>Depending on the attribute type that you select, the <STRONG>Default value</STRONG> field may be displayed either as a check box or as a field. You may have to enter additional data, such as a unit of measure or currency.</P>



6.  Click **Translate**, and then, in the **Text translation** form, enter the name, description, friendly name, and help text for the attribute in different languages.

7.  Repeat steps 2 through 6 to add more attributes.

## See also

[Add and update product attributes for retail channels (Retail essentials)](add-and-update-product-attributes-for-retail-channels-retail-essentials.md)

[Bulk edit product attributes by using Excel (Retail essentials)](bulk-edit-product-attributes-by-using-excel-retail-essentials.md)

  


