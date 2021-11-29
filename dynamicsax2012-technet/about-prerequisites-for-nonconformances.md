---
title: About prerequisites for nonconformances
TOCTitle: About prerequisites for nonconformances
ms:assetid: 7bb85741-fc4a-49e0-9892-563cd47cf1dc
ms:mtpsurl: https://technet.microsoft.com/library/Gg213025(v=AX.60)
ms:contentKeyID: 36058259
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- approve noncnformances
- nonconformance document
- nonconformance setup
- instance of nonconformance
- non-conformance
audience: Application User
ms.search.region: Global
---

# About prerequisites for nonconformances 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This topic covers the basic steps for using nonconformances. Additional steps are required for using quality orders.

To set up and use nonconformances, follow these steps:

1.  Define the inventory parameters that are related to nonconformances.
    
      - Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**. Click **Quality management**, and then select the **Use quality management** check box to use quality management. Use the **Hourly rate** field to enter an hourly labor rate in the local currency. The hourly rate is used for calculating costs for operations that are related to a nonconformance. The hourly rate and calculated costs provide reference information for a nonconformance, and they do not interact with other functionality.
    
      - Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**. Click **Quality management**, and then click the **Report setup** button to define the document type to be printed. You can print a nonconformance report, a nonconformance tag, and a correction report. More than one record can be defined for printing different document types on a report, or for printing internal and external notes. It is helpful to use the Document type form to define a unique document type for a nonconformance, and a unique document type for a correction. For example, you will enter notes on a nonconformance by using this unique document type, and you will identify this unique document type in the report options.
    
      - Click **Inventory management** \> **Setup** \> **Inventory and warehouse management parameters**. Click **Number sequences**, and enter the number sequences for the nonconformance and for the correction.

2.  Enable user approval of a nonconformance.
    
    Use the **User relations** form to assign an employee to each user who must approve a nonconformance. The system tracks the nonconformance history with regard to the employees who changed the status, and a user cannot approve a nonconformance unless the user has been assigned an employee identifier.

3.  Define the problem types that will be assigned to a nonconformance.
    
    Use the **Problem types** form to define a classification of quality problems that are encountered in the various nonconformance types. Nonconformance types can be set up with the types of **Internal**, **Customer**, **Vendor**, **Service request**, and **Production**.
    
    Use the **Non conformance types** form to authorize the use of a problem type in one or more of the nonconformance types. For example, a problem type regarding a defect code could apply to all nonconformance types, whereas a problem type about customer complaints may only apply to the customer and service request nonconformance types.

4.  Define the quarantine zones to provide guidance about how to handle defective material.
    
    Use the **Quarantine zones** form to define zones that can be assigned to a nonconformance. The printed nonconformance tag will display the assigned quarantine zone and information about usage to guide handling of defective material. The zones may correspond to inventory locations or operations resources.

5.  Define the diagnostic types that will be assigned to a correction.
    
    Use the **Diagnostic types** form to define a classification of diagnostic actions. A correction identifies what type of diagnostic action should be taken on an approved nonconformance, who should perform it, and the requested and planned completion date.

6.  Define the related operations that will be assigned to a nonconformance.
    
    Use the **Related operations** form to define a classification of the work that may be performed for an approved nonconformance. When you assign a related operation to a nonconformance, you can define detailed information. The detailed information can be about the associated material, labor hours, and miscellaneous charges that are required to perform the operation. This detailed information provides the basis for calculating an estimated cost for performing the operation. The detailed information and estimated costs are for references. The related operations for quality differ from the operations that can be defined for a production route.

## See also

[About nonconformance](about-nonconformance.md)

[Nonconformance (form)](https://technet.microsoft.com/library/hh242787\(v=ax.60\))

[Corrections (form)](https://technet.microsoft.com/library/hh416712\(v=ax.60\))

  


