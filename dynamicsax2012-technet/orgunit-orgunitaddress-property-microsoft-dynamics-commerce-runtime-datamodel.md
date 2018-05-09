---
title: OrgUnit.OrgUnitAddress Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OrgUnitAddress Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.OrgUnitAddress
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.orgunit.orgunitaddress(v=AX.60)
ms:contentKeyID: 62208307
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnit.OrgUnitAddress
dev_langs:
- CSharp
- C++
- VB
---

# OrgUnitAddress Property

Gets or sets the address of the organization unit.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
Public Property OrgUnitAddress As Address
    Get
    Set
'Usage
Dim instance As OrgUnit
Dim value As Address

value = instance.OrgUnitAddress

instance.OrgUnitAddress = value
```

``` csharp
[DataMemberAttribute]
public Address OrgUnitAddress { get; set; }
```

``` c++
[DataMemberAttribute]
public:
property Address^ OrgUnitAddress {
    Address^ get ();
    void set (Address^ value);
}
```

#### Property Value

Type: [Microsoft.Dynamics.Commerce.Runtime.DataModel.Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)  
Returns [Address](address-class-microsoft-dynamics-commerce-runtime-datamodel.md).  

## See Also

#### Reference

[OrgUnit Class](orgunit-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

