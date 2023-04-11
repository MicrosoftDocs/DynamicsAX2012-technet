---
title: ProductRules.DateToActivate Property  (Microsoft.Dynamics.Commerce.Runtime.DataModel)
TOCTitle: DateToActivate Property
ms:assetid: P:Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.DateToActivate
ms:mtpsurl: https://technet.microsoft.com/library/microsoft.dynamics.commerce.runtime.datamodel.productrules.datetoactivate(v=AX.60)
ms:contentKeyID: 62214836
author: tonyafehr
ms.date: 05/18/2015
mtps_version: v=AX.60
f1_keywords:
- Microsoft.Dynamics.Commerce.Runtime.DataModel.ProductRules.DateToActivate
dev_langs:
- CSharp
- C++
- VB
---

# DateToActivate Property


[!INCLUDE[archive-banner](includes/archive-banner.md)]

Gets the date to activate the item.

**Namespace:**  [Microsoft.Dynamics.Commerce.Runtime.DataModel](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)  
**Assembly:**  Microsoft.Dynamics.Commerce.Runtime.Entities (in Microsoft.Dynamics.Commerce.Runtime.Entities.dll)

## Syntax

``` vb
'Declaration
<DataMemberAttribute> _
<ColumnAttribute("DATETOACTIVATEITEM")> _
Public Property DateToActivate As DateTimeOffset
    Get
    Friend Set
'Usage
Dim instance As ProductRules
Dim value As DateTimeOffset

value = instance.DateToActivate
```

``` csharp
[DataMemberAttribute]
[ColumnAttribute("DATETOACTIVATEITEM")]
public DateTimeOffset DateToActivate { get; internal set; }
```

``` c++
[DataMemberAttribute]
[ColumnAttribute(L"DATETOACTIVATEITEM")]
public:
property DateTimeOffset DateToActivate {
    DateTimeOffset get ();
    internal: void set (DateTimeOffset value);
}
```

#### Property Value

Type: [System.DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\))  
Returns [DateTimeOffset](https://technet.microsoft.com/library/bb341783\(v=ax.60\)).  

## See Also

#### Reference

[ProductRules Class](productrules-class-microsoft-dynamics-commerce-runtime-datamodel.md)

[Microsoft.Dynamics.Commerce.Runtime.DataModel Namespace](microsoft-dynamics-commerce-runtime-datamodel-namespace.md)

