---
title: PaymentCard.CardNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: CardNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard.CardNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcard.cardnumber(v=AX.60)
ms:contentKeyID: 49836444
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard.CardNumber
dev_langs:
- CSharp
- C++
- VB
---

# CardNumber Property

Gets or sets the value for CardNumber.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property CardNumber As String
    Get
    Set
'Usage
Dim instance As PaymentCard
Dim value As String

value = instance.CardNumber

instance.CardNumber = value
```

``` csharp
[DataMemberAttribute]
public string CardNumber { get; set; }
```

``` c++
[DataMemberAttribute]
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

[PaymentCard Class](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

