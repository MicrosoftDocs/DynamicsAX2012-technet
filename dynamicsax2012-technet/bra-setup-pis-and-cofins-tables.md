---
title: (BRA) Setup PIS and COFINS tables
TOCTitle: (BRA) Setup PIS and COFINS tables
ms:assetid: da44a258-e975-4c7c-9fec-50f6d7fc83af
ms:mtpsurl: https://technet.microsoft.com/library/Mt267602(v=AX.60)
ms:contentKeyID: 66250920
author: tonyafehr
ms.date: 07/08/2015
mtps_version: v=AX.60
audience: Application User
ms.search.region: Brazil
---

# (BRA) Setup PIS and COFINS tables 


[!INCLUDE[archive-banner](includes/archive-banner.md)]


This topic describes how to setup specific PIS and COFINS tables used during the generation of PIS and COFINS tax assessment. These tables are required to generates the SPED EFD - Contributions text file.

## Set up CFOP and Credit base source table

This set up is used to create the Table 3.2.5 specified by the tax authorities and used in the tax assessment to clasify the operations that generates credit and determine the base credit source (Table 4.3.7) of fiscal documents based on the CFOP related.

## Set up the CFOP and Credit base source table

1.  Click **Fiscal books** \> **Setup** \> **Tax adjustment codes** \> **PIS and COFINS tables** \> **CFOP and Credit base source**.

2.  Click New to establish a new relation between the CFOP code and Credit base source.

3.  Introduce the CFOP code and CFOP description.

4.  Select the Credit Base source.

5.  In the Valid from and Valid to fields, enter the first and last dates that the adjustment codes are applicable.

## Import the CFOP and Credit base table from the tax authority site

1.  Click **Fiscal books** \> **Setup** \> **Tax adjustment codes** \> **PIS and COFINS tables** \> **CFOP and Credit base source**.

2.  Click **Import** to import the codes from txt file.

3.  Select the path and file name where the file is located.

4.  Click **OK**.


> [!NOTE]
> <P>When the <STRONG>Import</STRONG> process is used and already exist records in the table, the system will not update the current table.</P>



## Set up credit types

This set up is used to create the Table 4.3.6 specified by the tax authorities and used in the tax assessment to clasify the credits of fiscal document.

## Set up credit types

1.  Click **Fiscal books** \> **Setup** \> **Tax adjustment codes** \> **PIS and COFINS tables** \> **Credit types**.

2.  Click **New** to create a new credit type.

3.  Introduce the Credit type code and Description.

4.  In the **Valid from** and **Valid to** fields, enter the first and last dates that the adjustment codes are applicable.

## Import credit types

1.  Click **Fiscal books** \> **Setup** \> **Tax adjustment codes** \> **PIS and COFINS tables** \> **Credit types**.

2.  Click **Import** to import the codes from txt file.

3.  Select the path and file name where the file is located.

4.  Click OK.


> [!NOTE]
> <P>When the Import process is used and already exist records in the table, the system will not update the current table.</P>


  


