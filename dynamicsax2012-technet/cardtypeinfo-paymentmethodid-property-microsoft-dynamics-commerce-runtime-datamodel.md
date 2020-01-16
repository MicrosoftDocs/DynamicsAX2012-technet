---
title: CardTypeInfo.PaymentMethodId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PaymentMethodId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.PaymentMethodId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cardtypeinfo.paymentmethodid(v=AX.60)
ms:contentKeyID: 62208344
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CardTypeInfo.PaymentMethodId
dev_langs:
- CSharp
- C++
- VB
---

# PaymentMethodId Property

Gets or sets the payment method identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("TENDERTYPEID")> _
<DataMemberAttribute> _
Public Property PaymentMethodId As String
    Get
    Set
'Usage
Dim instance As CardTypeInfo
Dim value As String

value = instance.PaymentMethodId

instance.PaymentMethodId = value
```

``` csharp
[ColumnAttribute("TENDERTYPEID")]
[DataMemberAttribute]
public string PaymentMethodId { get; set; }
```

``` c++
[ColumnAttribute(L"TENDERTYPEID")]
[DataMemberAttribute]
public:
property String^ PaymentMethodId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[CardTypeInfo Class](cardtypeinfo-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

