---
title: Adapting your code to table normalization for country/region fields in Microsoft Dynamics AX 2012 R2
TOCTitle: Adapting your code to table normalization for country/region fields in Microsoft Dynamics AX 2012 R2
ms:assetid: a384a96a-7043-4b5b-830b-ae8533dfacd1
ms:mtpsurl: https://technet.microsoft.com/library/JJ870682(v=AX.60)
ms:contentKeyID: 50469187
author: Khairunj
ms.author: daxcpft
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Adapting your code to table normalization for country/region fields in Microsoft Dynamics AX 2012 R2 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

This document provides common patterns for how to use country-specific/region-specific tables.

Normalization of country/region fields that have been added to the core transaction tables in Microsoft Dynamics AX provides performance improvements in the product. Based on analysis of core transaction tables, Microsoft has moved several country-specific or region-specific fields into country-specific/region-specific child tables. Moving these fields to separate tables narrows the width of heavily used transaction tables, resulting in performance improvements. Country-specific/region-specific fields are good candidates to be moved, because the performance cost associated with the retrieval of the country-specific/region-specific fields should only be incurred by the countries and regions requiring those fields. Patterns and guidelines have been established for data model normalization and access to country-specific/region-specific fields. These guidelines apply to commonly used patterns and do not necessarily cover all application design scenarios. They will help save on development time by enabling access to these country-specific/region-specific tables and fields anywhere in code where we have access to the parent table, without requiring that we refactor complex class hierarchies and without bloating method signatures with country-specific/region-specific table buffer parameters. These patterns include form patterns and logic patterns.

[Download the paper](https://go.microsoft.com/fwlink/?linkid=273070)

  


