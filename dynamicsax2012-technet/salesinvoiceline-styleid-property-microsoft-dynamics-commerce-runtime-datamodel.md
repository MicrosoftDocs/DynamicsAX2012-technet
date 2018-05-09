---
title: SalesInvoiceLine.StyleId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: StyleId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.StyleId
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.styleid(v=AX.60)
ms:contentKeyID: 62208331
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.StyleId
dev_langs:
- CSharp
- C++
- VB
---

# StyleId Property

Gets or sets the style identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTSTYLEID")> _
<DataMemberAttribute> _
Public Property StyleId As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.StyleId

instance.StyleId = value
```

``` csharp
[ColumnAttribute("INVENTSTYLEID")]
[DataMemberAttribute]
public string StyleId { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTSTYLEID")]
[DataMemberAttribute]
public:
property String^ StyleId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The style identifier.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

