---
title: OrgUnitLocation.Address Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Address Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Address
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.address(v=AX.60)
ms:contentKeyID: 65319593
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Address
dev_langs:
- CSharp
- C++
- VB
---

# Address Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ADDRESS")> _
Public Property Address As String
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As String

value = instance.Address

instance.Address = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ADDRESS")]
public string Address { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ADDRESS")]
public:
property String^ Address {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

