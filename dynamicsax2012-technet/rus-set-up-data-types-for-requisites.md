---
title: (RUS) Set up data types for requisites
TOCTitle: (RUS) Set up data types for requisites
ms:assetid: c315aa00-5493-43a7-a96f-56fc4585c442
ms:mtpsurl: https://technet.microsoft.com/library/JJ677691(v=AX.60)
ms:contentKeyID: 49384991
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- data types
- requisites
- set up data types
audience: Application User
ms.search.region: Russia
---

# (RUS) Set up data types for requisites 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

You can use the data type directory to store and manage a list of all possible data types for requisites that are available in the electronic reporting templates. Data from this directory is used to verify report data. Data types in a directory are created automatically when you refresh the structure in the **Document templates** form, or when you transfer settings from one template to another. You can also create a data type manually.

You can use the following data types to create requisites.

<table>
<colgroup>
<col style="width: 33%" />
<col style="width: 33%" />
<col style="width: 33%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Data type</p></th>
<th><p>Description</p></th>
<th><p>Valid values</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>string</p></td>
<td><p>Line</p></td>
<td><p>Any line is valid.</p></td>
</tr>
<tr class="even">
<td><p>boolean</p></td>
<td><p>Boolean</p></td>
<td><p>true, false, 1, and 0</p></td>
</tr>
<tr class="odd">
<td><p>decimal</p></td>
<td><p>Decimal</p></td>
<td><p>Integers and fractions</p></td>
</tr>
<tr class="even">
<td><p>integer</p></td>
<td><p>Integer</p></td>
<td><p>Only integers</p></td>
</tr>
<tr class="odd">
<td><p>long</p></td>
<td><p>Integer</p></td>
<td><p>–9223372036854775807 to 9223372036854775808</p></td>
</tr>
<tr class="even">
<td><p>int</p></td>
<td><p>Integer</p></td>
<td><p>–2147483648 to 2147483647</p></td>
</tr>
<tr class="odd">
<td><p>short</p></td>
<td><p>Integer</p></td>
<td><p>–32768 to 32767</p></td>
</tr>
<tr class="even">
<td><p>byte</p></td>
<td><p>Integer</p></td>
<td><p>–128 to 127</p></td>
</tr>
<tr class="odd">
<td><p>nonPositiveInteger</p></td>
<td><p>Integer</p></td>
<td><p>Any value that is less than or equal to 0 (zero).</p></td>
</tr>
<tr class="even">
<td><p>nonNegativeInteger</p></td>
<td><p>Integer</p></td>
<td><p>Any value that is greater than or equal to 0 (zero).</p></td>
</tr>
<tr class="odd">
<td><p>unsignedLong</p></td>
<td><p>Integer</p></td>
<td><p>0 to 18446744073709551615</p></td>
</tr>
<tr class="even">
<td><p>positiveInteger</p></td>
<td><p>Integer</p></td>
<td><p>Any value that is greater than 0 (zero).</p></td>
</tr>
<tr class="odd">
<td><p>unsignedInt</p></td>
<td><p>Integer</p></td>
<td><p>0 to 4294967295</p></td>
</tr>
<tr class="even">
<td><p>unsignedShort</p></td>
<td><p>Integer</p></td>
<td><p>0 to 65535</p></td>
</tr>
<tr class="odd">
<td><p>unsignedByte</p></td>
<td><p>Integer</p></td>
<td><p>0 to 255</p></td>
</tr>
<tr class="even">
<td><p>float</p></td>
<td><p>Decimal</p></td>
<td><p>Integers and fractions</p></td>
</tr>
<tr class="odd">
<td><p>double</p></td>
<td><p>Decimal</p></td>
<td><p>Integers and fractions</p></td>
</tr>
<tr class="even">
<td><p>dateTime</p></td>
<td><p>Date and time</p></td>
<td><p>Values must be in the following format: '-'? yyyy '-' mm '-' dd 'T' hh ':' mm ':' ss ('.' s+)? (zzzzzz)?</p>
<ul>
<li><p>'-'? yyyy – The year expressed as four characters and a minus sign, if a minus sign is required.</p></li>
<li><p>'-' – The delimiter between date value parts.</p></li>
<li><p>mm – The month, expressed as two characters.</p></li>
<li><p>dd – The day, expressed as two characters.</p></li>
<li><p>T – The delimiter between the date and time.</p></li>
<li><p>hh – The hours, expressed as two characters.</p></li>
<li><p>':' – The delimiter between time value parts.</p></li>
<li><p>mm – The minutes, expressed as two characters.</p></li>
<li><p>ss – The seconds, expressed as two characters.</p></li>
<li><p>('.' s+)? – The milliseconds. This value is optional.</p></li>
<li><p>(zzzzzz)? – The time zone code. This value is optional.</p></li>
</ul>
<p>Example: 1999-01-01T13:20:21.12</p></td>
</tr>
<tr class="odd">
<td><p>time</p></td>
<td><p>Time</p></td>
<td><p>The value must be in the following format: hh:mm:ss.sss</p>
<ul>
<li><p>hh – The hours, expressed as two characters.</p></li>
<li><p>mm – The minutes, expressed as two characters.</p></li>
<li><p>ss – The seconds, expressed as two characters.</p></li>
<li><p>sss – The milliseconds, expressed as three characters.</p></li>
</ul>
<p>Example: 13:20:21.233</p></td>
</tr>
<tr class="even">
<td><p>date</p></td>
<td><p>Day</p></td>
<td><p>The value must be in the following format: '-'? yyyy '-' mm '-' dd zzzzzz?</p>
<ul>
<li><p>'-'? yyyy ' – The year expressed as four characters and a minus sign, if a minus sign is required.</p></li>
<li><p>mm – The month, expressed as two characters.</p></li>
<li><p>dd – The day, expressed as two characters.</p></li>
<li><p>zzzzzz? – The time zone code. This value is optional.</p></li>
</ul></td>
</tr>
<tr class="odd">
<td><p>gYearMonth</p></td>
<td><p>Year and month</p></td>
<td><p>The value must be in the following format: CCYY-MM</p>
<ul>
<li><p>CCYY– The year, expressed as four characters.</p></li>
<li><p>MM – The month, expressed as two characters.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>gYear</p></td>
<td><p>Year</p></td>
<td><p>0001 to 9999</p></td>
</tr>
<tr class="odd">
<td><p>gMonthDay</p></td>
<td><p>Day of the month</p></td>
<td><p>The value must be in the following format: mm-dd zzzzzz?</p>
<ul>
<li><p>mm – The month, expressed as two characters.</p></li>
<li><p>dd – The day, expressed as two characters.</p></li>
<li><p>zzzzzz? – The time zone code. This value is optional.</p></li>
</ul></td>
</tr>
<tr class="even">
<td><p>gDay</p></td>
<td><p>Day</p></td>
<td><p>The value must be in the following format: dd, where dd is the day, expressed as two characters.</p></td>
</tr>
<tr class="odd">
<td><p>gMonth</p></td>
<td><p>Month</p></td>
<td><p>The value must be in the following format: mm, where mm is the month, expressed as two characters.</p>
<p></p></td>
</tr>
<tr class="even">
<td><p>anySimpleType</p></td>
<td><p>Built-in data type</p></td>
<td><p>Any value</p></td>
</tr>
</tbody>
</table>


