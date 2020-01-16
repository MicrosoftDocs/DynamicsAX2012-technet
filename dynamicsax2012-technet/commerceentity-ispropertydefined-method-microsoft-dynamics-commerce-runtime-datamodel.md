---
title: CommerceEntity.IsPropertyDefined Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsPropertyDefined Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.IsPropertyDefined(System.String)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.commerceentity.ispropertydefined(v=AX.60)
ms:contentKeyID: 65320916
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity.IsPropertyDefined
dev_langs:
- CSharp
- C++
- VB
---

# IsPropertyDefined Method

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Framework (in Microsoft.Dynamics.Commerce.Runtime.Framework.dll)

## Syntax

``` vb
'Declaration
Public Function IsPropertyDefined ( _
    propertyName As String _
) As Boolean
'Usage
Dim instance As CommerceEntity
Dim propertyName As String
Dim returnValue As Boolean

returnValue = instance.IsPropertyDefined(propertyName)
```

``` csharp
public bool IsPropertyDefined(
    string propertyName
)
```

``` c++
public:
bool IsPropertyDefined(
    String^ propertyName
)
```

#### Parameters

  - propertyName  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

#### Return Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[CommerceEntity Class](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

