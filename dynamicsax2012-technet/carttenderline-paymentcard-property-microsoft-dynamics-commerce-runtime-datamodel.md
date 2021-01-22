---
title: CartTenderLine.PaymentCard Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PaymentCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine.PaymentCard
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.carttenderline.paymentcard(v=AX.60)
ms:contentKeyID: 62212324
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.CartTenderLine.PaymentCard
dev_langs:
- CSharp
- C++
- VB
---

# PaymentCard Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PAYMENTCARD")> _
Public Property PaymentCard As PaymentCard
    Get
    Set
'Usage
Dim instance As CartTenderLine
Dim value As PaymentCard

value = instance.PaymentCard

instance.PaymentCard = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PAYMENTCARD")]
public PaymentCard PaymentCard { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PAYMENTCARD")]
public:
property PaymentCard^ PaymentCard {
    PaymentCard^ get ();
    void set (PaymentCard^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)  

## See Also

#### Reference

[CartTenderLine Class](carttenderline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

