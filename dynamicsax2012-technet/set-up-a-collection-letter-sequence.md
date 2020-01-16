---
title: Set up a collection letter sequence
TOCTitle: Set up a collection letter sequence
ms:assetid: bbb16492-3816-4e2d-be84-60f6aaba8132
ms:mtpsurl: https://technet.microsoft.com/library/Aa498861(v=AX.60)
ms:contentKeyID: 36655948
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
audience: Application User
ms.search.region: Global
---

# Set up a collection letter sequence 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create and manage collection letter sequences that define the collections process. Each collection letter in a sequence can have the following characteristics:

  - Custom text for the letter

  - A specified number of days that the payment must be overdue before the letter can be generated

  - A fee amount that is associated with the collection of the overdue amount

  - An account where the fee amount is posted

<!-- end list -->

1.  Click **Accounts receivable** \> **Setup** \> **Collections** \> **Collection letter**.

2.  Click **New** to create a line in the upper pane, and then enter a name in the **Collection letter sequence** field.

3.  In the line that is created automatically in the lower pane, select a code in the **Collection letter code** list. The starting point is **Collection letter 1**.
    

    > [!NOTE]
    > <P>The first collection letter is created according to the due date on the invoice, the value that you enter for the grace period in the <STRONG>Days</STRONG> field on this line, and other information that you enter on this line.</P>



4.  Enter information in the appropriate fields on the line, such as the fee amount, the number of days before the collection letter is generated, and the account to which the fee is posted. The currency of the fee is always the customer's default currency, which is independent of the invoice currency.

5.  Click **Add** to create a second line in the lower pane, select **Collection letter 2** in the **Collection letter code** field, and enter information in the appropriate fields.

6.  Continue until you have defined all the collection letter codes of the collection letter sequence that is selected in the upper pane. You can create up to five collection letter codes for a collection letter sequence. The collection letters that you create for each sequence are used by only that sequence.

7.  Before you create collection letters from the collection letter sequences, determine how to handle the posting and the printing of collection letters. For more information, see [Control posting and printing of collection letters](control-posting-and-printing-of-collection-letters.md).

## Examples of collection letter sequences

This table illustrates the possible collection letter codes for sample collection letter sequences.

<table>
<colgroup>
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
<col style="width: 25%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Sequence 1</p></th>
<th><p>Sequence 2</p></th>
<th><p>Sequence 3</p></th>
<th><p>Sequence 4</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Collection letter 1 for sequence 1</p></td>
<td><p>Collection letter 1 for sequence 2</p></td>
<td><p>Collection letter 1 for sequence 3</p></td>
<td><p>Collection letter 1 for sequence 4</p></td>
</tr>
<tr class="even">
<td><p>Collection letter 2 for sequence 1</p></td>
<td><p>Collection letter 2 for sequence 2</p></td>
<td><p>Collection letter 2 for sequence 3</p></td>
<td><p>Collection letter warning about collection agency for sequence 4</p></td>
</tr>
<tr class="odd">
<td><p>Collection letter warning about collection agency for sequence 1</p></td>
<td><p>Collection letter 3 for sequence 2</p></td>
<td><p>Collection letter warning about collection agency for sequence 3</p></td>
<td><p></p></td>
</tr>
<tr class="even">
<td><p></p></td>
<td><p>Collection letter 4 for sequence 2</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
<tr class="odd">
<td><p></p></td>
<td><p>Collection letter warning about collection agency for sequence 2</p></td>
<td><p></p></td>
<td><p></p></td>
</tr>
</tbody>
</table>


## See also

[Collection letter (form)](https://technet.microsoft.com/library/aa620428\(v=ax.60\))

[Create collection letters](create-collection-letters.md)

  


