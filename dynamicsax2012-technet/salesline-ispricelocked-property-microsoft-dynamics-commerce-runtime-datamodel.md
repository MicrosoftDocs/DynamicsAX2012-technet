---
title: SalesLine.IsPriceLocked Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsPriceLocked Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.IsPriceLocked
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.ispricelocked(v=AX.60)
ms:contentKeyID: 62203190
author: Khairunj
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.IsPriceLocked
dev_langs:
- CSharp
- C++
- VB
---

# IsPriceLocked Property

Gets or sets a value indicating whether the price for this sales line is locked or not.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("LOCKPRICE")> _
<ReadOnlyAttribute("LOCKPRICE")> _
Public Property IsPriceLocked As Boolean
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Boolean

value = instance.IsPriceLocked

instance.IsPriceLocked = value
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("LOCKPRICE")]
[ReadOnlyAttribute("LOCKPRICE")]
public bool IsPriceLocked { get; set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"LOCKPRICE")]
[ReadOnlyAttribute(L"LOCKPRICE")]
public:
property bool IsPriceLocked {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

