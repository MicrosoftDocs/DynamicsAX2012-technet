---
title: About print management originals, copies, and settings
TOCTitle: About print management originals, copies, and settings
ms:assetid: 80a79cb6-b535-4043-8b19-5155690b39d4
ms:mtpsurl: https://technet.microsoft.com/library/Dd309731(v=AX.60)
ms:contentKeyID: 36058352
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- print
- copies
- footer
- original
- document
- copy
- conditional
- print management
- printing
- footers
- management
- originals
- printer
- printers
- setting
- carbon
- multipart
- multiple part
- multi-part
audience: Application User
ms.search.region: Global
---

# About print management originals, copies, and settings 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can use print management to print one original and many copies of a source document that is produced as part of a process. This is like using preprinted, multiple-part forms in manual accounting systems. You use footer text to distinguish the original from the copies. For example, for a sales order packing slip, you can set up footer text to print "Original" at the bottom of the original, "Customer copy" at the bottom of the first copy, and "Warehouse copy" at the bottom of the second copy.

An original or copy record contains the information that is used by print management to print the document. The record that is used to print a document determines the footer text for the document, which printer to use, and how many copies to print. For example, to print three pages for the sales order packing slip, each with different footer text, you would set up an original record and two copy records.

You can additionally customize the document output by using conditional settings that are applied based on the results of a query. For example, one copy might be sufficient for most customers, but you might want to print an extra customer copy for a certain set of customers. You can set up an additional copy record and a conditional setting with an associated query for the customer accounts that should have the additional copy printed, such as customer accounts 4000 through 4020, and then define "Customer copy 2" as the footer text for the extra copy.

If you confirm sales orders for customer accounts 4010 and 4025 with the original or copy records and conditional setting defined earlier in this topic, you will see the following results.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Customer</p></th>
<th><p>Documents that are printed</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Customer 4010</p></td>
<td><p>Original</p>
<p>Customer copy</p>
<p>Customer copy 2 (because the customer account falls in the query results for the setting)</p>
<p>Warehouse copy</p></td>
</tr>
<tr class="even">
<td><p>Customer 4025</p></td>
<td><p>Original</p>
<p>Customer copy</p>
<p>Warehouse copy</p></td>
</tr>
</tbody>
</table>


While conditional settings and queries provide flexibility in your print management settings, complex queries or many conditional settings can affect posting performance.


> [!NOTE]
> <P>Print management settings can also be used when reprinting documents. Click <STRONG>Preview/Print</STRONG> &gt; <STRONG>Use print management</STRONG> to reprint a document by using the effective print management settings.</P>



## See also

[About print management document types and modules](about-print-management-document-types-and-modules.md)

[About print management processing](about-print-management-processing.md)

[Print management setup (form)](https://technet.microsoft.com/library/hh209383\(v=ax.60\))

  


