---
title: Modify data types
TOCTitle: Modify data types
ms:assetid: 7b533e0b-f64d-410e-99ae-0296ace50900
ms:mtpsurl: https://technet.microsoft.com/en-us/library/Aa834488(v=AX.60)
ms:contentKeyID: 35132691
ms.date: 04/18/2014
mtps_version: v=AX.60
---

# Modify data types [AX 2012]


_**Applies To:** Microsoft Dynamics AX 2012 R3, Microsoft Dynamics AX 2012 R2, Microsoft Dynamics AX 2012 Feature Pack, Microsoft Dynamics AX 2012_

Properties for some extended data types can be changed by the administrator before data has been entered into the system. Property changes can be made without accessing the Application Object Tree (AOT).

## Example

To change the number of decimal places on the **Amount** data type, enter the number of decimal places you require in the **Decimals** field. If you change the number from 2 to 0, an amount that inherits from the **Amount** data type appears as 200 instead of 200.00. The change is reflected everywhere that the **Amount** data type is used.

## Modify data types

1.  Click **System administration** \> **Setup** \> **System** \> **Modify data types**. –or– Open the **Modify data types** form from the initialization checklist.

2.  Select a data type. The properties for the selected data type appear in the **Properties** pane, where you can edit them.

After you modify data types, you must synchronize the database. For more information, see [Synchronize the database](synchronize-the-database.md).

## See also

[Data types that can be modified](https://technet.microsoft.com/en-us/library/aa496486\(v=ax.60\))

  
**Announcements:** To see known issues and recent fixes, use [Issue search](http://go.microsoft.com/fwlink/?linkid=389258) in [Microsoft Dynamics Lifecycle Services](http://go.microsoft.com/fwlink/?linkid=306505) (LCS).

