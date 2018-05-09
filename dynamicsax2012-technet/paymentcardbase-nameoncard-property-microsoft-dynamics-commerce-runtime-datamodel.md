---
title: PaymentCardBase.NameOnCard Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: NameOnCard Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.NameOnCard
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcardbase.nameoncard(v=AX.60)
ms:contentKeyID: 65315818
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.NameOnCard
dev_langs:
- CSharp
- C++
- VB
---

# NameOnCard Property

Gets or sets the value for NameOnCard.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property NameOnCard As String
    Get
    Set
'Usage
Dim instance As PaymentCardBase
Dim value As String

value = instance.NameOnCard

instance.NameOnCard = value
```

``` csharp
[DataMemberAttribute]
public string NameOnCard { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ NameOnCard {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The name on card.  

## See Also

#### Reference

[PaymentCardBase Class](paymentcardbase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

