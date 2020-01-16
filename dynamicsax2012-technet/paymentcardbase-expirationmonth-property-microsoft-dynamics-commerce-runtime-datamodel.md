---
title: PaymentCardBase.ExpirationMonth Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ExpirationMonth Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.ExpirationMonth
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcardbase.expirationmonth(v=AX.60)
ms:contentKeyID: 65322765
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.ExpirationMonth
dev_langs:
- CSharp
- C++
- VB
---

# ExpirationMonth Property

Gets or sets the value for ExpirationMonth.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property ExpirationMonth As Integer
    Get
    Set
'Usage
Dim instance As PaymentCardBase
Dim value As Integer

value = instance.ExpirationMonth

instance.ExpirationMonth = value
```

``` csharp
[DataMemberAttribute]
public int ExpirationMonth { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property int ExpirationMonth {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The expiration month.  

## See Also

#### Reference

[PaymentCardBase Class](paymentcardbase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

