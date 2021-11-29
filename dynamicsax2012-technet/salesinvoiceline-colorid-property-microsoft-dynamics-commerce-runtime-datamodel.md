---
title: SalesInvoiceLine.ColorId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ColorId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.ColorId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.colorid(v=AX.60)
ms:contentKeyID: 62215215
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.ColorId
dev_langs:
- CSharp
- C++
- VB
---

# ColorId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the color identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("INVENTCOLORID")> _
Public Property ColorId As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.ColorId

instance.ColorId = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("INVENTCOLORID")]
public string ColorId { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"INVENTCOLORID")]
public:
property String^ ColorId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The color identifier.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

