---
title: Product Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Product Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.Product
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.product(v=AX.60)
ms:contentKeyID: 62211725
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Product
dev_langs:
- CSharp
- C++
- VB
---

# Product Class

Represents a product.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DefaultSortOrderAttribute(ColumnName := "RECID", IsDescending := False)> _
<DataContractAttribute> _
Public Class Product _
    Inherits CommerceEntity
'Usage
Dim instance As Product
```

``` csharp
[DefaultSortOrderAttribute(ColumnName = "RECID", IsDescending = false)]
[DataContractAttribute]
public class Product : CommerceEntity
```

``` c++
[DefaultSortOrderAttribute(ColumnName = L"RECID", IsDescending = false)]
[DataContractAttribute]
public ref class Product : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.Product  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

