---
title: PaymentCard.UseShippingAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: UseShippingAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard.UseShippingAddress
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcard.useshippingaddress(v=AX.60)
ms:contentKeyID: 49831769
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCard.UseShippingAddress
dev_langs:
- CSharp
- C++
- VB
---

# UseShippingAddress Property

Gets or sets a value indicating whether UseShippingAddress is true or false.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property UseShippingAddress As Boolean
    Get
    Set
'Usage
Dim instance As PaymentCard
Dim value As Boolean

value = instance.UseShippingAddress

instance.UseShippingAddress = value
```

``` csharp
[DataMemberAttribute]
public bool UseShippingAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property bool UseShippingAddress {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[PaymentCard Class](paymentcard-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

