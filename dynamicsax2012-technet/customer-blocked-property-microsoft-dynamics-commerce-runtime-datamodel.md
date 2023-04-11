---
title: Customer.Blocked Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Blocked Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.Blocked
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.customer.blocked(v=AX.60)
ms:contentKeyID: 62212140
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.Blocked
dev_langs:
- CSharp
- C++
- VB
---

# Blocked Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets a value indicating whether customer is blocked.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("BLOCKED")> _
<DataMemberAttribute> _
Public Property Blocked As Boolean
    Get
    Set
'Usage
Dim instance As Customer
Dim value As Boolean

value = instance.Blocked

instance.Blocked = value
```

``` csharp
[ColumnAttribute("BLOCKED")]
[DataMemberAttribute]
public bool Blocked { get; set; }
```

``` c++
[ColumnAttribute(L"BLOCKED")]
[DataMemberAttribute]
public:
property bool Blocked {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

