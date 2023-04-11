---
title: About nonconformance
TOCTitle: About nonconformance
ms:assetid: 94400adb-6f78-445f-a0aa-5434d0a1f9d7
ms:mtpsurl: https://technet.microsoft.com/library/Gg232202(v=AX.60)
ms:contentKeyID: 36058598
author: tonyafehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- nonconformance
- quality problem
- problem source
audience: Application User
ms.search.region: Global
---

# About nonconformance 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A nonconformance describes an item that has a quality problem, where the descriptive information includes the source and type of problem. The problem source is termed a “nonconformance type.”

You assign a nonconformance type and its detailed source information, and you assign the associated problem type when you create a nonconformance. There are five nonconformance types, and the detailed source information varies by type, as described in the following table. The detailed source information is optional, and a nonconformance can be created without detailed source information.

<table>
<colgroup>
<col style="width: 50%" />
<col style="width: 50%" />
</colgroup>
<thead>
<tr class="header">
<th><p>Nonconformance type</p></th>
<th><p>Detailed source information</p></th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p>Customer</p></td>
<td><p>Customer account number, sales order number, or a lot number of a sales order transaction. For example, the nonconformance could relate to a specific sales order shipment or to customer feedback about product quality.</p></td>
</tr>
<tr class="even">
<td><p>Service request</p></td>
<td><p>Customer account number, sales order number, or a lot number of a sales order transaction. For example, the nonconformance could relate to a specific sales order shipment or to a customer's complaint about item quality.</p></td>
</tr>
<tr class="odd">
<td><p>Vendor</p></td>
<td><p>Vendor account number, purchase order number, or a lot number of a purchase order transaction. For example, the nonconformance could relate to a purchase order receipt or to a vendor's concern about a part that it supplies.</p></td>
</tr>
<tr class="even">
<td><p>Production</p></td>
<td><p>Production order number or a lot number of a production order transaction. For example, the nonconformance could relate to a specific batch that was produced.</p></td>
</tr>
<tr class="odd">
<td><p>Internal</p></td>
<td><p>Quality-order number or a lot number of a quality-order transaction. For example, the nonconformance could relate to the tests that are performed as part of a quality order or to an employee's concern about product quality.</p></td>
</tr>
</tbody>
</table>


The user-definable problem types provide a classification of quality problems for each nonconformance type. For example, the problem types for service requests could reflect a classification of customer complaints, whereas the problem types for an internal nonconformance could represent a classification of defect codes. A problem type can be authorized for one or more nonconformance types, as defined in the **Non conformance types** form. For example, the problem type that concerns a defect code could apply to all nonconformance types. You can change the nonconformance type that is assigned to a nonconformance, and this might require changing the problem type to a valid value for the new nonconformance type.

A nonconformance is initially created with an approval status of new, which indicates that it represents a request for action. You can approve or refuse a nonconformance (which changes the approval status to approved or refused) to indicate that you will or will not take action on the nonconformance. You can also close a nonconformance (as indicated by a separate check box) to indicate that you are finished with it, or reopen a nonconformance to indicate that additional consideration is required.

Comments can be entered for a nonconformance by using the document handling capabilities. It is generally helpful to define a unique document type about nonconformances (by using the **Document type** form), so that you can enter notes and comments for the unique document type. Use the **Report setup** form to define your policy about printing comments for the unique document type on the nonconformance report and tag.

A printed conformance report and nonconformance tag can be used to assist with material disposition. You can selectively generate reports and tags based on selection criteria – such as the nonconformance number, item, customer, vendor, or status – that are associated with a nonconformance.

  - Nonconformance report − The nonconformance report displays identification information, such as the nonconformance number, item, and problem type. The report displays the related notes, based on your report setup policies.

  - Nonconformance tag − The nonconformance tag displays identification information, such as the nonconformance number and item. The tag displays the related notes, based on your report setup policies. The tag also displays the quarantine zone and type (such as restricted usage versus unusable) that you assigned to the nonconformance in order to guide disposition of the defective material.

You can optionally define one or more corrections for an approved nonconformance. A correction identifies what type of diagnostic should be performed, who should perform it, and a requested date and a planned date for completing the diagnostic. You predefine the user-defined diagnostic types and assign one to a corrective action. Indicate that you have finished the diagnostic step by changing the status of a correction to end. The status can be reopened. Comments can be entered for a correction by using the document handling capabilities.

It is generally helpful to define a unique document type about corrections (by using the **Document type** form), so that you can enter notes and comments for the unique document type. Use the **Report setup** form to define your policy about printing comments for the unique document type on the correction report. A printed correction report displays identification information about the nonconformance and the related nonconformance notes, in addition to the correction information (such as the diagnostic) and related correction notes. The report displays the related correction notes, based on your report-setup policies.

You can optionally define one or more related operations for an approved nonconformance. A related operation describes the work that should be performed and using a predefined list of user-defined quality operations, expressed as a selected operation. Descriptive text about the reason for the work should also be included. After you have defined an operation, you can optionally define the miscellaneous charges, items, and time sheet labor hours that are required to perform the work. The calculated costs are shown for the related operation, and the total calculated costs are shown for the nonconformance. The calculated costs and the underlying detail (about items, labor hours, and miscellaneous charges) represent reference information, and they are used only in the quality management function.

You can optionally create a quality order from a nonconformance by first performing an inquiry for quality orders, and then by creating the new quality order. For example, a quality order might identify the need to test (or retest) the defective material. The newly created quality order displays the link to the originating nonconformance.

You can optionally link one nonconformance to another or create a new nonconformance from an existing one. For example, the link can reflect the interconnection between quality problems.

## See also

[Nonconformance (form)](https://technet.microsoft.com/library/hh242787\(v=ax.60\))

[Corrections (form)](https://technet.microsoft.com/library/hh416712\(v=ax.60\))

[Quality orders (form)](https://technet.microsoft.com/library/hh209521\(v=ax.60\))

  


