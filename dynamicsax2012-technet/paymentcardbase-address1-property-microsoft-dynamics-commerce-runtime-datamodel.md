---
title: PaymentCardBase.Address1 Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Address1 Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.Address1
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.paymentcardbase.address1(v=AX.60)
ms:contentKeyID: 65316883
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PaymentCardBase.Address1
dev_langs:
- CSharp
- C++
- VB
---

# Address1 Property

Gets or sets the value for Address1.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property Address1 As String
    Get
    Set
'Usage
Dim instance As PaymentCardBase
Dim value As String

value = instance.Address1

instance.Address1 = value
```

``` csharp
[DataMemberAttribute]
public string Address1 { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property String^ Address1 {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The address1.  

## See Also

#### Reference

[PaymentCardBase Class](paymentcardbase-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

