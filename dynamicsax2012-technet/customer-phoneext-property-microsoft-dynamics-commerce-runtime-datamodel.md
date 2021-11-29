---
title: Customer.PhoneExt Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: PhoneExt Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PhoneExt
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.phoneext(v=AX.60)
ms:contentKeyID: 49840986
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.PhoneExt
dev_langs:
- CSharp
- C++
- VB
---

# PhoneExt Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the phone number extension.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("PHONEEXT")> _
Public Property PhoneExt As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.PhoneExt

instance.PhoneExt = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("PHONEEXT")]
public string PhoneExt { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"PHONEEXT")]
public:
property String^ PhoneExt {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

