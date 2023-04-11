---
title: LoyaltyCard.CardTenderType Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardTenderType Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.CardTenderType
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycard.cardtendertype(v=AX.60)
ms:contentKeyID: 62209277
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.CardTenderType
dev_langs:
- CSharp
- C++
- VB
---

# CardTenderType Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the card tender type.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CARDTENDERTYPE")> _
<DataMemberAttribute> _
Public Property CardTenderType As LoyaltyCardTenderType
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As LoyaltyCardTenderType

value = instance.CardTenderType

instance.CardTenderType = value
```

``` csharp
[ColumnAttribute("CARDTENDERTYPE")]
[DataMemberAttribute]
public LoyaltyCardTenderType CardTenderType { get; set; }
```

``` c++
[ColumnAttribute(L"CARDTENDERTYPE")]
[DataMemberAttribute]
public:
property LoyaltyCardTenderType CardTenderType {
    LoyaltyCardTenderType get ();
    void set (LoyaltyCardTenderType value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [LoyaltyCardTenderType](loyaltycardtendertype-enumeration-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

