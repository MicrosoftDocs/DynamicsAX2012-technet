---
title: 'How to: Use a Data Method in an Expression'
TOCTitle: 'How to: Use a Data Method in an Expression'
ms:assetid: bb2a1aeb-7911-4ecb-aec7-815b2d151046
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh538451(v=AX.60)
ms:contentKeyID: 39508875
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Use a Data Method in an Expression [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic describes how to use a data method in an expression. The experience is different, depending on the type of report design.

  - In an auto design report, you will add and edit expressions in the Edit Expression window. The Edit Expression window supports Microsoft Dynamics AX reports. The **Methods** category displays a list of data methods and built-in methods that are available for the report. A data method will appear in the list after it has been added to the AOT.

  - In a precision design report, you will add and edit expressions in the Expression dialog box. For information on when to use a precision design report, see [Considerations to Create a Report](considerations-for-creating-a-report.md).
    

    > [!TIP]
    > <P>To use the added support for data methods that are available in an auto design report, we recommend that you do the initial design with data methods in an auto design report and then convert the report to a precision design report.</P>



## Using a Data Method in an Expression

The following procedures describe how to use a data method in an expression in an auto design report and in a precision design report in Microsoft Visual Studio.

### To use a data method in an auto design report

1.  In Model Editor, you can access the Edit Expression window for any drop-down list that displays **\<Expression…\>**.
    
    Expand the drop-down list and then click **\<Expression…\>**.

2.  In the Edit Expression window, expand the **Methods** node, and then select **Data methods**.

3.  Select a data method and then click **Paste** to insert the value into the code section of the Edit Expression window.

4.  Type () parenthesis so that the data method expression resembles the following:
    
    \=DataMethodName()

5.  Click **OK**.

You can also type the value in the property field directly using the same syntax.

\=DataMethodName()

### To use a data method in a precision design report

1.  In SQL Report Designer, you can access the Expression dialog box for any property in a dialog box that displays the expression **(fx)** button or in a drop-down list that displays **\<Expression...\>**.
    
    Display the design surface. Right-click a report element and then click **Expression…**, or click the **(fx)** button.

2.  In the Expression dialog box, type the following in the code section:
    
    \=DataMethodName()

3.  Click **OK**.

You can also type the value in the property field directly using the same syntax.

\=\[DataMethodName\]()

For information about data methods, see [Report Data Method Overview](report-data-method-overview.md).

## See also

[Using Business Logic in Report Data Methods to Access Report Data](using-business-logic-in-report-data-methods-to-access-report-data.md)

[Working with Expressions](working-with-expressions.md)

