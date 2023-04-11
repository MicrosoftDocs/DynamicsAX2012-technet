---
title: PaymentCardBase.Address2 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Address2 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.Address2
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcardbase.address2(v=AX.60)
ms:contentKeyID: 65322200
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.Address2
dev_langs:
- CSharp
- C++
- VB
---

# Address2 Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value for Address2.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Address2 As String
    Get
    Set
'Usage
Dim instance As PaymentCardBase
Dim value As String

value = instance.Address2

instance.Address2 = value
```

``` csharp
[DataMemberAttribute]
public string Address2 { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Address2 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The address2.  

## See Also

#### Reference

[PaymentCardBase Class](paymentcardbase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

