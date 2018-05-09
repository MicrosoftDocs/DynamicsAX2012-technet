---
title: IDatabaseResult.FieldCount Property  (Microsoft.Dynamics.Commerce.Runtime.Data)
TOCTitle: FieldCount Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.FieldCount
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.data.idatabaseresult.fieldcount(v=AX.60)
ms:contentKeyID: 65317884
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.Data.IDatabaseResult.FieldCount
dev_langs:
- CSharp
- C++
- VB
---

# FieldCount Property

Gets the number of fields available in the current result set.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.Data](microsoft-dynamics-commerce-runtime-data-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
ReadOnly Property FieldCount As Integer
    Get
'Usage
Dim instance As IDatabaseResult
Dim value As Integer

value = instance.FieldCount
```

``` csharp
int FieldCount { get; }
```

``` c++
property int FieldCount {
    int get ();
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/en-us/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[IDatabaseResult Interface](idatabaseresult-interface-microsoft-dynamics-commerce-runtime-data.md)

[Microsoft.Dynamics.Commerce.Runtime.Data Namespace](microsoft-dynamics-commerce-runtime-data-namespace.md)

