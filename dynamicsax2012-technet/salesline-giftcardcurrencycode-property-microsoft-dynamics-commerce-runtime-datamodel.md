---
title: SalesLine.GiftCardCurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: GiftCardCurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.GiftCardCurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.giftcardcurrencycode(v=AX.60)
ms:contentKeyID: 62206524
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.GiftCardCurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# GiftCardCurrencyCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the gift card currency code if this instance is a gift card line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ReadOnlyAttribute("GIFTCARDCURRENCYCODE")> _
<DataMemberAttribute> _
<ColumnAttribute("GIFTCARDCURRENCYCODE")> _
Public Property GiftCardCurrencyCode As String
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As String

value = instance.GiftCardCurrencyCode

instance.GiftCardCurrencyCode = value
```

``` csharp
[ReadOnlyAttribute("GIFTCARDCURRENCYCODE")]
[DataMemberAttribute]
[ColumnAttribute("GIFTCARDCURRENCYCODE")]
public string GiftCardCurrencyCode { get; set; }
```

``` c++
[ReadOnlyAttribute(L"GIFTCARDCURRENCYCODE")]
[DataMemberAttribute]
[ColumnAttribute(L"GIFTCARDCURRENCYCODE")]
public:
property String^ GiftCardCurrencyCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

