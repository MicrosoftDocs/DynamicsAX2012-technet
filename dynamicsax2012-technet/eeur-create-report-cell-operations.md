---
title: (EEUR) Create report cell operations
TOCTitle: (EEUR) Create report cell operations
ms:assetid: 5b0882c2-a10f-4e22-ae82-c9612173be0e
ms:mtpsurl: https://technet.microsoft.com/en-us/library/JJ910979(v=AX.60)
ms:contentKeyID: 52075298
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (EEUR) Create report cell operations 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the Russian Financial reports generator (FRG) to generate reports by using Microsoft Word and Microsoft Excel templates. Use the **Field setup** form to indicate how the value in each report cell is calculated. The values in the cells are calculated based on the line type that is selected in the **Line type** field. The following line types are available:

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Line type</p></th>
<th><p>Data source</p></th>
<th><p>Available voucher types</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>Transactions</strong></p></td>
<td><p>Ledger transactions</p></td>
<td><p><strong>Balance</strong>, <strong>Credit balance</strong>, <strong>Debit balance</strong>, <strong>Turnover</strong>, <strong>Credit activity</strong>, <strong>Debit activity</strong>, <strong>Turnover in correspondence</strong>, <strong>Turnover in correspondence credit</strong>, <strong>Turnover in correspondence debit</strong>, <strong>Active balance (debit)</strong>, and <strong>Passive balance (credit)</strong></p>
<div class="alert">

> [!NOTE]
> <P>The <STRONG>Turnover in correspondence</STRONG>, <STRONG>Turnover in correspondence credit</STRONG>, and <STRONG>Turnover in correspondence debit</STRONG> voucher types are available only to legal entities whose primary address is in Russia.</P>


</div>
<p></p></td>
</tr>
<tr class="even">
<td><p><strong>Budget</strong></p></td>
<td><p>Budget transactions</p></td>
<td><p><strong>Balance</strong>, <strong>Credit balance</strong>, <strong>Debit balance</strong>, <strong>Turnover</strong>, <strong>Credit activity</strong>, and <strong>Debit activity</strong></p>
<p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Register</strong></p></td>
<td><p>Register field that is specified in the <strong>Register field</strong> on the <strong>Tax registers</strong> tab in the <strong>Field setup</strong> form</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Constant</strong></p></td>
<td><p>Value that is specified in the <strong>Data</strong> field in the <strong>Field setup</strong> form</p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p><strong>Function query</strong></p></td>
<td><p>Numerical data from any table that is set up by using the <strong>Query wizard</strong></p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p><strong>Contractor</strong></p></td>
<td><p>Ledger transactions that are related to contractors</p></td>
<td><p><strong>Active balance (debit)</strong> and <strong>Passive balance (credit)</strong></p></td>
</tr>
<tr class="odd">
<td><p><strong>Fixed requisite</strong></p></td>
<td><p>Fixed requisite that is specified in the <strong>Fixed requisite</strong> field in the <strong>Field setup</strong> form</p></td>
<td><p></p></td>
</tr>
</tbody>
</table>



> [!NOTE]
> <P>The <STRONG>Register</STRONG>, <STRONG>Contractor</STRONG>, and <STRONG>Fixed requisite</STRONG> line types are available only for legal entities whose primary address is in Russia.</P>



One or more lines with amount calculation parameters can be created for each report cell. The lines are linked together with a mathematical operator. Use the following procedure to create report cell operations.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Financial reports generator**.

2.  Create or select a report line, and then click **Setup**.

3.  Create or select a report cell line, and then in the lower pane, click **Add** to create a line.

4.  In the **Operator** field, select the mathematical operator that is applied to the cell value.
    

    > [!NOTE]
    > <P>The <STRONG>Operator</STRONG> field is used to set up the mathematical sign for the amount that is exported to the cell, and is also used as a mathematical sign when you set up multi-line composite vouchers. <STRONG>Credit balance</STRONG>, <STRONG>Credit activity</STRONG>, and <STRONG>Turnover in correspondence credit</STRONG> voucher types use a minus sign (<STRONG>-</STRONG>).</P>



