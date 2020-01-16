---
title: ProductPropertySchema.Add Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Add Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertySchema.Add(System.String,System.Int32)
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productpropertyschema.add(v=AX.60)
ms:contentKeyID: 62209267
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductPropertySchema.Add
dev_langs:
- CSharp
- C++
- VB
---

# Add Method

Adds the specified pair of property key and index, updating the reverse lookup in the process.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Sub Add ( _
    propertyKey As String, _
    propertyIndex As Integer _
)
'Usage
Dim instance As ProductPropertySchema
Dim propertyKey As String
Dim propertyIndex As Integer

instance.Add(propertyKey, propertyIndex)
```

``` csharp
public void Add(
    string propertyKey,
    int propertyIndex
)
```

``` c++
public:
void Add(
    String^ propertyKey, 
    int propertyIndex
)
```

#### Parameters

  - propertyKey  
    Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

<!-- end list -->

  - propertyIndex  
    Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  

## See Also

#### Reference

[ProductPropertySchema Class](productpropertyschema-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

