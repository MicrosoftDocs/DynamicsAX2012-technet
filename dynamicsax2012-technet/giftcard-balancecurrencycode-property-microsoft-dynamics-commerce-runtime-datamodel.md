---
title: GiftCard.BalanceCurrencyCode Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BalanceCurrencyCode Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.GiftCard.BalanceCurrencyCode
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.giftcard.balancecurrencycode(v=AX.60)
ms:contentKeyID: 62212378
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.GiftCard.BalanceCurrencyCode
dev_langs:
- CSharp
- C++
- VB
---

# BalanceCurrencyCode Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the currency code of balance amount.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BALANCECURRENCYCODE")> _
Public Property BalanceCurrencyCode As String
    Get
    Set
'Usage
Dim instance As GiftCard
Dim value As String

value = instance.BalanceCurrencyCode

instance.BalanceCurrencyCode = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BALANCECURRENCYCODE")]
public string BalanceCurrencyCode { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BALANCECURRENCYCODE")]
public:
property String^ BalanceCurrencyCode {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GiftCard Class](giftcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

