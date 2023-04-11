---
title: SalesInvoiceLine.ItemId Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: ItemId Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.ItemId
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesinvoiceline.itemid(v=AX.60)
ms:contentKeyID: 62207969
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesInvoiceLine.ItemId
dev_langs:
- CSharp
- C++
- VB
---

# ItemId Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the item identifier.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ITEMID")> _
<DataMemberAttribute> _
Public Property ItemId As String
    Get
    Set
'Usage
Dim instance As SalesInvoiceLine
Dim value As String

value = instance.ItemId

instance.ItemId = value
```

``` csharp
[ColumnAttribute("ITEMID")]
[DataMemberAttribute]
public string ItemId { get; set; }
```

``` c++
[ColumnAttribute(L"ITEMID")]
[DataMemberAttribute]
public:
property String^ ItemId {
    String^ get ();
    void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/library/s1wwdcbf\(v=ax.60\))  
The item identifier.  

## See Also

#### Reference

[SalesInvoiceLine Class](salesinvoiceline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

