---
title: Cart.StaffId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StaffId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.StaffId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.cart.staffid(v=AX.60)
ms:contentKeyID: 62207810
author: tfehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Cart.StaffId
dev_langs:
- CSharp
- C++
- VB
---

# StaffId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the staff identifier for the person who created or resumed this transaction.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("STAFF")> _
<DataMemberAttribute> _
Public Property StaffId As String
    Get
    Set
'Usage
Dim instance As Cart
Dim value As String

value = instance.StaffId

instance.StaffId = value
```

``` csharp
[ColumnAttribute("STAFF")]
[DataMemberAttribute]
public string StaffId { get; set; }
```

``` c++
[ColumnAttribute(L"STAFF")]
[DataMemberAttribute]
public:
property String^ StaffId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Cart Class](cart-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

