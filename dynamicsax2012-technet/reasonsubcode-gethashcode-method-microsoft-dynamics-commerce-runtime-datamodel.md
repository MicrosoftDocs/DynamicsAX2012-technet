---
title: ReasonSubCode.GetHashCode Method  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GetHashCode Method
ms:assetid: M:Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.GetHashCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.reasonsubcode.gethashcode(v=AX.60)
ms:contentKeyID: 62205571
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ReasonSubCode.GetHashCode
dev_langs:
- CSharp
- C++
- VB
---

# GetHashCode Method


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Serves as a hash function for a particular type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
Public Overrides Function GetHashCode As Integer
'Usage
Dim instance As ReasonSubCode
Dim returnValue As Integer

returnValue = instance.GetHashCode()
```

``` csharp
public override int GetHashCode()
```

``` c++
public:
virtual int GetHashCode() override
```

#### Return Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
A hash code for the current object.  

## See Also

#### Reference

[ReasonSubCode Class](reasonsubcode-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