5.  In the **Line type** field, select the data source that is used to calculate the selected line. For more information, see [(EEUR) Field setup (form)](https://technet.microsoft.com/en-us/library/jj910976\(v=ax.60\)).

6.  If you selected **Constant** in the **Line type** field, in the **Data** field, enter the value to use for the calculation.

7.  In the **Type of operation** and **Balance type** fields, select a type of operation and a balance type. For more information, see [(EEUR) Field setup (form)](https://technet.microsoft.com/en-us/library/jj910976\(v=ax.60\)) and [(RUS) Field setup (form)](https://technet.microsoft.com/en-us/library/jj853197\(v=ax.60\)).
    

    > [!NOTE]
    > <P>The <STRONG>Balance type</STRONG> field is available only if you select <STRONG>Balance</STRONG>, <STRONG>Credit balance</STRONG>, <STRONG>Debit balance</STRONG>, <STRONG>Active balance (debit)</STRONG>, or <STRONG>Passive balance (credit)</STRONG> in the <STRONG>Type of operation</STRONG> field.</P>



8.  In the **Period** field, select the voucher calculation period.

9.  In the **Account interval** and **Account** fields, select whether the mathematical operator is applied to an **Account** or an **Interval**, and an account number. For more information, see [(EEUR) Field setup (form)](https://technet.microsoft.com/en-us/library/jj910976\(v=ax.60\)).
    

    > [!NOTE]
    > <P>The <STRONG>Account</STRONG> field is available only if you select <STRONG>Account</STRONG> in the <STRONG>Account interval</STRONG> field.</P>



10. In the **Offset interval** and **Corr. account** fields, select whether an **Account** or **Interval** is offset, and an account number.
    

    > [!NOTE]
    > <P>The <STRONG>Offset interval</STRONG> field is available only if you select <STRONG>Turnover in correspondence</STRONG>, <STRONG>Turnover in correspondence credit</STRONG>, and <STRONG>Turnover in correspondence debit</STRONG> in the <STRONG>Type of operation</STRONG> field.</P>



11. On the **General** tab, do the following:
    
      - In the **Budget model** field, select a budget model number.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Budget</STRONG> in the <STRONG>Data</STRONG> field.</P>

    
      - In the **Balance detail** field, select **Document**, **Agreement**, or **Contractor** to calculate active or passive balance.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Contractor</STRONG> in the <STRONG>Line type</STRONG> field.</P>



12. Do the following on the other tabs:
    
      - On the **Type of transactions** tab, in the **Transaction usage** field, select the type of transaction to calculate the cell value. For more information, see [(EEUR) Field setup (form)](https://technet.microsoft.com/en-us/library/jj910976\(v=ax.60\)).
        

        > [!NOTE]
        > <P>This tab is available only if you select <STRONG>Transactions</STRONG> in the <STRONG>Line type</STRONG> field.</P>

    
      - On the **Type of operation** tab, click **Add**, and then in the **Transaction type** field, select a transaction type.
    
      - On the **Operations/Tax** tab, click **Add**, and then in the **Posting layer** field, select a posting layer that has transactions to include in the report.
    
      - On the **Tax registers** tab, in the **Register code** and **Register field** fields, select a register number and a field. The data from the register field is used as the cell value.
        

        > [!NOTE]
        > <P>This tab is available only if you select <STRONG>Register</STRONG> in the <STRONG>Line type</STRONG> field</P>



13. On the **Financial dimensions** tab, do the following:
    
      - Click **Add**, and then in the **Reference** field, select a dimension name.
    
      - In the **From** and **To** fields, select the starting and ending codes for the dimension range for the transactions that are included in the report.

14. If you selected **Interval** in the **Account interval** or **Offset interval** field, do the following to indicate the account interval for the cell.
    
      - Click **Setup** \> **Account interval**.
    
      - Press CTRL+N to create a line, and then in the **From** and **To** fields on the **Account interval** and/or **Offset interval** tab, select the starting and ending ledger account numbers that are used in the calculation. Close the form.

15. Click **Setup** \> **Edit the query** to open the **Query wizard** form to set up query parameters to calculate cell values.
    

    > [!NOTE]
    > <P>The <STRONG>Edit the query</STRONG> button is available only if you select <STRONG>Function query</STRONG> in the <STRONG>Line type</STRONG> field.</P>



After you create the lines, you can arrange them in the correct order. Select a line, and then click **Up** or **Down** to move the selected line one position up or down.

## See also

[(EEUR) Account interval (form)](https://technet.microsoft.com/en-us/library/jj710790\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

