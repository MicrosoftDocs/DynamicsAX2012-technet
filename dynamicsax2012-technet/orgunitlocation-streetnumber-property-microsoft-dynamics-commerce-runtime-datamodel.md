---
title: OrgUnitLocation.StreetNumber Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StreetNumber Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.StreetNumber
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.streetnumber(v=AX.60)
ms:contentKeyID: 65321429
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.StreetNumber
dev_langs:
- CSharp
- C++
- VB
---

# StreetNumber Property

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("STREETNUMBER")> _
Public Property StreetNumber As String
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As String

value = instance.StreetNumber

instance.StreetNumber = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("STREETNUMBER")]
public string StreetNumber { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"STREETNUMBER")]
public:
property String^ StreetNumber {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

