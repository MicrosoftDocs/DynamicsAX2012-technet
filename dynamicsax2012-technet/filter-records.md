---
title: Filter records
TOCTitle: Filter records
ms:assetid: c94550e8-414f-4fdb-bcb7-114ee67aaf3e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa550877(v=AX.60)
ms:contentKeyID: 37822159
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Filter records 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use filtering to find and work with a subset of the data in a form. When you apply a filter on a form, you see only the records that meet the criteria that you specify.

For example, you can filter the records on the **All customers** list page so that only customers from a specific customer group are displayed.

The following commands are used to filter records:

  - **Filter By Selection** (ALT+F3)

  - **Filter By Field** (CTRL+K)

  - **Filter By Grid** (CTRL+G)

  - **Advanced Filter** (CTRL+F3), for more complex criteria

Unlike sorting, filtering does not rearrange the records. Filtering temporarily hides records that you do not want to display in a grid.

## Filter by selection

1.  Select the field that meets the criterion for the filter that you want to apply.

2.  Click **File** \> **Edit** \> **Filter** \> **Filter By Selection** or press ALT+F3.


> [!NOTE]
> <P><STRONG>Filter By Selection</STRONG> removes any filter that is applied to the table and finds all records that meet your search criteria.</P>



## Filter by field

**Filter By Field** is similar to **Filter By Selection**, except that you can specify the filtering criteria for the field.

1.  Select the field to use as the filter.

2.  Click **File** \> **Edit** \> **Filter** \> **Filter By Field** or press CTRL+K.

3.  In the **Filter:** Name of the field dialog box, enter the filtering criteria, and then press ENTER.


> [!NOTE]
> <P>Repeat steps 1 through 3 to apply more filters to the records.</P>



## Filter by grid

1.  Click **File** \> **Edit** \> **Filter** \> **Filter By Grid** or press CTRL+G to open the filter line at the top of the grid.

2.  Press TAB to select the column to filter by.

3.  Type the filter criteria, and then press the DOWN ARROW key to select a filtering option.

4.  Repeat steps 2 and 3 to add more criteria to the filter.

## Remove filter/sort

To remove a filter that is applied to one or more columns in the form, click **File** \> **Edit** \> **Remove Filter/Sort** or press CTRL+SHIFT+F3.


> [!NOTE]
> <P>The <STRONG>Remove Filter/Sort</STRONG> option is available on the <STRONG>Edit</STRONG> menu only if a filter is applied.</P>



## Save filter as

1.  Create a filter by using one of the filtering options.

2.  Click **File** \> **Edit** \> **Filter** \> **Save filter as**.

3.  In the **Save inquiry** dialog box, type a name for the filter that you created.
    

    > [!NOTE]
    > <P>To save changes to an existing filter, click <STRONG>File</STRONG> &gt; <STRONG>Edit</STRONG> &gt; <STRONG>Filter</STRONG> &gt; <STRONG>Save filter</STRONG>.</P>



## Apply filter

To apply a filter that you previously saved, click **File** \> **Edit** \> **Apply filter**, and then select a filter in the list.


> [!NOTE]
> <P>The list of filters is empty if you have not saved any filters in the active form or list.</P>



## Delete filter

1.  Click **File** \> **Edit** \> **Delete filter**, and then select a filter to delete.

2.  In the **Delete filter** dialog box, click **Yes** to delete the selected filter, or click **No** to cancel the operation and keep the filter.

## See also

[Advanced filtering and query options](advanced-filtering-and-query-options.md)

[Find records](find-records.md)

[Sort records](sort-records.md)

  


