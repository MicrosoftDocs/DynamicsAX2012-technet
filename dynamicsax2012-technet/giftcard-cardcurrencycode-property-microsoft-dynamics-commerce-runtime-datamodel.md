---
title: GiftCard.CardCurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardCurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.GiftCard.CardCurrencyCode
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.giftcard.cardcurrencycode(v=AX.60)
ms:contentKeyID: 62212963
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.GiftCard.CardCurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# CardCurrencyCode Property

Gets or sets the gift card's currency code.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("CARDCURRENCYCODE")> _
<DataMemberAttribute> _
Public Property CardCurrencyCode As String
    Get
    Set
'Usage
Dim instance As GiftCard
Dim value As String

value = instance.CardCurrencyCode

instance.CardCurrencyCode = value
```

``` csharp
[ColumnAttribute("CARDCURRENCYCODE")]
[DataMemberAttribute]
public string CardCurrencyCode { get; set; }
```

``` c++
[ColumnAttribute(L"CARDCURRENCYCODE")]
[DataMemberAttribute]
public:
property String^ CardCurrencyCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GiftCard Class](giftcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

