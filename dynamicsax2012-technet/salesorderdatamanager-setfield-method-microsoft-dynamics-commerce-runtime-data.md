---
title: SalesOrderDataManager.SetField Method  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: SetField Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.SetField(Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow,System.String,System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.data.salesorderdatamanager.setfield(v=AX.60)
ms:contentKeyID: 65321031
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.SalesOrderDataManager.SetField
dev_langs:
- CSharp
- C++
- VB
---

# SetField Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.DataManagers (in Microsoft.Dynamics.Commerce.Runtime.DataManagers.dll)

## Syntax

``` vb
'Declaration
Protected Shared Sub SetField ( _
    row As DataRow, _
    field As String, _
    value As Object _
)
'Usage
Dim row As DataRow
Dim field As String
Dim value As Object

SalesOrderDataManager.SetField(row, field, value)
```

``` csharp
protected static void SetField(
    DataRow row,
    string field,
    Object value
)
```

``` c++
protected:
static void SetField(
    DataRow^ row, 
    String^ field, 
    Object^ value
)
```

#### Parameters

  - row  
    Type: [Microsoft.Dynamics.Commerce.Runtime.Data.Types.DataRow](datarow-class-microsoft-dynamics-commerce-runtime-data-types.md)  

<!-- end list -->

  - field  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - value  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

## See Also

#### Reference

[SalesOrderDataManager Class](salesorderdatamanager-class-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

