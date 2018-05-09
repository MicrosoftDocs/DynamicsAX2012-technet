---
title: ProductRules.DateToBlock Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DateToBlock Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.DateToBlock
ms:mtpsurl: https://technet.microsoft.com/en-us/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.datetoblock(v=AX.60)
ms:contentKeyID: 62209694
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.DateToBlock
dev_langs:
- CSharp
- C++
- VB
---

# DateToBlock Property

Gets the date to block the item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("DATETOBEBLOCKED")> _
<DataMemberAttribute> _
Public Property DateToBlock As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As DateTimeOffset

value = instance.DateToBlock
```

``` csharp
[ColumnAttribute("DATETOBEBLOCKED")]
[DataMemberAttribute]
public DateTimeOffset DateToBlock { get; internal set; }
```

``` c++
[ColumnAttribute(L"DATETOBEBLOCKED")]
[DataMemberAttribute]
public:
property DateTimeOffset DateToBlock {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/en-us/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

