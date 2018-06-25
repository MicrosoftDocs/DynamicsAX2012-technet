---
title: Update product data by using the mass update worksheet
TOCTitle: Update product data by using the mass update worksheet
ms:assetid: 334d85f2-9e00-4fe2-afea-bd18a82973d3
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh580603(v=AX.60)
ms:contentKeyID: 39519089
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- BR - 00038
---

# Update product data by using the mass update worksheet [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack_

You can update the properties of multiple products at the same time by using the Mass update worksheet tool. You can also use this tool to modify product properties at the product category level and then apply the changes to all products that are assigned to the category.

1.  Click **Retail** \> **Periodic** \> **Mass update worksheet**.

2.  In the **Mass update worksheet** form, click **New** to create a new worksheet.

3.  In the **Worksheet number** form, select the product properties to modify. The appropriate columns are generated in the worksheet.
    

    > [!NOTE]
    > <P>In Microsoft Dynamics AX 2012 Feature Pack, this form is called <STRONG>Select properties</STRONG>.</P>

    
    To select properties from multiple areas, select the name of an area in the **Areas** grid. Then select the check box next to each field to include in the worksheet. The areas that appear in the **Areas** grid correspond to the FastTabs in the **Product details** form.

4.  On the **Products** FastTab, click **Add products**, and then in the **Add products** form, select the products to update properties for.

5.  After you add the products to the **Products** FastTab, enter your changes. You can change each product individually, or you can enter the changes on the first product row, and then click **Paste first row** to copy the changes to one or more rows in the worksheet.

6.  In Microsoft Dynamics AX 2012 R2, you can set a value for a field based on a formula. Do one of the following:
    
      - Select one or more rows, and then click **Apply price formula** to use a formula to enter values in price fields. For example, you can reduce the product price for selected products by a specified percentage.
    
      - Select one or more rows, and then click **Apply date formula** to use a formula to enter values in date fields. For example, you can change the sales date for selected products by adding a specific number of days to the current date.

7.  Click **Validate** to verify that the changes that you entered are valid. If you enter additional changes after you validate the worksheet, you must revalidate the worksheet before you post the changes.

8.  Click **Post** to apply the changes that you entered in the worksheet to the products. After a worksheet has been posted, it cannot be modified.

## See also

[Mass update worksheet (form)](https://technet.microsoft.com/en-us/library/hh597155\(v=ax.60\))

[Apply formula (form)](https://technet.microsoft.com/en-us/library/jj728731\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

