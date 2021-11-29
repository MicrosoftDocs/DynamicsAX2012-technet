---
title: ShiftTenderLine.RemoveFromTenderAmountOfStoreCurrency Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: RemoveFromTenderAmountOfStoreCurrency Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.RemoveFromTenderAmountOfStoreCurrency
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.shifttenderline.removefromtenderamountofstorecurrency(v=AX.60)
ms:contentKeyID: 62211722
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ShiftTenderLine.RemoveFromTenderAmountOfStoreCurrency
dev_langs:
- CSharp
- C++
- VB
---

# RemoveFromTenderAmountOfStoreCurrency Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets amount removed from tender in store curreny.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
Public Overridable ReadOnly Property RemoveFromTenderAmountOfStoreCurrency As Decimal
    Get
'Usage
Dim instance As ShiftTenderLine
Dim value As Decimal

value = instance.RemoveFromTenderAmountOfStoreCurrency
```

``` csharp
[IgnoreDataMemberAttribute]
public virtual decimal RemoveFromTenderAmountOfStoreCurrency { get; }
```

``` c++
[IgnoreDataMemberAttribute]
public:
virtual property Decimal RemoveFromTenderAmountOfStoreCurrency {
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

