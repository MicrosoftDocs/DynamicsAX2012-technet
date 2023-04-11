---
title: (RUS) Set up the functions directory for electronic reporting
TOCTitle: (RUS) Set up the functions directory for electronic reporting
ms:assetid: a4ea6b5e-f7da-4a85-a21d-2477417fff98
ms:mtpsurl: https://technet.microsoft.com/library/JJ677638(v=AX.60)
ms:contentKeyID: 49384941
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- reporting
- functions
- electronic reporting
- functions directory
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up the functions directory for electronic reporting 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the functions directory to create and update functional queries, which are used to calculate requisites based on data from databases. You can use configured functions to create values for fixed requisites.

The fixed requisite values are calculated based on the operator and line type that are selected in the **Operator** and **Line type** fields in the **Query function setup** form. For a **Constant** line type, when you create two consecutive lines that have numeric values, an arithmetic operation is performed, and the value is displayed in the cell. If one of the lines is a string, a line is created.

## Example

For the values in the following table, the following line is created: 2500Rubles500Rubles900Rubles.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p><strong>Operator</strong></p></th>
<th><p><strong>Line type</strong></p></th>
<th><p><strong>Data</strong></p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><strong>+</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>50</p></td>
</tr>
<tr class="even">
<td><p><strong>*</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>50</p></td>
</tr>
<tr class="odd">
<td><p><strong>/</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>Rubles</p></td>
</tr>
<tr class="even">
<td><p><strong>+</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>500</p></td>
</tr>
<tr class="odd">
<td><p><strong>+</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>Rubles</p></td>
</tr>
<tr class="even">
<td><p><strong>+</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>300</p></td>
</tr>
<tr class="odd">
<td><p><strong>*</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>3</p></td>
</tr>
<tr class="even">
<td><p><strong>+</strong></p></td>
<td><p><strong>Constant</strong></p></td>
<td><p>Rubles</p></td>
</tr>
</tbody>
</table>


Use the following procedure to set up the functions directory for electronic reporting.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Functions**.

2.  Click **New**, and then in the **Function** and **Name** fields, enter an identification number and a name for the function.

3.  Click **Setup**, and then click **New** to create a query function.

4.  In the **Operator** field, select the mathematical sign to apply to the requisite value.
    

    > [!NOTE]
    > <P>The <STRONG>Operator</STRONG> field is used to set up the mathematical sign for the amount that is applied to the requisite value. The mathematical sign that you select in this field is also used when you set up multi-line composite vouchers. The <STRONG>Credit balance</STRONG>, <STRONG>Credit activity</STRONG>, and <STRONG>Turnover in correspondence credit</STRONG> voucher types use a minus sign (-).</P>



5.  In the **Line type** field, select the data source that is used to calculate the requisite value.

6.  On the **Type of transactions** tab, do the following:
    
      - In the **Type of operation** field, select the type of operation. For more information, see [(RUS) Query function setup (form)](https://technet.microsoft.com/library/jj923571\(v=ax.60\)).
    
      - In the **Balance type** field, select a balance type.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Balance</STRONG>, <STRONG>Credit balance</STRONG>, <STRONG>Debit balance</STRONG>, <STRONG>Active balance (debit)</STRONG>, or <STRONG>Passive balance (credit)</STRONG> in the <STRONG>Type of operation</STRONG> field.</P>

    
      - In the **Period** field, select the voucher calculation period.
    
      - In the **Account interval** and **Account** fields, select whether the mathematical operator is applied to an **Account** or an **Interval**, and an account number.
        

        > [!NOTE]
        > <P>The <STRONG>Account</STRONG> field is available only if you select <STRONG>Account</STRONG> in the <STRONG>Account interval</STRONG> field.</P>

    
      - In the **Offset interval** field, select whether an **Account** or **Interval** is offset.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Turnover in correspondence</STRONG>, <STRONG>Turnover in correspondence credit</STRONG>, or <STRONG>Turnover in correspondence debit</STRONG> in the <STRONG>Type of operation</STRONG> field.</P>

    
      - In the **Offset account** field, select an account number.
        

        > [!NOTE]
        > <P>This field is available only if you select <STRONG>Account</STRONG> in the <STRONG>Offset interval</STRONG> field.</P>

    
      - In the **Transaction usage** field, select the rule for calculating the requisite value.

7.  On the **Operations/Tax** tab, press CTRL+N to create a line, and then in the **Posting layer** field, select the posting layer that has transactions to include on the report.

8.  On the **Type of operation** tab, press CTRL+N to create a line, and then in the **Transaction type** field, select a transaction type.

9.  On the **Financial dimensions** tab, do the following:
    
      - Click **Add** to create a line, and then the **Reference** field, select a dimension type.
    
      - In the **From** and **To** fields, select the starting and ending codes for the dimension range for the transactions that are included on the report.

10. Do the following on the other tabs:
    
      - On the **Budget** tab, in the **Budget model** field, select a budget model number.
        

        > [!NOTE]
        > <P>This tab is available only if you select <STRONG>Budget</STRONG> in the <STRONG>Line type</STRONG> field.</P>

    
      - On the **Tax registers** tab, in the **Register code** and **Register field** fields, select a register number and a field. The data from the register field is used as the cell value.
        

        > [!NOTE]
        > <P>This tab is available only if you select <STRONG>Register</STRONG> in the <STRONG>Line type</STRONG> field.</P>

    
      - On the **Constant** tab, in the **Data** field, enter the value that is used in the calculation. The constant value can be a number or a line.
        

        > [!NOTE]
        > <P>This tab is available only if you select <STRONG>Constant</STRONG> in the <STRONG>Line type</STRONG> field.</P>

    
      - On the **Contractor** tab, in the **Balance detail** field, select an option to indicate whether the balance is from a document, agreement, or contractor.
        

        > [!NOTE]
        > <P>This tab is available only if you select <STRONG>Contractor</STRONG> in the <STRONG>Line type</STRONG> field.</P>

    
      - On the **Requisite** tab, in the **Fixed requisite** field, select a requisite for the report.
        

        > [!NOTE]
        > <P>This tab is available only if you select <STRONG>Fixed requisite</STRONG> in the <STRONG>Line type</STRONG> field.</P>



11. If you selected **Interval** in the **Account interval** or **Offset interval** field, do the following to indicate the account interval for the cell.
    
      - Click **Setup** \> **Account interval**.
    
      - Press CTRL+N to create a line, and then in the **From** and **To** fields on the **Account interval** and/or **Offset interval** tab, select the starting and ending ledger account numbers that are used in the calculation. Close the form.

12. If you selected **Function query** in the **Line type** field, click **Edit the query** to open the **Query wizard** form. You can use this form to set up query parameters to calculate cell values.
    

    > [!NOTE]
    > <P>The <STRONG>Edit the query</STRONG> button is available only if you select <STRONG>Function query</STRONG> in the <STRONG>Line type</STRONG> field.</P>



After you create the lines, you can arrange them in the correct order. Select a line, and then click **Up** or **Down** to move the selected line one position up or down.

## See also

[(RUS) Functions (form)](https://technet.microsoft.com/library/jj710703\(v=ax.60\))

[(RUS) Query function setup (form)](https://technet.microsoft.com/library/jj923571\(v=ax.60\))

[(EEUR) Account interval (form)](https://technet.microsoft.com/library/jj710790\(v=ax.60\))

[(EEUR) Query wizard (form)](https://technet.microsoft.com/library/jj710772\(v=ax.60\))

  


