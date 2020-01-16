---
title: OrgUnitLocation.BuildingCompliment Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: BuildingCompliment Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.BuildingCompliment
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.buildingcompliment(v=AX.60)
ms:contentKeyID: 65320098
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.BuildingCompliment
dev_langs:
- CSharp
- C++
- VB
---

# BuildingCompliment Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("BUILDINGCOMPLIMENT")> _
Public Property BuildingCompliment As String
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As String

value = instance.BuildingCompliment

instance.BuildingCompliment = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("BUILDINGCOMPLIMENT")]
public string BuildingCompliment { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"BUILDINGCOMPLIMENT")]
public:
property String^ BuildingCompliment {
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

