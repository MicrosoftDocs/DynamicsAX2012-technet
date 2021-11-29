---
title: QuantityDiscountLevel Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: QuantityDiscountLevel Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.quantitydiscountlevel(v=AX.60)
ms:contentKeyID: 49855992
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel
dev_langs:
- CSharp
- C++
- VB
---

# QuantityDiscountLevel Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Defines a threshold level for a quantity discount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class QuantityDiscountLevel _
    Inherits CommerceEntity
'Usage
Dim instance As QuantityDiscountLevel
```

``` csharp
[DataContractAttribute]
public class QuantityDiscountLevel : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class QuantityDiscountLevel : public CommerceEntity
```

## Remarks

For example, $20/each at 2 or more; $15/each at 4 or more; etc.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.QuantityDiscountLevel  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

