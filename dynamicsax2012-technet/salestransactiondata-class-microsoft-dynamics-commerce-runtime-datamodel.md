---
title: SalesTransactionData Class (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesTransactionData Class
ms:assetid: T:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salestransactiondata(v=AX.60)
ms:contentKeyID: 62205381
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData
dev_langs:
- CSharp
- C++
- VB
---

# SalesTransactionData Class


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Sales transaction database representation.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataContractAttribute> _
Public Class SalesTransactionData _
    Inherits CommerceEntity
'Usage
Dim instance As SalesTransactionData
```

``` csharp
[DataContractAttribute]
public class SalesTransactionData : CommerceEntity
```

``` c++
[DataContractAttribute]
public ref class SalesTransactionData : public CommerceEntity
```

## Remarks

This class should be hidden from developers since it contains the serialized transaction.

## Inheritance Hierarchy

[System.Object](https://technet.microsoft.com/library/e5kfa45b\(v=ax.60\))  
  [Microsoft.Dynamics.Commerce.Runtime.DataModel.CommerceEntity](commerceentity-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
    Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesTransactionData  

## Thread Safety

Any public static (Shared in Visual Basic) members of this type are thread safe. Any instance members are not guaranteed to be thread safe.

## See Also

#### Reference

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

