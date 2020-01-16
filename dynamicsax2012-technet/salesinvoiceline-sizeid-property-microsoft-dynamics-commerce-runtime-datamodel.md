---
title: SalesInvoiceLine.SizeId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SizeId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.SizeId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.sizeid(v=AX.60)
ms:contentKeyID: 62210894
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.SizeId
dev_langs:
- CSharp
- C++
- VB
---

# SizeId Property

Gets or sets the size identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTSIZEID")> _
Public Property SizeId As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.SizeId

instance.SizeId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTSIZEID")]
public string SizeId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTSIZEID")]
public:
property String^ SizeId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The size identifier.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