Use the following procedure to set up data types for requisites that are used in electronic reporting.

1.  Click **General ledger** \> **Setup** \> **Financial reports generator** \> **Data types**.

2.  Click **New**, and then, in the **Extended data type** and **Description** fields, enter an identification number and a name for the extended data type.

3.  In the **Base type** field, select the base data type that is used in the XML schema definition (XSD).
    

    > [!NOTE]
    > <P>The XSD schema is the requisite that is used on the electronic report that uses the XML format for the elements.</P>



4.  To create the data type automatically, select the **Automatic creation** check box. In this case, you do not have to complete steps 5 through 10.
    
    –or–
    
    To create the data type manually, clear the **Automatic creation** check box, and then follow steps 5 through 10.

5.  If you selected **string** in the **Base type** field, follow these steps:
    
      - In the **Minimum length** and **Maximum length** fields, enter the minimum and maximum lengths for the requisite.
    
      - In the **String length**, enter the string length of the requisite.

6.  If you selected **integer** in the **Base type** field, follow these steps:
    
      - In the **Number of digits** field, enter the maximum number of digits for the number.
    
      - In the **Number of decimals**, enter the number of decimal places for the number.
    
      - In the **Min exclusive** field, enter the minimum value of the requisite.
    
      - In the **Max exclusive** field, enter the maximum value of the requisite. For example, if the maximum value is 10, the valid value is less than 10.
    
      - In the **Min inclusive** field, enter the minimum value of the requisite.
    
      - In the **Max inclusive** field, enter the maximum value of the requisite. For example, if the maximum value is 10, the valid value is less than or equal to 10.

7.  On the **Templates** FastTab, click **Add** to create a line.

8.  In the **Template** field, enter the template that defines the valid sequence of characters and numbers in a value.

9.  On the **Values** FastTab, click **Add** to create a line.

10. In the **Value** field, enter a value for the selected base type.

## See also

[(RUS) Extended data types (form)](https://technet.microsoft.com/library/jj710678\(v=ax.60\))

[(RUS) Document templates (form)](https://technet.microsoft.com/library/jj923585\(v=ax.60\))

  


