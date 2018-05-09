---
title: SalesInvoiceLine.SizeName Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SizeName Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.SizeName
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.sizename(v=AX.60)
ms:contentKeyID: 62209079
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.SizeName
dev_langs:
- CSharp
- C++
- VB
---

# SizeName Property

Gets or sets the size name.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTSIZENAME")> _
<DataMemberAttribute> _
Public Property SizeName As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.SizeName

instance.SizeName = value
```

``` csharp
[ColumnAttribute("INVENTSIZENAME")]
[DataMemberAttribute]
public string SizeName { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTSIZENAME")]
[DataMemberAttribute]
public:
property String^ SizeName {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
The size name.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

