---
title: SalesLine.OriginLineId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: OriginLineId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.OriginLineId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.originlineid(v=AX.60)
ms:contentKeyID: 49847485
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.OriginLineId
dev_langs:
- CSharp
- C++
- VB
---

# OriginLineId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the origin line id.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ORIGINLINEID")> _
Public Property OriginLineId As String
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As String

value = instance.OriginLineId

instance.OriginLineId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ORIGINLINEID")]
public string OriginLineId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ORIGINLINEID")]
public:
property String^ OriginLineId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## Remarks

Discounts can split sales lines to separate discounted and undiscounted items. This property points back to the line Id of the origin line in case any remerging is needed for reporting.

For non-split lines this aliases to the LineId.

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

