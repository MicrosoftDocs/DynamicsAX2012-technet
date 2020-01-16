---
title: PaymentCardBase.Phone Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Phone Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.Phone
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcardbase.phone(v=AX.60)
ms:contentKeyID: 65315821
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.Phone
dev_langs:
- CSharp
- C++
- VB
---

# Phone Property

Gets or sets the value for Phone.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Phone As String
    Get
    Set
'Usage
Dim instance As PaymentCardBase
Dim value As String

value = instance.Phone

instance.Phone = value
```

``` csharp
[DataMemberAttribute]
public string Phone { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Phone {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The phone.  

## See Also

#### Reference

[PaymentCardBase Class](paymentcardbase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

