---
title: OrgUnitLocation.Zip Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Zip Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Zip
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.orgunitlocation.zip(v=AX.60)
ms:contentKeyID: 62202368
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.OrgUnitLocation.Zip
dev_langs:
- CSharp
- C++
- VB
---

# Zip Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the location zip.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ZIPCODE")> _
<DataMemberAttribute> _
Public Property Zip As String
    Get
    Set
'Usage
Dim instance As OrgUnitLocation
Dim value As String

value = instance.Zip

instance.Zip = value
```

``` csharp
[ColumnAttribute("ZIPCODE")]
[DataMemberAttribute]
public string Zip { get; set; }
```

``` c++
[ColumnAttribute(L"ZIPCODE")]
[DataMemberAttribute]
public:
property String^ Zip {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[OrgUnitLocation Class](orgunitlocation-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

