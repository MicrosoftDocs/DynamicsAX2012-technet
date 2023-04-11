---
title: SalesInvoiceLine.StyleName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StyleName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.StyleName
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.stylename(v=AX.60)
ms:contentKeyID: 62211330
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.StyleName
dev_langs:
- CSharp
- C++
- VB
---

# StyleName Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the style name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTSTYLENAME")> _
<DataMemberAttribute> _
Public Property StyleName As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.StyleName

instance.StyleName = value
```

``` csharp
[ColumnAttribute("INVENTSTYLENAME")]
[DataMemberAttribute]
public string StyleName { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTSTYLENAME")]
[DataMemberAttribute]
public:
property String^ StyleName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The style name.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

