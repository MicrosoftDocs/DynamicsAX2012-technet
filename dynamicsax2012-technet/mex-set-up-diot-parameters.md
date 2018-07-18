---
title: (MEX) Set up DIOT parameters
TOCTitle: (MEX) Set up DIOT parameters
ms:assetid: 4cc166e4-fe89-49d3-bda1-fff84bdf7244
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Hh208741(v=AX.60)
ms:contentKeyID: 36057014
ms.date: 04/18/2014
mtps_version: v=AX.60
f1_keywords:
- Mexico
- parameters
- DIOT
audience: Application User
ms.search.region: Mexico
---

# (MEX) Set up DIOT parameters 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Legal entities and persons in Mexico that deal with vendors must submit a Declaración Informativa de Operaciones con Terceros (DIOT) to the Servicio de Administración Tributaria (SAT). All VAT transaction details are included as field concepts in the DIOT. You can define a concept representing the VAT amount at a specific tax rate.

Before you generate a DIOT, set up the necessary parameters, such as the field concept ID and descriptions for a sales tax code, column type, and nondeductible amount details.

1.  Click **General ledger** \> **Setup** \> **Sales tax** \> **DIOT declaration**.

2.  Press CTRL+N to create a new field concept for a sales tax code.

3.  On the right pane, in the **Concept ID** and **Concept description** fields, enter a field concept ID and concept description for a sales tax code.

4.  In the **Order number** field, enter a valid order number between 8 and 20 for the field concept. The order number defines the sequence in which the information related to a field concept is reported in the DIOT.

5.  Select the **Nondeductible** check box to specify that the sales tax amount is nondeductible.

6.  In the **Column type** field, select the type of column to determine the value to be assigned to the field concept:
    
      - **1: net amount** – The net amount of all taxes selected for the field concept is assigned to the column.
    
      - **2: tax amount** – The tax amount of the taxes selected for the field concept is assigned to the column.
    
      - **0: none** – The value of the column is 0. Some fields or columns are optional and a value cannot be introduced for the column.

7.  In the **% of nondeductible amount** field, enter the percentage of nondeductible amount for a domestic vendor. This field is available when you select the **Nondeductible** check box.

8.  Close the form to save your changes.

## See also

[(MEX) Set up DIOT declaration (form)](https://technet.microsoft.com/en-us/library/hh242543\(v=ax.60\))

  


