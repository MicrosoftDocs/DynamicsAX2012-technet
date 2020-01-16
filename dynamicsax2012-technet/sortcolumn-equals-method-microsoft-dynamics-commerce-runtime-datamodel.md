---
title: SortColumn.Equals Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Equals Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn.Equals(System.Object)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.sortcolumn.equals(v=AX.60)
ms:contentKeyID: 65321571
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SortColumn.Equals
dev_langs:
- CSharp
- C++
- VB
---

# Equals Method

Determines whether the specified [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\)) is equal to this instance.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function Equals ( _
    obj As Object _
) As Boolean
'Usage
Dim instance As SortColumn
Dim obj As Object
Dim returnValue As Boolean

returnValue = instance.Equals(obj)
```

``` csharp
public override bool Equals(
    Object obj
)
```

``` c++
public:
virtual bool Equals(
    Object^ obj
) override
```

#### Parameters

  - obj  
    Type: [System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
If true the specified [Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\)) is equal to this instance; otherwise, false.  

## See Also

#### Reference

[SortColumn Class](sortcolumn-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

