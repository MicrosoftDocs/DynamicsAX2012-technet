---
title: SalesInvoiceLine.Site Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Site Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.Site
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.site(v=AX.60)
ms:contentKeyID: 62212169
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.Site
dev_langs:
- CSharp
- C++
- VB
---

# Site Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the site.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTSITEID")> _
<DataMemberAttribute> _
Public Property Site As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.Site

instance.Site = value
```

``` csharp
[ColumnAttribute("INVENTSITEID")]
[DataMemberAttribute]
public string Site { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTSITEID")]
[DataMemberAttribute]
public:
property String^ Site {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The site identifier.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

