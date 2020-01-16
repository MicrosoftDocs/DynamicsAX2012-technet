---
title: (EEUR, RUS) Generate upgrade configuration macro
TOCTitle: (EEUR, RUS) Generate upgrade configuration macro
ms:assetid: aee421a1-5c2a-4e48-91a1-a142df7ce5bb
ms:mtpsurl: https://technet.microsoft.com/library/JJ714198(v=AX.60)
ms:contentKeyID: 49651307
author: Khairunj
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# (EEUR, RUS) Generate upgrade configuration macro 


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2_

Since some Russian Federation and Eastern European configurations of Microsoft Dynamics AX 4.0 lack objects targeted for compilation by the Microsoft Dynamics AX 2012 R2 or R3 upgrade scripts, errors can occur during upgrade preprocessing. The upgrade framework avoids this problem by compiling objects conditionally. The **Generate upgrade configuration macro** task verifies the existence of certain tables and fields in the Microsoft Dynamics AX 4.0 source system prior to data preprocessing, and then creates a macro to customize the execution of the data preprocessing scripts.

## Generate and save the macro

The **Generate upgrade configuration macro** task performs the following operations:

  - Analyzes the code configuration of the source system.

  - Generates a macro text file that defines conditional compilation directives in the upgrade preprocessing scripts.

  - Saves the macro as a library in the Application Object Tree (AOT).

The following steps describe how to create the macro file and to save it as a library.

1.  In the **Preprocessing upgrade checklist**, click the **Generate upgrade configuration macro** task to open the **Upgrade configuration macro generator** form.

2.  In the **Report file name** field, enter a path and name for the macro file that will be generated. This file can be created even without a development license, allowing a customer to generate a macro and send it to a partner. The partner can use the generated macro to compile a version of the preprocessing upgrade scripts tailored to the customer’s Microsoft Dynamics AX 4.0 system.

3.  (Optional) Select the **Save macro library** check box to save the generated macro file as a library in the Application Object Tree (AOT).

4.  Click **OK** to generate the macro and, optionally, to save it to the AOT. You can find the saved macro library in the **AOT** at **Macros** \> **Upgrade Configuration Macro**.

## See also

[(EEUR, RUS) Upgrade configuration macro generator (form)](https://technet.microsoft.com/library/jj713627\(v=ax.60\))

  


