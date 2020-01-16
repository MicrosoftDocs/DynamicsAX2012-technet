---
title: SalesInvoiceLine.Warehouse Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: Warehouse Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.Warehouse
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.warehouse(v=AX.60)
ms:contentKeyID: 62213830
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.Warehouse
dev_langs:
- CSharp
- C++
- VB
---

# Warehouse Property

Gets or sets the warehouse.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("INVENTLOCATIONID")> _
<DataMemberAttribute> _
Public Property Warehouse As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.Warehouse

instance.Warehouse = value
```

``` csharp
[ColumnAttribute("INVENTLOCATIONID")]
[DataMemberAttribute]
public string Warehouse { get; set; }
```

``` c++
[ColumnAttribute(L"INVENTLOCATIONID")]
[DataMemberAttribute]
public:
property String^ Warehouse {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The warehouse.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

