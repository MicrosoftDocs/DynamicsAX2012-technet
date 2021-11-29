---
title: Customer.LastName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: LastName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.LastName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.lastname(v=AX.60)
ms:contentKeyID: 49823985
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.LastName
dev_langs:
- CSharp
- C++
- VB
---

# LastName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer last name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LASTNAME")> _
Public Property LastName As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.LastName

instance.LastName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LASTNAME")]
public string LastName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LASTNAME")]
public:
property String^ LastName {
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

