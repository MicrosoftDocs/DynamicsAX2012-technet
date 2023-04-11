---
title: ChargeLine Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ChargeLine Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.chargeline(v=AX.60)
ms:contentKeyID: 49843767
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine
dev_langs:
- CSharp
- C++
- VB
---

# ChargeLine Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents a taxable charge line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class ChargeLine _
    Inherits TaxableItem
'Usage
Dim instance As ChargeLine
```

``` csharp
[DataContractAttribute]
public class ChargeLine : TaxableItem
```

``` c++
[DataContractAttribute]
public ref class ChargeLine : public TaxableItem
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    [Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxableItem](taxableitem-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
      Microsoft.Dynamics.Commerce.Runtime.DataModel.ChargeLine  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

