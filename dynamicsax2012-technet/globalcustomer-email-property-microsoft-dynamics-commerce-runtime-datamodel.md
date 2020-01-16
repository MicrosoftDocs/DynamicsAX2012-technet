---
title: GlobalCustomer.Email Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Email Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.Email
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.globalcustomer.email(v=AX.60)
ms:contentKeyID: 62209653
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.GlobalCustomer.Email
dev_langs:
- CSharp
- C++
- VB
---

# Email Property

Gets or sets the customer Email address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("EMAIL")> _
<DataMemberAttribute> _
Public Property Email As String
    Get
    Set
'Usage
Dim instance As GlobalCustomer
Dim value As String

value = instance.Email

instance.Email = value
```

``` csharp
[ColumnAttribute("EMAIL")]
[DataMemberAttribute]
public string Email { get; set; }
```

``` c++
[ColumnAttribute(L"EMAIL")]
[DataMemberAttribute]
public:
property String^ Email {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[GlobalCustomer Class](globalcustomer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

