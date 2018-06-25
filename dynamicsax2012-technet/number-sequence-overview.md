---
title: Number sequence overview
TOCTitle: Number sequence overview
ms:assetid: a2913331-a267-44db-94f9-f35ce3318796
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh209457(v=AX.60)
ms:contentKeyID: 36058801
ms.date: 05/02/2014
mtps_version: v=AX.60
---

# Number sequence overview [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Number sequences in Microsoft Dynamics AX are used to generate readable, unique identifiers for master data records and transaction records that require identifiers. A master data record or transaction record that requires an identifier is referred to as a reference.

Before you can create new records for a reference in Microsoft Dynamics AX, you must set up a number sequence and associate it with the reference. We recommend that you use the forms in **Organization administration** to set up number sequences. If module-specific settings are required, you can use the parameters form in a module to specify number sequences for the references in that module. For example, in **Accounts receivable** and **Accounts payable**, you can set up number sequence groups to allocate specific number sequences to specific customers or vendors.

When you set up a number sequence, you must specify a scope, which defines which organization uses the number sequence. The scope can be **Shared**, **Company**, **Legal entity**, or **Operating unit**. If you are using Microsoft Dynamics AX 2012 R3 or cumulative update 6 or later for AX 2012 R2, the scope **Operating unit type** is also available. Legal entity and company scopes can be combined with **Fiscal calendar period** to create even more specific number sequences.


> [!NOTE]
> <P>If you are using Microsoft Dynamics AX 2012 R3 or AX 2012 R2, the <STRONG>Company</STRONG> scope also includes virtual companies. You cannot use module-specific forms to set up number sequences for virtual companies. You must use the forms in <STRONG>Organization administration</STRONG> instead.</P>



Number sequence formats consist of segments. Number sequences with a scope other than **Shared** can contain segments that correspond to the scope. For example, a number sequence with a scope of **Legal entity** can contain a legal entity segment. By including a scope segment in the number sequence format, you can identify the scope of a particular record by looking at its number.


> [!IMPORTANT]
> <P>The available scopes depend on the reference that you are setting up a number sequence for. The <STRONG>Shared</STRONG> scope is available only for some references. To determine whether a reference can use a shared scope, select the area and reference in the <STRONG>Segment configuration</STRONG> form. (Click <STRONG>Organization administration</STRONG> &gt; <STRONG>Common</STRONG> &gt; <STRONG>Number sequences</STRONG> &gt; <STRONG>Segment configuration</STRONG>.) If a scope segment is listed under <STRONG>Segments</STRONG>, the selected reference cannot use the shared scope.</P>
> <P>A customization is required to change the scope for a reference. For more information about how to customize number sequences, see <A href="using-the-enhanced-number-sequence-framework-white-paper.md">Using the Enhanced Number Sequence Framework (White paper)</A>.</P>



In addition to segments that correspond to scopes, number sequence formats can contain **Constant** and **Alphanumeric** segments. A **Constant** segment contains a set of letters, numbers, or symbols that does not change. An **Alphanumeric** segment contains a set of letters or numbers that increment every time that a number is used. Use a number sign (\#) to represent incrementing numbers and an ampersand (&) to represent incrementing letters. For example, the format \#\#\#\#\#\_2014 creates the sequence 00001\_2014, 00002\_2014, and so on.

## Number sequence examples

The following examples show how to use segments to create number sequence formats. In particular, the examples demonstrate the effects of using scope segments.

## Expense report numbers

In the following example, expense report numbers are set up for the legal entity that is titled **CS**.

**Area**: **Travel and expense**

**Reference**: **Expense report number**

**Scope**: **Legal entity**

**Legal entity**: CS

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Segments</p></th>
<th><p>Segment type</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Segment 1</p></td>
<td><p>Legal entity</p></td>
<td><p>CS</p></td>
</tr>
<tr class="even">
<td><p>Segment 2</p></td>
<td><p>Constant</p></td>
<td><p>-EXPENSE-</p></td>
</tr>
<tr class="odd">
<td><p>Segment 3</p></td>
<td><p>Alphanumeric</p></td>
<td><p>####</p></td>
</tr>
</tbody>
</table>


**Example of formatted number**: CS-EXPENSE-0039

You can set up a similar number sequence format for other legal entities. For example, for a legal entity that is named **RW**, if you change only the value of the legal entity segment, the formatted number is RW-EXPENSE-0039. You can also change the whole number sequence format for other legal entities. For example, you can omit the legal entity scope segment to create a formatted number such as Exp-0001.

## Sales order numbers

In the following example, sales order numbers are set up for the company ID **CEU**.

**Area**: **Sales**

**Reference**: **Sales order**

**Scope**: **Company**

**Company**: CEU

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Segments</p></th>
<th><p>Segment type</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Segment 1</p></td>
<td><p>Constant</p></td>
<td><p>SO-</p></td>
</tr>
<tr class="even">
<td><p>Segment 2</p></td>
<td><p>Alphanumeric</p></td>
<td><p>####</p></td>
</tr>
</tbody>
</table>


**Example of formatted number**: SO-0029

Even though a scope segment is not included in the format, numbering restarts for each company ID. If you use the same format for all company IDs, the same numbers are used in each company. For example, sales order number SO-0029 is used in each company. You can also change the whole number sequence format for other company IDs.

## Purchase requisition numbers

In the following example, purchase requisition numbers are organization-wide.

**Area**: **Purchase**

**Reference**: **Purchase requisition**

**Scope**: **Shared**

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Segments</p></th>
<th><p>Segment type</p></th>
<th><p>Value</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Segment 1</p></td>
<td><p>Constant</p></td>
<td><p>Req</p></td>
</tr>
<tr class="even">
<td><p>Segment 2</p></td>
<td><p>Alphanumeric</p></td>
<td><p>####</p></td>
</tr>
</tbody>
</table>


**Example of formatted number**: Req0052

Because the scope is **Shared**, the number sequence format is used across the organization. You cannot set up different number sequence formats for different parts of the organization.

## Performance considerations for number sequences

Consider the following information about how the configuration of number sequences can affect system performance before you set up number sequences.

## Continuous and non-continuous number sequences

Number sequences can be continuous or non-continuous. A continuous number sequence does not skip any numbers, but numbers may not be used sequentially. Numbers from a non-continuous number sequence are used sequentially, but the number sequence may skip numbers. For example, if a user cancels a transaction, a number is generated, but not used. In a continuous number sequence, that number is recycled later. In a non-continuous number sequence, the number is not used.

Continuous number sequences are typically required for external documents, such as purchase orders, sales orders, and invoices. However, continuous number sequences can adversely affect system response times because the system must request a number from the database every time that a new document or record is created.

If you use a non-continuous number sequence, you can enable **Preallocation** on the **Performance** FastTab of the **Number sequences** form. When you specify a quantity of numbers to preallocate, the system selects those numbers and stores them in memory. New numbers are requested from the database only after the preallocated quantity has been used.

Unless there is a regulatory requirement that you use continuous number sequences, we recommend that you use non-continuous number sequences for better performance.

## Automatic cleanup of number sequences

In case of a power failure, an application error, or other unexpected failure, the system cannot recycle numbers automatically for continuous number sequences. You can run the cleanup process manually or automatically to recover the lost numbers.

Carefully consider server usage when you plan the cleanup process. We recommend that you perform the cleanup as a batch job during non-peak hours.

## See also

[Number sequences (form)](https://technet.microsoft.com/en-us/library/hh209531\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

