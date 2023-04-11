---
title: (ESP) About tax-exempt number validation
TOCTitle: (ESP) About tax-exempt number validation
ms:assetid: 7a550539-d1c0-445c-8a7e-9e4c7ffd3f81
ms:mtpsurl: https://technet.microsoft.com/library/Hh209262(v=AX.60)
ms:contentKeyID: 36058248
author: tonyafehr
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Spain
- tax-exempt number
audience: Application User
ms.search.region: Spain
---

# (ESP) About tax-exempt number validation 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Tax-exempt numbers are unique identifiers issued by the Agencia Estatal de Administración Tributaria (AEAT) to Spanish companies and individuals, and to foreign residents. These numbers must be included on all legal documents. To comply with validation requirements, some companies must change their tax-exempt numbers, and will post transactions using both their old and new tax-exempt numbers.

The three tax-exempt numbers are the Código de Identificación Fiscal (CIF), Número de Identificación Fiscal (NIF), and Número de Identificación de Extranjeros (NIE).

## CIF tax-exempt number validation

The CIF is issued to Spanish companies. It consists of nine alphanumeric characters in the format TDDDDDDDC, where:

  - T – A letter that identifies the type of company.

  - D – A number from zero to nine.

  - C – A control element, which can be a number or a letter.

## NIF tax-exempt number validation

The NIF is issued to individuals. It consists of nine alphanumeric characters in the format DDDDDDDDC, where:

  - D – A number from zero to nine.

  - C – A control element, which can be a number or a letter.

## NIE tax-exempt number validation

The NIE is issued to foreign individuals who reside in Spain. It consists of nine alphanumeric in the format MDDDDDDDC, where:

  - M – A marker that can be the letter X, Y, or Z.

  - D – A number from zero to nine.

  - C – A control element, which is a letter.

## See also

[Tax exempt numbers (form)](https://technet.microsoft.com/library/aa583706\(v=ax.60\))

  


