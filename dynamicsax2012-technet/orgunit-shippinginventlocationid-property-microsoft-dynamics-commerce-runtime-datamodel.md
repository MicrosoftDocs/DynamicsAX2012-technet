---
title: OrgUnit.ShippingInventLocationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ShippingInventLocationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.ShippingInventLocationId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.shippinginventlocationid(v=AX.60)
ms:contentKeyID: 62213214
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.ShippingInventLocationId
dev_langs:
- CSharp
- C++
- VB
---

# ShippingInventLocationId Property

Gets or sets the warehouse id (invent location id) to be used for orders that will be shipped to customers.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<IgnoreDataMemberAttribute> _
<ColumnAttribute("SHIPPINGINVENTLOCATION")> _
Public Property ShippingInventLocationId As String
    Get
    Set
'Usage
Dim instance As OrgUnit
Dim value As String

value = instance.ShippingInventLocationId

instance.ShippingInventLocationId = value
```

``` csharp
[IgnoreDataMemberAttribute]
[ColumnAttribute("SHIPPINGINVENTLOCATION")]
public string ShippingInventLocationId { get; set; }
```

``` c++
[IgnoreDataMemberAttribute]
[ColumnAttribute(L"SHIPPINGINVENTLOCATION")]
public:
property String^ ShippingInventLocationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnit Class](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

