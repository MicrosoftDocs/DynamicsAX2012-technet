---
title: LoyaltyCard.CardNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.CardNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.loyaltycard.cardnumber(v=AX.60)
ms:contentKeyID: 62208758
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.LoyaltyCard.CardNumber
dev_langs:
- CSharp
- C++
- VB
---

# CardNumber Property

Gets or sets the card number.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CARDNUMBER")> _
<DataMemberAttribute> _
<KeyAttribute> _
Public Property CardNumber As String
    Get
    Set
'Usage
Dim instance As LoyaltyCard
Dim value As String

value = instance.CardNumber

instance.CardNumber = value
```

``` csharp
[ColumnAttribute("CARDNUMBER")]
[DataMemberAttribute]
[KeyAttribute]
public string CardNumber { get; set; }
```

``` c++
[ColumnAttribute(L"CARDNUMBER")]
[DataMemberAttribute]
[KeyAttribute]
public:
property String^ CardNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[LoyaltyCard Class](loyaltycard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

