---
title: Customer.FirstName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: FirstName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.FirstName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.firstname(v=AX.60)
ms:contentKeyID: 49840712
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.FirstName
dev_langs:
- CSharp
- C++
- VB
---

# FirstName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the customer first name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("FIRSTNAME")> _
Public Property FirstName As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.FirstName

instance.FirstName = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("FIRSTNAME")]
public string FirstName { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"FIRSTNAME")]
public:
property String^ FirstName {
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

