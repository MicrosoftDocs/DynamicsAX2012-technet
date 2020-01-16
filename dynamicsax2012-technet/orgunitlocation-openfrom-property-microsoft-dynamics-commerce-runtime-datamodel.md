---
title: OrgUnitLocation.OpenFrom Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OpenFrom Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.OpenFrom
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.openfrom(v=AX.60)
ms:contentKeyID: 62213927
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.OpenFrom
dev_langs:
- CSharp
- C++
- VB
---

# OpenFrom Property

Gets or sets the open from value.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("OPENFROM")> _
Public Property OpenFrom As Integer
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As Integer

value = instance.OpenFrom

instance.OpenFrom = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("OPENFROM")]
public int OpenFrom { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"OPENFROM")]
public:
property int OpenFrom {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
Returns [Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

