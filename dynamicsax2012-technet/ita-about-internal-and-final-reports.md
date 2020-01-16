---
title: (ITA) About internal and final reports
TOCTitle: (ITA) About internal and final reports
ms:assetid: 92de7ea6-3a05-432d-a329-3d9563761f36
ms:mtpsurl: https://technet.microsoft.com/library/Aa498384(v=AX.60)
ms:contentKeyID: 36058579
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- final fiscal LIFO report
- fiscal LIFO reports
- reporting fiscal LIFO
- internal fiscal LIFO report
audience: Application User
ms.search.region: Italy
---

# (ITA) About internal and final reports 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

You can create two types of fiscal LIFO reports: final and internal reports.

The final report is the yearly fiscal LIFO report that you send to municipal authorities. The final report cannot be changed after it is approved, and you can create only one version of the final report.

Internal reports are drafts created for your own reference. You can create as many versions as required to try different scenarios. For example, you can perform multiple calculations of fiscal LIFO for the same period and adjust the various time periods. The calculations that you perform for your internal reports do not affect the calculation of fiscal LIFO for the yearly final report.

The calculation of inventory value for the final report covers the whole fiscal year and all items.

## Internal and final report journals

The inventory value calculation is maintained in two separate journals. The internal and final reports are printed from these journals.

You can have multiple internal report journals and you can calculate fiscal LIFO as many times as you want.

You can only have one final report journal per year and it cannot be deleted.

In the internal report journal, you can calculate the inventory value from the first day in the fiscal year and up to a date that you specify.

In the final report journal, the calculation covers the whole fiscal year.

## See also

[(ITA) Create fiscal LIFO journals](ita-create-fiscal-lifo-journals.md)

[(ITA) Calculate fiscal LIFO journal lines](ita-calculate-fiscal-lifo-journal-lines.md)

  


