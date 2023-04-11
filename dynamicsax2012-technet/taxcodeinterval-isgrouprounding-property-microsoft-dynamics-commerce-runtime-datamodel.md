---
title: TaxCodeInterval.IsGroupRounding Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsGroupRounding Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.IsGroupRounding
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.taxcodeinterval.isgrouprounding(v=AX.60)
ms:contentKeyID: 62211634
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.TaxCodeInterval.IsGroupRounding
dev_langs:
- CSharp
- C++
- VB
---

# IsGroupRounding Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets a value indicating whether the tax group is used for rounding.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("TAXGROUPROUNDING")> _
Public Property IsGroupRounding As Boolean
    Get
    Friend Set
'Usage
Dim instance As TaxCodeInterval
Dim value As Boolean

value = instance.IsGroupRounding
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("TAXGROUPROUNDING")]
public bool IsGroupRounding { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"TAXGROUPROUNDING")]
public:
property bool IsGroupRounding {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  
Returns [Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\)).  

## See Also

#### Reference

[TaxCodeInterval Class](taxcodeinterval-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

