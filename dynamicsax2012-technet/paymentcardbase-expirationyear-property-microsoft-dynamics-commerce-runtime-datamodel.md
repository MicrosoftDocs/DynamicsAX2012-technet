---
title: PaymentCardBase.ExpirationYear Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExpirationYear Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.ExpirationYear
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcardbase.expirationyear(v=AX.60)
ms:contentKeyID: 65321377
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.ExpirationYear
dev_langs:
- CSharp
- C++
- VB
---

# ExpirationYear Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the value for ExpirationYear.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExpirationYear As Integer
    Get
    Set
'Usage
Dim instance As PaymentCardBase
Dim value As Integer

value = instance.ExpirationYear

instance.ExpirationYear = value
```

``` csharp
[DataMemberAttribute]
public int ExpirationYear { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int ExpirationYear {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The expiration year.  

## See Also

#### Reference

[PaymentCardBase Class](paymentcardbase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

