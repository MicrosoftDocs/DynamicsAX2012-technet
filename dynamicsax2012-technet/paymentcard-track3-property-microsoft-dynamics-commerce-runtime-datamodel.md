---
title: PaymentCard.Track3 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Track3 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard.Track3
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcard.track3(v=AX.60)
ms:contentKeyID: 62211145
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard.Track3
dev_langs:
- CSharp
- C++
- VB
---

# Track3 Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value for Track3.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Track3 As String
    Get
    Set
'Usage
Dim instance As PaymentCard
Dim value As String

value = instance.Track3

instance.Track3 = value
```

``` csharp
[DataMemberAttribute]
public string Track3 { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Track3 {
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

