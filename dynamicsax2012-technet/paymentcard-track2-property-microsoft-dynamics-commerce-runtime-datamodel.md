---
title: PaymentCard.Track2 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Track2 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard.Track2
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcard.track2(v=AX.60)
ms:contentKeyID: 62203208
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard.Track2
dev_langs:
- CSharp
- C++
- VB
---

# Track2 Property

Gets or sets the value for Track2.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Track2 As String
    Get
    Set
'Usage
Dim instance As PaymentCard
Dim value As String

value = instance.Track2

instance.Track2 = value
```

``` csharp
[DataMemberAttribute]
public string Track2 { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Track2 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PaymentCard Class](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

