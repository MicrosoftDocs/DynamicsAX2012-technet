---
title: ProductRules.IsActiveInSalesProcess Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: IsActiveInSalesProcess Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.IsActiveInSalesProcess
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.isactiveinsalesprocess(v=AX.60)
ms:contentKeyID: 65319111
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.IsActiveInSalesProcess
dev_langs:
- CSharp
- C++
- VB
---

# IsActiveInSalesProcess Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("ISACTIVEINSALESPROCESS")> _
Public Property IsActiveInSalesProcess As Boolean
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As Boolean

value = instance.IsActiveInSalesProcess
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("ISACTIVEINSALESPROCESS")]
public bool IsActiveInSalesProcess { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"ISACTIVEINSALESPROCESS")]
public:
property bool IsActiveInSalesProcess {
    bool get ();
    internal: void set (bool value);
}
```

#### Property Value

Type: [System.Boolean](https://technet.microsoft.com/library/a28wyd50\(v=ax.60\))  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

