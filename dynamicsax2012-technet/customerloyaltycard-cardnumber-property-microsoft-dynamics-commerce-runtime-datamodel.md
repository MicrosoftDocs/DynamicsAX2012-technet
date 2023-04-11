---
title: CustomerLoyaltyCard.CardNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerLoyaltyCard.CardNumber
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customerloyaltycard.cardnumber(v=AX.60)
ms:contentKeyID: 49845354
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CustomerLoyaltyCard.CardNumber
dev_langs:
- CSharp
- C++
- VB
---

# CardNumber Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the loyalty card number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("CARDNUMBER")> _
Public Property CardNumber As String
    Get
    Friend Set
'Usage
Dim instance As CustomerLoyaltyCard
Dim value As String

value = instance.CardNumber
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("CARDNUMBER")]
public string CardNumber { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"CARDNUMBER")]
public:
property String^ CardNumber {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CustomerLoyaltyCard Class](customerloyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

