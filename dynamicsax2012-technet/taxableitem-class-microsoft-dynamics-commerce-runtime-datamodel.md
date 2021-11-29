---
title: TaxableItem Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: TaxableItem Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxableitem(v=AX.60)
ms:contentKeyID: 49826768
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem
dev_langs:
- CSharp
- C++
- VB
---

# TaxableItem Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Common interface for taxable entities.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class TaxableItem _
    Inherits CommerceEntity
'Usage
Dim instance As TaxableItem
```

``` csharp
[DataContractAttribute]
public class TaxableItem : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class TaxableItem : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine](chargeline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

