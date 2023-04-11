---
title: SalesTransaction Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesTransaction Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransaction(v=AX.60)
ms:contentKeyID: 49826786
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransaction Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Represents a channel agnostic sales transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
<KnownTypeAttribute(GetType(SalesOrder))> _
Public Class SalesTransaction _
    Inherits CommerceEntity
'Usage
Dim instance As SalesTransaction
```

``` csharp
[DataContractAttribute]
[KnownTypeAttribute(typeof(SalesOrder))]
public class SalesTransaction : CommerceEntity
```

``` c++
[DataContractAttribute]
[KnownTypeAttribute(typeof(SalesOrder))]
public ref class SalesTransaction : public CommerceEntity
```

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransaction  
      [Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesOrder](salesorder-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

