---
title: Customer.OrganizationId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrganizationId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.OrganizationId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.customer.organizationid(v=AX.60)
ms:contentKeyID: 62208864
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Customer.OrganizationId
dev_langs:
- CSharp
- C++
- VB
---

# OrganizationId Property

Gets or sets the organization identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ORGID")> _
Public Property OrganizationId As String
    Get
    Set
'Usage
Dim instance As Customer
Dim value As String

value = instance.OrganizationId

instance.OrganizationId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ORGID")]
public string OrganizationId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ORGID")]
public:
property String^ OrganizationId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The organization identifier.  

## See Also

#### Reference

[Customer Class](customer-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

