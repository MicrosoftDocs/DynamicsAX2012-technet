---
title: Design the rows and columns of a traditional financial statement
TOCTitle: Design the rows and columns of a traditional financial statement
ms:assetid: ef8dc67f-adcd-49f0-b0d9-3745162d3b09
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa551563(v=AX.60)
ms:contentKeyID: 44081061
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Design the rows and columns of a traditional financial statement [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

After you design the row structure of a traditional financial statement, you can design the rows and columns for the traditional financial statement. For more information, see [Design the row structure of a traditional financial statement](design-the-row-structure-of-a-traditional-financial-statement.md).


> [!NOTE]
> <P>This topic includes information about features that were added or changed for cumulative update 6 or later for Microsoft Dynamics AX 2012 R2. This information also applies to AX 2012 R3.</P>



To print financial statements, you can use Management Reporter, or you can use the traditional financial statements that are included with Microsoft Dynamics AX. For more information about how to print financial statements by using Management Reporter, see [Management Reporter for Microsoft Dynamics ERP](http://go.microsoft.com/fwlink/?linkid=324762).

The **Financial statement** form is available only when the **Financial statement (traditional)** configuration key is selected.

## Set up a financial statement

1.  Click **General ledger** \> **Setup** \> **Financial statement (traditional)** \> **Financial statement (traditional)**.

2.  Click **New**, and then enter a name and description for the traditional financial statement.
    

    > [!NOTE]
    > <P>For more information about the fields that are mentioned in this topic, see <A href="https://technet.microsoft.com/en-us/library/aa600912(v=ax.60)">Financial statement setup (form)</A>.</P>



3.  Continue creating the traditional financial statement by following the steps in the following sections.

## Design a row

Use the **Financial statement** form to design a row for a traditional financial statement. You can design a row either at the same time that you set up a traditional financial statement, or at another time.

1.  Click **General ledger** \> **Setup** \> **Financial statement (traditional)** \> **Financial statement (traditional)**.

2.  In the upper pane, select the traditional financial statement to design rows for.

3.  Click the **General** tab, and then select the primary dimension set to use on the traditional financial statement.

4.  To use a secondary row pattern, select a secondary dimension set.

5.  To insert a page break after each primary dimension set on the traditional financial statement, select the **Page break per primary dimension set** check box.

6.  On the **Setup** tab, you can select a row definition for the primary dimension set. If you selected a secondary dimension set, you can also select a row definition for the secondary dimension set.
    
    The dimension set and row definition combinations determine the information that is printed on the traditional financial statement.
    
    <table>
    <colgroup>
    <col style="width: 33%" />
    <col style="width: 33%" />
    <col style="width: 33%" />
    </colgroup>
    <thead>
    <tr class="header">
    <th><p>Dimension sets</p></th>
    <th><p>Row definitions</p></th>
    <th><p>Information that is printed on the traditional financial statement</p></th>
    </tr>
    </thead>
    <tbody>
    <tr class="odd">
    <td><p>Primary dimension set</p></td>
    <td><p>No row definition</p></td>
    <td><p>The primary dimension set, in no particular order</p></td>
    </tr>
    <tr class="even">
    <td><p>Primary and secondary dimension sets</p></td>
    <td><p>No row definition for the primary dimension set</p>
    <p>Row definition for the secondary dimension set</p></td>
    <td><p>The primary dimension set, in alphanumeric order</p>
    <p>The secondary dimension set, which is repeated for each occurrence of the primary dimension set</p></td>
    </tr>
    <tr class="odd">
    <td><p>Primary and secondary dimension sets</p></td>
    <td><p>Row definition for the primary dimension set</p>
    <p>No row definition for the secondary dimension set</p></td>
    <td><p>The primary dimension set, in the order of the rows in the primary dimension set</p>
    <p>The secondary dimension set, in alphanumeric order</p></td>
    </tr>
    <tr class="even">
    <td><p>Primary and secondary dimension sets</p></td>
    <td><p>Row definitions for the primary and secondary dimension sets</p></td>
    <td><p>All dimension sets, based on the row definition for the primary and secondary dimensions</p>
    <p>The secondary dimension set, which is repeated for each occurrence of the primary dimension set</p></td>
    </tr>
    </tbody>
    </table>


7.  Select the printing settings, and the default settings for the details and elements to print on the traditional financial statement, by selecting one or more of the following check boxes:
    
      - **Print range** – Print a description of the range before the traditional financial statement.
    
      - **Cover page** – Print a cover page for the traditional financial statement.
    
      - **Skip zero** – Exclude accounts or financial dimensions from the traditional financial statement if the balance of the account or financial dimension is 0 (zero).
    
      - **Header line** – Print header rows or header accounts.
    
      - **Transaction line** – Print details, elements, rows, or account numbers for transaction lines.
    
      - **Total line** – Print total rows, or both total rows and account numbers, for main accounts that have a main account type of **Total**.

## Design a column

Use the **Financial statement** form to design a column for a traditional financial statement. You can design a column either at the same time that you set up a traditional financial statement, or at another time.

Each column is defined by a column type. Some column types, such as **Primary dimension set code**, are used for naming purposes only. Some column types, such as **Current**, determine how information is printed. Other column types, such as **Calculation**, are used to calculate information.

1.  Click **General ledger** \> **Setup** \> **Financial statement (traditional)** \> **Financial statement (traditional)**.

2.  In the upper pane, select the traditional financial statement to design columns for.

3.  In the lower pane, click **Add** to add a line for the first column on the traditional financial statement. A column number is assigned automatically in the **Column** field.

4.  In the **Name** field, enter a name for the column. This name is displayed as the column header on the financial statement.

5.  In the **Column type** field, select the type of column. For more information about the column types, see [Financial statement setup (form)](https://technet.microsoft.com/en-us/library/aa600912\(v=ax.60\)).

6.  You can create additional column types, and then specify their order by clicking the **Up** and **Down** buttons.
    
    To specify criteria for accounts and financial dimensions for the selected column type, click **Select**.

7.  You can enter additional information for each column by using the fields on the **Setup**, **Formatting**, and **Transactions** tabs.

8.  For columns that have a column type of **Calculation**, enter the calculation expression on the **Calculation** tab.

After you set up all the rows and columns, you can generate the traditional financial statement. For more information, see [Generate, print, and export a traditional financial statement](generate-print-and-export-a-traditional-financial-statement.md).

## See also

[About traditional financial statements](about-traditional-financial-statements.md)

[Financial statement setup (form)](https://technet.microsoft.com/en-us/library/aa600912\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

