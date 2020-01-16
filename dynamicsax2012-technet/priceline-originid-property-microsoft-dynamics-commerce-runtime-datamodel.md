---
title: PriceLine.OriginId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OriginId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceLine.OriginId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.priceline.originid(v=AX.60)
ms:contentKeyID: 62206282
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.PriceLine.OriginId
dev_langs:
- CSharp
- C++
- VB
---

# OriginId Property

Gets or sets the unique identifier for the originating source of this price line.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ORIGINID")> _
Public Property OriginId As String
    Get
    Set
'Usage
Dim instance As PriceLine
Dim value As String

value = instance.OriginId

instance.OriginId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ORIGINID")]
public string OriginId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ORIGINID")]
public:
property String^ OriginId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[PriceLine Class](priceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

