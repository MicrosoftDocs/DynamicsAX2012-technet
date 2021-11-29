---
title: ShiftTenderLine.RemoveFromTenderAmountOfTenderCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RemoveFromTenderAmountOfTenderCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.RemoveFromTenderAmountOfTenderCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.removefromtenderamountoftendercurrency(v=AX.60)
ms:contentKeyID: 62211468
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.RemoveFromTenderAmountOfTenderCurrency
dev_langs:
- CSharp
- C++
- VB
---

# RemoveFromTenderAmountOfTenderCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets amount removed from tender.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overridable ReadOnly Property RemoveFromTenderAmountOfTenderCurrency As Decimal
    Get
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.RemoveFromTenderAmountOfTenderCurrency
```

``` csharp
[IgnoreDataMemberAttribute]
public virtual decimal RemoveFromTenderAmountOfTenderCurrency { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
virtual property Decimal RemoveFromTenderAmountOfTenderCurrency {
    Decimal get ();
}
```

#### Property Value

Type: [System.Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\))  
Returns [Decimal](https://technet.microsoft.com/library/1k2e8atx\(v=ax.60\)).  

## See Also

#### Reference

[ShiftTenderLine Class](shifttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

