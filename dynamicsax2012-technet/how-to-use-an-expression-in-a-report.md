---
title: 'How to: Use an Expression in a Report'
TOCTitle: 'How to: Use an Expression in a Report'
ms:assetid: d7c98d1f-d515-4821-8e49-a95781a350d8
ms:mtpsurl: https://technet.microsoft.com/library/Hh533449(v=AX.60)
ms:contentKeyID: 39056465
author: Khairunj
ms.date: 11/07/2012
mtps_version: v=AX.60
---

# How to: Use an Expression in a Report 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Expressions are used throughout a report definition to control content and to format the data in a report. The following steps describe how to use the Edit Expression window to write an expression for a report design data element.

### To write an expression for a data element

1.  In Model Editor, expand the node for the report, and then expand the **Designs** node.

2.  Expand the node for the auto design that you want to work with, and then expand the node for the data region.

3.  Select the data element for which you want to write an expression. You can select a data element under **Groupings**, **Sorting**, **Filters**, or **Data**.

4.  Some data elements, such as Filters, have an **Expression** property that can have its value set using the Edit Expression window. Other data elements have properties like **Sort By** that can also have their value set with the Edit Expression window. When a property has the **\<Expression…\>** choice in its list of predefined values, you can choose that item to open the Edit Expression window and create an expression for the property value. In the Properties window, select the **Expression** or **Sort By** property. Click the drop-down list and then select **\<Expression…\>**. The Edit Expression window opens with the current expression for the element. If no expression exists, it will display an equal sign (=).

5.  Select items from the various categories that you want to add to the expression, and then click **Paste**. You can also double-click an item to add it to an expression. A wavy red underline indicates a syntax error. Hover over the underlined text to see the error message. When you have enter an item name followed by a punctuation separator (such as a period or exclamation mark), you will see a drop-down list of available properties, members, or methods. From the drop-down list, you can type the first few characters followed by a tab to automatically complete the selection. This makes it easier to write expressions that include field names or properties.
    
    An example of a complex expression that is used for the ExceedAmount field on the CustBalanceList report is: =IIF(Fields\!CreditMax.Value=0 or Fields\!CreditMax.Value \> Fields\!AmountMST.Value ,cdbl(0), cdbl(Fields\!AmountMST.Value-Fields\!CreditMax.Value))
    
    In this example, the exceeded amount will be zero if there is no maximum credit or if the amount in MST is less than the maximum credit limit. If that is not the case, then the amount exceeded is the amount in MST minus the maximum credit.

To see evaluated expression values in a report, select an element in the report design, and then click **Preview** to preview the report. When the report runs, the report processor evaluates the expressions and substitutes the expression results for the property values.

## See also

[Edit Expression Overview](edit-expression-overview.md)

[How to: Use an Expression in a Report Parameter](how-to-use-an-expression-in-a-report-parameter.md)

