---
title: About tests and quality orders
TOCTitle: About tests and quality orders
ms:assetid: 4232dd41-7dc2-4695-9e32-931ef863e8de
ms:mtpsurl: https://technet.microsoft.com/library/Gg231366(v=AX.60)
ms:contentKeyID: 36056870
author: tfehr
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- perform test
- test quantity
audience: Application User
ms.search.region: Global
---

# About tests and quality orders 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

A quality order defines a set of one or more tests that must be performed for an item and a test quantity of its related order (such as a purchase, sales, or production order) or a test quantity of its inventory.

  - For each test, the quality order defines the quality specifications, an acceptable quality level (AQL), the applicable test instrument, the documents that describe the test, and several other factors. A test can be quantitative (with specifications and test results expressed as values for a specified unit of measure) or qualitative (with specifications and test results expressed as user-defined outcomes that reflect pass or fail). You can add, change, or delete the tests that are in a quality order.

  - For the set of tests, the quality order defines the overall AQL, the sampling plan and associated test quantity, the need for destructive tests, and the sequence of tests.

You can create a quality order manually or establish quality guidelines in each business process (such as a process that is related to purchase, sales, or production orders) for creating a quality order automatically. The quality guidelines define the set of tests, overall AQL, sampling plan for the quality order, and conditions for when to generate a quality order in the business process. In the business process for purchase order receipts, for example, the conditions can apply to the site, item, and vendor, so that a quality order will be generated selectively.

After you report the test results for each test that is in a quality order, you initiate a validation process that assigns a pass or fail status (based on meeting the overall AQL) and closes the quality order. An Infolog can warn you that the quality order has failed or has not yet been closed when you perform the next step in the business process. In addition, you can optionally reopen the quality order and force the validation process to assign a pass status by accepting any error conditions.

You can optionally create a nonconformance when a quality order identifies defective material. The nonconformance provides the basis for additional investigation. For more information, see [About nonconformance](about-nonconformance.md).

A quality order builds on the information that is defined by several prerequisite steps. These steps include:

1.  The definition of quantitative tests and the associated unit of measure.

2.  The definition of qualitative tests and the associated test variables and outcomes.

3.  The optional definition of test instruments and associated test areas.

4.  The definition of test groups.

Additional steps include the definition of sampling plans and the assignment of tests to a test group, together with the quality specifications, AQL, test sequence, and validity dates for each test in the test group. The automatic generation of quality orders requires an additional step to define the quality associations about the events and conditions in each business process that will trigger a quality order.

## See also

[Quality orders (form)](https://technet.microsoft.com/library/hh209521\(v=ax.60\))

[About system-generated quality orders](about-system-generated-quality-orders.md)

[About nonconformance](about-nonconformance.md)

  


