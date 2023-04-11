---
title: CardTypeInfo.CardType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.CardType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cardtypeinfo.cardtype(v=AX.60)
ms:contentKeyID: 62210895
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.CardType
dev_langs:
- CSharp
- C++
- VB
---

# CardType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the card type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("CARDTYPES")> _
Public Property CardType As CardType
    Get
    Set
'Usage
Dim instance As CardTypeInfo
Dim value As CardType

value = instance.CardType

instance.CardType = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("CARDTYPES")]
public CardType CardType { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"CARDTYPES")]
public:
property CardType CardType {
    CardType get ();
    void set (CardType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.CardType](cardtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [CardType](cardtype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[CardTypeInfo Class](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

