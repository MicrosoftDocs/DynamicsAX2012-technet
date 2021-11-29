---
title: Address.SortOrder Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: SortOrder Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.SortOrder
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.address.sortorder(v=AX.60)
ms:contentKeyID: 62214108
author: Khairunj
ms.author: daxcpft
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.Address.SortOrder
dev_langs:
- CSharp
- C++
- VB
---

# SortOrder Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets or sets the sort order for the address.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<ColumnAttribute("SORTORDER")> _
<DataMemberAttribute> _
<ReadOnlyAttribute("SORTORDER")> _
Public Property SortOrder As Integer
    Get
    Set
'Usage
Dim instance As Address
Dim value As Integer

value = instance.SortOrder

instance.SortOrder = value
```

``` csharp
[ColumnAttribute("SORTORDER")]
[DataMemberAttribute]
[ReadOnlyAttribute("SORTORDER")]
public int SortOrder { get; set; }
```

``` c++
[ColumnAttribute(L"SORTORDER")]
[DataMemberAttribute]
[ReadOnlyAttribute(L"SORTORDER")]
public:
property int SortOrder {
    int get ();
    void set (int value);
}
```

#### Property Value

Type: [System.Int32](https://technet.microsoft.com/library/td2s409d\(v=ax.60\))  
The sort order.  

## See Also

#### Reference

[Address Class](address-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

