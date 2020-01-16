---
title: Design the row structure of a traditional financial statement
TOCTitle: Design the row structure of a traditional financial statement
ms:assetid: af59c513-1f9a-4a8b-ac16-ddd79623f429
ms:mtpsurl: https://technet.microsoft.com/library/Aa498632(v=AX.60)
ms:contentKeyID: 44081026
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Design the row structure of a traditional financial statement 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Use the **Row definition** form to design a row structure for a financial statement. You can use the same row structure more than one time.


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 6 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



To print financial statements, you can use Management Reporter, or you can use the traditional financial statements that are included with Microsoft Dynamics AX. For more information about how to print financial statements using Management Reporter, see [Management Reporter for Microsoft Dynamics ERP](https://go.microsoft.com/fwlink/?linkid=324762).

This form is available only when the **Financial statement (traditional)** configuration key is selected.

## Create a row definition

1.  Click **General ledger** \> **Setup** \> **Financial statement (traditional)** \> **Row definition**.

2.  Click **New** to create a row definition.

3.  In the **Row definition** field, enter a unique identifier for the row definition. For example, the identifier can link the row definition to a particular traditional financial statement.

4.  In the **Name** field, enter a descriptive name for the row definition. This name additionally describes the row structure.
    
    The **Depth** field displays the number of levels that the tree structure in the row structure designer contains. You cannot modify this field.

5.  In the **Financial dimension set** field, select the financial dimension set that defines the elements for this row definition.
    

    > [!NOTE]
    > <P>If your legal entity received a row definition from the consolidated legal entity, or from a country/region-specific cash flow template, import the row definition template. Click <STRONG>Template</STRONG> &gt; <STRONG>Import from a file</STRONG>, and then select the file to import. To transfer the structure from an XBRL definition, click <STRONG>Template</STRONG> &gt; <STRONG>Transfer from XBRL taxonomy</STRONG>. After you import the basic structure, you can add the data and accounts for your legal entity to the basic structure.</P>



6.  To design or view the row structure of the selected row definition, click **Structure designer**. For more information, see [Structure designer (form)](https://technet.microsoft.com/library/aa552297\(v=ax.60\)).

## Structure designer views

The structure designer has two views, the tree control view and the line view.

If you select the **Tree control** check box, the row definitions are displayed in a tree structure. When you design the traditional financial statement, you can drag financial dimensions to the tree structure. For information about how to design row structures by using this method, see the “Design the row structure by using the tree structure” section in this topic.

To view a list of values that you can select, double-click a row type in the tree structure, or click **Edit**.

If you clear the **Tree control** check box, you can view each row in the structure designer. For information about how to design row structures by using this method, see the “Design the row structure without using the tree structure” section in this topic.

## Design the row structure by using the tree structure

Use the **Structure designer** form to design the row structure of a row definition. For more information, see the field descriptions in [Structure designer (form)](https://technet.microsoft.com/library/aa552297\(v=ax.60\)).


> [!NOTE]
> <P>After a row definition line has been created, you cannot change the value in the <STRONG>Type</STRONG> field.</P>



1.  Click **General ledger** \> **Setup** \> **Financial statement (traditional)** \> **Row definition**. Select a row definition, and then click **Structure designer**.

2.  Select the **Tree control** check box to view the tree structure.

3.  Click **Create**.

4.  Enter a name and description for the row.
    
    By default, the **Print name** and **Print description** fields display the information that is entered in the **Row name** and **Row description** fields, respectively. To display different information, change the values in the **Print name** and **Print description** fields.

5.  Select the type of row. You can select among the following options:
    
      - **Dimension** – The row identifies financial dimension values, such as a main account or other financial dimension value, for each component of the row definition.
    
      - **Group** – The row can be used as the header for a group or subtotal, such as a header for a collection of accounts or dimension values.
    
      - **Structure** – The row identifies or refers to another row definition. Rows of this type are linked to branches in another row definition. Therefore, you can reuse substructures that you already set up for other traditional financial statements. For example, when you prepare a cash flow statement, you can reuse the row structure that was set up for the income statement.
    
      - **Calculation** – The row expresses a calculation that uses other rows. Calculation rows are usually created last, because the definition of a calculation row uses the position of other lines.
    
      - **Exception** – The row prints an exception report when the traditional financial statement is generated. This report displays missing or duplicate balances in the row definition. For example, a traditional financial statement that has an exception type of **Duplicate** lists element value combinations for which balances are present multiple times on the traditional financial statement.
    

    > [!NOTE]
    > <P>To prepare a row definition template for export, select <STRONG>Group</STRONG>, <STRONG>Calculation</STRONG>, or <STRONG>Exception</STRONG>.</P>



6.  On the **Designer** tab, select the row definition in the tree structure.

7.  Click **Edit** to display the **Financial dimensions** and **Structures** tabs in the rightmost pane.

8.  On the **Financial dimensions** tab, you can view the main accounts or the financial dimension values that are part of the primary dimension set that you selected for the row definition for the traditional financial statement.

9.  In the rightmost pane, select the main accounts or financial dimension values to use. Then drag the main accounts of financial dimension values to the item in the tree structure that contains them.
    
    You can also use the following methods to add rows to the tree structure:
    
      - Press Ctrl+N, and then click in another part of the tree to see the new row.
    
      - Position the pointer at the location in the tree where you want to insert an element, and then double-click a row in the rightmost pane.
    
      - Right-click the row above the location where you want to insert a row, and then click **Create**.

10. To modify a line in the tree structure, double-click the line. A new set of tabs is displayed in the rightmost pane.

11. In the rightmost pane, on the **Setup** tab, you can set up parameters for the layout of the traditional financial statement and the data that is printed on the traditional financial statement.
    
    For example, select the **Header** and **Subtotal** check boxes to print a header, sublevels, and a subtotal that rolls up the sublevel figures.
    

    > [!NOTE]
    > <P>In the <STRONG>Value</STRONG> field, you can use expressions to generate multiple authorized values. For example, you enter the expression p*. In this case, all departments that start with the letter P are listed in the tree structure. Select the <STRONG>Simulate</STRONG> check box to expand the nodes for the row definition in the tree structure.</P>



12. In the rightmost pane, on the **Special report** tab, define the format of the line, and specify the column field in which the row value is displayed on the traditional financial statement.

## Check the tree structure

After you design a row structure, you can check for errors and duplicates. Follow these steps in the **Structure designer** form.

1.  Select the **Simulate** check box to view all the values for the nodes in the tree structure.

2.  To identify duplicates, select the **Check** check box, and then select the **Simulate** check box. A search for duplicates is performed. Any duplicates that are found are identified by an icon.


> [!NOTE]
> <P>In simulation mode, you cannot make changes in the <STRONG>Structure designer</STRONG> form.</P>



When the row structure of the row definition is completed, you can prepare, view, and print a traditional financial statement by using the **Financial statement** form. Click **General ledger** \> **Reports** \> **Transactions** \> **Financial statement (traditional)**.

## Design the row structure without using the tree structure

Use the **Structure designer** form to design the row structure of a row definition.


> [!NOTE]
> <P>If you clear the <STRONG>Tree control</STRONG> check box, you can view, create, and format all the lines in a specific group by using a grid. Select the group row to create or format component rows for, and then click <STRONG>Sub-branches</STRONG>. You can create all the rows that define the group. You can also format all the rows consistently by selecting and clearing the fields on each line. In the tree control view, these fields are displayed on the <STRONG>Setup</STRONG> tab. When you create a sub-branch, you cannot return directly to the tree control view. However, the parent branch is indicated at the bottom of the grid. Therefore, if you have to return to the tree control view, first return to the parent level by closing the <STRONG>Structure designer</STRONG> form for the sub-branch. Then, from the top-level parent branch, you can return to the tree control view.</P>



1.  Click **General ledger** \> **Setup** \> **Financial statement (traditional)** \> **Row definition**. Select a row definition, and then click **Structure designer**.

2.  Clear the **Tree control** check box to view the row definition in a grid format.

3.  Press Ctrl+N to add a line.

4.  Enter values in the **Row name** and **Print name** fields.

5.  In the **Type** field for the row, select the type of row.

## Example: Create a cash flow statement

You design a cash flow statement that includes all data for your legal entity that is relevant to cash holdings and cash equivalents. You select how to include all relevant data, and then use the traditional financial statement functionality to create the cash flow statement.

Typically, a cash flow statement includes the following rows, most of which you create as rows that have a row type of **Group**.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Row</p></th>
<th><p>Description</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Net cash from operations</p></td>
<td><p>This row usually includes the net income for the legal entity.</p>
<p>You create a row of the <strong>Structure</strong> type that identifies the row definition for income statements for the legal entity. The row also identifies the row in this row definition that produces the net income.</p></td>
</tr>
<tr class="even">
<td><p>Net cash used for financing</p></td>
<td><p>In this row, you map the appropriate ledger accounts. You can further specify the structure by adding groups of intermediate row types, such as groups for common stock that has been issued, common stock that has been repurchased, and cash dividends for common stock.</p></td>
</tr>
<tr class="odd">
<td><p>Net cash from investments</p></td>
<td><p>In this row, you map the appropriate ledger accounts. You can further specify the structure by adding groups of intermediate row types.</p></td>
</tr>
<tr class="even">
<td><p>Net change in cash and equivalents</p></td>
<td><p>This row displays the sum of the three previous rows as a debit or credit.</p>
<p>You can add a <strong>Calculation</strong> row type that uses the previous rows as the arguments of a sum. Alternatively, you can add a group row type that is set up as a total, and that includes the previous lines as part of the group's total. In effect, the previous lines are rolled up to produce a total.</p></td>
</tr>
<tr class="odd">
<td><p>Effect of exchange rates on cash and equivalents</p></td>
<td><p>This row displays adjustments to unrealized, or open, customer transactions and vendor transactions as a debit or credit. Identify these adjustments by mapping the appropriate accounts.</p></td>
</tr>
<tr class="even">
<td><p>Cash and equivalents, beginning of period</p></td>
<td><p>This row displays information about cash and cash equivalents from cash flow statements from the previous period as a debit or credit.</p>
<p>You can select the ledger accounts that compose the cash flow statement. Then, in the rightmost pane, on the <strong>Setup</strong> tab, set the <strong>Type</strong> field to <strong>Opening</strong>. You might have to click <strong>Edit</strong> to display the <strong>Setup</strong> tab.</p>
<p>The balance from the previous period for the rows that have been defined is then obtained. Click <strong>Copy</strong> to adjust the attributes to match the requirements of the cash flow statement.</p></td>
</tr>
<tr class="odd">
<td><p>Cash and equivalents, end of period</p></td>
<td><p>This row displays the net change in cash and equivalents, the effect of exchange rates on cash and equivalents, and the cash and equivalents from the start of the period.</p>
<p>You can create a row of the <strong>Calculation</strong> type to perform a calculation of the previous rows. Alternatively, you can create a row of the <strong>Group</strong> type that is set up as a total. The previous rows are then inserted and rolled up under this row.</p></td>
</tr>
</tbody>
</table>


For all cash flow statements, each main account must be used only one time. Follow these steps to make sure that main accounts are not used more than one time.

1.  In the **Structure designer** form, in the tree control view, click the **Setup** tab.

2.  Select the **Indicate times used** check box. The **Times used** field appears on the grid in the rightmost pane. You can see whether an account or dimension has been used more than one time.
    

    > [!NOTE]
    > <P>To update the <STRONG>Times used</STRONG> field after you change the row structure, select the <STRONG>Simulate</STRONG> check box at the top of the form.</P>



## See also

[About traditional financial statements](about-traditional-financial-statements.md)

  


