﻿---
title: SalesLine.IsPriceOverridden Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsPriceOverridden Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.IsPriceOverridden
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.salesline.ispriceoverridden(v=AX.60)
ms:contentKeyID: 49852006
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.SalesLine.IsPriceOverridden
dev_langs:
- CSharp
- C++
- VB
---

# IsPriceOverridden Property

Gets or sets a value indicating whether the price was overriden.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("ISPRICEOVERRIDDEN")> _
<DataMemberAttribute> _
Public Property IsPriceOverridden As Boolean
    Get
    Set
'Usage
Dim instance As SalesLine
Dim value As Boolean

value = instance.IsPriceOverridden

instance.IsPriceOverridden = value
```

``` csharp
[ColumnAttribute("ISPRICEOVERRIDDEN")]
[DataMemberAttribute]
public bool IsPriceOverridden { get; set; }
```

``` c++
[ColumnAttribute(L"ISPRICEOVERRIDDEN")]
[DataMemberAttribute]
public:
property bool IsPriceOverridden {
    bool get ();
    void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/en-us/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[SalesLine Class](salesline-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)
