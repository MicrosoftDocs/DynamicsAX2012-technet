---
title: Item.SalesUnitOfMeasure Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SalesUnitOfMeasure Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.SalesUnitOfMeasure
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.item.salesunitofmeasure(v=AX.60)
ms:contentKeyID: 49855967
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Item.SalesUnitOfMeasure
dev_langs:
- CSharp
- C++
- VB
---

# SalesUnitOfMeasure Property

Gets the sales unit of measure.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("UNITID")> _
<DataMemberAttribute> _
Public Property SalesUnitOfMeasure As String
    Get
    Friend Set
'Usage
Dim instance As Item
Dim value As String

value = instance.SalesUnitOfMeasure
```

``` csharp
[ColumnAttribute("UNITID")]
[DataMemberAttribute]
public string SalesUnitOfMeasure { get; internal set; }
```

``` c++
[ColumnAttribute(L"UNITID")]
[DataMemberAttribute]
public:
property String^ SalesUnitOfMeasure {
    String^ get ();
    internal: void set (String^ value);
}
```

#### Property Value

Type: [System.String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\))  
Returns [String](https://technet.microsoft.com/en-us/library/s1wwdcbf\(v=ax.60\)).  

## See Also

#### Reference

[Item Class](item-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

