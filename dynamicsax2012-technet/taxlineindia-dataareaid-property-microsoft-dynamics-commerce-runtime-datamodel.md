---
title: TaxLineIndia.DataAreaId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DataAreaId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.DataAreaId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxlineindia.dataareaid(v=AX.60)
ms:contentKeyID: 62207249
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxLineIndia.DataAreaId
dev_langs:
- CSharp
- C++
- VB
---

# DataAreaId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets DataAreaId.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DATAAREAID")> _
<DataMemberAttribute> _
Public Property DataAreaId As String
    Get
    Set
'Usage
Dim instance As TaxLineIndia
Dim value As String

value = instance.DataAreaId

instance.DataAreaId = value
```

``` csharp
[ColumnAttribute("DATAAREAID")]
[DataMemberAttribute]
public string DataAreaId { get; set; }
```

``` c++
[ColumnAttribute(L"DATAAREAID")]
[DataMemberAttribute]
public:
property String^ DataAreaId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[TaxLineIndia Class](taxlineindia-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

