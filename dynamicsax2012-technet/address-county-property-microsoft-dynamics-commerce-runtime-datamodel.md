---
title: Address.County Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: County Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.County
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.county(v=AX.60)
ms:contentKeyID: 49825247
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.County
dev_langs:
- CSharp
- C++
- VB
---

# County Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets County.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("COUNTY")> _
<DataMemberAttribute> _
Public Property County As String
    Get
    Set
'Usage
Dim instance As Address
Dim value As String

value = instance.County

instance.County = value
```

``` csharp
[ColumnAttribute("COUNTY")]
[DataMemberAttribute]
public string County { get; set; }
```

``` c++
[ColumnAttribute(L"COUNTY")]
[DataMemberAttribute]
public:
property String^ County {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

